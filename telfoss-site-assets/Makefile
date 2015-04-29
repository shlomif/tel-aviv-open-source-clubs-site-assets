all:

upload: all
	(cd to-upload && rsync -a -v --progress --inplace * gnu.hamakor.org.il:/home/www/tel.foss.org.il/)

upload_temp_location: all
	(cd to-upload && rsync -a -v --progress --inplace * $$__HOMEPAGE_REMOTE_PATH/tel.foss.org.il-temp/)
