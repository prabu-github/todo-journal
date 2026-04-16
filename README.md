### UWF
- **[DONE]** SinCosPosEmbed and cls_tkn, clean up 
- **[DONE]** mae decoder finish up
- **[DONE]** make tensor shapes step through
- **[DONE]** 1D/2D unfold (called patchify in Kaiming) 
- **[DONE]** loss computation
- **[DONE]** step through pretraining to verify shapes in GHS
- **[DONE]** add encode function
- fine tuning code from GHS
- dataloaders set up for GHS
- train
- comment code for MAE
   

---

### MB1
- train best hyp model inside outer loop 
- generate outer loop test predictions with best hyp model
- predict with ensemble on new data; call columns as oi_N
- collate oi outputs
- PLSR optuna pipeline on CHTC
- SPLSR optuna pipeline on CHTC
- Ridge pipeline on CHTC
- Lasso pipeline on CHTC
- ElasticNet pipeline on CHTC
- SVR with Nystroem on CHTC
- (S)PLS-RF on CHTC
- (S)PLS-GPR on CHTC
- (S)PLS-SVR on CHTC
- Stacked (S)PLS on CHTC
