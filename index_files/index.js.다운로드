$(function(){

  $('.title').click(function(){
    $(this).addClass('active')
    $(this).siblings('.title').removeClass('active')
    $(this).siblings('.desc').stop().slideUp()
    $(this).next().stop().slideDown()

    var img = $(this).attr('data-img')
    $('.image img').attr('src',img)
    })


})