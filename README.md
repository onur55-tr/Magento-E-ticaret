# README

## Tar.xz Nasıl Çıkartırım?
1. Git clone
	
		git clone https://github.com/onur55-tr/Magento-E-ticaret.git
2. Tar dosyası çıkartma
			
		tar -xf Magento.tar.xz
3. Tar dosyasını açmak isterseniz eğer
	
	Debian:
		
		sudo apt-get install xz-utils
	CentOS/RHEL/Fedora:

		sudo dnf install xz
	Open:

		xz -d -v Magento.tar.xz


## Sistem Gereksinimleri
1. Mcrypt fonksiyonu
2. GD2 fonksiyonu
3. Curl fonksiyonu
4. pdo_mysql fonksiyonu (açık olmazsa eğer kurulum aşamasında hata alacaksınız.)

## Kurulum
1. Bir database oluşturunuz.
2. Sunucuya tardan çıkarılan dosyaları aktarınız.
3. Web siteden kuruluma geçebilirsiniz.

# Not: Local sunucudan hata alıyorsanız eğer Varien.php dosyayı app/code/Mage/Core/Model/Session/Abstract/ klasörün içerisine atınız.

###
