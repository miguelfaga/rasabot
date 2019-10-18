## greetings
* greet
  - utter_greet

## user_asks_docs_missing_info
* greet
  - utter_greet
* document_query{"destination"}
  - utter_ask_nacionality
* inform{"departure"}
  - action_check_docs
* thanks
  - utter_welcome

## user_ask_docs_all_info
* document_query{"destination", "departure"}
  - action_check_docs
* thanks
  - utter_welcome
