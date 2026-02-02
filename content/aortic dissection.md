---
title: Aortic dissection
---
# What is Aortic Dissection?

Aortic dissection is a hazardous condition in which a tear (a rupture) in the aortic intimal layer allows blood to enter and separate the wall layers, creating a true lumen (the original channel) and a false lumen alongside it. In the Stanford classification, type B dissection involves the descending aorta. Because symptoms can mimic other cardiovascular diseases, identification and ongoing monitoring are critical, especially since the status of the false lumen (patent, partially thrombosed, or completely thrombosed) strongly influences prognosis and late adverse events [[publication list#^a5e2c7|(1)]] [[publication list#^30c813|(2)]].

# Why our models must reflect real people?

As researchers working at the intersection of mechanics, imaging, and multiphysics modeling of the aorta, we have learned an important lesson: human variability isn’t noise, it is the signal. The geometry, mechanics, and even the electrical properties of blood and tissue vary meaningfully between individuals, and those differences shape disease onset, progression, and treatment response in aortic dissection.

The mechanics of aortic flow are inseparable from the shape of the vessel. Subtle differences in arch length, curvature, and ascending aorta morphology can influence hemodynamics and, in turn, risk profiles for acute events and long-term outcomes [[publication list#^503860|(3)]] [[publication list#^a5e2c7|(4)]]. Yet, building large databases of high-quality, patient-specific models is difficult: CT data are not always accessible, and segmentation-to-mesh pipelines are time consuming and user dependent [[publication list#^503860|(3)]]. This is one reason many studies have relied on idealized geometries. But such idealizations can miss clinically relevant behavior, use parameters that don’t map cleanly to measurable quantities, and introduce sharp features that corrupt physiologic flow in simulations [[publication list#^a5e2c7|(4)]].

# Morphology, mechanics, monitoring

Aortic dissection creates a true and a false lumen. Hemodynamics in and between them are central to prognosis. The status of the false lumen, e.g., patent, partially thrombosed, or completely thrombosed, is a strong predictor of late adverse outcomes, which makes its evolution clinically consequential [[publication list#^30c813|(2)]]. Computational thrombosis models help us explore how flow features relate to thrombus growth, but phenomenological models carry many parameters and often need careful sensitivity analysis to identify what truly matters and where models fall short (e.g., predicting growth rates) [[publication list#^2a5e8f|(5)]]. To compare patients of different sizes, dimensionless morphological indices can improve transferability, allowing us to classify the likelihood of patent versus thrombosed false lumen states across a spectrum of anatomies [[publication list#^a5e2c7|(4)]].