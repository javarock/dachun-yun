
$(function(){
	
var bodyW=$("body").width();


if(bodyW<800){
	
$(".slides img").each(function() {
  
 
  $(this).attr("src",$(this).attr("data-sm"))
  
});		
}


/*手机屏幕*/
if(bodyW<=767){
	
$(".otherCSS").addClass("xsScreen");	
}else if(bodyW>=768 && bodyW<950){
	
$(".otherCSS").addClass("ipad");
$(".newsTab .newsCt ul li:nth-child(2n)").css("float","right");
	
}else if(bodyW>951){	
$(".otherCSS").addClass("Middle");
$(".newsTab .newsCt ul li:nth-child(2n)").css("float","right");	
	
}

//新闻
$(".newsTab .newsCt:eq(0)").show();
$(".newsBox a:eq(0)").addClass("active");

$(".newsBox a").hover(function(){
	
	$(this).addClass("active").siblings().removeClass("active");
	var index=$(this).index();
	$(".newsTab .newsCt").eq(index).show().siblings().hide();
	
});


//链接
$(".link p").width($(".link").width()-100);

//案例

//公司简介
$(".company .comTab a:last-child").css({"border-right-width":"1px","border-right-color":"#007cd9","border-right-style":"solid"});

$(".comTab a:eq(0)").addClass("active");
$(".companyConn .companyCT:eq(0)").show();

$(".comTab a").click(function(){
	
$(this).addClass("active").siblings().removeClass("active");	
var index=$(this).index();
$(".companyConn .companyCT").eq(index).show().siblings().hide();
	
});

//常见问题

$(".qBox ul li").click(function(){
	
$(this).children("div").toggle();

});


$(".trust ul.eee li:eq(0)").children("h5").addClass("active");
$(".nnnBox .nnn:eq(0)").show();
$(".trust ul.eee li").click(function(){
	
	$(this).children("h5").addClass("active").parent().siblings().children("h5").removeClass("active");
	var index=$(this).index();
	
	$(".nnnBox .nnn").eq(index).show().siblings().hide();
	
})


$(".slides li").width('100%');



});
