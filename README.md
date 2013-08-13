This project provides a binding for TestFlight SDK for Android for Xamarin.Android users.

To use, put this in your MainApplication:

using Com.Testflightapp.Lib;
..
TestFlight.TakeOff(this, "Your App token");
TestFlight.Log("blah");
...
TestFlight.PassCheckpoint("Passed some checkpoint...");