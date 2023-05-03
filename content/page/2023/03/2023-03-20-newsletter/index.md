---
title: "Newsletter"
date: "2023-03-20"
---

### Subscribe for newsletter

<div>
    <form name="contactform" method="POST" action="index.php">                  
        <div class="form-row">
            <div class="form-group col-lg-6" id="name">
                <input type="text" class="form-control" placeholder="name" required="True" name="name" data-rule="minlen:4" data-msg="Please enter at least 4 chars">
            </div>
            <div class="form-group col-lg-6" id="mail">
                <input type="email" class="form-control" placeholder="Email" name="email" data-rule="email" data-msg="Please enter a valid email">
            </div>
        </div>  
        <div class="text-center"><button type="submit" id="button" name="submit" title="Send Message">Subscribe now</button></div>
    </form>
</div>
