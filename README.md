Hello-World
===========

my first test post

#pragma strict
 
var Speed = 1;
var acl = 2; 
// a variable for accelration 

function Update () {

         if (Input.GetKey (KeyCode.UpArrow)) transform.Translate (Vector3(0,1,0) * Time.deltaTime*Speed);
         if (Input.GetKey (KeyCode.DownArrow)) transform.Translate (Vector3(0,-1,0) * Time.deltaTime*Speed);
         if (Input.GetKey (KeyCode.LeftArrow)) transform.Translate (Vector3(-1,0,0) * Time.deltaTime*Speed);
         if (Input.GetKey (KeyCode.RightArrow)) transform.Translate (Vector3(1,0,0) * Time.deltaTime*Speed);
     }
