# jQuery val()
This project is the form including input, checkbox, and finally using val() to get values.<br>
text,date,range: $("#id").val();<br>
switch, dropdown: $("#id option:checked").val();<br>
option: $("input[name=name]:checked").val();<br>
checkbox: $ ("input[type='checkbox']:checked").each(function(){checkboxSave += $(this).val()+" ";});<br>
