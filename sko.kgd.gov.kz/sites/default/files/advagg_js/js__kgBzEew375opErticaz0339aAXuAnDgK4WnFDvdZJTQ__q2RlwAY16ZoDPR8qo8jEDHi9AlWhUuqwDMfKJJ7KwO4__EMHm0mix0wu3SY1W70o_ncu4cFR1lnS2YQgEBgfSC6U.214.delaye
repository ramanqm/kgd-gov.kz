/* Russian (UTF-8) initialisation for the jQuery UI date picker plugin. */
/* Written by Andrew Stromnov (stromnov@gmail.com). */
jQuery(function($){
        $.datepicker.regional['ru'] = {
                closeText: 'Закрыть',
                prevText: '&#x3c;Пред',
                nextText: 'След&#x3e;',
                currentText: 'Сегодня',
                monthNames: ['Январь','Февраль','Март','Апрель','Май','Июнь',
                'Июль','Август','Сентябрь','Октябрь','Ноябрь','Декабрь'],
                monthNamesShort: ['Янв','Фев','Мар','Апр','Май','Июн',
                'Июл','Авг','Сен','Окт','Ноя','Дек'],
                dayNames: ['воскресенье','понедельник','вторник','среда','четверг','пятница','суббота'],
                dayNamesShort: ['вск','пнд','втр','срд','чтв','птн','сбт'],
                dayNamesMin: ['Вс','Пн','Вт','Ср','Чт','Пт','Сб'],
                weekHeader: 'Не',
                dateFormat: 'dd.mm.yy',
                firstDay: 1,
                isRTL: false,
                showMonthAfterYear: false,
                yearSuffix: ''};
        $.datepicker.setDefaults($.datepicker.regional['ru']);



		$.datepicker.regional['kk'] = {
				closeText: 'Жабу',
				prevText: '&#x3c;Алдыңғы',
				nextText: 'Келесі&#x3e;',
				currentText: 'Бүгін',
				monthNames: ['Қаңтар','Ақпан','Наурыз','Сәуір','Мамыр','Маусым',
				'Шілде','Тамыз','Қыркүйек','Қазан','Қараша','Желтоқсан'],
				monthNamesShort: ['Қаң','Ақп','Нау','Сәу','Мам','Мау',
				'Шіл','Там','Қыр','Қаз','Қар','Жел'],
				dayNames: ['Жексенбі','Дүйсенбі','Сейсенбі','Сәрсенбі','Бейсенбі','Жұма','Сенбі'],
				dayNamesShort: ['жкс','дсн','ссн','срс','бсн','жма','снб'],
				dayNamesMin: ['Жк','Дс','Сс','Ср','Бс','Жм','Сн'],
				weekHeader: 'Не',
				dateFormat: 'dd.mm.yy',
				firstDay: 1,
				isRTL: false,
				showMonthAfterYear: false,
				yearSuffix: ''};
		$.datepicker.setDefaults($.datepicker.regional['kz']);

});;/**/
(function(a){a.isScrollToFixed=function(b){return !!a(b).data("ScrollToFixed")};a.ScrollToFixed=function(d,i){var l=this;l.$el=a(d);l.el=d;l.$el.data("ScrollToFixed",l);var c=false;var G=l.$el;var H;var E;var e;var y;var D=0;var q=0;var j=-1;var f=-1;var t=null;var z;var g;function u(){G.trigger("preUnfixed.ScrollToFixed");k();G.trigger("unfixed.ScrollToFixed");f=-1;D=G.offset().top;q=G.offset().left;if(l.options.offsets){q+=(G.offset().left-G.position().left)}if(j==-1){j=q}H=G.css("position");c=true;if(l.options.bottom!=-1){G.trigger("preFixed.ScrollToFixed");w();G.trigger("fixed.ScrollToFixed")}}function n(){var I=l.options.limit;if(!I){return 0}if(typeof(I)==="function"){return I.apply(G)}return I}function p(){return H==="fixed"}function x(){return H==="absolute"}function h(){return !(p()||x())}function w(){if(!p()){t.css({display:G.css("display"),width:G.outerWidth(true),height:G.outerHeight(true),"float":G.css("float")});cssOptions={"z-index":l.options.zIndex,position:"fixed",top:l.options.bottom==-1?s():"",bottom:l.options.bottom==-1?"":l.options.bottom,"margin-left":"0px"};if(!l.options.dontSetWidth){cssOptions.width=G.width()}G.css(cssOptions);G.addClass(l.options.baseClassName);if(l.options.className){G.addClass(l.options.className)}H="fixed"}}function b(){var J=n();var I=q;if(l.options.removeOffsets){I="";J=J-D}cssOptions={position:"absolute",top:J,left:I,"margin-left":"0px",bottom:""};if(!l.options.dontSetWidth){cssOptions.width=G.width()}G.css(cssOptions);H="absolute"}function k(){if(!h()){f=-1;t.css("display","none");G.css({"z-index":y,width:"",position:E,left:"",top:e,"margin-left":""});G.removeClass("scroll-to-fixed-fixed");if(l.options.className){G.removeClass(l.options.className)}H=null}}function v(I){if(I!=f){G.css("left",q-I);f=I}}function s(){var I=l.options.marginTop;if(!I){return 0}if(typeof(I)==="function"){return I.apply(G)}return I}function A(){if(!a.isScrollToFixed(G)){return}var K=c;if(!c){u()}else{if(h()){D=G.offset().top;q=G.offset().left}}var I=a(window).scrollLeft();var L=a(window).scrollTop();var J=n();if(l.options.minWidth&&a(window).width()<l.options.minWidth){if(!h()||!K){o();G.trigger("preUnfixed.ScrollToFixed");k();G.trigger("unfixed.ScrollToFixed")}}else{if(l.options.maxWidth&&a(window).width()>l.options.maxWidth){if(!h()||!K){o();G.trigger("preUnfixed.ScrollToFixed");k();G.trigger("unfixed.ScrollToFixed")}}else{if(l.options.bottom==-1){if(J>0&&L>=J-s()){if(!x()||!K){o();G.trigger("preAbsolute.ScrollToFixed");b();G.trigger("unfixed.ScrollToFixed")}}else{if(L>=D-s()){if(!p()||!K){o();G.trigger("preFixed.ScrollToFixed");w();f=-1;G.trigger("fixed.ScrollToFixed")}v(I)}else{if(!h()||!K){o();G.trigger("preUnfixed.ScrollToFixed");k();G.trigger("unfixed.ScrollToFixed")}}}}else{if(J>0){if(L+a(window).height()-G.outerHeight(true)>=J-(s()||-m())){if(p()){o();G.trigger("preUnfixed.ScrollToFixed");if(E==="absolute"){b()}else{k()}G.trigger("unfixed.ScrollToFixed")}}else{if(!p()){o();G.trigger("preFixed.ScrollToFixed");w()}v(I);G.trigger("fixed.ScrollToFixed")}}else{v(I)}}}}}function m(){if(!l.options.bottom){return 0}return l.options.bottom}function o(){var I=G.css("position");if(I=="absolute"){G.trigger("postAbsolute.ScrollToFixed")}else{if(I=="fixed"){G.trigger("postFixed.ScrollToFixed")}else{G.trigger("postUnfixed.ScrollToFixed")}}}var C=function(I){if(G.is(":visible")){c=false;A()}};var F=function(I){(!!window.requestAnimationFrame)?requestAnimationFrame(A):A()};var B=function(){var J=document.body;if(document.createElement&&J&&J.appendChild&&J.removeChild){var L=document.createElement("div");if(!L.getBoundingClientRect){return null}L.innerHTML="x";L.style.cssText="position:fixed;top:100px;";J.appendChild(L);var M=J.style.height,N=J.scrollTop;J.style.height="3000px";J.scrollTop=500;var I=L.getBoundingClientRect().top;J.style.height=M;var K=(I===100);J.removeChild(L);J.scrollTop=N;return K}return null};var r=function(I){I=I||window.event;if(I.preventDefault){I.preventDefault()}I.returnValue=false};l.init=function(){l.options=a.extend({},a.ScrollToFixed.defaultOptions,i);y=G.css("z-index");l.$el.css("z-index",l.options.zIndex);t=a("<div />");H=G.css("position");E=G.css("position");e=G.css("top");if(h()){l.$el.after(t)}a(window).bind("resize.ScrollToFixed",C);a(window).bind("scroll.ScrollToFixed",F);if("ontouchmove" in window){a(window).bind("touchmove.ScrollToFixed",A)}if(l.options.preFixed){G.bind("preFixed.ScrollToFixed",l.options.preFixed)}if(l.options.postFixed){G.bind("postFixed.ScrollToFixed",l.options.postFixed)}if(l.options.preUnfixed){G.bind("preUnfixed.ScrollToFixed",l.options.preUnfixed)}if(l.options.postUnfixed){G.bind("postUnfixed.ScrollToFixed",l.options.postUnfixed)}if(l.options.preAbsolute){G.bind("preAbsolute.ScrollToFixed",l.options.preAbsolute)}if(l.options.postAbsolute){G.bind("postAbsolute.ScrollToFixed",l.options.postAbsolute)}if(l.options.fixed){G.bind("fixed.ScrollToFixed",l.options.fixed)}if(l.options.unfixed){G.bind("unfixed.ScrollToFixed",l.options.unfixed)}if(l.options.spacerClass){t.addClass(l.options.spacerClass)}G.bind("resize.ScrollToFixed",function(){t.height(G.height())});G.bind("scroll.ScrollToFixed",function(){G.trigger("preUnfixed.ScrollToFixed");k();G.trigger("unfixed.ScrollToFixed");A()});G.bind("detach.ScrollToFixed",function(I){r(I);G.trigger("preUnfixed.ScrollToFixed");k();G.trigger("unfixed.ScrollToFixed");a(window).unbind("resize.ScrollToFixed",C);a(window).unbind("scroll.ScrollToFixed",F);G.unbind(".ScrollToFixed");t.remove();l.$el.removeData("ScrollToFixed")});C()};l.init()};a.ScrollToFixed.defaultOptions={marginTop:0,limit:0,bottom:-1,zIndex:1000,baseClassName:"scroll-to-fixed-fixed"};a.fn.scrollToFixed=function(b){return this.each(function(){(new a.ScrollToFixed(this,b))})}})(jQuery);;/**/
(function($) {
    Drupal.behaviors.kgdSpecVer = {
        attach: function (context, settings) {
        	function getDomain() {
		        var fulldomainname = document.domain;
		        var domain_levels = fulldomainname.split(".");
		        var domain_level = domain_levels.length;
		        var all_domains = "." + domain_levels[domain_level-3] + "." + domain_levels[domain_level-2] + "." + domain_levels[domain_level-1];
		        return all_domains;
		    }
        	$(document).ready(function(){
        		$("#enableuGost").click(function(){
			        var panel = $("#CecutientWrapper");
			        if (panel.css("display")=="none"){
			        	$('#enableuGost').html('<i class="fa fa-eye-slash fa-lg m-l-sm m-r-sm"></i>');
				        panel.animate({
			                //display:"inline-block",
			                height: "toggle"
			              }, 500, function() {
			                chengeColor('white');
			              });

			        } else {
			        	$('#enableuGost').html('<i class="fa fa-eye fa-lg m-l-sm m-r-sm"></i>');

			            panel.animate({
			                display:"none",
			                height: "toggle"
			              }, 500, function() {
			              	$.cookie("CecutientCookie", null, { domain: getDomain(), path: '/' });
			                $.cookie("style", null, { domain: getDomain(), path: '/' });
			                $.cookie("image", null, { domain: getDomain(), path: '/' });
			                $.cookie("fonts", null, { domain: getDomain(), path: '/' });
			                $.cookie("settings", null, { domain: getDomain(), path: '/' });

			                window.location.reload();
			              });
			        }
				});

				

				$("#settingVer").click(function(){
			        var panel2 = $("#poppedSettings");
			        if (panel2.css("display") == "none"){
				        panel2.animate({
			                //display:"inline-block",
			                height: "toggle"
			              }, 500, function() {
			              	panel2.css({"display":"inline-block"})
			              	$.cookie("settings", true, {
				                expires: 365,
				                domain: getDomain(),
				                path: '/'
				            });
			              });

			        } else {
			            panel2.animate({
			                display:"none",
			                height: "toggle"
			              }, 500, function() {
			              	$.cookie("settings", false, {
				                expires: 365,
				                domain: getDomain(),
				                path: '/'
				            });
			              });
			        }
				});

				if ($.cookie("settings") == "true") $("#settingVer").trigger('click');

				$("#NormalVer").click(function(){
					var panel = $("#CecutientWrapper");
					$('#enableuGost').html('<i class="fa fa-eye fa-lg m-l-sm m-r-sm"></i>');
		            panel.animate({
		                display:"none",
		                height: "toggle"
		              }, 500, function() {
		              	$.cookie("CecutientCookie", null, { domain: getDomain(), path: '/' });
		                $.cookie("style", null, { domain: getDomain(), path: '/' });
		                $.cookie("image", null, { domain: getDomain(), path: '/' });
		                $.cookie("fonts", null, { domain: getDomain(), path: '/' });

		                window.location.reload();
		              });
				});
			    
			    if ($.cookie("CecutientCookie")=="on"){
			    	$('#enableuGost').html('<i class="fa fa-eye-slash fa-lg m-l-sm m-r-sm"></i>');
			        $("#CecutientWrapper").css("display","block");
			        if ($.cookie("fonts")=="small"){SmallFonts();}
			        if ($.cookie("fonts")=="medium"){MediumFonts();}
			        if ($.cookie("fonts")=="big"){BigFonts();}
			        if ($.cookie("image")=="on"){ImageOn();}
			        if ($.cookie("image")=="off"){ImageOff();}
			        if ($.cookie("style")=="white"){chengeColor('white');}
			        if ($.cookie("style")=="black"){chengeColor('black');}
			        if ($.cookie("style")=="blue"){chengeColor('blue');}
			        if ($.cookie("style")=="green"){chengeColor('green');}
			        if ($.cookie("style")=="brown"){chengeColor('brown');}			        
			    } else {
			        $("#CecutientWrapper").css("display","none");
			    }
			    /*alert($.cookie("fonts")+'&'+$.cookie("CecutientCookie"));*/
			    /*Включение стилей для слабовидящих*/
			    //$('#CecutientOn').click(function(){CecutientOn();});

			    /*Цветовая схема*/
			    $('#WhiteStyle').click(function(){chengeColor('white');});
			    $('#BlackStyle').click(function(){chengeColor('black');});
			    $('#BlueStyle').click(function(){chengeColor('blue');});
			    $('#GreenStyle').click(function(){chengeColor('green');});
			    $('#BrownStyle').click(function(){chengeColor('brown');});

			    $('#WhiteStyle2').click(function(){chengeColor('white');});
			    $('#BlackStyle2').click(function(){chengeColor('black');});
			    $('#BlueStyle2').click(function(){chengeColor('blue');});
			    /*Включение выключение изображений*/
			    $('#ImageOn').click(function(){ImageOn();});
			    $('#ImageOff').click(function(){ImageOff();});
			    /*Размер шрифта*/
			    $('#SmallFonts').click(function(){SmallFonts();});
			    $('#MediumFonts').click(function(){MediumFonts();});
			    $('#BigFonts').click(function(){BigFonts();});


			    function chengeColor(color){
			    	var color1, color2;

			    	$.cookie("CecutientCookie", "on", {
			            expires: 365,
			            domain: getDomain(),
			            path: '/'
			        });

					switch (color) {
					  case "white":
					    color1 = "#fff";
					    color2 = "#000";
					    hclass = "hoverWt";
					    break
					  case "black":
					    color1 = "#000";
					    color2 = "#fff";
					    hclass = "hoverBk";
					    break
					  case "blue":
					    color1 = "#9DD1FF";
					    color2 = "#063462";
					    hclass = "hoverBe";
					    break
					  case "green":
					    color1 = "#3B2716";
					    color2 = "#A9E44D";
					    hclass = "hoverGn";
					    break
					  case "brown":
					    color1 = "#f7f3d6";
					    color2 = "#4d4b43";
					    hclass = "hoverBn";
					    break
					  default:
					  	color = "white";
					  	color1 = "#fff";
					    color2 = "#000";
					    hclass = "hoverWt";
				        return false;
					}
					$('a, .nav-dot-current, .btn-index, .btn-default, .i-checks').removeClass('hoverWt hoverBk hoverBe hoverGn hoverBn');
			        if ($.cookie("CecutientCookie")=="on"){
			        	$('#placeholder, #legendChar').css('cssText', 'display: none');
			        	$('a, .cuprum a span, .pagination-lang .active a, .form-submit, #user-login-form button, .voteTop, .nav-dot-current').addClass(hclass);
			        	$('.log, .slides a, #CecutientWrapper a, .btn-top, #site-name a, .dropdown-toggle, .user-picture a, .call-center a, .list-group .btn, .mod-news a').removeClass(hclass);
			        	$(".btn-index, .btn-default, .i-checks").addClass(hclass);
			        	$(".call-center").css('cssText', 'background: url(/sites/all/themes/KGD17/images/call-center-phoneGS.png) no-repeat left center; background-size: 11%;');
			        	if ($.cookie("image")=="on" || $.cookie("image")==null){
			        		$(".header #site-name a.kgd_logo, img, .demo-2 .bg-img").css('cssText', '-webkit-filter: grayscale(100%)');
			        	}
			        	$('body, html').css({"background-color":color1,"color":color2});
			        	$('canvas').css({"background-color":"none","color":color2});
			        	$(".breadcrumb span, .call-center ins, .fcred, .dropdown-toggle, .exchange-rates span, .today_event span").css({"color":color2});
			        	$("#loginBtn, #loginBtn a").css('cssText','color:'+color1);
			        	$("#smartmenus_1 li a, #smartmenus_3 li a, #smartmenus_2 li a").css({"background-color":color1,"color":color2});
			        	$("#smartmenus_1 li ul, #smartmenus_3 li ul, #smartmenus_2 li ul, .chosen-container-single .chosen-single, .btn-index, .btn-default").css('cssText', 'background-color: '+color1+'; color:'+color2+'!important; border: 1px solid '+color2+';');
			            $("#admin-menu .dropdown li li a").css('cssText','color:'+color2+'; border-top: 1px solid '+color2)
			            $(".cur-vt-none, .cur-vt, #admin-menu, #admin-menu .dropdown li li, .right-bg, .title-mess-a, .head-title, .breadcrumb span a, .title-mess, .mess-date, .title-mess-2, .mod-news .text-muted, .text-muted, .mod-news-title, .mod-news-time, .mod-news a").css({"background":color1,"color":color2});
			            $(".ico-pin, .panel-boss").css('cssText', 'background-color: '+color2+'; color: '+color1+'!important');
			            $("input").css({"background":color1,"color":color2});
			            $('#content *').css({"background":color1,"color":color2});
			            $('#content').css({"width":"100%","padding":"0px"});
			            $(".form-control, #deliver, table thead tr th, table tbody tr td").css({"background-color":color1, "border-color":color2});
			            $("#centerUp a, #headUp").css('cssText', 'background-color: '+color2+'; color: '+color1+'!important; border-right-color:'+color1+'!important');
			            $("#enableuGost").css('cssText', 'background-color: '+color1+'; color: '+color2+'!important');
			            $(".call-center div").css({"color":color2});
			            $(".nav-tabs li a").css({"background":color1,"color":color2});
						$(".nav-tabs").css({"border-bottom":"0"});
						$("#smartmenus_2").css({"border":"2px solid "+color1});
						$(".tax-calendar .today_date").css({"color":color2});
						$(".text-danger").css({"color":color2});

						//$(".flex-control-paging li a.flex-active").css({"background":color2});
			            $(".nav-tabs > li > a, table").css({"max-height":"100%","background":color1,"color":color2,"border":"1px solid "+color2});
                  $(".tab-content").css({"max-height":"100%","background":color1,"color":color2,"border-top":"1px solid "+color2})
			            $('#site-name .suffix, #site-name a span, #site-name a span strong').css({"color":color2})
			            $('.navbar-nav > li > .dropdown-menu').css({"background":color1,"color":color2,"border":"1px solid "+color2});
			            //$('.navbar-nav > li > .dropdown-menu > li > a').css({"color":color2});
			            $('.list-group-item, .links, .progress').css({"background-color":color1,"color":color2});
			            $(".title, .text-boss, .text-danger, .text-black").css("color",color2);
			            
			            $(".panel-heading").css({"background":color2,"color":color1});
			            $("#tax_audit .panel-heading").css({"background":color1,"color":color2});
			            $(".panel-body").css({"background-color":color1, "border":"1px solid "+color2});
			            $(".panel").css({"border":"none"});
			            $(".panel-footer").css({"background-color":color1, "border":"none","padding":"0px"});
			            
			            $("#top-page").css({"background":color2,"color":color1});
			            $(".navicon, .sr-only").css({"color":color1});
			            $(".nav-link").css({"color":color2});
			            $(".navbar-nav>li>a").css({"background-color":color1});
			            $("#loginBtn > .navbar-nav > li > .dropdown-toggle").css('cssText','background-color:'+color2+'; color:'+color1);
			            $(".label").css({"background":color2,"color":color1});
			            $("#colophon").css({"background":color1});
			            $(".btn-icon .fa").css({"background-color":"transparent", "color":"inherit"});
			            $('.b-light').css({"border-color":color2});
			            $('.foreground').css({"background-color":color2});

                  $('.btn-group .dropdown-menu a').css('cssText','background-color:'+color1+'!important;'+'color:'+color2);

                  $('head').append('<style>.dropdown-menu > li >a:hover,.dropdown-menu > li >a:focus,.dropdown-menu > .active >a,.dropdown-menu > .active >a:hover,.dropdown-menu > .active >a:focus {color:'+color1+'!important;background-color:'+color2+'!important;}.dropdown-menu > li > a {color:'+color2+';}</style>');

                  $('head').append('<style>#reloadImg{color:'+color2+'}.form-control, .selectpicker.btn-default{background-color:'+color1+';border-color:'+color2+';color:'+color2+'!important;}.form-control:focus{outline:none;border-color:'+color2+';background-color:'+color1+'!important}.selectpicker.btn-default:focus,.selectpicker.btn-default:hover,.selectpicker.btn-default:active, .selectpicker.btn-default:focus.active, .open .dropdown-toggle.selectpicker.btn-default{background:'+color1+';color:'+color2+'!important;border-color:'+color2+'!important;}.selectpicker.btn-default+.dropdown-menu.open, .selectpicker.btn-default+.dropdown-menu .dropdown-menu{background-color:'+color1+'}.bootstrap-select.btn-group .no-results{background:'+color1+'!important}#btnGetResult,#btnClearField{background:'+color1+';color:'+color2+'!important;border-color:'+color2+'}.list-tax-format article > header h3 a, .list-tax-format article .node-inner > header h2 a{border-color:'+color1+'}.list-tax-format article > header h3 a:hover, .list-tax-format article .node-inner > header h2 a:hover{border-color:'+color2+'}</style>')

			            $.cookie("style", color, {
			                expires: 365,
			                domain: getDomain(),
			                path: '/'
			            });
			            return false;
			        }
			    }

			    /*Функции изменения размера шрифта*/
			    function SmallFonts(){
			        if ($.cookie("CecutientCookie")=="on"){
			            $('body').removeClass("MediumFonts BigFonts").addClass("SmallFonts");
			            $('#content-site * a, #copyr').removeClass("MediumFonts BigFonts").addClass("SmallFonts");
			            $("#block-views-news-block-1 .panel-body").css({"padding-top":"15px"});
			            $('.touch-button').css({"width":"31px","height":"31px"});
			            
			            $.cookie("fonts", "small", {
			                expires: 365,
			                domain: getDomain(),
			                path: '/'
			            });
			            return false;
			        }
			    }
			    function MediumFonts(){
			        if ($.cookie("CecutientCookie")=="on"){
			            $('body').removeClass("SmallFonts BigFonts").addClass("MediumFonts");
			            $('#content-site * a, #copyr').removeClass("SmallFonts BigFonts").addClass("MediumFonts");
			            $("#block-views-news-block-1 .panel-body").css({"padding-top":"25px"});
			            $('.touch-button').css({"width":"41px","height":"41px"});
			            
			            $.cookie("fonts", "medium", {
			                expires: 365,
			                path: '/'
			            });
			            return false;
			        }
			    }
			    function BigFonts(){
			        if ($.cookie("CecutientCookie")=="on"){
			            $('body').removeClass("SmallFonts MediumFonts").addClass("BigFonts");
			            $('#content-site * a, #copyr').removeClass("SmallFonts MediumFonts").addClass("BigFonts");
			            $("#block-views-news-block-1 .panel-body").css({"padding-top":"35px"});
			            $('.touch-button').css({"width":"31px","height":"52px"});
			            
			            $.cookie("fonts", "big", {
			                expires: 365,
			                domain: getDomain(),
			                path: '/'
			            });
			            return false;
			        }
			    }
			    /*Функции обработчик отображения изображений*/
			    function ImageOn(){
			        if ($.cookie("CecutientCookie")=="on"){
			            $('img, #newsPhoto').css("display","inline-block");
			            $('#ImageOff').css('cssText',"display: inline-block; padding-left:10px;");
			            $('#ImageOn').css('cssText',"display: none;");
			            
			            $('#frontNews .row .col-md-3, #newsPhoto').removeClass("hidden");
			            $('#BannerFooter, .demo-2').removeClass("hidden");
			            $("#InfoBlock").removeClass("hidden");
			            $("#InfoBlock2").removeClass("hidden");
			            $("#block-block-1").removeClass("hidden");
			            $(".kgd_logo").removeClass("hidden");
			            $("#slidebox").removeClass("hidden");
			            $("#block-views-projectss-block .panel-body").removeClass("hidden");

			            $(".header #site-name a.kgd_logo, img").css('cssText', '-webkit-filter: grayscale(100%)');
			            $(".call-center").css('cssText', 'background: url(/sites/all/themes/KGD17/images/call-center-phoneGS.png) no-repeat left center; background-size: 11%;');
			            $.cookie("image", "on", {
			                expires: 365,
			                domain: getDomain(),
			                path: '/'
			            });
			            return false;
			        }
			    }
			    function ImageOff(){
			        if ($.cookie("CecutientCookie")=="on"){
			            $('img, #newsPhoto').css("display","none");
			            $('#ImageOff').css('cssText',"display: none;");
			            $('#ImageOn').css('cssText',"display: inline-block; padding-left:10px;");
			            //$('#CecutientBtn img').css("display","inline-block");
			            
			            $('#frontNews .row .col-md-3, #newsPhoto').addClass("hidden");
			            $('#BannerFooter, .demo-2').addClass("hidden");
			            $("#InfoBlock").addClass("hidden");
			            $("#InfoBlock2").addClass("hidden");
			            $("#block-block-1").addClass("hidden");
			            $(".kgd_logo").addClass("hidden");
			            $("#slidebox").addClass("hidden");
			            $("#block-views-projectss-block .panel-body").addClass("hidden");
			            $(".call-center").css('cssText', 'background: transparent;');
			            $.cookie("image", "off", {
			                expires: 365,
			                domain: getDomain(),
			                path: '/'
			            });
			            return false;
			        }
			    }

			    /*Отключение версии для слабовидящих*/
			    $('#CecutientOff').click(function(){
			        $.cookie("CecutientCookie", null);
			        $.cookie("style", null);
			        $.cookie("image", null);
			        $.cookie("fonts", null);
			        window.location.reload();
			        return false;
			    });
			});
        }
    }
})(jQuery);;/**/
(function($) {
    Drupal.behaviors.kgdCookie = {
        attach: function (context, settings) {
            jQuery.fn.center = function () {
                this.css("margin-left", (($(window).width() - this.outerWidth()) / 2) - 50 + "px");
                return this;
            }

            $(document).ready(function(){

              $('a[href$="covid-19"]').addClass('smartmenu-covid');
              $('.btn-google').removeClass('smartmenu-covid');
              $('li.kk > a').removeClass('smartmenu-covid');
              $('li.ru > a').removeClass('smartmenu-covid');
              $('li.en > a').removeClass('smartmenu-covid');

                var headertext = [],
                headers = document.querySelectorAll("#mobile th"),
                tablerows = document.querySelectorAll("#mobile th"),
                tablebody = document.querySelector("#mobile tbody");

                if (headers && tablerows && tablebody) {
                    for(var i = 0; i < headers.length; i++) {
                      var current = headers[i];
                      headertext.push(current.textContent.replace(/\r?\n|\r/,""));
                    }

                    for (var i = 0, row; row = tablebody.rows[i]; i++) {
                      for (var j = 0, col; col = row.cells[j]; j++) {
                        col.setAttribute("data-th", headertext[j]);
                      }
                    }
                }


                $('iframe:not(#akordaId)', parent.document.body).height($(document.body).height());

                $('#smartmenus_1 > li > a > .sub-arrow').remove();
                $('.btn').removeClass('active');

                $(window).on("load resize", function () {
                    $('#mobileLang > li:first-child > a').center();
                });

                if ($(window).width() <= 800 && $('body.front').length > 0) {
                    $('#mobiledepmenu').append($('#depmenu .w-full'));
                    $('#tabFront').html('');
                    $('#tabPage, #tabPage div').removeClass('hide');
                    $('#tabPage').append($('#tabFront'));
                }

                if (!String.prototype.startsWith) {
                  String.prototype.startsWith = function(searchString, position) {
                    position = position || 0;
                    return this.indexOf(searchString, position) === position;
                  };
                }

                $('.catmenu > ul li a.nolink').click(function(e) {
                    $(this).next('.menu').slideToggle();
                });

                $('a').each(function() {
                  var url = $(this).attr('href');
                  if (url && (url.substring(0,6) === ('http://') || url.substring(0,7) === ('https://'))) {
                    if (window.location.href.split("/")[2] != url.split("/")[2] && url.split("/")[2].split(".")[1] != "kgd" && url.split("/")[2].split(".")[0] != "kgd") {
                      $(this).attr('target', '_blank').click(function(e) {
                        if (!confirm(Drupal.t('You are going to external website. Continue?'))) {
                          e.preventDefault();
                        }
                      });
                    }
                  }
                });

                $('.file-widget input.form-submit').addClass('btn btn-index');

                $('table').addClass('table table-bordered');

                $('#navIco').bind('click', function(event) {
                    $('#main-nav').addClass('b-navi');
                    $('#navi').slideToggle();
                });
                $('.dMenu').bind('click', function(event) {
                    $('#caretDown').slideToggle();
                });
                // $('.base-row').each(function(){
                //     var highestBox = 50;
                //     $('li ', this).each(function(){
                //         if($(this).height() > highestBox) {
                //             highestBox = $(this).height();
                //         }ss
                //     });
                //     $('li ',this).height(highestBox);
                // });
                // if ($(window).width() <= 1024) {
                //     $('#fixed-header').scrollToFixed({
                //         marginTop: -500,
                //         zIndex: 113,
                //         dontSetWidth: true
                //     });
                // } else {
                //     $('#fixed-header').scrollToFixed({
                //         marginTop: 6,
                //         zIndex: 113,
                //         dontSetWidth: true
                //     });
                // }

                $("#indexTab").html($('.dropdown-menu a[aria-controls="eservice"]').text()+' <span class="caret"></span>');

                $('a[data-toggle="tab"]').on('shown.bs.tab', function(e){
                    var activeTab = $(e.target).text();
                    var previousTab = $(e.relatedTarget).text();
                    $("#indexTab").html(activeTab+' <span class="caret"></span>');
                });

                function hideallDropdowns() {
                    $(".dropped .drop-menu-main-sub").hide();
                    $(".dropped").removeClass('dropped');
                    $(".dropped .drop-menu-main-sub .title").unbind("click");
                }

                function showDropdown(el) {
                    var el_li = $(el).parent().addClass('dropped');
                    el_li
                        .find('.title')
                        .click(function () {
                            hideallDropdowns();
                        })
                        .html($(el).html());

                    el_li.find('.drop-menu-main-sub').show();
                }

                $(".drop-down").click(function(){
                    showDropdown(this);
                });

                $(document).mouseup(function () {
                    hideallDropdowns();
                });

                var font = $.cookie('kgd_spec_fontsize');

                $('#eye-'+font).addClass('active');
                $('#fixed-down').css({'display':'none'});

                var $menu = $("#fixed-div");

                if ($(window).scrollTop() > 300 && $menu.hasClass("no-scroll")) {
                    $menu.removeClass("no-scroll").addClass("scroll");
                } else if ($(window).scrollTop() <= 300 && $menu.hasClass("scroll")) {
                    $menu.removeClass("scroll").addClass("no-scroll");
                }

                $(window).scroll(function () {
                    if ($(this).scrollTop() > 300 && $menu.hasClass("no-scroll")) {
                        $menu.removeClass("no-scroll").addClass("scroll");
                    } else if ($(this).scrollTop() <= 300 && $menu.hasClass("scroll")) {
                        $menu.removeClass("scroll").addClass("no-scroll");
                    }
                });
                $(context).on('click', "#print", function (event) {
                    //console.log(event);
                    var printing_css='<style media=print>body {font-family: Times, serif;} .tabs-wrapper, ul.links, .pagination {display:none;} #site-name {font-size:18px; height:90px; padding-top:25px; text-transform: uppercase;} #site-name strong {display: block; font-weight: 700;} #site-name a {color: #1b1f21; border: none; display: inline-block; text-decoration: none;} #site-name a span{ vertical-align: middle; display: inline-block; line-height: 1.2; margin-left: 10px;} .logo-top {position:relative; float:left;} .breadcrumb {margin-top:20px; margin-bottom:10px;} .pull-right-block {width: 100%; text-align: right; display: block;} .content > .pic > img {width:40%; float:left; margin-right:15px; margin-bottom:15px;} #PrintContent > .content {width:100%; padding-top:10px;} .pull-left {float:left; margin:5px;} .header {position: relative;padding: 10px 0;float: left;} .title-news {font-size: 18px; font-weight: 600; display: block;} .element-invisible, .tabs, .contextual-links, .contextual-links-trigger, .contextual-links-trigger-active, .contextual-links-wrapper, .contextual-links-processed, .widgets-top-right, .header_right, .nav-bar, p.external {position: absolute !important; clip: rect(1px 1px 1px 1px); clip: rect(1px, 1px, 1px, 1px); overflow: hidden; height: 1px;</style>';
                    var logo_to_print='<img class="logo-top" src="/sites/all/themes/KGD17/images/kgd-logo.png?update_v1">';
                    var logotxt_to_print=$('.header').html();
                    var title_to_print=$('#fixed-header').html();
                    var html_to_print=$('#content-wrap').html();
                    var iframe=$('<iframe id="print_frame">');
                    $('body').append(iframe);
                    var win = iframe[0].contentWindow;
                    win.document.getElementsByTagName('body')[0].innerHTML=logo_to_print+logotxt_to_print+html_to_print+printing_css;
                    win.focus();
                    win.print();
                    $('iframe').remove();
                    event.preventDefault();
                });

                $("#nav").navgoco({
                    caretHtml: '',
                    accordion: false,
                    openClass: 'open',
                    save: true,
                    cookie: {
                        name: 'navgoco',
                        expires: false,
                        path: '/'
                    },
                    slide: {
                        duration: 400,
                        easing: 'swing'
                    }
                    // Add Active class to clicked menu item
                });

                $("#collapseAll").click(function(e) {
                    e.preventDefault();
                    $("#nav").navgoco('toggle', false);
                });

                $("#expandAll").click(function(e) {
                    e.preventDefault();
                    $("#nav").navgoco('toggle', true);
                });

                $(function() {
                    $('#main-menu').smartmenus({
                        subMenusSubOffsetX: 1,
                        subMenusSubOffsetY: -8,
                        showOnClick: true,
                        hideOnClick:true,
                        noMouseOver:true
                    });
                });
                $(function() {
                    $('#dep-menu').smartmenus({
                        subMenusSubOffsetX: 1,
                        subMenusSubOffsetY: -8,
                        showOnClick: true,
                        hideOnClick:true,
                        noMouseOver:true
                    });
                });
                $.datepicker.setDefaults($.datepicker.regional[settings.locale]);

                $('#toggleMap').on('click', function(event) {
                     $('#showMap').slideToggle('medium');
                });
            });
            // switch to default version of site
            $('.a-simple', context).click(function () {
                $.cookie('kgd_spec_version', 'normal', {path: '/', domain: getDomain()});
                $('body').removeClass('eye').addClass('normal');
                $.cookie('kgd_spec_color', 'c1', {path: '/', domain: getDomain()});
                $('body').removeClass('c1 c2 c3 c4 c5').addClass('c1');
                $.cookie('kgd_spec_img', 'imageson', {path: '/', domain: getDomain()});
                $('body').removeClass('imagesoff').addClass('imageson');
            });

            // switch to impared version of site
            $('#eye', context).click(function () {
                $.cookie('kgd_spec_version', 'eye', {path: '/', domain: getDomain()});
                $('body').removeClass('normal').addClass('eye');
                //updatemason();
            });

            $('.a-colors a').click(function () {
                var kgd_spec_color = $(this).attr('rel');
                $('dl.a-colors a').removeClass('active');
                $('dl.a-colors .a-' + $(this).attr('rel') + ' a').addClass('active');
            });

            $('.a-fontsize a').click(function () { updateFontSize(this); });
            $('.set-font-size a').click(function () { updateFontSize(this); });

        }
    }
    var top_show = 250;
    var delay = 1000;
    $(document).ready(function($) {
        if ($(window).width() <= 1024) {
            $('#fixed-header').scrollToFixed();
            $(window).scroll(function () { // При прокрутке попадаем в эту функцию
                /* В зависимости от положения полосы прокрукти и значения top_show, скрываем или открываем кнопку "Наверх" */
              if ($(this).scrollTop() > top_show) { $('#fixed-down').fadeIn(); } else { $('#fixed-down').fadeOut(); }
            });
        } else {
            $('#fixed-header').scrollToFixed();
            $(window).scroll(function () {
                if ($(this).scrollTop() > top_show) {
                    $('#fixed-down').fadeIn();
                    $('#fixed-header').removeClass('cur-vt-none').addClass('cur-vt');
                    $('#fixed-header').animate({
                        scrollTop: 0
                    }, delay, "easeInOutCirc");
                }
                else {
                    $('#fixed-down').fadeOut();
                    $('#fixed-header').removeClass('cur-vt').addClass('cur-vt-none');
                }
            });
        }
        $('#fixed-down').click(function () { // При клике по кнопке "Наверх" попадаем в эту функцию
            /* Плавная прокрутка наверх */
            $('body, html').animate({
                scrollTop: 0
            }, delay, "easeInOutCirc");
        });
    });
    function getDomain() {
        var fulldomainname = document.domain;
        var domain_levels = fulldomainname.split(".");
        var domain_level = domain_levels.length;
        var all_domains = "." + domain_levels[domain_level-3] + "." + domain_levels[domain_level-2] + "." + domain_levels[domain_level-1];
        return all_domains;
    }
    function updateFontSize(elem) {
        var kgd_spec_fontsize = $(elem).attr('rel');
        $('.a-fontsize a').removeClass('active');
        $('.set-font-size a').removeClass('active');
        $(elem).addClass('active');
        $('body').removeClass('font-small font-normal font-big').addClass(kgd_spec_fontsize);
        $.cookie('kgd_spec_fontsize', kgd_spec_fontsize, {path: '/', domain: getDomain()});
        //updatemason();
        //sliderheight();
    }
    // function updatemason() {
    //     var $container = $('.list-news');
    //     $container.masonry({
    //         itemSelector: '.item'
    //     });
    // }
    function sliderheight() {
        if ($('#slider').length > 0) {
            var kgd_spec_fontsize = $.cookie('kgd_spec_fontsize');
            // console.log(kgd_spec_fontsize);
            if ($('body').hasClass('logged-in')) {
                var innh = 355;
                var innu = 315;
                if (kgd_spec_fontsize == 'font-normal') {
                    innh = 446;
                    innu = 406;
                }
                if (kgd_spec_fontsize == 'font-big') {
                    innh = 507;
                    innu = 467;
                }
            }
            else {
                var innh = 375;
                var innu = 335;
                if (kgd_spec_fontsize == 'font-normal') {
                    innh = 426;
                    innu = 386;
                }
                if (kgd_spec_fontsize == 'font-big') {
                    innh = 487;
                    innu = 447;
                }
            }
            //$('#slider').attr("style", "height: " + innh + "px !important");
            //$('.section-top .user-panel').attr("style", "height: " + innu + "px !important");
        }
    }

    $(document).ready(function(){

        var kgd_spec_version = $.cookie('kgd_spec_version');
        if (kgd_spec_version === undefined || kgd_spec_version == null) {
            kgd_spec_version = 'normal';
            $.cookie('kgd_spec_version', kgd_spec_version, {path: '/', domain: getDomain()});
            if (!$('body').hasClass(kgd_spec_version)) {
                $('body').addClass(kgd_spec_version);
            }
        }
        else {
            if (!$('body').hasClass(kgd_spec_version)) {
                $('body').addClass(kgd_spec_version);
            }
        }

        var kgd_spec_color = $.cookie('kgd_spec_color');
        if (kgd_spec_color === undefined || kgd_spec_color == null) {
            kgd_spec_color = 'c1';
            $.cookie('kgd_spec_color', kgd_spec_color, {path: '/', domain: getDomain()});
            if (!$('body').hasClass(kgd_spec_color)) {
                $('body').addClass(kgd_spec_color);
            }
        }
        else {
            if (!$('body').hasClass(kgd_spec_color)) {
                $('body').addClass(kgd_spec_color);
            }
        }
        $('.a-' + kgd_spec_color + ' a').addClass('active');

        var kgd_spec_fontsize = $.cookie('kgd_spec_fontsize');
        if (kgd_spec_fontsize === undefined || kgd_spec_fontsize == null) {
            kgd_spec_fontsize = 'font-small';
            $.cookie('kgd_spec_fontsize', kgd_spec_fontsize, {path: '/', domain: getDomain()});
            if (!$('body').hasClass(kgd_spec_fontsize)) {
                $('body').removeClass('font-small').removeClass('font-normal').removeClass('font-big').addClass(kgd_spec_fontsize);
            }
        }
        else {
            if (!$('body').hasClass(kgd_spec_fontsize)) {
                $('body').removeClass('font-small').removeClass('font-normal').removeClass('font-big').addClass(kgd_spec_fontsize);
            }
        }
        $('.a-' + kgd_spec_fontsize + ' a').addClass('active');

        var kgd_spec_img = $.cookie('kgd_spec_img');
        if (kgd_spec_img === undefined || kgd_spec_img == null) {
            kgd_spec_img = 'imageson';
            $.cookie('kgd_spec_img', kgd_spec_img, {path: '/', domain: getDomain()});
            if (!$('body').hasClass(kgd_spec_img)) {
                $('body').addClass(kgd_spec_img);
            }
        }
        else {
            if (!$('body').hasClass(kgd_spec_img)) {
                $('body').addClass(kgd_spec_img);
            }
        }
        if (kgd_spec_img == 'imageson') {
            $('.a-imagesoff').addClass('active');
        }

        //updatemason();
        //sliderheight();
    });

    function changeMobileIcons() {
        apple = $("#apple-icon img");
        android = $("#android-icon img");
        appleC5 = "/sites/all/themes/KGD17/images/apple_app_c5.png";
        appleC2 = "/sites/all/themes/KGD17/images/apple_app_c2.png";
        androidC5 = "/sites/all/themes/KGD17/images/pm_app_c5.png";
        androidC2 = "/sites/all/themes/KGD17/images/pm_app_c2.png";
        androidDefault = "/sites/all/themes/KGD17/images/pm_app.png";
        appleDefault = "/sites/all/themes/KGD17/images/apple_app.png";
        if($.cookie('kgd_spec_color') && $("body").hasClass("eye")){

            switch ($.cookie('kgd_spec_color')) {
                case "c5": apple.attr("src",appleC5);android.attr("src",androidC5);break;
                case "c2": apple.attr("src",appleC2);android.attr("src",androidC2);break;
                case "c1": apple.attr("src",appleDefault);android.attr("src",androidDefault);break;
                case "c3": apple.attr("src",appleDefault);android.attr("src",androidDefault);break;
                case "c4": apple.attr("src",appleDefault);android.attr("src",androidDefault);break;
            }
        } else {
            apple.attr("src",appleDefault);
            android.attr("src",androidDefault);
        }
    }

    $(document).ready(function($) {

        changeMobileIcons();
        if ($(".exchange-rates").length > 0) getCurrency(function(data){
            for (i = 0; i < data.length; i++) {
                el = $('.exchange-rates .'+ data[i].title);
                el.find('.rate').html(data[i].value);
                if (data[i].change > 0) {
                    el.find('#ico').addClass('fa fa-angle-up m-l-xs text-boss');
                    el.find('.rate').addClass('text-boss text-boss');
                } else if (data[i].change < 0) {
                    el.find('#ico').addClass('fa fa-angle-down m-l-xs text-danger');
                    el.find('.rate').addClass('text-danger');
                } else {
                    el.find('.rate').addClass('text-black');
                }
            }
        });

        $(".search input").attr("placeholder", Drupal.t("Search on site"));

        $('.search .clear').click(function () {
            $('.search input').val('');
        });

        //$('.element-list .content').jScrollPane({ autoReinitialise: true });

        /*
         $(window).resize(function() {
         if ( $(window).width() <= 600) {
         var element = $('.element-list').jScrollPane({});
         var api = element.data('jsp');
         api.destroy();
         } else {
         $('.element-list').jScrollPane();
         }
         });

         */
        var lang = ($('html').attr('lang') != undefined) ? $('html').attr('lang') : 'ru';
        $.datepicker.setDefaults($.datepicker.regional[lang]);

        var events = [
            { id: "20", Date: new Date("12/20/2014") },
        ];

        $( "#datepicker" ).datepicker({
            dateFormat: 'mm/dd/yy',
            beforeShowDay: function(date) {
                var result = [true, '', null];
                var matching = $.grep(events, function(event) {
                    return event.Date.valueOf() === date.valueOf();
                });

                if (matching.length) {
                    result = [true, 'highlight-date', null];
                }
                return result;
            },
            onSelect: function(dateText) {
                var date,
                    selectedDate = new Date(dateText),
                    i = 0,
                    event = null;
                while (i < events.length && !event) {
                    date = events[i].Date;
                    if (selectedDate.valueOf() === date.valueOf()) {
                        event = events[i];
                    }
                    i++;
                }
        //         if (event) {
        //             //в базе аяксом по айди евента (event.id) ищите и выводите справа, на текущую дату и на дату ближайшую на которой что-то есть

        // //              пока идет запрос на див #listTasks добавляете класс ajax-loader
        // //              когда запрос заканчивается класс удаляете и выводите то что найдено в шаблоне как в разметке. Если дата сегодняшняя то ставим класс today где необходимо ( в разметку пример есть )



        //             /*То что ниже можно удалить это просто для визуальной наглядности*/

        //             $('#listTasks').addClass("ajax-loader");
        //              setTimeout(function(){
        //              $('#listTasks').html('<div class="date"><strong>'+event.id+'</strong> дек.</div><div class="task"><a>Налог на&nbsp;прибыль организаций</a></div><div class="task"><a>Страховые взносы в&nbsp;Пенсионный фонд Республики Казахстан</a></div><div class="task"><a>Страховые взносы в&nbsp;Республиканский фонд обязательного мед. страхования</a></div>');
        //              $('#listTasks').removeClass("ajax-loader");
        //              }, 2000);

        //             /*/конец того что можно удалить*/

        //         }
            }
        });



        $('.lang a[lang]').click(function () {
            var lang = ($(this).attr('lang') != undefined) ? $(this).attr('lang') : 'ru';
            $('#datepicker').datepicker('destroy').datepicker($.datepicker.regional[lang]);
            $('.lang a[lang]').removeClass("active");
            $(this).addClass("active");
        });



        // var $container = $('.list-news');

        // $container.masonry({
        //     itemSelector: '.item'
        // });

        // $container.imagesLoaded( function() {
        //     $container.masonry();
        // });

        // $('.news-view .icn-list').click(function () {
        //     $('.list-news').removeClass('grid-view');
        //     $('.list-news').addClass('list-view');
        //     $container.masonry({
        //         itemSelector: '.item'
        //     });
        //     $('.news-view .icn-grid').removeClass('active');
        //     $(this).addClass('active');
        // });

        // $('.news-view .icn-grid').click(function () {
        //     $('.list-news').removeClass('list-view');
        //     $('.list-news').addClass('grid-view');
        //     $container.masonry({
        //         itemSelector: '.item'
        //     });
        //     $('.news-view .icn-list').removeClass('active');
        //     $(this).addClass('active');
        // });
        // $('.news-view .icn-image').click(function () {
        //     $('.list-news').toggleClass('hide-image');
        //     $container.masonry({
        //         itemSelector: '.item'
        //     });
        //     $container.imagesLoaded( function() {
        //         $container.masonry();
        //     });
        //     $(this).toggleClass('active');
        // });


        $('.user-panel-toggle').click(function () {
            var panel = $('.user-panel');
            panel.toggleClass('close');
        });

        $('#login').click(function () {
            dialogShow($(this));
            return false;
        });
        $('#loginMobile').click(function () {
            dialogShow($(this));
            return false;
        });


        $('#forumlogin').click(function () {
            dialogShow($(this));
            return false;
        });


        $('#domainList').click(function () {
            dialogShow($(this));
            return false;
        });

        $('#cityList').click(function () {
            dialogShow($(this));
            return false;
        });


        function dialogShow($this){
            var overlay = $('.overlay').length ?  $('.overlay') : $('<div class="overlay"></div>') ;
            var id = $this.attr('data-id-dialog');

            if(id!=undefined){
                var dialog = $('#'+id) ;
                if(dialog.hasClass('dialog')){
                    $('body').append(overlay);
                    $('html').addClass('hide-overflow');
                    overlay.fadeIn();
                }

                if(dialog.hasClass('dialog')){
                    dialog.css('margin-top', dialog.outerHeight()/(-2) ).css('margin-left', dialog.outerWidth()/(-2) ).fadeIn();
                }

                if(dialog.hasClass('local-dialog')){
                    dialog.css('top', $this.offset().top ).css('left', $this.offset().left ).fadeIn();
                }

                dialog.find('#closeModal').click(function () {
                    dialog.fadeOut();
                    overlay.fadeOut();
                    setTimeout(function(){
                        $('html').removeClass('hide-overflow');
                    }, 300);
                });

                if(dialog.hasClass('dialog')){
                    overlay.click(function () {
                        dialog.fadeOut();
                        overlay.fadeOut();
                        setTimeout(function(){
                            $('html').removeClass('hide-overflow');
                        }, 300);
                    });
                }

            }
        }

        function getCurrency(callback) {
            data_url = 'http://kgd.gov.kz/get_currency';
            $.ajax({
                dataType: "jsonp",
                url: data_url,
                success: callback
            });
        }


        $('.nav-toggle').click(function () {
            $(this).closest('.nav').toggleClass("open");
        });

        $('.icn-remove').click(function () {
            $('input#edit-search-block-form--2').val('');
        });

        if ($('#slider .slide img').length > 1) {
            $('#slider').slidesjs({
                preload: true,
                width: 1300,
                height: 355,
                navigation: false,
                pagination: {
                    effect: "fade"
                },
                play: {
                    effect: "fade",
                    interval: 15000,
                    auto: true
                },
                animationStart: function (current) {
                    $('.caption').animate({
                        bottom: -35
                    }, 100);
                },
                animationComplete: function (current) {
                    $('.caption').animate({
                        bottom: 0
                    }, 200);
                },
                slidesLoaded: function () {
                    $('.caption').animate({
                        bottom: 0
                    }, 200);
                }
            });
        }
    });

  (function ($) {
    Drupal.behaviors.recaptchaAjax = {
      attach: function (context, settings) {
        if ('grecaptcha' in window && context !== document) {
          $('.g-recaptcha:empty', context).each(function () {
            grecaptcha.render(this, $(this).data());
            setTimeout(function () {
              jQuery('div.g-recaptcha > div > div > iframe').css('height','100px');
            },100);
          });
        }
      }
    };
  })(jQuery);


})(jQuery);
;/**/
