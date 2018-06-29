# bootsonboard
1) \app\etc

config.xml

2)  \app\design\frontend\ultimo\default\template\checkout\cart\item

default.phtml     ----> show guest member on cart page


3)  \app\design\frontend\ultimo\default\template\checkout\onepage\review

item.phtml         ----> show guest member on order confirmation page

4) \app\design\adminhtml\default\custom\template\sales\items\column

name.phtml         -----> add guest member to order in admin copy exiting file from D:\xampp\htdocs\bootsonboard\app\design\adminhtml\default\default\template\sales\items\column


5) \app\code\core\Mage\Sales\Model

Quote.php	  ---->	delete tax products from cart
