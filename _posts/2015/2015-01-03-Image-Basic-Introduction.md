---
layout: post
title: Image basic introduction
categories:
- Image
tags:
- Lens, ISP, AWB, AE
---
## **Introduction**
## **Camera Lens**
A camera lens (also known as photographic lens or photographic objective) is an optical lens or assembly of lenses used in conjunction with a camera body and mechanism to make images of objects either on photographic film or on other media capable of storing an image chemically or electronically.
The two fundamental parameters of an optical lens are the focal length and the maximum aperture.
### **Focal Length**
The lens' focal length determines the magnification of the image projected onto the image plane. For a given photographic system the focal length determines the angle of view, short focal lengths giving a wider field of view than longer focal length lenses.Focal lengths are usually specified in millimetres (mm).

Here is example how focal length affects photograph composition: adjusting the camera's distance from the main subject while changing focal length, the main subject can remain the same size, while the other at a different distance changes size.

There are two kinds of camera lens according to their focal length: 
 + Zoom lenses
 + Prime lenses

The term prime has come to be used as the opposite of zoom; that is, a prime lens is a fixed-focal-length, or unifocal lens, while a zoom lens has a variable focal length.

### **Aperture**
The aperture indicates the light intensity of that image.A wider aperture, identified by a smaller f-number, allows using a faster shutter speed for the same exposure.[9]
We use F value to describe the aperture.


     F = Focal length/diameter of aperture.


The lower the f-number, the higher light intensity at the focal plane. Larger aperture (smaller f-numbers) provide a much shallower depth of fiedl than smaller apertures, other conditions being equal.
## **Image Sensor**
An image sensor is a device that converts an optical image into an electronic signal. It is used mostly in digital cameras, camera modules and other imaging devices. most currently used are digital charge-coupled device (CCD) or complementary metal–oxide–semiconductor (CMOS) active pixel sensors.


Neither technology has a clear advantage in image quality. On one hand, CCD sensors are more susceptible to vertical smear from bright light sources when the sensor is overloaded; High-end frame transfer CCDs in turn do not suffer from this problem. On the other hand, CMOS sensors are susceptible to undesired effects that come as a result of rolling shutter.

###**Color separation**###

There are several main types of color image sensors, differing by the type of color-separation mechanism:

Bayer filter sensor, low-cost and most common, using a color filter array that passes red, green, or blue light to selected pixel sensors, forming interlaced grids sensitive to red, green, and blue – the missing color samples are interpolated using a demosaicing algorithm. In order to avoid interpolated color information, techniques like color co-site sampling use a piezo mechanism to shift the color sensor in pixel steps. The Bayer filter sensors also include back-illuminated sensors, where the light enters the sensitive silicon from the opposite side of where the transistors and metal wires are, such that the metal connections on the devices side are not an obstacle for the light, and the efficiency is higher.[7][8]

## **shutter**
Shuttering is the process of exposing an imaging sensor to light at a rate equal to or faster than the frame rate. The purpose of the shuttering is to reduce the motion blur within an image frame.
### **Rolling Shutter**
The rolling shutter is where a line or a group of lines is read out while all other lines on the sensor continue to be exposed. When a group of lines are read out at one time, this is called a block readout. Typical line times, depending on the frame rate and sensor architecture, can be several hundred microseconds.

The "Rolling Shutter" can be either mechanical or electronic. The advantage of this method is that the image sensor can continue to gather photons during the acquisition process, thus effectively increasing sensitivity. It is found on many digital still and video cameras using CMOS sensors. The effect is most noticeable when imaging extreme conditions of motion or the fast flashing of light. While some CMOS sensors use a global shutter,[3] the majority found in the consumer market utilize a rolling shutter.

### **Global Shutter**
 + A global shutter, unlike the rolling shutter, exposes all pixels at the same time.
 + There is no time discontinuity in the image.
 + The global shutter has a storage element that allows the pixel to dump the storage charge into a shielded area. This shielded area than can be read out while the next image frame is being exposed. Therefore, there are no discontinuities or image artifacts associated with the electronic exposure.

### **Why is Global Shuttering Better**###
 + Image is integrated without discontinuities in time
 + Image Quality is superior with less motion blur � Measurements are more accurate
 + No mechanical moving parts
 + Strobes are not required to stop the motion blur
 + Special Recording modes such as Slip Sync or Burst ROC are only possible with Electronic Shuttering (Global).
 
## **Black Level**
black level is defined as the level of brightness at the darkest (black) part of a visual image or the level of brightness at which no light is emitted from a screen, resulting in a pure black screen.

Video displays generally need to be calibrated so that the displayed black is true to the black information in the video signal. If the black level is not correctly adjusted, visual information in a video signal could be displayed as black, or black information could be displayed as above black information (gray).

## **Auto Exposure(AE)**
In photography, exposure is the amount of light per unit area.
Determined by : 
 + Aperture:
  Controls the area over which light can enter your camera.
 + Shutter speed:
  Controls the duration of the exposure
 + ISO speed:
  Controls the sensitivity of your camera’s sensor to give amount of light.

Exposure is like collecting rain in a bucket. We cannot control the rate of the rainfall, and there are 3 factors we can determine: size of the bucket, duration we leave it in the rain, and the quantity of rain we want to collect.

Collect too much is just like “overexposed”, collect too little is just “underexposed”. In photography, the exposure settings of aperture, shutter speed and ISO speed are analogous to the size, time and quantity discussed above.

Each of the 3 factors, which determines exposure, controls exposure differently, and each setting also influences other image properties, just like in the chart below, aperture affects depth of field, shutter speed affects motion blur and ISO speed affects image noise.

## **Auto White Balance(AWB)**##
**White Balance(WB)** is the process of removing unrealistic color casts, so that objects will preserve natural color under different light source. 
Influenced by :
**Color temperature of a light source**
**Color temperature** is a way of measuring the quality of a light source. It is based on the ratio of the amount of blue light to the amount of red light, and the green light is ignored. The unit for measuring this ratio is in degree Kelvin (K)

Human brain can quickly adjust to different color temperature. Digital cameras usually have built-in sensor to measure the current color temperature and use an alogrithm to process the image so that the final result may be close to what we see(with our eyes,of course). But the algorithm(s) being used may not be accurate enough to make every situtation correct.  Under some difficult situations when the in-camera algorithm is not able to set eh color temperature correctly or when some crative and special effects are needed, we can instruct the camera to use a particular color temperature to fulfill our need. The adjustment that makes sure the white color we view directly will also appeare white in the image is refered to as **white balance**  
## **Dynamic Range**##
Dynamic range in photography describes the ratio between the max and min measurable light intensities(white and black, respectively).  Incident and reflected light can contribute to the dynamic range of scene  
## **Flicker Detection** ##
## **Image Histogram**
## **Sharpness**
## **Image stabilization**
## **References**
 9.Kingslake 1989,[page needed]
