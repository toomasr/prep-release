Prepare Release
============

You know this feeling when tests are not all green but you would like to believe they are? Here is a snippet that you can use to make this release green. Just drag the following button to your bookmark bar and next time you are on your Jenkins page just give it a shot :)

 <h2><a href='javascript:(function() {
        $$("img[alt=\"Failed\"]").each(function(item){item.src=$$("img[alt=\"Success\"]").first().src});
        $$("img[alt=\"Pending\"]").each(function(item){item.src=$$("img[alt=\"Success\"]").first().src});
        $$("img[alt=\"Disabled\"]").each(function(item){item.src=$$("img[alt=\"Success\"]").first().src});
        $$("img[alt=\"Aborted\"]").each(function(item){item.src=$$("img[alt=\"Success\"]").first().src});
        $$("img[alt=\"In progress\"]").each(function(item){item.src=$$("img[alt=\"Success\"]").first().src});
        $$("img[alt=\"Unstable\"]").each(function(item){item.src=$$("img[alt=\"Success\"]").first().src});
        }())
        '>Prep Release</a></h2>
