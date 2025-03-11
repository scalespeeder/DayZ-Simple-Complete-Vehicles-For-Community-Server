DayZ Community Server Simple Complete Vehicles XML Code Snippet Mod Changelog & Terms Of Use

Limited Testing on PC Chernarus Local Server DAYZ Version 1.27 Mar 2025.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

Simple replacement code that makes vehicles spawn in complete with a can of fuel in the storage.

Players will still need to find water for the radiator if required.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded xml files could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded xml files neccessitates increased regular restarts to prevent server crashing.

I advise you use an XML / JSON validator to check any modded files.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

cfgspawnabletypes.xml code snippet, simple copy and paste the below code OVER THE TOP of the existing code, save & upload if necessary, then restart your server.
(please note it will take some time for the old vehicles to despawn & be replaced by the new ones).

	
	<type name="Boat_01_Black">
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.0" />
		</attachments>
	</type>
	<type name="Boat_01_Blue">
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.0" />
		</attachments>
	</type>
	<type name="Boat_01_Camo">
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.0" />
		</attachments>
	</type>
	<type name="Boat_01_Orange">
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.0" />
		</attachments>
	</type>
	<type name="OffroadHatchback">
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackDoors_Driver" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackDoors_CoDriver" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackHood" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackTrunk" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="OffroadHatchback_Blue">
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackDoors_Driver_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackDoors_CoDriver_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackHood_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackTrunk_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="OffroadHatchback_White">
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackDoors_Driver_White" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackDoors_CoDriver_White" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackHood_White" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HatchbackTrunk_White" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="Offroad_02">
		<attachments chance="1.00">
			<item name="Offroad_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Trunk" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Hood" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Door_1_1" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Door_1_2" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Door_2_1" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Offroad_02_Door_2_2" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="GlowPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<!-- -->
	<type name="CivilianSedan">
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_Driver" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_CoDriver" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_BackLeft" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_BackRight" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanHood" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanTrunk" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="CivilianSedan_Wine">
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_Driver_Wine" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_CoDriver_Wine" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_BackLeft_Wine" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_BackRight_Wine" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanHood_Wine" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanTrunk_Wine" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="CivilianSedan_Black">
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanWheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_Driver_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_CoDriver_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_BackLeft_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanDoors_BackRight_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanHood_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CivSedanTrunk_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<!-- -->
	<type name="Hatchback_02">
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_1_1" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_1_2" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_2_1" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_2_2" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Hood" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Trunk" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="Hatchback_02_Black">
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_1_1_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_1_2_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_2_1_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_2_2_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Hood_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Trunk_Black" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="Hatchback_02_Blue">
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_1_1_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_1_2_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_2_1_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Door_2_2_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Hood_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Hatchback_02_Trunk_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<!-- -->
	<type name="Sedan_02">
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_1_1" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_1_2" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_2_1" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_2_2" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Hood" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Trunk" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="Sedan_02_Red">
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="sedan_02_Door_1_1_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_1_2_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_2_1_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_2_2_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Hood_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Trunk_Red" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="Sedan_02_Grey">
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarRadiator" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CarBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="SparkPlug" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="sedan_02_Door_1_1_Grey" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_1_2_Grey" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_2_1_Grey" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Door_2_2_Grey" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Hood_Grey" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Sedan_02_Trunk_Grey" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="Truck_01_Covered">
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Hood" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Door_1_1" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Door_2_1" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="Truck_01_Covered_Blue">
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Hood_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Door_1_1_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Door_2_1_Blue" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
	<type name="Truck_01_Covered_Orange">
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Wheel" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_WheelDouble" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="TruckBattery" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="HeadlightH7" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Hood_Orange" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Door_1_1_Orange" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="Truck_01_Door_2_1_Orange" chance="1.00" />
		</attachments>
		<attachments chance="1.00">
			<item name="CanisterGasoline" chance="1.00" />
		</attachments>
	</type>
