# PersianYearCalendar


#### Preview

![persianyearcalendar](https://github.com/mahdinai/PersianYearCalendar/blob/master/preview.JPG)

#### Usage

1- include jQuery & bootstrap-rtl.min.css & PersianYearCalendar.css & PersianYearCalendar.js

``` html

<script src="http://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
<link rel="stylesheet" href="css/bootstrap-rtl.min.css">
<link rel="stylesheet" href="css/PersianYearCalendar.css">
<script src="js/PersianYearCalendar.js"></script>

```

2- add your div tag

``` html
<div class="persianyearcalendar yearview table-responsive"></div>
```

**Notice** : you can change persianyearcalendar class name But (yearview & table-responsive) class name is **required**

3- call the persianyearcalendar plugin

``` html

<script type="text/javascript">
		
		jQuery(".persianyearcalendar").mahdinaseri_calendar({
			classname:".persianyearcalendar"
        });
        
</script>

```

#### Options

``` html

  <script>

        jQuery(".persianyearcalendar").mahdinaseri_calendar({
            empty_box: "*",
            current_day: 2,
            current_month: 5,
            current_year: 1395,
            DayonClick: function (date) {
            }
        });
    </script>
    
 ```
**Notice 1** : if (current_day & current_month & current_year) be empty persianyearcalendar get current day date from javascript and you can set date from server with top example
