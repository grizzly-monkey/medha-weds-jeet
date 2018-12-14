# medha-weds-jeet
You are cordially intvited to our Wedding.


                          .-------------------.
                         /  Finally they are    \
                         \  getting hitched.    /
                          ) _________________.'
                         /.'   )
                        /'    (\\\
     \   /    .-.  .---.  .-. ()  )                  .------------------------.
      \ /    (   `'     `'   )/ \/                  ( Let's go to bless them!  )
       X      \    @   @    //  /\                   ) .----------------------'
    ((O(O      `._  / \  _.'/  /  `.                /.'
     `.  `--------\_| |_/--'  /     `-.         (()/'
       `.______     | |V     (         `/`.     ..\
               )     \ \_,    \       _/   `.  <_  \
              /  /    `._; \.  `-----'/      `.  )) L .-'
             (  (           |`.______/       .-\''_ |/
              \  `.   _.--'\|       /       /`. ((__/
       .-.    |`.  `./\    _\     .'       /   (_____)
      /   `-._|__\\\(| \.-' |__.-'        /     {===}
     /            ````. |   |            /      {===}
    /_                 `.--'            /       {===}
        
        
        
    
```Java

/**
 * Copyright (c) 2019- 7 janams. All Rights Reserved.
 * Author: Medha Mehta & Jeet Parmar
 */

public final class Wedding {

  private String groom;
  private String bride;

  private void setBride() {
    this.bride = "Medha Mehta";
  }

  private void setGroom() {
    this.groom = "Jeet Parmar";
  }

  public List<String> getWeddingEvents() {

    final List<String> events = new ArrayList<>();

    events.add("Ring Ceremony 7:00 PM 9th March 2019");
    events.add("Sangeet 7:00 PM onwards 9th March 2019");
    events.add("Haldi 4:00 PM 10th March 2019");
    events.add("Wedding 8:00 PM 10th March 2019");
    return events;
  }

  protected void inviteForBlessings(String invitee) {
    if(youAreReadingThisProgram){
      System.out.println("You are cordially invited to our wedding");
    }
  }

  protected void getWeddingLocationForEngineers() {
    System.out.println("Lats: 28.0385144, Longs: 73.324484");
  }

  protected void getWeddingLocationForHumans() {
    System.out.println("Hotel Sagar Bikaner," +
        "Lalgarh Palace Campus," +
        "Sri Ganganagar Rd, " +
        "Bikaner, " +
        "Rajasthan 334002" +
        "Maps: https://tinyurl.com/y8rtgtvf" +
        "Nearest Airport: Jaipur / Nearest Railway station : Bikaner");
  }


  void execute7Vows() {
    helpBrideAndGroomUnderstandVow("Om esha ekapadi bhava iti prathaman");
    helpBrideAndGroomUnderstandVow("Om oorje jara dastayaha");
    helpBrideAndGroomUnderstandVow("Om rayas santu joradastayaha");
    helpBrideAndGroomUnderstandVow("Om mayo bhavyas jaradastaya ha");
    helpBrideAndGroomUnderstandVow("Om prajabhyaha santu jaradastayaha");
    helpBrideAndGroomUnderstandVow("Rutubhyah shat padi bhava");
    helpBrideAndGroomUnderstandVow("Om sakhi jaradastayahga");
  }

  void helpBrideAndGroomUnderstandVow(String vow) {
    System.out.println(vow);
  }

  void bindThemForever(){
    while (true){
      "Jeet and Medha grow old togather no fucks given about exceptions and errors in life."
    }
  }
  
  String getStatus(){
    return "Happily" + "Married" ;
  } 

   boolean isAllowedToBringGifts(){
    return false ;
  } 
  
  void rsvp(){
    "9th and 10th March 2019" ;
  } 
}
```
