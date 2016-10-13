# export-google-form
A small Google Apps Script file to export a form into a JSON file.

### Installation

* Create a Google Apps script.


### Example output

This example output is for [this form](https://docs.google.com/forms/d/e/1FAIpQLScPzx56zhMgV_iTxrm7F6O7-uFhqKYnuP2lda1OeL_ohAQsmw/viewform).

```json
{
   "metadata":{
      "title":"Fun information",
      "id":"12XJWWr-Z8gkRdxrkwoU8CYg1h8GqWv3OJh-AOLzpyyQ",
      "description":"",
      "publishedUrl":"https://docs.google.com/forms/d/e/1FAIpQLScPzx56zhMgV_iTxrm7F6O7-uFhqKYnuP2lda1OeL_ohAQsmw/viewform",
      "editorEmails":[
         "stevenschmatz@gmail.com"
      ],
      "count":13,
      "confirmationMessage":"Thanks for submitting your contact info!",
      "customClosedFormMessage":""
   },
   "items":[
      {
         "type":"TEXT",
         "helpText":"",
         "title":"Name",
         "index":0,
         "id":1633920210,
         "isRequired":false
      },
      {
         "type":"TEXT",
         "helpText":"",
         "title":"Email",
         "index":1,
         "id":227649005,
         "isRequired":true
      },
      {
         "type":"PARAGRAPH_TEXT",
         "helpText":"",
         "title":"Address",
         "index":2,
         "id":790080973,
         "isRequired":true
      },
      {
         "type":"MULTIPLE_CHOICE",
         "helpText":"",
         "index":3,
         "id":1770822543,
         "title":"How much do you like choices?",
         "isRequired":false,
         "hasOtherOption":true,
         "choices":[
            "Option 1",
            "Option 2"
         ]
      },
      {
         "type":"CHECKBOX",
         "helpText":"",
         "index":4,
         "id":1846923513,
         "title":"How much do you like checkboxes?",
         "isRequired":false,
         "hasOtherOption":true,
         "choices":[
            "Option 1 Check",
            "Option 2 Check"
         ]
      },
      {
         "type":"LIST",
         "helpText":"",
         "index":5,
         "id":449887830,
         "title":"How much do you like dropdowns?",
         "isRequired":false,
         "choices":[
            "Option 1 Dropdown",
            "Option 2 Dropdown",
            "Option 3 Dropdown"
         ]
      },
      {
         "type":"SCALE",
         "helpText":"",
         "index":6,
         "id":1522153189,
         "upperBound":5,
         "title":"How much do you like scales?",
         "rightLabel":"Not fun",
         "leftLabel":"Fun",
         "lowerBound":1,
         "isRequired":false
      },
      {
         "type":"GRID",
         "helpText":"",
         "index":7,
         "id":271830833,
         "rows":[
            "Row 1",
            "Row 2"
         ],
         "columns":[
            "Column 1",
            "Column 2"
         ],
         "title":"How much do you like grids?",
         "isRequired":true
      },
      {
         "type":"DATE",
         "helpText":"",
         "index":8,
         "id":132128974,
         "title":"When were you born?",
         "isRequired":true,
         "includesYear":true
      },
      {
         "type":"TIME",
         "helpText":"",
         "title":"What time is it right now?",
         "index":9,
         "id":241877230,
         "isRequired":false
      },
      {
         "type":"SECTION_HEADER",
         "helpText":"No questions here.",
         "title":"This is a title.",
         "index":10,
         "id":1461919302
      },
      {
         "type":"VIDEO",
         "helpText":"",
         "index":11,
         "id":1219208494,
         "width":320,
         "title":"This is a YouTube video.",
         "alignment":"LEFT"
      },
      {
         "type":"PAGE_BREAK",
         "helpText":"Please work.",
         "title":"This is a new section.",
         "index":12,
         "pageNavigationType":{

         },
         "goToPage":null,
         "id":259261228
      }
   ],
   "count":13
}
```
