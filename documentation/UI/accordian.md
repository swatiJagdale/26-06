Mobile starter Kit
================================

UI components
--------------------------------

###Accordion
		<div class="accordion">
				<dl>
					<dt>
						<div>Title 1</div>
					</dt>
					<dd>
						<div>Lorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsumLorem ipsum</div>
					</dd>
				</dl>
		</div>
		
		$(function(){
					$('.accordion dt').addClass('inactive');
					$('dt').bind("click", function(){
						$(this).next('dd').slideToggle(100);
						$(this).toggleClass('inactive');
					});
					$('dd').bind('click',function(){
						$(this).slideToggle(100);
						$(this).prev().toggleClass('inactive');
					});
			});



Demo

![alt text] [Demo]
[Demo]: ../screenshots/accordian.png "Demo"   

![alt text] [Demo]
[Demo]: ../screenshots/accordian.png "Demo"

		
*[back] (UI_overview.md)*  
		
