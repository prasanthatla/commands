## Generated Story -6520783467905744743
* greet
    - utter_greet
* pendingreport
    - pending_report

## Generated Story -8336484008990275207
* greet
    - utter_greet
* createreportfull{"name": "australia"}
    - slot{"name": "australia"}
    - create_report_form
    - form{"name": "create_report_form"}
    - slot{"requested_slot": "startdate"}
* form: enterdata
    - form: create_report_form
    - slot{"startdate": "10/02/2019"}
    - slot{"requested_slot": "enddate"}
* form: enterdata
    - form: create_report_form
    - slot{"enddate": "30/03/2019"}
    - form{"name": null}
    - slot{"requested_slot": null}
* bye
    - utter_goodbye
