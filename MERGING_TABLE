**DATA PREPROCESSING**


**Merging table based on the common columns**
import pandas as pd

variable_name=pd.merge(dataframe_1,dataframe_2,on="common_columns") 
*merging sales and store table*
df_sales_store=pd.merge(df_sales,df_stores,on="Store")

*merging sales_store table and feature table*
df_final=pd.merge(df_sales_store,df_feature,on=['Store','Date','IsHoliday'])
