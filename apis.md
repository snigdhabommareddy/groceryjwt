/*****Get all user******/
(GET)>


/*******register*********/
(POST)>
(body)=>{ }

/******Login***********/
(POST)>
(response)=>{auth:true,token:'abc'}


/********userinfo********/
(GET)>
(header) =>{'y-access-token':'token value from login'}