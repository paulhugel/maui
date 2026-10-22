# Maui X3D world

An interactive Maui world with a three-minute UFO sightseeing circuit and a photographic observatory arrival. Maintained by Paul Garrett Hugel.

## Visit

[Open Maui](https://paulhugel.github.io/maui/)

## Controls

- Wait for the scene to load; the X3D file is approximately 52 MB.
- From **High_Altitude**, click the saucer to start the tour and follow it.
- **Follow UFO tour** selects the riding camera; it does not start the flight.
- From other viewpoints, touching the UFO starts its flight without changing the camera.
- Enable sound using the scene sound control if the hum is muted.
- Reload the page to reset the flight and return the UFO to its starting point.
- When riding, the completed tour shows the UFO in front of the observatory photograph. **Original Observatory** restores the modeled landscape.

The photographic observatory relief uses hand-authored approximate depth from a video frame. It is intended for its composed viewpoint; hidden building surfaces are not reconstructed. Original scene credits remain in the X3D file.

## Files

- `index.html` and `maui.html`: interactive viewer, using X_ITE 16.5.0 from jsDelivr.
- `maui.x3d`: complete scene and animation.
- `big_286743bd39_opaque.png`: terrain texture.
- `Maui_observatory_photo.jpg`: observatory photo.
- `maui_ufo_hum.wav`: positional UFO audio.

## Local viewing

Run `python3 -m http.server 8000` in this folder, then open <http://127.0.0.1:8000/>. An internet connection is required to load X_ITE.
