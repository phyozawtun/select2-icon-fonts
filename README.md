# README.md

## 1. Include require CSS and JS file
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.6-rc.0/css/select2.min.css">
<link rel="stylesheet" href="https://unicons.iconscout.com/release/v4.0.0/css/line.css">

<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/select2/4.0.13/js/select2.min.js"></script>

## 2. Declare Select2 Options
```
<script>
    ...
    // Declare Select2 Options
    $('.select2-icon').select2({
        data: json2,
        placeholder: "Select an Unicons icon",
        allowClear: true,
        templateResult: function(state) {
            var $state = $('<span><i class="uil uil-'+state.name+'"></i> '+state.name+'</span>');
            return $state;
        }
    });
    ...
</script>
```

## 3. Declare Select2 Options
```
<script>
    ...
    $('.select2-icon').select2({
        data: json2,
        placeholder: "Select an Unicons icon",
        allowClear: true,
        templateResult: function(state) {
            var $state = $('<span><i class="uil uil-'+state.name+'"></i> '+state.name+'</span>');
            return $state;
        }
    });
    ...
</script>
```