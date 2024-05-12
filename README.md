# CAP-60Days-State-Management-Techniques-and-useState-Hook

<div className="parent">
          <form>
            <label for="hobbie">Hobbie : </label>
            <input type="text" placeHolder="Enter your hobbie"/>
            <br/>
            <button type="submit">Submit</button>
            </form>

          <div>
            <div>
                 <h3>Playing Cricket</h3>
                 <p>Wow! That's Awesome</p>
            </div>
            </div>
        </div>


        .parent{
      border: 2px solid rgba(0, 0, 0, 0.096);
      padding: 2%;
      height: 88vh;
     }
     button{
      width: 90%;
      margin-top: 2%;
      height: 6vh;
      background-color: crimson;
      border: none;
      color: white;
      box-shadow: rgba(9, 30, 66, 0.25) 0px 4px 8px -2px, rgba(9, 30, 66, 0.08) 0px 0px 0px 1px;
     }
     input{
      width: 71%;
     }
     .parent>form{
      border: 1px solid rgba(3, 3, 3, 0.205);
      width: 30%;
      padding: 1%;
      margin: 1%;
      text-align: center;
      box-shadow: rgba(9, 30, 66, 0.25) 0px 4px 8px -2px, rgba(9, 30, 66, 0.08) 0px 0px 0px 1px;
     }
     .parent>div{
      border: 1px solid rgba(7, 7, 7, 0.219);
      width: 90%;
      margin-left: 1%;
      padding: 2%;
      box-shadow: rgba(9, 30, 66, 0.25) 0px 4px 8px -2px, rgba(9, 30, 66, 0.08) 0px 0px 0px 1px;
      display: grid;
      grid-template-columns: repeat(4,1fr);
      gap: 20px;
     }
     .parent>div>div{
      border: 1px solid rgba(0, 0, 0, 0.393);
      width: 20vw;
      padding: 0% 2%;
      box-shadow: rgba(253, 5, 5, 0.562) 0px 2px 4px, rgba(0, 0, 0, 0.3) 0px 7px 13px -3px, rgba(0, 0, 0, 0.2) 0px -3px 0px inset;
     }