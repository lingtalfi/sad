Sad
=============
2016-09-24



Sad is a methodology to create reusable html modules with performances and accessibility in mind.




Sad stands for Structure Accessibility Design.
Those 3 words actually represent the workflow used by sad:


- first you start by building the html structure.
    At this stage, you think browser, seo, performances (load time), and accessibility.
    There is no design consideration at all in this stage.
    In fact, it's recommended that you disable styles while developing your html module at this stage.
    Html alone (without css) is ugly, but it's how the browser sees your page.
    
    You also might want to think about how you will target your elements in the other phases (accessibility
    and design). I personally use the [shy](https://github.com/lingtalfi/shy) system.
     
     
- second, you add the accessibility layer.
     I recommend that you follow the wai-aria guidelines (what other choices do we have?).
     So, make sure to test your "html module" with accessibility tools like voice over, and or chrome vox,
     implement focus and keyboard behaviour, all that stuff....
     Be sure to make smart use of js (reuse components if you can), because you want a performant module. 
     Note: at this point, your module is still ugly, but it's now usable by anybody.
     
     
- third, the design.
     I personally use Google's material, but at that phase you have the choice.
     However, you should always aim at silky smooth animations (if you have animations),
     because again, you want a fast page (performance again).
      
        
    
    
 
That's it.
Happy coding.