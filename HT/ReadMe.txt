HawgTouch - Touch Cockpit Panels for DCS

Check http://forums.eagle.ru/showthread.php?t=71729


HT Buttons and Lamps:

       <Buttons>
        <Button>
             <Name>APSelect</Name>
             <SwitchUp>\Images\LASTE\pressed\APSelect_UP.png</SwitchUp>
             <SwitchMiddle>\Images\LASTE\depressed\APSelect.png</SwitchMiddle>
             <SwitchDown>\Images\LASTE\pressed\APSelect_DOWN.png</SwitchDown>
             <Type>ThreeStateSwitch</Type>
             <ID>1</ID>
             <Y>16</Y>
             <X>572</X>
             <KeyCommandUp>{RALT}{LALT}1</KeyCommandUp>
             <KeyCommandMiddle>{RALT}{LALT}2</KeyCommandMiddle>
             <KeyCommandDown>{RALT}{LALT}3</KeyCommandDown>
        </Button>
		<Button>
          <Name>MASTERCAUTION</Name>
          <DataImportID>MASTER_CAUTION</DataImportID>
          <Clickable>false</Clickable>
          <PressedImage>\Images\UFC\ufc-Mcaution-on.png</PressedImage>
          <DepressedImage>\Images\UFC\ufc-Mcaution-off.png</DepressedImage>
          <Type>ClickButton</Type>
          <ID>20</ID>
          <Y>900</Y>
          <X>900</X>
          <KeyCommand>1</KeyCommand>
        </Button>
       </Buttons>


	   Spezial KeyCommands:

		{LSHIFT}
		{RSHIFT}
		{LCONTROL}
		{RCONTROL}
		{LALT}
		{RALT}
		{LWIN}
		{RWIN} 