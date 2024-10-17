# Fine-Tunning-using-LORA

Fine Tunning:
 
1# FIne tunning is a “conversation of HIGH-MEMO0RY model to LOW-MEMORY model”

2# “Converting “full-Precision(FP)” model into “half-precision”model

3# “Convert a big model(“32 bit) into 16 or 8 bit by using the Lora, Qlora
       Under the PEFT”

￼

￼
￼

4# PEFT: it freeze the entire parameter in the model and start train only the cetrain most  important parameter

5# llm model with large parameter :example(llm, game etc)

￼

(Real time eg: 1. If we are using a high memory model for that use cannot able to adapt in our system because of a system capability but we can proceed by buy create an instance in a cloud where we can get memory and Gpu depending upon the model we want to store for that it takes more cost in that case we will go for an fine -tunning

2. If we want to convert a ”LLama2” & “Gemma” it contains a 7B parameter covert that into low-memory model of 660M parameter for that we can use that model in any “edge-devices”(tab, phone , watch) but while doing this we may loss of the data so that our “accuracy” can be reduce.



Work process of Fine- tunning:
* Fine-tuning was done by “Quantization” makes full precision into half-precision 
       Type:
       1. Post quantisation training(loss of data- accuracy reduction)
       2. Quantization Awareness training (to over come previous one-Lora Qlora)
    

*  inside Quantixzation contains the concept of ‘calibration’ which will used to Quize the data 


* Convert a big model(“32 bit) into 16 or 8 bit by using the Lora, Qlora
       (Low rank adaption of a large language model, QuantizationLow rank adaption of a large language model)

*  Lora : it contain a Floating point and convert a 32-bit in to smaller bit (rank ) buy the step of “MATRIX DECOMPOSITION” it convert 32bit into an 2 matrixes for that we can give the “RANK” for the matrixes like 8. Researcher says that lora perform good in rank ‘8’
