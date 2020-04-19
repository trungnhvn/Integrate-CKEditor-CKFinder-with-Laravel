# Integrate-CKEditor-CKFinder-with-Laravel
Add CKFinder to CKEditor to Laravel5 for image file management.

Installation Guide:

#1: Download then extract two folder namely CKEditor and CKFinder

#2. Copy the 2 folders to public directory of Laravel project

#3. Usage:

      <textarea name="" class="ckeditor" id="editor1" cols="30" rows="10"></textarea>
      <script>
        CKEDITOR.replace( 'editor1' );
      </script>
      <script src="http://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js"></script>
      <script src="/ckeditor/ckeditor.js"></script>
      
#4 In case of permission error, please run command from terminal:
      
      chmod -R 777 public/userfiles


[![ckeditor.jpg](https://i.postimg.cc/WbwwxNHL/ckeditor.jpg)](https://postimg.cc/3dWGvThn)

[![ckeditor1.jpg](https://i.postimg.cc/L843pccq/ckeditor1.jpg)](https://postimg.cc/TpSDj4YG)

[![ckfinder.jpg](https://i.postimg.cc/Qd6kx6Df/ckfinder.jpg)](https://postimg.cc/VJCbKWdt)
