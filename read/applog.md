app log
shellCmd("logcat -v time *:W")
gAndroidDevice.shellCmd
AndroidDevice::shellCmd(std::string cmd)
static_cast<AndroidShell*>(DeviceBase::mShellClient)->shellCmd(cmds);
AndroidShell::shellCmd(std::vector<std::string> &cmds)
startShell()
mSocket->SendLine("0006shell:");
DeviceBase::startLoop()
click to exit the app log in menu
    device->onStart();
    while(device->onLoop());
device->onExit();
*********************************************************



