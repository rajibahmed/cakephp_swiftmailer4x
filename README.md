#Cakephp SwiftMailer-4.x.x componenet 

##Configuration

Firstly, change the line to the directory of your SwiftMailer 4x Library
  
  //required third party library "SwiftMailer" under GPL license
App::import('Vendor', 'Swift', array('file' => 'swiftmailer'.DS.'lib'.DS.'swift_required.php'))

  
Currently it is pointing to the app/vendors/swiftmailer/swift_required.php 

##Example of Usage
  http://bakery.cakephp.org/articles/sky_l3ppard/2009/11/07/updated-swiftmailer-4-xx-component-with-attachments-and-plugins


## Added Feature

* Batch Send of emails 

##Code
  $this->Swiftmailer->batchSend();
