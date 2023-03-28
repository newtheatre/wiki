---
title: Setting up the Production Desk
---

When we talk about the Tech or Production Desk, we talk about where our sound computer, our lighting desk and our lighting monitors (there are two of them!) are set up. 

In the Auditorium, this setup tends to live in the Tech Box, because that is where the show is called and operated from, particularly for End-On shows. However, sometimes, you don’t want the tech desk in the Tech Box! 

At NNT, we tend to set up our Tech Desk in the seats to make it easier for our technical designers to program their In House shows. It’ll probably stay there for the Tech Run, and if the show is End-On the Tech Desk goes back to the Box before the Dress Run. 

For a show with alternative seating (eg. thrust or traverse), it might stay there for the show, and a gauze hung between the stage and the desk.

# Into the Auditorium Seats

Everything you need for this is in the blue crate under the back desk of the tech box. 

1. Grab the piece of deck from behind the tech box labelled TECH DESK. (2 person lift!)

2. Position it over Row D of the Auditorium, and install it using the four legs (two long, two short, all marked with green tape on the ends). 
> These legs are the specific length for the Tech Desk- don’t let them get mixed up with the other legs we own!

3. Grab the 13A 8-way and plug it into the sockets underneath the seats. The 8-way can live in the runners of the deck using the bolts. 

4. Move the QLab Mac and Ion down to the desk. You'll need to unplug the Mac sound multi from 1-8 in the sound desk. The sound desk itself and comms can stay in the tech box. 

5. In the tech box, patch the DMX to join Workshop to Seats using the two short cables already plugged into the 'Seats' sockets
> Read more about how DMX patching works in the auditorium

6. Run the DMX from the Ion into the DMX patch points under the seats using the two cables that were plugged into the desk in the tech box

7. Depending on how many speakers you're using:

	* **Less than 4:** 
		* Run the blue sound multi cable from the Mac to the appropriate XLR sockets under the seats. 
		* For instance, if you're using Left, Right and Foyer, plug 1, 2 and 3 into the floor. 
		* If you're using Left, right, and an on stage speaker (eg, the speaker plugged into channel 5), plug 1, 2, and 5 into the floor.
		* Number 4 is occasionally patched into the Comms system to be able to use Comms at the desk.

	* **More than 4:**
		* Run the yellow multi cable from the sound multi to the tech box. You can use all 8 outputs from the Mac but might require some adapters. (The adapters should be left connected when you're done.)

8. Plug in the appropriate multi into the relevant sound desk inputs, either the seats multi or the yellow multi as per the previous step. 

9. If using projection, bring the VGA out from the tech box and drop it out the trunking at Row D. Run it along the floor to the Mac and tape it down so people don't trip over it.

10. Test everything! Try and turn lights on and make sound come out of all your speakers. 
Pat yourself on the back for a job well done. 

11. If you're leaving the desk there for the performance (eg, in the round), hang the gauze on the bar above Row B.

# Tech Desk in the SR Wing

Even more alternative seating sometimes warrants installing the tech desk in the SR wing. This is a bit more involved and MUST be reset when you're done otherwise everyone will get very angry and confused.

1. Install the tech desk deck in the wing using legs appropriate for you. 0.8m or 1.2m will probably be good here. 

2. Move the Mac and Ion down to the desk and use the 13A 8-way from the crate, powering it from the installed 13A outlet on the wall closest to the workshop corridor (not the one on the floor).

3. **Sound**

	* You can plug in all of 1-8 from the Mac into the SR XLR multi. You will likely need to unspool some of the multi from the hook on the wall for it to reach. Plug up in order.

	* At the sound desk in the tech box, unplug the inputs from the SR multi that you are using and move them to 1-8. There are some inputs from the SR multi that are not plugged into the sound desk by default that you can use too.

4. **Lighting**

	> This is where it gets complicated and involved. Make a note of **everything** you do and reset it afterwards.

	* **Explanation** _(you can skip this bullet if you just want to get on and do it)_:

	We use two universes, one for the dimmers and one for everything else. 

	We don't have a simple way of running a second universe from stage right, you can only do Universe 2 from the tech box or Row D, so we need to squeeze everything onto one universe. The dimmers go from 1-48 and the LEDs use 1, 11, 21, 31, 41, 51. Therefore, these will conflict when on one universe. For the sake of only changing one thing, we're going to change the address of the dimmers so they don't conflict with the LED fixtures. 

	_Additional Note_: If we have sufficient adapters, we could repatch the SR DMX drop in the workshop to be the second universe. 

	* You will need:
		* 1x 5 pin Male to 3 pin female 
		* 1x 3 pin male to 5 pin female 
		* 2x 5m 3 pin DMX

	* Connect Universe 2 of the lighting desk to a 5-3 pin adapter, a piece of 3 pin DMX and connect that to one of the lines of the SR XLR multi. 

	* Up in the tech box, disconnect that line of the XLR multi from the sound desk and connect another piece of 3 pin DMX to it, another adapter, and plug this into the Universe 2 Workshop DMX socket. 

	* **In the workshop:**
		* Unplug the line for Universe 1.  
		* Patch the demux into the DMX splitter for Universe 2. 
		* Press and hold MENU on the demux and use the buttons to change the address to 100.
	* **At the lighting desk**:
		* Repatch the dimmers to be starting at address 2/100 as follows: 
		* Enter Patch (via New Tab)
		* 1 [Thru] 60 [at] 2/100 Enter 
		* It may ask you if you're happy to overwrite an existing patch. Double check the fixtures you're using to make sure there isn't a clash and go for it. 
		* If there is a clash, you can find another space for the dimmers to go and readdress the demux again. 

5.  Test everything! 

6.  No but really test everything. 
7.  Make a note of everything that has changed so that the get out team can undo it all. 
8.  Pat yourself on the back and give yourself a cuppa - big job well done!














