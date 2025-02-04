# Term Project: Silent Portable Air Compressor
<h4>Contributors: </h4><i>Arda Küçükparmak - Burak Emre Doğan - Dora Köksal - Muhammet Berke Uçmak -Necmi Arda Coşkun</i>

<h2>Project Description</h2>
An air compressor is a machine that converts electrical power into potential energy stored as compressed air. This compressed air is used to power tools, machinery, and equipment in various industrial and commercial applications. There are several types of air compressors such as reciprocating, rotary, and centrifugal. The main difference between them is the method they use to compress air. Our air compressor is a reciprocating air compressor that uses two pistons to compress the air. Pistons increase the efficiency of air compression manipulating air more effectively into the compressor.
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/-FJPG-FWEBP-B800.jpg"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/ASSEMBLY.png"  style="width:400px;">
<h2>Disassembly</h2>
During the disassembly, we encountered some challenges such as separating the shaft and the pistons from other components. We used a tool called “puller” and separated the shrink-fitted rotor and discs. In total, the disassembly of parts took approximately 2 hours.
After the disassembly, all of our group members bought a caliper to measure their parts. Some troubles occurred during the measurements as well. For instance, it was challenging to measure the dimensions where the caliper wouldn’t fit. We had to come up with practical solutions such as inserting pencil leads into the holes and measuring them.
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-03-00.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-03-42.png"  style="width:400px;">
<h2>Assembly and Exploded View</h2>
We had 64 unique parts and we assembled them all virtually in Siemens NX. We used fix, concentric, touch align, parallel, and align lock as constraints. 
Fix: We used fix constraints for the parts with no motion such as the main body of the compressor: and the air tank.
Concentric: The most frequently used constraint in our assembly is concentric because we had a lot of parts connected by screws. 
Touch Align: When two parts have faces that are touching each other, we have used the touch align constraint to assemble them.
	Align lock: Align lock constraints were used in our assembly when the desired assembly required two parts to have the same axis.
	The most difficult challenge we faced during the assembly process was dimension differences between two parts that needed to be connected. When such a problem occurred we went back to the modeling and fixed the problem. However, sometimes it was hard to update models. Thus, it took time and required effort.
<h2>Exploded views (Modeling and Drafting)</h2>
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/EXPLOSION_DRAFT.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/EXPLOSION_MODEL.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/PART_LIST_.jpg"  style="width:400px;">
<h2>Modeling and Drafting of Important Parts</h2>
<h4> 1 - Air Tank (Designer: Dora Köksal)</h4>
To model the main body of the tank revolve command was used, then to add some of the features datum planes were created as there were many details with angled positioning. To model the holder sweep along guide command was used with many guides along angled sketches. Additionally, some edge blends, chamfers, and hole commands were used to model the part as similar to the real product as possible. 
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-30-06.png"  style="width:400px;">

The drafting of this part includes 2 sheets as it is a detailed part with many features requiring many detailed views. Some dimensional tolerances were defined aligning with the manufacturing processes of the product. Also, some form tolerances were introduced such as concentricity, parallelity, flatness, and profile. 

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-32-25.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-36-09.png"  style="width:400px;">
<h4> 2 - Piston (Designer: Dora Köksal)</h4>
To model this part mainly extrude and revolve commands are used and for the details chamfer, edge blend, rib, and hole commands are used. As some details were symmetric, mirror and pattern commands were utilized too. 
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

The drafting of this part includes 2 sheets as it has many details on every face requiring many views with many detailed views. Again some dimensional tolerances, form tolerances, and a surface roughness tolerance were defined for this part to operate properly. 

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">
<h4> 3 - Shaft Holder (Designer: Muhammet Berke Uçmak)</h4>
For modeling this part, I used many commands including revolve (for the main body), extrude, and sweep (for features). After completing the main body I used some edge blends and draft commands to make the model almost identical to the real part. 
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

For a clear drafting, first I have chosen the main views that I need to give and for the other dimensions that are not able to be given, I gave a section view. Then, I gave too many detailed views since my part was very complex. If I had tried to give them without section views, probably I would have violated the dimensioning rules and also ended up with a bad-looking hard-to-understand drafting. 

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">
<h4> 4 - Rotor (Designer: Muhammet Berke Uçmak)</h4>
To design the rotor in Siemens NX, first I started with the main body of the rotor which can be done with one revolve command since the geometry of the main body is axis-symmetric. Then I modeled the features on both sides by modeling one of them by revolve command and I used a pattern feature to copy it in desired positions. After that, I designed the shaft for one part and mirrored it to the other side as well. There were some differences between the two sides of the shaft. Designing them had been done separately to get the same part.
           You cannot see the outer side of the bearings in the modeling. Because I design them in another file. The reason is to get the appropriate motion in the motion analysis.

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

In the drafting, I gave two views of the part since it was sufficient. After the main dimensions of the part were shown in the main views, I gave detailed views to give the dimensions of the smaller features. Tolerances are given according to the manufacturing process and functionality of the rotor. To give an example, in the front view (on the left), a shaft tolerance “p6” is given. The reason is, that between the rotor’s shaft and other parts which need to be assembled with it, an interference (tight) fit is required.
 

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">
<h4> 5 - Disc&Bearing (Designer: Necmi Arda Coşkun)</h4>
In the process of modeling this part in Siemens NX, I start with the sketch of the main body of the disc part. After extrusion, I introduce a new plane on the top of the disc, followed by the individual sketches of the bearing part. Individual and non-united (none) extrusions are needed so that the part can be painted properly as it is in reality. Finally, I finish the part with the final touches such as holes, edge blends, etc.
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

