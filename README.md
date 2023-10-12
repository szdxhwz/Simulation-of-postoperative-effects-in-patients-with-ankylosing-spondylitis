# AS surgery outcome simulation
This project proposes a method for postoperative three-dimensional posture simulation of patients with ankylosing spondylitis by combining three-dimensional surface surface model and CT data. The preoperative patient's body surface surface is obtained by depth camera, and the trunk part of the CT image and the surface model is segmented and registered by the neural network, so that the surgical plan planned by the doctor in the CT image is applied to the surface model, and the osteotomy simulation is performed using log-Euclidean multi-affine transformation. The advantage of this approach is that it can visually demonstrate the expected corrective effect of the surgery. The study included 12 AS patients who required surgery, and we used five patients who had completed surgery to verify the accuracy of the simulation effect of our method. The average error between the predicted jaw angle and the actual postoperative jaw angle is 0.8 degrees, and the closest point pair distance of the point cloud is 10 mm, which shows that our method can provide doctors and patients with a credible prediction and display of postoperative results in the preoperative planning stage. In addition, a postoperative effect simulation system for AS was developed based on the 3D Slicer platform.
