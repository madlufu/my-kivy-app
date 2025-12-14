#albumine gore duzeltilmis kalsiyum hesaplama 
print("=" * 80)
print("\t\t\tDüzeltilmiş Kalsiyum Hesaplama")
print("=" * 80, "\n")
albumin=float(input("Serum Albumin düzeyini giriniz g/dl olarak:  "))
if float(albumin >4) :
	print("-" * 80)
	print("Albümin degerini muhtemelen kalsiyum degeri olarak girdiniz lutfen tekrar deneyin")
	print("-" * 80)
	albumin=float(input("Serum Albumin düzeyini giriniz g/dl olarak:  "))
			
			
else:
	

	print("-" * 80)
calcium_serum=float(input("Serum Kalsiyum düzeyini giriniz mg/dl olarak:  "))
print("-" * 80)

corrected_calcium=float((calcium_serum+((0.8)*(4-albumin))))

if float(corrected_calcium < 8.5):
	print("Albümine göre düzeltilmiş kalsiyum düzeyi:  ",corrected_calcium,"mg/dl 'dir.\nDüzeltilmiş Kalsiyum değeri referans araliğin altındadır. (Ref: 8.5-10.5) ")
elif float(corrected_calcium > 10.5):
	print("Albümine göre düzeltilmiş kalsiyum düzeyi:  ",corrected_calcium,"mg/dl 'dir.\nDüzeltilmiş Kalsiyum değeri referans araliğin üstündedir. (Ref: 8.5-10.5)")
else:
	print("Albümine göre düzeltilmiş kalsiyum düzeyi:  ",corrected_calcium,"mg/dl 'dir.\n Kalsiyum düzeyi referans değerler arasındadır.  (Ref:8.5-10.5)")
print("=" * 80)
print("=" * 80)