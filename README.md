# comp3431_interfaces

[![Build and Test (foxy)](../../actions/workflows/build_and_test_foxy.yaml/badge.svg)](../../actions/workflows/build_and_test_foxy.yaml)
[![Build and Test (galactic)](../../actions/workflows/build_and_test_galactic.yaml/badge.svg)](../../actions/workflows/build_and_test_galactic.yaml)
[![Build and Test (rolling)](../../actions/workflows/build_and_test_rolling.yaml/badge.svg)](../../actions/workflows/build_and_test_rolling.yaml)

## List of Interfaces

* _QRCodeBlock.msg_: A data type for storing information about a QR Code Block

* _MapInfo.srv_: contains data obtained from exploring the map about the locations and data of the qr codes. This is used to notify the planning node about the environment.

* _MoveObjectToRoom.action_: action to be used to perform an action to move a certain object to a certain room.