In the drafting part, I give 3 views as it is sufficient in understanding the shape of the part. I carefully declare the dimensions, hence extension lines do not cross at all. Small details are given as detailed views as understanding those details from the base view is challenging. 
    All the tolerances in the part are given according to the corresponding manufacturing processes, which are CNC milling and turning. Additionally, hole tolerance is given as H7, which is to be fitted by the “Rotor” part designed by Berke. We give tolerances as (H7/p6) resulting in a tight fit.

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">
<h4> 6 - Plastic Cover (Designer: Necmi Arda Coşkun)</h4>
To model this part in Siemens NX, I start with the main rectangular prism part and then using the shell command, I get a shell. After that, I add the side part with extrusion commands. Then the complex part begins, sketch of the detailed holes and details have to be precise since a little measurement error ends up in an unsimilar model. 
     For the top of the cover, a drafted extrusion command is used since these holes are through at an angle. After creating the features for one quadrant (if the part was to be thought as an xy plane from orthogonal views), the mirror command is used to complete the rest.
     In the finalization of the part, many edge blends are created as the part has curved edges.
 
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

 In the drafting of this part, I had to use 2 sheets as the part had too many details. In drafting, all the tolerances are given according to the injection molding manufacturing process. Symmetry lines are crucial in this part since the part is symmetric and dimensions are only given from one side of the part.
 
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">
<h4> 7 - Compressor Head (Designer: Burak Emre Doğan)</h4>
A compressor head is a critical component of a compressor, the device used to increase the pressure of a gas by reducing its volume. The compressor head houses the essential mechanisms that perform the compression process. 
       To model this component, we should initially draw a square for the assembly with a valve plate which is also extruded on the square plate. Then, add the cooling details on the top of the object. 
        Finally, we create the required holes with appropriate threads for the wiring of the essential mechanisms functioning in the compression process.

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

On the drafting side, it is observed that there are some tolerances and roughnesses. Hole and shaft tolerances are adjusted as to which type of tolerance is more appropriate for the true fitting method. It is possible to see that many shrink fit here because the component should house the significant parts that are not able to move by vibration. On the surface roughness side, I determined that this component is produced by the die casting method by researching resemble objects and how they are produced. Also, I see that the roughness value should not be much more than a level when I examine the surface by touching it. Therefore, I determined the 1.6 value which corresponds to the minimum roughness value for the die-casting method in the surface roughness table. In addition, this draft includes linearity, flatness, and concentricity tolerance types due to the listed reasons:
* Flatness is important for the compressor head located properly on the valve plate without any air leak.
* To ensure proper fit, we need to keep holes and shafts in a specific tolerance range which means concentricity.  
* Linearity is also important for the cooling process in the compressor head.
 

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">
<h4> 8 - Valve Plate (Designer: Burak Emre Doğan)</h4>
A valve plate is a key component in reciprocating compressors and other machinery where the regulation of fluid or gas flow is essential. It acts as a structural element that supports the movement of valves, ensuring efficient operation by controlling the flow of air, gas, or refrigerant within the compressor system. This part also includes many holes for fitting to the compressor head. To draft this part, Edge blends and holes should be added with the required measures after drawing a square.
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

 In the drafting part, there are hole tolerances that are going to make interference fit and shrink fit with the compressor head. In addition, we see that 3.2 roughness value. We get that value by examining roughness tables and production methods. When we got the component, it was hard to understand which production method was used in this part. Basically, that component might be produced by milling or turning methods. It is decided from cost analysis by the producer. Therefore, I chose 3.2 to involve both milling and turning range. Also flatness and concentricity tolerance types are included in the draft for the same reasons listed on the previous draft.

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">
<h4> 9 - Starting Button (Designer: Arda Küçükparmak)</h4>
We can simply call it the button that starts the compressor. It contains a semi-electronic, semi-mechanical system. At the bottom, there is a metal part that directs the air coming from the tank to the hose connection. In the modeling process, I mostly used the extrude command. Besides that, chamfer and edge blends were predominantly used. I also used the thread command 3 times.

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

 Taking into account that the part is manufactured through plastic injection molding, I applied tolerances and callout the threads.

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">
<h4> 10 - Barometer (Designer: Arda Küçükparmak)</h4>
The barometer measures the pressure of the air in the tank in real time, providing information about its overall status. In the modeling process, I mostly used the extrude command. Differently in this model, I drew the needle and the barometer itself separately to allow motion.

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-41-00.png"  style="width:400px;">

 In this draft, I applied circularity tolerance to ensure the compatibility of the needle and the barometer. Additionally, I provided dimensional tolerances based on plastic injection molding.

<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-44-14.png"  style="width:400px;">
<img src="https://github.com/faceofburak/reciprocal_slient_compressor/blob/main/2025-02-02_22-43-34.png"  style="width:400px;">



