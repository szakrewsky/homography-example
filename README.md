# homography-example

Example of homography.

homography-example.pl image

Opens two image panes.  The first pane is the image given as an argument and referred to as image1.
The second image pane is a blank image referred to as image2.  User can click four points on image1 to
identify a planar surface.  Then the user can click four points on image2 to specify where the four
points from image1 should map.  Program then computes homography matrix H and transforms image1.