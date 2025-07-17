The 1–18 group designation has been recommended by the International Union of Pure and Applied Chemistry (IUPAC) but is not yet in wide use. No names have been assigned
for elements 110–112, 114, 116, and 118. Elements 113, 115, and 117 have not yet been synthesized.
Source: Chang, R. Chemistry, 7th ed. Copyright © 2002 The McGraw-Hill Companies, Inc. New York. Reproduced wih permission.
WATER AND
WASTEWATER
ENGINEERING
This page intentionally left blank 
WATER AND
WASTEWATER
ENGINEERING
 Design Principles and Practice
 Mackenzie L. Davis, Ph.D., P.E., BCEE
 Michigan State University
New York Chicago San Francisco Lisbon
London Madrid Mexico City Milan New Delhi
San Juan Seoul Singapore Sydney Toronto 
Copyright © 2010 by The McGraw-Hill Companies, Inc. All rights reserved. Except as permitted under the United States Copyright Act of 1976, no part of this
publication may be reproduced or distributed in any form or by any means, or stored in a database or retrieval system, without the prior written permission of
the publisher.
ISBN: 978-0-07-171385-6
MHID: 0-07-171385-9
The material in this eBook also appears in the print version of this title: ISBN: 978-0-07-171384-9, MHID: 0-07-171384-0.
All trademarks are trademarks of their respective owners. Rather than put a trademark symbol after every occurrence of a trademarked name, we use names in
an editorial fashion only, and to the benefi t of the trademark owner, with no intention of infringement of the trademark. Where such designations appear in this
book, they have been printed with initial caps.
McGraw-Hill eBooks are available at special quantity discounts to use as premiums and sales promotions, or for use in corporate training programs. To contact
a representative please e-mail us at bulksales@mcgraw-hill.com.
Information contained in this work has been obtained by The McGraw-Hill Companies, Inc. (“McGraw-Hill”) from sources believed to be reliable. However,
neither McGraw-Hill nor its authors guarantee the accuracy or completeness of any information published herein, and neither McGraw-Hill nor its authors
shall be responsible for any errors, omissions, or damages arising out of use of this information. This work is published with the understanding that McGraw-Hill
and its authors are supplying information but are not attempting to render engineering or other professional services. If such services are required, the assistance
of an appropriate professional should be sought.
TERMS OF USE
This is a copyrighted work and The McGraw-Hill Companies, Inc. (“McGrawHill”) and its licensors reserve all rights in and to the work. Use of this work is
subject to these terms. Except as permitted under the Copyright Act of 1976 and the right to store and retrieve one copy of the work, you may not decompile,
disassemble, reverse engineer, reproduce, modify, create derivative works based upon, transmit, distribute, disseminate, sell, publish or sublicense the work or
any part of it without McGraw-Hill’s prior consent. You may use the work for your own noncommercial and personal use; any other use of the work is strictly
prohibited. Your right to use the work may be terminated if you fail to comply with these terms.
THE WORK IS PROVIDED “AS IS.” McGRAW-HILL AND ITS LICENSORS MAKE NO GUARANTEES OR WARRANTIES AS TO THE
ACCURACY, ADEQUACY OR COMPLETENESS OF OR RESULTS TO BE OBTAINED FROM USING THE WORK, INCLUDING ANY INFORMATION
THAT CAN BE ACCESSED THROUGH THE WORK VIA HYPERLINK OR OTHERWISE, AND EXPRESSLY DISCLAIM ANY WARRANTY, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE.
McGraw-Hill and its licensors do not warrant or guarantee that the functions contained in the work will meet your requirements or that its operation will be
uninterrupted or error free. Neither McGraw-Hill nor its licensors shall be liable to you or anyone else for any inaccuracy, error or omission, regardless of cause,
in the work or for any damages resulting therefrom. McGraw-Hill has no responsibility for the content of any information accessed through the work. Under no
circumstances shall McGraw-Hill and/or its licensors be liable for any indirect, incidental, special, punitive, consequential or similar damages that result from the
use of or inability to use the work, even if any of them has been advised of the possibility of such damages. This limitation of liability shall apply to any claim or
cause whatsoever whether such claim or cause arises in contract, tort or otherwise.
Dedication
 To all the professionals in the water and wastewater industry who give of their time and wisdom
to the generations that follow, and especially to
 Myron Erickson, P.E
 Thomas C. Gavin, P.E.
 Timothy D. McNamara, P.E.
 Thomas Newhof, P.E., BCEE
 Lucy B. Pugh, P.E., BCEE
 Carlos A. Sanlley, Ph.D.
 Jimmy L. Spangler, P.E.
 Jeffrey R. Stollhans, P.G.
for the advice and wisdom they shared to make this book possible. 
This page intentionally left blank 
vii
ABOUT THE AUTHOR
Mackenzie L. Davis is an Emeritus Professor of Environmental Engineering at Michigan State
University. He received all his degrees from the University of Illinois. From 1968 to 1971 he
served as a Captain in the U.S. Army Medical Service Corps. During his military service he
conducted air pollution surveys at Army ammunition plants. From 1971 to 1973 he was Branch
Chief of the Environmental Engineering Branch at the U.S. Army Construction Engineering
Research Laboratory. His responsibilities included supervision of research on air, noise, and water
pollution control and solid waste management for Army facilities. In 1973 he joined the faculty
at Michigan State University. He has taught and conducted research in the areas of air pollution
control, hazardous waste management, and water and wastewater engineering.
 In 1987 and 1989–1992, under an intergovernmental personnel assignment with the Office
of Solid Waste of the U.S. Environmental Protection Agency, Dr. Davis performed technology
assessments of treatment methods used to demonstrate the regulatory requirements for the
land disposal restrictions (“land ban”) promulgated under the Hazardous and Solid Waste
Amendments.
 Dr. Davis is a member of the following professional organizations: American Chemical
Society, American Institute of Chemical Engineers, American Society for Engineering Education,
American Meteorological Society, American Society of Civil Engineers, American Water Works
Association, Air & Waste Management Association, Association of Environmental Engineering
and Science Professors, and the Water Environment Federation.
 His honors and awards include the State-of-the-Art Award from the ASCE, Chapter Honor
Member of Chi Epsilon, Sigma Xi, election as a Fellow in the Air & Waste Management
Association, and election as a Diplomate in the American Academy of Environmental Engineers
with certification in hazardous waste management. He has received teaching awards from the
American Society of Civil Engineers Student Chapter, Michigan State University College of
Engineering, North Central Section of the American Society for Engineering Education, Great
Lakes Region of Chi Epsilon, and the Amoco Corporation. In 1998, he received the Lyman
A. Ripperton Award for distinguished achievement as an educator from the Air & Waste
Management Association. In 2007, he was recognized as the Educational Professional of the
Year by the Michigan Water Environment Association. He is a registered professional engineer
in Michigan.
Dr. Davis is the co-author of two previous books: Introduction to Environmental Engineering,
4th ed. with Dr. David A. Cornwell and Principles of Environmental Engineering and Science, 2nd ed.
with Dr. Susan Masten.
 In 2003, Dr. Davis retired from Michigan State University. 
This page intentionally left blank 
 PREFACE
 This book is designed for use by professionals. The book covers the design of municipal water
and wastewater facilities. I have assumed that the reader has had an introductory environmental engineering course and a first course in fluid mechanics. That is, I have assumed the
reader is familiar with notation such as mg/L and acronyms such as BOD as well as the concepts of mass balance, Bernoulli’s equation, and friction loss. Because I could not assume
that the reader has used either Introduction to Environmental Engineering or Principles of
Environmental Engineering and Science, some material from those texts is used to introduce
the subject matter included here.
 A Professional Advisory Board has provided their experience and expertise to vet the material
in Water and Wastewater Engineering. The Board is composed of licensed engineers, a licensed
geologist, and licensed treatment plant operators. A short biographical sketch and affiliation of
the Professional Advisory Board members is presented following this preface. They have read
and commented on all of the chapters. In addition, a number of operators have been interviewed
to obtain hints on methods for improving designs.
 The book format is one that I used successfully over the 20 years that I taught the material.
The book starts with an overview of the design and construction process including the application
of the code of ethics in the process. The first half of the book addresses water treatment. Because
my course was built around a term design project, the subject matter follows the flow of water
through the unit processes of coagulation, flocculation, softening (including NF and RO), sedimentation, filtration (including MF and UF), disinfection, and residuals management.
 The topics of wastewater treatment follow a similar pattern of following the flow through a
plant, that is, preliminary treatment, primary treatment, secondary treatment, tertiary treatment,
and residuals management. Special attention is given to the application of membranes.
 Each subject in each chapter is introduced with a discussion of the theoretical principles that
are to be applied in the design of the unit process. In addition, in each chapter, appropriate design
criteria from the Great Lakes–Upper Mississippi River Board of State and Provincial Public
Health and Environmental Managers (known to the elders of the profession as the Ten State Standards) as well as alternative approaches from the literature are addressed.
 The text features over 100 example problems, 500 end-of-chapter problems, and 300 illustrations. A highlight of the book is the inclusion of safety issues in the design requirements as well
as operation and maintenance activities. Hints from the field bring real-life experience in solving
technical issues.
For those using this book for a formal university level course, an instructor’s manual is available online for qualified instructors. Please inquire with your McGraw-Hill representative for the
necessary access password. The instructor’s manual includes sample course outlines for both a onesemester option and a two-semester option, solved example exams, and detailed solutions to the
end-of-chapter problems. In addition, there are suggestions for using the pedagogic aids in the text.
 McGraw-Hill hosts a website at http://www.mhprofessional.com/wwe . It includes over 500
annotated photos of equipment and the construction process as well as a primer on engineering
economics, and seminar presentations by professional engineers and operators.
ix
 There is a student edition of this book under the same title. It does not contain chapters on the
following subjects: (1) intake structures, (2) wells, (3) chemical handling and feeding, (4) removal
of specific contaminants, (5) water plant process selection and integration, (6) storage and distribution systems, (7) sanitary sewer design, and (8) clean water plant process selection and
integration.
 I appreciate any comments, suggestions, corrections, and contributions for future editions.
 Mackenzie L. Davis
Acknowledgements
 The following individuals provided opportunities for photographs, insight on current design practice, operational problems, and hints from the field:
 John Allen, Plant Superintendent, Grand Rapids Water Filtration Plant
 Tom Arlington, Project Manager, United Water, Armada WWTP
 Michael P. Avrill, Operations Supervisor, Wyoming Water Treatment Plant
 Richard S. Bacon, Project Manager, Wixom WWTP
 Don Baron, District Manager, Johnson Screens
 Larry Campbell, Plant Superintendent, PARRC Wastewater Treatment Plant
 Gerald H. Caron, Plant Superintendent,Wyoming Water Treatment Plant
 Jim Carrol, Operations Supervisor, East Lansing, Meridian Township Water Authority
 Patrick Cook, P.E, Michigan Department of Environmental Quality
 Ryan Craven, Project Foreman, C&D Hughes, Inc., Charlotte, MI
 Jerry Crisp, Assistant Superintendent, Wastewater Treatment Plant, Brownsburg, IN
 Delvin E. DeBoer, South Dakota State University
 Bruce DeVantier, Southern Illinois University-Carbondale
 Stanley Diamond, P.E., Associate, Greeley and Hansen, Indianapolis, IN
Kathy Dillon, Superintendent, Wastewater Treatment Plant, Brownsburg, IN
 Chad Everts, Site Engineer, FTC&H, Grand Rapids, MI
 Larry Fitzgerald, Director of Operations, Southern Clinton County Municipal Utilities
Authority
 Ira Gabin, P.E., Vice President, Dixon Engineering, Lake Odessa, MI
 Brock Howard, P.E., Michigan Department of Environmental Quality
James E. Kilduff, Rensselaer Polytechnic Institute
Dave Koch, P.E., Project Manager, Black and Veatch, Grand Rapids, MI
 Brian Lee, Operator, United Water, Armada Project
 Andy Linebaugh, Michigan State University Physical Plant
 Benjamin S. Magbanua, Jr., Mississippi State University
K. Andrews Miller, P.E., Associate, Greeley and Hansen, Indianapolis, IN
 Pauline Rampanelli, Utility Plant Operator, Clean Water Plant, Wyoming, MI
 Ed Renkie, Landing Board of Water and Light, Lansing, MI
x PREFACE
 Larry Sanford, Assistant Supervisor, Ann Arbor Water Treatment Plant
 Mike St. Bernard, Plant Superintendent, East Lansing, Meridian Township Water Authority
 T. J. Short, P.E., Associate, Greeley and Hansen, Indianapolis, IN
 Gary J. Timmer, Area Manager, United Water
 Don Uitvlugt, Utility Plant Operator, Clean Water Plant, Wyoming, MI
 Art K. Umble, Ph.D., P.E., BCEE, Associate and Director of Process Engineering, Greeley
and Hansen, Indianapolis, IN
 Benjamin Whitehead, P.E., Project Engineer, Black & Veatch, Grand Rapids, MI
 Tom Wilson, Maintenance Supervisor, Utilities Department, Clean Water Plant, Wyoming, MI
 Brian Wood, Oregon State University
 David Yonge, Washington State University
 Rebecca Hullman, Terry Stines, Heather Wilkinson, and Adam Wolfsen provided technical editing, checked problem solutions, and typed the solution manual. Dr. Susan J. Masten, P. E. provided insights and suggestions to improve the instructional content of the book.
 To each and all of these people, I give a hearty thank you.
 An especial thank you to my editors, Lora Kalb-Neyens, Debra Hash, and Joy Bramble for their
creative support in bringing the book to fruition.
PREFACE xi
This page intentionally left blank 
 PROFESSIONAL ADVISORY BOARD
 Myron Erickson, P. E., Laboratory Services Manager, City of Wyoming, MI
 Mr. Erickson holds a bachelor’s degree from the University of Evansville (IN) and a master’s
degree in environmental engineering from Michigan State University. He is licensed as a Class B
operator in the State of Michigan. In his 15 years with the City of Wyoming (MI) utilities department
he has served as the environmental compliance and research specialist for the City’s programs in
industrial sewer use, biosolids disposition, disinfection byproducts, and PPCPs. Currently he manages
the laboratories for both the wastewater and drinking water utility plants. While the biosolids and IPP
programs were under his direction, the City won a First Place EPA Award for Biosolids Public Education and a Second Place EPA Award for overall excellence of their IPP program.
 The 35 employees of City of Wyoming Clean Water Plant serve a population of about 170,000.
The maximum design flow of the plant is 24 MGD. With about 35 employees, the Drinking Water
Plant serves a population of about 210,000. The maximum design flow is 120,000 MGD. The
laboratory is a certified drinking water lab.
 Clean Water Plant
 2350 Ivanrest, SW
 Wyoming, MI 49418
 Thomas C. Gavin, P. E., Senior Process Engineer, FTC&H
 Mr. Gavin received his B.S. in Civil Engineering and his M.S. in Environmental Engineering from
Northwestern University. His 30 years of experience in process design includes three new water treatment plants and renovation/expansion of eight others. This experience includes conventional surface
water treatment, lime-soda softening, deep-bed high-rate direct filtration, and membrane filtration.
His wastewater experience includes design and start-up of eight activated sludge plants treating highstrength industrial wastewaters. In addition, his experience includes design of four water distribution
systems and three wastewater collection systems. Mr. Gavin has been with FTC&H for 21 years.
 Established in 1956, Fishbeck, Thompson, Carr, & Huber (FTC&H) is a full-service engineering and architectural firm with 350 employees that is headquartered in Grand Rapids, Michigan.
FTC&H has four other offices located in Michigan and Ohio. FTC&H specializes in engineering,
architecture, environmental science, and construction management.
Fishbeck, Thompson, Carr & Huber, Inc.
 1515 Arboretum Drive, SE
 Grand Rapids, Michigan 49546
xiii
 Timothy D. McNamara, P. E., Senior Vice President, FTC&H
 Mr. McNamara received his B.S. in Civil Engineering and his M.S. in Sanitary Engineering from
Michigan State University. He is Principal-in-Charge of his firm’s Process Engineering Department
and of their Construction Division. He has over 28 years of progressive design and management
experience with water supply and treatment, wastewater collection and treatment, and environmental
engineering projects. His design experience includes 27 water supply projects, 18 water treatment
plants, and 12 wastewater treatment projects. He has particular expertise with membrane filtration,
iron filtration, and lime-soda softening processes, and has been with his firm for 25 years. He is the
former Chair of the Michigan Section of the American Water Works Association.
 Established in 1956, Fishbeck, Thompson, Carr, & Huber (FTC&H) is a full-service
engineering and architectural firm with 350 employees that is headquartered in Grand Rapids,
Michigan. FTC&H has four other offices located in Michigan and Ohio. FTC&H specializes in
engineering, architecture, environmental science, and construction management.
Fishbeck, Thompson, Carr & Huber, Inc.
 1515 Arboretum Drive, SE
 Grand Rapids, Michigan 49546
 Thomas Newhof, P. E., BCEE, Chairman of the Board, Prein&Newhof
 Mr. Newhof received his B.S. degree from Calvin College and his M.S. in Sanitary Engineering
from the University of Michigan. He is a licensed professional engineer in Michigan, Wisconsin,
and Illinois. As both a Project Manager and Principal-in-Charge of many of Prein&Newhof’s
environmental and civil engineering projects, his experience includes: planning and design of
water treatment and wastewater treatment facilities with conventional or membrane filtration
technology, water and sewer systems, intakes, pipelines, pumping stations, storm drainage and
flood control, airport and road improvements, and residential and commercial development.
 The American Water Works Association recognized Thomas Newhof’s contributions to the
profession with the 1998 George Warren Fuller Award. The University of Michigan honored him
with the Jack A. Borchardt Award in 2008.
 Mr. Newhof co-founded Prein&Newhof in 1969 with a fellow civil engineer. He is the Chairman
of the firm’s Board of Directors, providing leadership for Prein&Newhof’s 100 employees who
work in its environmental laboratory and five offices located throughout West Michigan.
 Prein&Newhof
3355 Evergreen Drive, NE
 Grand Rapids, MI 49525
xiv PROFESSIONAL ADVISORY BOARD
 Lucy B. Pugh, P. E., BCEE, Vice President, AECOM
 Ms. Pugh received her B.S.E. and M.S.E. in Civil/Environmental Engineering from the
University of Michigan. Her 28 years of experience in municipal process water and wastewater
treatment design includes three new water treatment plants, two new wastewater treatment plants,
and renovation/expansion of seven other wastewater treatment plants. Ms. Pugh’s industrial
water and wastewater design experience includes over 25 facilities. She has also provided process
troubleshooting and optimization at numerous other municipal and industrial treatment facilities.
Her experience spans a broad range of technologies, including ion exchange, greensand filtration,
low pressure membrane filtration, reverse osmosis, dissolved air flotation, conventional activated
sludge, oxidation ditches, SBRs, biological nutrient removal, PACT, UV disinfection, upflow
anaerobic sludge blanket reactors, anaerobic fluidized bed reactors, and first application of GAC/
fluidized bed for perchlorate removal.
AECOM is a global provider of professional, technical, and management support services
to a broad range of markets, including water/wastewater, environmental, transportation, building and energy. With 43,000 employees providing services in over 100 countries around the
globe, AECOM is a leader in all key markets that it serves. Ms. Pugh has been with AECOM
for 22 years.
 AECOM
5555 Glenwood Hills Pkwy, SE
 Grand Rapids, Michigan 49512
 Carlos A. Sanlley Pagán, Ph.D., Design Engineer, Greeley and Hansen
 Dr. Sanlley received his is Ph.D. from Michigan State University in 2009. His thesis research
identified byproducts formed during Advance Oxidation Processes. His work experience
includes the design of CSO control structures, design of a fermentation system to enhance VFA
production for a Bardenpho wastewater treatment process, and design and analysis of a water
intake structure in Lake Michigan. He is the firm-wide resource on AQUIFAS modeling and
IFAS process design.
 Greeley and Hansen, founded in 1914, is a leader in developing innovative engineering
solutions for a wide array of water, wastewater, water reuse, and solid waste challenges aimed
at improving public health, safety, and welfare. The projects that Greeley and Hansen has completed for clients continue to receive various industry awards for design and engineering excellence. Engineering News Record ranks Greeley and Hansen among the Top 25 Designers in
Wastewater Treatment, Sewerage, and Solid Waste Management.
 Greeley and Hansen
 6640 Intech Boulevard, Suite 180
 Indianapolis, IN 46278
PROFESSIONAL ADVISORY BOARD xv
 Jimmy L. Spangler, P. E., Senior Manager, Municipal Group, Tetra Tech
 Mr. Spangler received his B.S. in Civil Engineering from Michigan State University. He holds
a Class A operator’s license from the State of Michigan. His 36 years of experience includes 29
years of wastewater collection and treatment as a certified operator in positions of Plant Engineer
(Washington Suburban Sanitary Commission—3 yrs), Assistant Superintendent (City of Pontiac,
MI—3 yrs), and Superintendent (City of Lansing, MI—19 yrs) and 4 years as Deputy Public Service
Department Director (City of Lansing). These facilities ranged in capacity from 40,000 gpd to 50
mgd. The processes included screening, grit removal, primary treatment, various activated sludge
processes, phosphorous and ammonia nitrogen removal, chemical precipitation, tertiary filtration,
chlorination, dechlorination, UV disinfection, aerobic digestion, anaerobic digestion, elutriation,
WAS thickening, wet air oxidation, dewatering, incineration, and land application of biosolids. He
also has had direct involvement in facility expansion and rehabilitation projects. For the last seven
years he has been with Tetra Tech, Inc. His work includes conducting facility evaluations, reviewing designs, preparing and reviewing operation and maintenance manuals, plant operation reviews
and inspections, process evaluations, preparing studies, and long-term capital plans.
 Tetra Tech provides consulting, engineering, and technical services worldwide. The
10,000 employees of Tetra Tech provide expertise in water and wastewater facility design and
operation, water resource management, program management, and construction services.
1921 E. Miller Road, Suite A
Lansing, MI 48911
 Jeffrey R. Stollhans, P.G., District Manager, Layne-Northern
 Mr. Stollhans received his B.S. in Geology from Illinois State University. His 24 years of
experience in water well design and construction includes hundreds of well and pump installations throughout Michigan, Illinois, Indiana, and Ohio as well as multiple water treatment plants
throughout Michigan. He is a Registered Water Well Contractor and Pump Installer in Michigan,
Illinois, and Indiana and a Registered Geologist in Illinois, Missouri, and Kentucky. Prior to joining Layne Christensen in 1989, Mr. Stollhans worked in the Ground Water Section of the Illinois
State Water Survey in Champaign, Illinois.
 Layne Christensen’s Water Resources Division provides a full line of water-related services and
products including hydrological studies, site selection, well design, drilling and well development,
pump installation, and repair and maintenance. The division’s offerings include the design and construction of water treatment facilities and the manufacture and sale of products to treat volatile organics
and other contaminants such as nitrates, iron, manganese, arsenic, radium, and radon in groundwater.
 Layne-Northern
3126 N. Martin Luther king Jr. Blvd.
 Lansing, MI 48906
xvi PROFESSIONAL ADVISORY BOARD
CONTENTS
 Preface ix
 1 The Design and Construction Processes 1-1
 1-1 Introduction 1-2
 1-2 Project Participants 1-2
 1-3 The Professional–Client Relationship and The Code of Ethics 1-3
 1-4 Responsible Care 1-9
 1-5 Overall Design Process 1-10
 1-6 Overall Construction Process 1-19
 1-7 Hints from the Field 1-23
 1-8 Chapter Review 1-24
 1-9 Problems 1-24
 1-10 Discussion Questions 1-25
 1-11 References 1-26
 2 General Water Supply Design Considerations 2-1
 2-1 Water Demand 2-2
 2-2 Water Source Evaluation 2-7
 2-3 Water Quality 2-22
 2-4 Evaluation of Process Options 2-37
 2-5 Plant Sizing and Layout 2-37
 2-6 Plant Location 2-39
 2-7 Chapter Review 2-39
 2-8 Problems 2-40
 2-9 Discussion Questions 2-45
 2-10 References 2-46
 3 Intake Structures 3-1
3-1 Introduction 3-2
3-2 Design Elements 3-2
3-3 Design Criteria 3-8
3-4 Operational Considerations 3-31
3-5 Operation and Maintenance 3-34
3-6 Chapter Review 3-35
3-7 Problems 3-36
3-8 Discussion Questions 3-41
3-9 References 3-41
 4 Wells 4-1
 4-1 Introduction 4-2
 4-2 Design Elements 4-2
xvii
 4-3 Well Protection 4-3
 4-4 Well Design 4-15
 4-5 Chapter Review 4-41
 4-6 Problems 4-42
 4-7 Discussion Questions 4-51
 4-8 References 4-51
 5 Chemical Handling and Storage 5-1
5-1 Introduction 5-2
5-2 Redundancy and Capacity Provisions 5-2
5-3 Delivery, Handling, and Storage 5-2
5-4 Chemical Feed and Metering Systems 5-7
5-5 Chemical Compatibility 5-14
5-6 Materials Compatibility 5-14
 5-7 Designing for Safety and Hazardous Conditions 5-17
 5-8 Operation and Maintenance 5-17
5-9 Chapter Review 5-21
5-10 Problems 5-22
5-11 Discussion Questions 5-24
 5-12 References 5-25
 6 Coagulation and Flocculation 6-1
 6-1 Introduction 6-2
 6-2 Characteristics of Particles 6-3
 6-3 Coagulation Theory 6-5
 6-4 Coagulation Practice 6-22
 6-5 Flocculation Theory 6-23
 6-6 Mixing Theory 6-24
 6-7 Mixing Practice 6-26
 6-8 Operation and Maintenance 6-49
 6-9 Chapter Review 6-49
 6-10 Problems 6-50
 6-11 Discussion Questions 6-57
 6-12 References 6-58
 7 Lime-Soda Softening 7-1
 7-1 Hardness 7-2
 7-2 Lime-Soda Softening 7-6
 7-3 Softening Processes 7-11
 7-4 Chemical Dosages Based on Stoichiometry 7-15
 7-5 Concurrent Removal of Other Constituents 7-26
 7-6 Process Configurations and Design Criteria 7-27
 7-7 Operation and Maintenance 7-34
 7-8 Stabilization 7-34
 7-9 Chapter Review 7-39
xviii CONTENTS
 7-10 Problems 7-40
 7-11 Discussion Questions 7-46
 7-12 References 7-47
 8 Ion Exchange 8-1
 8-1 Introduction 8-2
 8-2 Fundamental Concepts of Ion Exchange 8-2
 8-3 Process Operation 8-10
 8-4 Ion Exchange Practice 8-13
 8-5 Operation and Maintenance 8-24
 8-6 Chapter Review 8-25
 8-7 Problems 8-25
 8-8 Discussion Question 8-28
 8-9 References 8-29
 9 Reverse Osmosis and Nanofiltration 9-1
 9-1 Introduction 9-2
 9-2 Theory 9-3
 9-3 Properties of RO and NF Membranes 9-6
 9-4 RO and NF Practice 9-8
 9-5 Electrodialysis 9-18
 9-6 Chapter Review 9-18
 9-7 Problems 9-19
 9-8 Discussion Question 9-20
 9-9 References 9-20
 10 Sedimentation 10-1
 10-1 Introduction 10-2
 10-2 Sedimentation Theory 10-2
 10-3 Sedimentation Practice 10-20
 10-4 Sedimentation Basin Design 10-25
 10-5 Operation and Maintenance 10-38
 10-6 Chapter Review 10-39
 10-7 Problems 10-40
 10-8 Discussion Questions 10-43
 10-9 References 10-44
 11 Granular Filtration 11-1
 11-1 Introduction 11-2
 11-2 An Overview of the Filtration Process 11-2
 11-3 Filter Media Characteristics 11-5
 11-4 Granular Filtration Theory 11-9
 11-5 Theory of Granular Filter Hydraulics 11-12
 11-6 Granular Filtration Practice 11-20
CONTENTS xix
 11-7 Operation and Maintenance 11-45
 11-8 Chapter Review 11-46
 11-9 Problems 11-47
 11-10 Discussion Questions 11-54
 11-11 References 11-55
 12 Membrane Filtration 12-1
 12-1 Introduction 12-2
 12-2 Membrane Filtration Theory 12-3
 12-3 Properties of MF and UF Membranes 12-7
 12-4 MF and UF Practice 12-13
 12-5 Chapter Review 12-19
 12-6 Problems 12-19
 12-7 Discussion Questions 12-21
 12-8 References 12-21
 13 Disinfection and Fluoridation 13-1
 13-1 Introduction 13-2
 13-2 Disinfection 13-2
 13-3 Emergency Disinfection 13-42
 13-4 Fluoridation 13-42
 13-5 Operation and Maintenance 13-46
 13-6 Chapter Review 13-47
 13-7 Problems 13-48
 13-8 Discussion Questions 13-55
 13-9 References 13-55
 14 Removal of Specific Constituents 14-1
 14-1 Introduction 14-2
 14-2 Arsenic 14-2
 14-3 Carbon Dioxide 14-6
 14-4 Fluoride 14-8
 14-5 Iron and Manganese 14-11
 14-6 Nitrate 14-14
 14-7 Natural Organic Material (NOM) 14-15
 14-8 Perchlorate 14-18
 14-9 Pharmaceuticals and Endocrine-Disrupting Compounds (EDCs) 14-20
 14-10 Radionuclides 14-21
 14-11 Synthetic Organic Chemicals (SOCs) and Volatile Organic Compounds (VOCs) 14-22
 14-12 Taste and Odor (T&O) 14-31
 14-13 Chapter Review 14-36
 14-14 Problems 14-37
 14-15 Discussion Questions 14-40
 14-16 References 14-40
xx CONTENTS
 15 Water Plant Residuals Management 15-1
 15-1 Introduction 15-2
 15-2 Solids Computations 15-3
 15-3 Solids Production and Characteristics 15-6
 15-4 Minimization of Residuals Generation 15-11
 15-5 Recovery of Treatment Chemicals 15-13
 15-6 Residuals Conveyance 15-15
 15-7 Management of Sludges 15-15
 15-8 Management of Liquid Residuals 15-44
 15-9 Disposal of Specific Residuals Constituents 15-45
 15-10 Ultimate Disposal 15-49
 15-11 Chapter Review 15-51
 15-12 Problems 15-52
 15-13 Discussion Questions 15-57
 15-14 References 15-58
 16 Drinking Water Plant Process Selection and Integration 16-1
 16-1 Introduction 16-2
 16-2 Process Selection 16-2
 16-3 Process Integration 16-16
 16-4 Security 16-31
 16-5 Chapter Review 16-35
 16-6 Problems 16-36
 16-7 Discussion Questions 16-47
 16-8 References 16-47
 17 Storage and Distribution Systems 17-1
 17-1 Introduction 17-2
 17-2 Demand Estimates 17-2
 17-3 Service Pressures 17-9
 17-4 Pipe Network Design 17-10
 17-5 Storage Tank Design 17-22
 17-6 Pump Selection 17-32
 17-7 Network Analysis 17-36
 17-8 Sanitary Protection 17-38
 17-9 Chapter Review 17-40
 17-10 Problems 17-41
 17-11 Discussion Questions 17-50
 17-12 References 17-51
 18 General Wastewater Collection and Treatment Design
Considerations 18-1
 18-1 Wastewater Sources and Flow Rates 18-2
 18-2 Wastewater Characteristics 18-7
CONTENTS xxi
 18-3 Wastewater Treatment Standards 18-11
 18-4 Sludge Disposal Regulations 18-14
 18-5 Plant Sizing and Layout 18-20
 18-6 Plant Location 18-22
 18-7 Chapter Review 18-22
 18-8 Problems 18-23
 18-9 Discussion Questions 18-27
 18-10 References 18-28
 19 Sanitary Sewer Design 19-1
 19-1 Introduction 19-2
 19-2 Predesign Activities 19-9
 19-3 Gravity Sewer Collection System Design 19-9
 19-4 Alternatives Sewers 19-28
 19-5 Pump Station Design 19-31
 19-6 Operation and Maintenance 19-39
 19-7 Sewer Safety 19-40
 19-8 Chapter Review 19-41
 19-9 Problems 19-42
 19-10 Discussion Questions 19-48
 19-11 References 19-48
 20 Headworks and Preliminary Treatment 20-1
 20-1 Introduction 20-2
 20-2 Pump Station 20-2
 20-3 Flow Measurement 20-5
 20-4 Bar Racks and Screens 20-9
 20-5 Coarse Solids Reduction 20-23
 20-6 Grit Removal 20-25
 20-7 Flow Equalization 20-36
 20-8 Alternative Preliminary Process Arrangements 20-46
 20-9 Chapter Review 20-47
 20-10 Problems 20-48
 20-11 Discussion Questions 20-52
 20-12 References 20-52
 21 Primary Treatment 21-1
 21-1 Introduction 21-2
 21-2 Sedimentation Theory 21-2
 21-3 Sedimentation Practice 21-3
 21-4 Sedimentation Basin Design 21-6
 21-5 Other Primary Treatment Alternatives 21-25
 21-6 Chapter Review 21-26
 21-7 Problems 21-27
 21-8 References 21-30
xxii CONTENTS
 22 Wastewater Microbiology 22-1
 22-1 Introduction 22-2
 22-2 Role of Microorganisms 22-2
 22-3 Classification of Microorganisms 22-2
 22-4 Microbial Biochemistry 22-4
 22-5 Population Dynamics 22-10
 22-6 Decomposition of Waste 22-15
 22-7 Microbiology of Secondary Treatment Unit Processes 22-16
 22-8 Operation and Maintenance 22-24
 22-9 Chapter Review 22-25
 22-10 Problems 22-26
 22-11 Discussion Questions 22-28
 22-12 References 22-28
 23 Secondary Treatment by Suspended Growth Biological
Processes 23-1
 23-1 Introduction 23-2
 23-2 Processes for BOD Removal and Nitrification 23-2
 23-3 Processes for Denitrification 23-8
 23-4 Processes for Phosphorus Removal 23-10
 23-5 Biological Treatment with Membrane Separation 23-12
 23-6 Suspended Growth Design Principles 23-14
 23-7 Suspended Growth Design Practice 23-39
 23-8 Membrane Bioreactor Design Practice 23-95
 23-9 Chapter Review 23-98
 23-10 Problems 23-99
 23-11 Discussion Questions 23-109
 23-12 References 23-113
 24 Secondary Treatment by Attached Growth and
Hybrid Biological Processes 24-1
 24-1 Introduction 24-2
 24-2 Attached Growth Processes 24-2
 24-3 Attached Growth Design Principles 24-4
 24-4 Attached Growth Design Practice 24-6
 24-5 Hybrid Processes 24-12
 24-6 Chapter Review 24-14
 24-7 Problems 24-15
 24-8 References 24-16
 25 Secondary Settling, Disinfection, and Postaeration 25-1
 25-1 Introduction 25-2
 25-2 Secondary Settling 25-2
 25-3 Disinfection 25-15
 25-4 Postaeration 25-21
CONTENTS xxiii
 25-5 Chapter Review 25-22
 25-6 Problems 25-23
 25-7 Discussion Questions 25-24
 25-8 References 25-25
 26 Tertiary Treatment 26-1
 26-1 Introduction 26-2
 26-2 Chemical Precipitation of Phosphorus 26-2
 26-3 Granular Filtration 26-5
 26-4 Membrane Filtration 26-10
 26-5 Carbon Adsorption 26-12
 26-6 Chapter Review 26-15
 26-7 Problems 26-16
 26-8 References 26-17
 27 Wastewater Plant Residuals Management 27-1
 27-1 Sludge Handling Alternatives 27-2
 27-2 Sources and Characteristics of Solids and Biosolids 27-3
 27-3 Solids Computations 27-6
 27-4 Grit Handling and Sludge Pumping 27-11
 27-5 Management of Solids 27-17
 27-6 Storage and Thickening of Sludges 27-18
 27-7 Alkaline Stabilization 27-23
 27-8 Aerobic Digestion 27-27
 27-9 Anaerobic Digestion 27-33
 27-10 Sludge Conditioning 27-52
 27-11 Dewatering 27-53
 27-12 Alternative Disposal Techniques 27-58
 27-13 Land Application and Biosolids 27-59
 27-14 Chapter Review 27-60
 27-15 Problems 27-61
 27-16 References 27-68
 28 Clean Water Plant Process Selection and Integration 28-1
 28-1 Introduction 28-2
 28-2 Process Selection 28-2
 28-3 Simulation Modeling 28-24
 28-4 Process Integration 28-25
 28-5 Chapter Review 28-31
 28-6 Problems 28-34
 28-7 References 28-36
xxiv CONTENTS
 Appendix A A-1
Properties of Air, Water, and Selected Chemicals
 Appendix B B-1
U.S. Standard Sieve Sizes
 Appendix C C-1
Pipe, Fitting, and Valve Data
 Appendix D D-1
 U.S. Environmental Protection Agency Ct Values for Disinfectants
 Index I-1
CONTENTS xxv
This page intentionally left blank 
1-1
 1-6 OVERALL CONSTRUCTION PROCESS
 1-7 HINTS FROM THE FIELD
 1-8 CHAPTER REVIEW
 1-9 PROBLEMS
 1-10 DISCUSSION QUESTIONS
 1-11 REFERENCES
 THE DESIGN AND CONSTRUCTION
PROCESSES
 1-1 INTRODUCTION
 1-2 PROJECT PARTICIPANTS
 1-3 THE PROFESSIONAL–CLIENT
RELATIONSHIP AND THE CODE
OF ETHICS
 1-4 RESPONSIBLE CARE
 1-5 OVERALL DESIGN PROCESS
If it works, it is good. The trick, of course, is designing
something that works.
P. Aarne Vesilind
Wastewater Treatment Plant Design
Water Environment Federation, 2003
The devil is in the details.
Anonymous
 1
CHAPTER
1-2 WATER AND WASTEWATER ENGINEERING
 1-1 INTRODUCTION
 Overview
 Water and wastewater engineering encompasses the planning, design, construction, and supervision of water and wastewater systems. This chapter gives an overview of the design and construction process as an introduction to planning. Chapters 2 through 17 address water treatment. The
subject matter follows the flow of water (and the design of unit processes) from the development
of a source through the unit processes of coagulation, flocculation, softening, reverse osmosis,
nanofiltration, sedimentation, granular filtration, membrane filtration, disinfection, and residuals
management. The topics of wastewater treatment follow a similar pattern of following the flow
through a plant. Chapters 18 through 28 address preliminary treatment, primary treatment, secondary treatment, tertiary treatment, and residuals management. Special attention is given to the
application of membranes.
 Setting the Stage
 Before presenting the design and construction processes, the stage is set by identifying the
project participants and their roles. The Code of Ethics provides a framework to discuss the
professional–client relationship. Responsible care is introduced as a higher level of performance than demanded by the code of ethics.
 1-2 PROJECT PARTICIPANTS
 Decision making for any municipal water or wastewater engineering design involves many participants: the public, the regulator, the legal counsel, the owner, the designer, the financier/investment banker, the operator, and the contractor. The owner serves as the focus of all the project’s
activities. The design professional, as a member of the design team under the owner’s direction,
responds to the project’s design needs. The design team consists of principal design engineers
and supporting specialists (WEF, 1991).
 All projects begin with an identification of a problem by the regulator, the public, legal counsel, or owner.
The design professional then enters the project during the idea generation and evaluation phase of the
problem-solving activity. Thereafter, the design professional or firm generally participates actively in all
of the project’s activities, typically until the end of the first year of operation. (WEF, 1991)
 The design professional may enter the process by many routes. Typically one of the following three methods or a combination of the methods are used to obtain engineering design
services:
 • Request for Qualifications (RFQ): The owner solicits qualifications from firms that wish to
be considered for engineering services on a design project.
 • Request for Proposals (RFP): The owner solicits proposals for engineering services on a
project. The RFP usually includes a requirement to provide a statement of qualifications.
Alternatively, the RFQ may be a second step following the evaluation of the responses to
the RFP.
 • Qualified Bidder Selection (QBS): The owner selects the design firm from a list of previously qualified companies. 
THE DESIGN AND CONSTRUCTION PROCESSES 1-3
In the case of the focus of this text, the owner is a municipality or an operating authority representing several municipalities.
 The central issue in the professional–client relationship is the allocation of responsibility and
authority in decision making—who makes what decisions. These are ethical models that are, in
effect, models of different distributions of authority and responsibility in decision making. One
can view the professional–client relationship as one in which the client has the most authority and
responsibility in decision making, the professional being an employee; one in which the professional and the client are equals, either dealing at arm’s length or at a more personal level; or one
in which the professional, in different degrees, has the primary role (Bayles, 1991). The models
are summarized in Table 1-1 .
 1-3 THE PROFESSIONAL–CLIENT RELATIONSHIP
AND THE CODE OF ETHICS
 The professional–client relationship may move back and forth between two or more models as
the situation changes. However, for the professional engineer, the requirements of the Code of
Ethics are overarching. The American Society of Civil Engineers (ASCE) Code of Ethics is
shown in Figure 1-1 .
 First Canon
 This canon is paramount. It is held superior to all the others.
 Regulations, codes, and standards serve as the engineer’s guidance in ensuring that the facilities are safe and protect the health of the community. A large portion of this book and, for that
Model Description and comments
Agency Professional acts as an expert for agency, but agency has authority and responsibility.
Plausible for an attorney or a consultant to a government agency such as the Corps of
Engineers.
Contract Authority and responsibility shared equally. This model assumes bargaining between
equals. Not likely for an engineering consultant in classical design and construction.
Paternal Professional has superior knowledge and makes all the decisions for the client. This
model assumes the professional has not only superior technical knowledge but also
knows what is in the client’s best interest. Paternalism requires justification because it
involves performing on behalf of the client regardless of that person’s consent.
Fiduciary Professional’s superior knowledge is recognized, but the client retains significant
authority and responsibility for decision making. The professional supplies ideas and
information and proposes courses of action. The client’s judgement and consent are
required.
Extracted from Bayles, 1991.
TABLE 1-1
Some observed professional–client relationship models
1-4 WATER AND WASTEWATER ENGINEERING
matter, the education of environmental engineers is focused on these two issues. They will be
discussed in more detail at appropriate points in the remaining chapters.
 The public “welfare” is not articulated in regulations, codes, and standards. It is comprised of
two parts: prosperity and happiness. The public prospers when the decisions of the professional
result in economical projects. The public is “happy” when their trust and reliance on the professional is justified by successful completion of a project.
 Economical projects do not imply the cheapest project. Rather, they imply projects that
serve the client’s needs and satisfy the client’s elective options while conforming to regulatory constraints. In the classical engineering approach economical projects are achieved by
the following:
 • Scoping of the engineering contract (Bockrath, 1986 and Sternbach, 1988).
 • Economic analysis of alternatives (GLUMRB, 2003; WEF, 1991; WPCF, 1977).
 • Selection of lowest responsible bidder (Bockrath, 1986).
 • Diligent inspection of the work in progress (Firmage, 1980) .
FIGURE 1-1
American Society of Civil Engineers code of ethics.
THE DESIGN AND CONSTRUCTION PROCESSES 1-5
In alternative approaches such as design-build, economy is achieved by alternate delivery
methods.
 At the beginning of a project, on approval of the selection of a specific consulting engineer,
it is customary to hold a “scope meeting.” At the scope meeting a typical agenda includes (Firmage, 1980 and Sternbach, 1988):
 • Identification of primary contacts for the owner and engineering firm.
 • Scope and extent of engineering work.
 • Starting and completion dates.
 • Construction inspection.
 • Responsibility for allied engineering services.
 • Procedures for out-of-scope requests.
 • The fee.
Many times these items are addressed in the engineering firm’s proposal. In the proposal process, the clarity with which these are addressed may serve as a basis for selection of the engineering firm.
 The scope and extent of engineering work should be explicitly defined, in writing, to
avoid misunderstanding. The scope ensures that the client understands the limits of the work
the engineer is willing and/or able to perform. It provides the engineer with a framework for
establishing the fee and level of effort to be provided as well as ensuring that the engineer is
not expected to perform work outside of the area of competence. It may include such things as
personnel assigned to the project, their qualifications and responsibilities, evaluation of alternatives, design of the facility, preparing detail drawings, cost estimates, evaluating bids, as well as
bidder qualifications, surveying, staking the project, preparation of operation and maintenance
manuals, attendance at meetings, and documentation.
 The starting and completion dates provide both the client and the engineer with realistic
expectations as to the progress of the project.
 The scope meeting should identify the design engineer’s responsibilities for construction
inspection. Typically, the design engineering firm provides a field engineer and/or a construction
observer to diligently observe and, to the best of their ability, assure the owner that the construction is taking place in accordance with the plans and specifications as the project is being built.
Although a field engineer from a firm not involved in the design may be retained, it is preferable
that the design firm provide the engineer to ensure continuity. While construction observers may
be competent to do routine examinations of the progress of work, they generally do not have the
technical background to assure compliance with design specifications unless they are given specific training. For large projects, a full-time field engineer is on site. For small projects, periodic
inspection and inspection at critical construction milestones is provided.
 Small engineering firms may not have the expertise to provide the design specifications for
all of the components of the design. In this instance, the responsibility for providing allied engineering services such as geotechnical/soils consultants and electrical, mechanical, and structural
engineering as well as architectural services should be spelled out in writing at the scope meeting.
The professional engineering qualifications of those supplying the allied engineering should also 
1-6 WATER AND WASTEWATER ENGINEERING
be explicitly defined. For example, structural engineers that specialize in building design may not
be appropriate for designing structures subject to aggressive wastewater.
 Billing schedules and expectations of payment are also included in the scope meeting.
Typical fee structures are outlined in Table 1-2 .
 Economic analysis of alternatives, selection of lowest responsible bidder, and diligent
inspection of the work in progress will be discussed in the context of the design/construction
process described below.
 Turning to the issue of “happiness” or more formally “How is trust and reliance on the professional justified?”, three elements are to be considered:
 • The engineer’s view of the client.
 • The client’s view of the project.
 • Minimal versus appropriate standards.
For all but the very largest municipal systems, the first two models of the professional–client
relationship, Agency and Contract, do not apply. That leaves us with the latter two models. “Although a professional and a client are not equals, sufficient client competence exists to undermine
the paternalistic model as appropriate for their usual relationship. Clients can exercise judgement
over many aspects of professional services. If they lack information to make decisions, professionals can provide it.” (Bayles, 1991) This is not meant to suggest that the public needs to be taught
environmental engineering. Rather, it suggests that educated members of our modern society are
capable of understanding alternatives and making reasonable choices based on their values. They
should be provided enough information to make choices that accomplish their purposes—not
those of the professional.
Model Description and comments
Fixed percentage The engineering fee is a fixed percentage of the final cost of the constructed
facility. There is a negative incentive for the engineer to produce an economical
design. This fee system is outdated and rarely, if ever, used.
Fixed fee (lump sum) The engineering fee is a stated sum. There is no incentive for the engineer
to explore alternatives when it is specified as part of the work. There is an
incentive to get the work done as expeditiously as possible.
Time and materials
(T&M) or time and
expenses (T&E)
The cost of engineering services (the amount paid for salaries, fringe benefits,
retirement allowances, and operating costs) plus a percentage for overhead
and a fee for profit. In this procedure, the client will pay the “true” cost of the
engineering. However, without a scope of work and deadline, there is an no
incentive for the engineer to expedite the work.
Time and materials,
not to exceed
Same as T&M above but a maximum fee is specified. This provides the
engineer some incentive to expedite the work but only so as not to exceed
the ceiling fee. On the other hand, the owner has an incentive to expand the
scope. Both parties need to be alert to these possibilities and make appropriate
adjustments.
TABLE 1-2
Common fee structures
THE DESIGN AND CONSTRUCTION PROCESSES 1-7
 The client’s view of the project is most closely matched by the Fiduciary model, where the
client has more authority and responsibility in decision making than in the Paternal model. The
client must exercise judgement and offer or withhold consent in the decision making process.
In the Fiduciary model, the client depends on the professional for much of the information they
need to give or withhold their consent. The term consents (the client consents) rather than decides
(the client decides) indicates that it is the professional’s role to propose courses of action. It is
not the conception of two people contributing equally to the formulation of plans, whether or not
dealing at arm’s length. Rather, the professional supplies the ideas and information, and the client
agrees or not. For the process to work, the client must trust the professional to analyze accurately
the problem, canvass the feasible alternatives and associated costs, know as well as one can their
likely consequences, fully convey this information to the client, perhaps make a recommendation, and work honestly and loyally for the client to effectuate the chosen alternative. In short,
the client must rely on the professional to use his or her knowledge and ability in the client’s
interests. Because the client cannot check most of the work of the professional or the information
supplied, the professional has special obligations to the client to ensure that the trust and reliance
are justified.
 This is not to suggest that the professional simply presents an overall recommendation for
the client’s acceptance or rejection. Rather, a client’s interests can be affected by various aspects
of a professional’s work, so the client should be consulted at various times (Bayles, 1991).
 “Sustainable development is development that meets the needs of the present without compromising the ability of future generations to meet their own needs.” (WECD, 1987) If we look
beyond the simple idea of providing water and controlling pollution to the larger idea of sustaining our environment and protecting the public health, we see that there are better solutions for our
pollution problems. For example:
 • Pollution prevention by the minimization of waste production.
 • Life cycle analysis of our production techniques to include built-in features for extraction
and reuse of materials.
 • Selection of materials and methods that have a long life.
 • Manufacturing methods and equipment that minimize energy and water consumption.
 Second Canon
 Engineers are smart, confident people. With experience, we gain wisdom. The flaw of our nature
is to overextend our wisdom to areas not included in our experience. Great care must be taken to
limit engineering services to areas of competence. Jobs may be too large, too complicated, require
technology or techniques that are not within our experience. Competence gained by education
or by supervised on-the-job training sets the boundaries on the areas in which we can provide
service. Others more qualified must be called upon to provide service beyond these experiences.
 Engineers are creative. We pride ourselves in developing innovative solutions. We believe
that civilization advances with advances in technology. Someone has to build the first pyramid,
the first iron bridge, the first sand filter. Many times “the first” design fails (Petroski, 1985).
Thus, there may be a conflict between creativity and service in an area of competence. The conflict must be resolved very carefully. Although safety factors, bench and pilot scale experiments,
and computer simulations may be used, the client and professional must, in a very explicit way, 
1-8 WATER AND WASTEWATER ENGINEERING
agree on a venture into uncharted territory. If the territory is simply uncharted for the design
engineer but not for the profession, then the design engineer must employ a partner that can bring
experience or obtain the necessary training to become competent.
 Third Canon
 It may not seem that engineers would be called upon to issue public statements. Yet, there are numerous times that public statements are issued. Often these are formal, such as signing contracts,
making presentations to a city council or other public body, and issuing statements to the news
media. In other instances it is not so obvious that the statements are public. Verbal statements
to individual members of the public, posting of signs, and signing change orders on government
financed projects are examples of informal public statements.
 Fourth Canon
 A faithful agent is more than a loyal one. A faithful agent must be completely frank and open
with his/her employer and client. This means getting the facts, explaining them, and not violating
the other canons to please the client or your employer.
 Conflicts of interest may be subtle. A free lunch, a free trip, or a golf outing may not seem
like much of a conflict of interest, but in the eyes of the public, any gift may be seen as an attempt
to gain favors. Appearances do count and, in the public’s view, perception is reality.
 Fifth Canon
 This canon appears to be self-explanatory. We understand that cheating on exams is unethical.
Likewise, cheating by claiming credit for work that someone else has done is unethical.
 Unfair competition has taken a broad meaning in the review of ethics boards. For example,
offering services to a potential client that has retained another engineer to do the same work falls
into the category of unfair competition if the engineer solicits the work. The circumstances are
different if the client solicits the engineer after having already retained another engineer. This
type of request must be treated with great care. It is best to decline this type of employment until
the client and original engineer resolve or dissolve their relationship.
 Similarly, a request to review the work of another engineering firm may be construed to be
unfair competition. The best procedure is for the client to advise the original firm of their desire
to have an independent review. Another alternative is to advise the originating engineering firm
that the request has been made. This is a matter of courtesy, if not a matter of ethics.
 Sixth Canon
 This canon has two elements. The first is to treat others with the same courtesy that you
would expect from them. The second is to behave such that the credibility of your work is not
jeopardized.
Seventh Canon
 Engineers use technology both in the process of doing their job and in the provision of solutions
to problems. It is incumbent on them to keep up with the technology. One of the best means of
doing this is to participate in one of the relevant professional societies by attending meetings, 
THE DESIGN AND CONSTRUCTION PROCESSES 1-9
reading journal articles, and participating in workshops. Appropriate organizations for municipal
water and wastewater engineering include the American Society of Civil Engineers ( Journal
of Environmental Engineering ), American Water Works Association ( Journal AWWA ), and the
Water Environment Federation ( Water Environment Research ).
 1-4 RESPONSIBLE CARE
 Codes of ethics are minimalist (Ladd, 1991). They stipulate only the minimal acceptable standards. To say that only minimal standards qualify as reasonable and sufficient is to suggest
that these standards result in a product that is as good as anyone could expect it to be (Harris
et al., 1995). This is belied by the fact that others in the profession choose to exceed the minimal standards:
“A major responsibility of the engineer is to precisely determine the wants of the client.”
(Firmage, 1980).
“. . . the fi rst task of the engineer is fi nd out what the problem really is.”
“An important aspect of the problem defi nition that is frequently overlooked is human
factors. Matters of customer use and acceptance are paramount.” (Kemper and Sanders,
2001)
 The responsibilities of engineers are to (Baum, 1983):
 1. “Recognize the right of each individual potentially affected by a project to participate to
an appropriate degree in the making of decisions concerning that project.”
 2. “Do everything in their power to provide complete, accurate, and understandable information to all potentially affected parties.”
To go beyond the minimalist requirements is to endorse the concepts of responsible or reasonable care and informed consent. Reasonable care is “a standard of reasonableness as seen by a
normal, prudent nonprofessional” (Harris et al., 1995). Informed consent is understood as including two main elements: knowledge and voluntariness. To elaborate, informed consent may be
defined by the following conditions (Martin and Schinzinger, 1991):
 1. The consent is given voluntarily without being subjected to force, fraud, or deception.
 2. The consent is based on the information that a rational person would want, together with
any other information requested, presented to them in an understandable form.
 3. The decision is made by an individual competent to process the information and make
rational decisions.
 4. The consent is offered in proxy by an individual or group that collectively represents
many people of like interests, concerns, and exposure to the risks that result from the
decision.
To go beyond the minimalist level of holding the public welfare paramount, the professional
engineer must view the relationship to the client as fiducial. They owe the client responsible care.
The client must be given the right and opportunity to express informed consent or to withhold
1-10 WATER AND WASTEWATER ENGINEERING
consent as they deem fit. This is not to say that the client must consent to the selection of every
nut and bolt in the project, but rather that critical decision points must be identified for the client.
At these decision points the client must be provided enough information to allow rational decisions. This information should include the alternatives, the consequences of choosing one alternative over another, and the data and/or logic the engineer used to arrive at the consequences.
 1-5 OVERALL DESIGN PROCESS
 Project Design and Construction Delivery Processes
 The design process is not like a computer program that is executed exactly the same way for
every project. The process described here is an overview of the classical engineering approach
to design- and construction-related activities. In this approach, vendor-furnished equipment is
procured according to performance or prescriptive specifications through contractors who are
bidding from drawings and specifications prepared by a consulting engineer. All funding and
ownership of the facilities rest with the owner in the classical approach. In actual practice some
of the steps described below will be bypassed and others, not described, will be inserted based on
the experience of the designer and the complexity of the design.
 Other approaches to the design and construction process include (1) design-build, (2) construction management-agent, (3) construction management-at risk, (4) design engineer/
construction manager. These alternative approaches are discussed at the website http://www.
mhprofessional.com/wwe .
 The classic design procedure includes the following steps:
 • Study and conceptual design
 • Preliminary design
 • Final design
These steps will be examined in more detail in the following paragraphs. Each of these steps
forms a major decision point for the owner. He or she must be provided enough information to
allow a rational decision among the alternatives, including the alternative to not proceed.
 The design process is iterative. Each step requires reevaluation of the design assumptions
made in previous steps, the ability of the design to meet the design criteria, the compatibility of
processes, and integration of the processes. At key decision points, the economic viability of the
project must be reassessed.
 Study and Conceptual Design
 In this phase of the design, alternatives are examined and appropriate design criteria are established. It is in this stage of the project that alternatives to facility construction are examined. For
water supply, the alternatives to facility construction might include purchasing water from a
nearby community, instituting water conservation, or having individual users supply their own
water by private wells. For wastewater treatment, the alternatives to facility construction might
include connection to a nearby community’s system or controlling infiltration and inflow into
the sewer system. In addition, the null alternative, that is the cost of doing nothing must also be
considered.
THE DESIGN AND CONSTRUCTION PROCESSES 1-11
 Establishment of Design Criteria. Design criteria are the boundary conditions that establish
the functional performance of the facility. Two general types of criteria are used: performance
and prescriptive. Performance criteria define the desired objective, but not the means of achieving it. Prescriptive criteria define the explicit details of how the facility will be built. The design
criteria are frequently a combination of the two types of criteria.
 Water and wastewater treatment systems will be used for illustration in the following paragraphs. Some of the factors to be considered will differ for water supply and sewer systems.
Six factors are normally considered in establishing the design criteria for water and wastewater
treatment systems:
 • Raw water or wastewater characteristics.
 • Environmental and regulatory standards.
 • System reliability.
 • Facility limits.
 • Design life.
 • Cost.
 Raw water or wastewater characteristics. Water characteristics include the demand for water
and the composition of the untreated ( raw ) water. Wastewater characteristics include the flow
rate of the wastewater and its composition.
 Sound design practice must anticipate the range of conditions that the facility or process can reasonably be
expected to encounter during the design period. The range of conditions for a plant typically varies from
a reasonably certain minimum in its first year of operation to the maximum anticipated in the last year of
the design service period in a service area with growth of customers. . . . Often the minimum is overlooked
and the maximum is overstated. (WEF, 1991)
 Consideration of the flowrates during the early years of operation is often overlooked, and over sizing
of equipment and inefficient operations can result. (Metcalf & Eddy, Inc., 2003).
 The water characteristics include:
 • Raw water composition.
 • Hourly, daily, weekly, monthly, and seasonal variations in raw water composition and
availability.
 • Variations in demand from domestic, industrial, commercial, and institutional activities.
 The wastewater characteristics include:
 • Composition and strength of the wastewater.
 • Hourly, daily, weekly, monthly, and seasonal variations in flow and strength of the wastewater.
 • Contributions from industrial and commercial activities.
 • Rainfall/runoff intrusion. 
1-12 WATER AND WASTEWATER ENGINEERING
 • Groundwater infiltration.
 • Raw water mineral composition.
 Water quality standards to be met. Early consideration of the water quality standards provides
the basis for elimination of treatment technologies that are not appropriate. The standards are prescribed by the regulating agency. The standards require that the treatment facility provide potable
water or discharge wastewater that meets numerical requirements ( performance standards). They
are based on statutory requirements. For example, regulations specify the concentration of coliform organisms that may be delivered to consumers or discharged into a river. For wastewater,
modeling studies of the stream or river may also be required. For the river, the regulating agency
will focus on the critical seasonal parameters for the stream or river. Normally, this will be in the
summer dry-season because the flow in the river or stream will be low (reducing the capacity for
assimilation of the treated wastewater), the oxygen carrying capacity of the stream will be low
(stressing the aquatic population), and the potential exposure from recreational activities will be
high. The potable water or wastewater effluent standards do not prescribe the technology that is
to be used in meeting the standards, but they do establish the goals that the engineer uses to select
the appropriate treatment processes.
 Other requirements. In addition to the numerical standards, other requirements may be
established by the regulatory agency as well as the owner. For example, drinking water limits on
taste and odor, and specific minerals such as calcium, magnesium, iron, and manganese may be
specified. For wastewater, in addition to the numerical standards, the absence of foam, floating
material, and oil films may be required.
 System reliability. System reliability refers to the ability of a component or system to perform
its designated function without failure. Regulatory reliability requirements are, in fact, redundancy requirements. True reliability requirements would specify the mean time between failure
for given components or processes. This is difficult, if not impossible, criteria to specify or, for
that matter, to design, for the wide range of equipment and environmental conditions encountered
in municipal water and wastewater projects.
For water supply systems, some redundancy recommendations of the Great Lakes–Upper
Mississippi River Board of State and Provincial Pubic Health and Environmental Managers are
shown in Table 1-3 (GLUMRB, 2003).
 There are three “reliability” classes for wastewater treatment facilities established by the
U.S. Environmental Protection Agency (EPA). Class I reliability is required for those plants that
discharge into navigable waters that could be permanently or unacceptably damaged by effluent
that was degraded in quality for only a few hours. Class II reliability is required for those plants
that discharge into navigable waters that would not be permanently or unacceptably damaged
by short-term effluent quality, but could be damaged by continued (several days) effluent quality degradation. Class III reliability is required for all other plants (U.S. EPA, 1974). Table 1-4
provides EPA guidance on minimum equipment to meet reliability requirements. In reviewing
the design that is submitted by the engineer, the regulatory agency uses this guidance to establish prescriptive requirements prior to the issuance of the permit to construct the facility. Some
states may require more stringent requirements than the federal guidance. For example, Michigan
requires Class I reliability for all plants. 
THE DESIGN AND CONSTRUCTION PROCESSES 1-13
Component Recommendation
Source
Surface water
 Capacity Meet a one-in-50-year drought with due consideration for multiple year
droughts
 Intake structures Where intake tower is used, provide two independent intake cells, each
with three intake ports at different elevations
 Pumps Minimum of two; meet the maximum day demand with one unit out of
service
Groundwater
 Capacity Equal or exceed maximum day demand with largest producing well out
of service
 Wells Minimum of two
Treatment
Rapid mix Minimum of two; meet the maximum day demand with one unit out of
service
Flocculation Minimum of two; meet the maximum day demand with one unit out of
service
Sedimentation Minimum of two; meet the maximum day demand with one unit out of
service
Disinfection Minimum of two; meet the maximum day demand with one unit out of
service
Power Provide primary transmission lines from two separate sources or
standby generator
Finished water storage
Capacity Equal to the average day demand when fire protection is not provided
Meet domestic demand and fire flow demand where fire protection is
provided
Distribution
High service pumps Minimum of two; meet the maximum day demand with one unit out of
service
System pressure Minimum of 140 kPa at ground level at all points in the system
Nominal working pressure should be 410 to 550 kPa and not less than
240 kPa
Sources: Foellmi, 2005; GLUMRB, 2003.
TABLE 1-3
Guidance for minimum equipment and process reliability for water treatment
1-14
Reliability classification
I II III
Component Treatment
system
Power
source
Treatment
system
Power
source
Treatment
system
Power
source
Holding basin Adequate capacity for all flows Not applicable Not applicable
Degritting Optional No No
Primary sedimentation Multiple unitsa Yes Same as class I Two minimuma Yes
Trickling filters Multiple unitsb Yes Same as class I Optional No backup No
Aeration basins Two minimum w/equal
volume
Yes Same as class I Optional Single unit
permissible
No
Blowers or mechanical
aerators
Multiple unitsc Yes Same as class I Optional Two minimumc No
Diffusers Multiple sectionsd Same as class I Same as class I
Final sedimentation Multiple unitsb Yes Multiple unitsa Optional Two minimuma No
Chemical flash mixer Two minimum or backupe Optional No backup Optional Same as class II No
Chemical sedimentation Multiple unitsb Optional No backup Optional Same as class II No
Flocculation Two minimum Optional No backup Optional Same as class II No
Disinfection basins Multiple unitsb Yes Multiple unitsa Yes Same as class II
TABLE 1-4
EPA Construction Grants Program guidance for minimum equipment and process reliability for the liquid-processing train
aRemaining capacity with largest unit out of service must be for at least 50% of the design maximum flow.
bRemaining capacity with largest unit out of service must be for at least 75% of the design maximum flow.
cRemaining capacity with largest unit out of service must be able to achieve design maximum oxygen transfer; backup unit need not be installed.
dMaximum oxygen transfer capability must not be measurably impaired with largest section out of service.
eIf only one basin, backup system must be provided with at least two mixing devices (one may be installed).
Source: U.S. EPA, 1974.
THE DESIGN AND CONSTRUCTION PROCESSES 1-15
 Site limitations. The location and area available for the treatment plant, availability of power,
roads, and a connection to the raw water supply or point to discharge define the facility limits. In
addition, the need for easements for the water distribution system and sewer system, and connection to the power and road grid are limitations that must be considered.
 Design life. The basis for economic comparison of alternatives is the design life. Processes and
components of processes with different design lives must be brought to an equivalent life for
valid economic comparison. Standard engineering economic techniques are available to perform
this analysis. A primer on economic analysis is given at http://www.mhprofessional.com/wwe .
 Cost. Cost is part of the design criteria because “(t)he ultimate selection among otherwise
acceptable unit processes or process trains is based on an economic evaluation.” (WPCF, 1977)
The degree of effort and care taken to estimate the capital investment cost and the operating and
maintenance cost depends on the stage of development of the project. In the early stages, rough
and relatively rapid estimation methods are usually the only ones justified. These are called
order-of-magnitude estimates. In the middle stages of the development of the project more
sophisticated estimates are made based on better information about the alternatives. These are
called study estimates. Authorization estimates are made to make the final choice between competing alternatives to complete the project. Bid estimates are made when the decision is made
to proceed with construction of the project. To provide an accurate document against which
to control expenditures during construction, a project control estimate is made using detailed
drawings and equipment inquiries (Valle-Riestra, 1983).
Cost estimates consist of two parts: capital costs and operating costs. “The capital cost and
operating cost estimated for each alternative must be made equivalent to make an economic comparison.” (WPCF, 1977) Several alternative methods may be used to make equivalent economic
comparisons. These include present worth analysis, annual cash flow analysis, rate of return
analysis, benefit-cost analysis, and breakeven analysis. These are described in numerous standard
textbooks on engineering economic analysis, for example, Newnan et al. (2000) and Thuesen and
Fabrycky (2000). Consideration of both the capital cost and the operating cost on an equivalent
basis is an essential part of making the correct choice in selecting the most economical alternative, as illustrated in Table 1-5 . Using Table 1-5 , on the basis of capital cost alone, alternative
B would be selected as the more economical plant. On an equivalent basis (total annual costs),
alternative A is the more economical plant. The selection of alternative B on the basis of capital
cost alone would result in an excess expenditure of more than $1,000,000 over that of alternative
A over the 25-year life of the project.
 A frequent omission failure in the examination of alternatives is the failure to consider the
null alternative. In addition, care must be taken not to include sunk costs (that is, past costs) in
the economic analysis and decision making process. The only relevant costs in an engineering
economic analysis are present and future costs (Newnan and Johnson, 1995).
 Screening of alternatives. Alternative designs are examined for the feasibility of meeting
design criteria. Either experience, literature review, or rough calculations are used to determine
sizes to be used in examining feasibility. Potential sites for the project are identified based on the
rough sizes. An order-of-magnitude level of cost is made at this point.
 This is a critical decision point for the project. The owner must be provided enough information to allow a rational decision about the choices available. This information should include the 
1-16 WATER AND WASTEWATER ENGINEERING
Cost Items
Equivalent Costs
b
Alternative A Alternative B
Capital costs
 Construction cost $6,300,000 $5,300,000
 Engineering 945,000 795,000
 Land 130,000 200,000
 Legal, fiscal, administrative 50,000 80,000
 Interest during construction 189,000 159,000
Subtotal $7,614,000 $6,534,000
 Inflation prior to construction 228,000 196,000
Total capital costs $7,842,000 $6,730,000
 Annualized capital cost
c 557,000 478,000
Operating and maintenance costs
 Personnel 220,000 290,000
 Power 120,000 60,000
 Chemicals 15,000 128,000
 Miscellaneous utilities 30,000 30,000
 Miscellaneous supplies and materials 50,000 50,000
Annual operating and maintenance costs $ 435,000 $ 558,000
Total annual costs
d $ 992,000 $1,036,000
TABLE 1-5
Comparison of design alternatives by equivalent costsa
a
Adapted from Water Pollution Control Federation, MOP 8, Wastewater Treatment Plant Design, Washington. D.C., 1977. b
Cost basis  2006. Engineering News Record Construction Cost Index  7690.72. c
Also called “debt service.” Capital cost recovery factor (A/P, 5%, 25)  0.0710. d
Annualized capital cost  annual operating and maintenance costs.
alternatives, the consequences of deciding one alternative over another, and the data and/or logic
the engineer used to arrive at the consequences.
 In the iterative process of design, the engineer must return to this step each time the list of alternatives or the cost estimates change to verify the original decision or to make a new decision.
 Preliminary Design
 At this stage, the engineer is given approval to perform the initial stages of design. This stage of
design is to allow a more rigorous comparison of the alternatives that appear to meet the goals of
the client.
 The engineer develops a work plan and schedule. These provide the client with realistic expectations of the timing of the project, while ensuring that the level of effort and degree of detail
developed by the engineer are appropriate for making decisions about the economic feasibility
of the project. 
THE DESIGN AND CONSTRUCTION PROCESSES 1-17
 In conjunction with the client, the engineer establishes the level of sophistication of the
facility. The following are examples of the items to be established:
 1. Degree of automation.
 2. Nature of maintenance history.
 3. Number of people to operate the facility.
 4. Qualifications of personnel required to operate and maintain the facility.
 The availability and responsibility for providing connection to the electric grid, road access,
fuel requirements, and sludge disposal alternatives are also established at this stage. In addition,
facility aesthetics (architecture) and construction impacts on the local community are discussed.
 The engineer completes a design of the major processes. This design includes sufficient
calculations to firm up the estimated land requirements, directs the location of soil borings, and
establishes horizontal and vertical control surveying.
 An authorization estimate is made to provide a basis for making the final choice of the
treatment processes and to allow the client’s budget planning to proceed. Sufficient information is available at this stage to allow a rigorous cost estimate comparison, such as that shown in
 Table 1-5, to be completed.
 This is another critical decision point for the project. As noted previously, the owner must
be provided enough information to allow a rational decision about the choices available. This
information should include the alternatives, the consequences of deciding one alternative over
another, and the data and/or logic the engineer used to arrive at the consequences. This is also
an opportunity to revisit the assumptions made in screening the alternatives to determine if they
have changed due to circumstances or the passage of time. The null alternative should also be
explicitly addressed.
 Final Design
 At this point the project alternative has been selected. Detailed calculations and justifications
are prepared. In these calculations, a range of conditions are examined. For example, minimum
values for hydraulics, reactor oxygen, mixing, biological nutrient control, alkalinity, seasonal
nitrification temperature, and unit equipment sizing and maximum values for waste solids, reactor
sizing, oxygen demand, and return sludge are recommended (WEF, 1991). In addition, in cold
weather regions, the following should be addressed in the detailed design (WEF, 1991):
 • The potential for ice formation on equipment.
 • Freezing of the process equipment.
 • Freezing of chemicals in storage.
 • Freezing of pipes not located below the frost line.
 • Viscosity changes in lubricants.
 • Snow and ice accumulations on structures, equipment, and roads.
 • Changes in the reaction rates of biological, physical and chemical processes. 
1-18 WATER AND WASTEWATER ENGINEERING
Extreme heat must also be considered. The following should be addressed in a detailed design:
 • Operator heat exposure.
 • Equipment temperature limits.
 • Flammability of chemicals and fuels in storage.
 • Viscosity changes in lubricants.
 • Expansion of joints and piping.
 • Changes in the reaction rates of biological, physical, and chemical processes.
 The design is completed in sufficient detail to select standard manufacturers’ equipment, prepare specifications in draft form, and firm up the site plan and layout of the facilities. The choice
of equipment is another critical decision point for the project. It is frequently to the economic
advantage of the owner to purchase the equipment directly, rather than through the construction
contract, because the contractor may have to pay taxes on the purchase and the municipality
will not. Owner-procured equipment provides the owner greater control in selection of specific
equipment. Thus, the equipment choices should be thoroughly reviewed with the owner.
 As the design is finalized, well-developed drawings and specifications are prepared. Bid estimates are prepared based on the detailed design. The economics of alternative means of completing the selected treatment process are considered in the bid estimate. For example, the choice of a
variable-speed drive or constant-speed drive for pumps is analyzed on a life-cycle cost basis (capital plus operating, maintenance, and replacement). Quotes are obtained to finalize cost estimates,
and an engineer’s opinion of the probable cost and cash flow projections are prepared. Because
the financial arrangements for funding the project are based on this estimate, it is imperative that
an accurate estimate of the cost be made.
 The detailed design process is completed with an ongoing review of the project with the
client. Typically, these occur at 30, 60 and 90 percent completion. These are critical decision
points for the project. As before, the owner must be provided enough information to allow a rational decision about the choices available. This is not to imply that the owner needs to consent
to every nut and bolt in the design, but they should have the opportunity to review alternatives
with major economic and/or operating implications. This is also an opportunity to revisit the
assumptions made at the preceding decision points to determine if they have changed due to
circumstances or the passage of time. The null alternative should also be explicitly addressed.
 At this point the project is sufficiently well understood to submit an application to the permitting authority for a construction permit.
 Once the final design is complete, bid documents are prepared and the bid is let. This is the
end of the formal design process and the beginning of the construction phase of the project. Unusual circumstances such as the unavailability of specified equipment or materials or unexpected
soil conditions may require more design work. At this point the engineer’s scope of work may
have to be renegotiated.
 Incremental Design and Iteration
 As noted earlier, the design process is incremental. In addition, individual steps as well as critical decision points often may require iteration. That is, a trial design may not meet performance 
THE DESIGN AND CONSTRUCTION PROCESSES 1-19
requirements because an initial assumption to start the design is not valid. For example, a pipe
diameter may be assumed to carry an estimated flow rate. The selection of this pipe diameter may
not be large enough based on friction loss calculations. Thus, a larger pipe must be selected, and
a second friction loss calculation must be completed.
 1-6 OVERALL CONSTRUCTION PROCESS
From the owner’s perspective, the construction process has the following important steps or
stages:
 • Initiation of project financing arrangements.
 • Acquisition of land or easements.
 • Project design.
 • Completion of project financing.
 • Bid letting.
 • Construction.
 • Preparation of project record documents.
 • Preparation of the O&M manual.
 • Start-up and shake-down.
 • Acceptance of the project.
 The owner’s perspective is taken because the contracts for construction are with the owner
and, ultimately, the facility belongs to the owner, not the engineer. None the less, the engineer’s
role is critical because he/she must diligently observe and, to the best of their ability, assure the
owner that the facility is built according to the plans and specifications.
 The construction process should not begin before the design process and project financing
are complete. Practicing engineers recommend that with the classical design-bid-construct project delivery, construction not begin until the design is complete. Other delivery methods, such
as design-build, may begin the construction process before the design is complete. Although
starting before the design is complete expedites the process, it imposes a need for extreme care
in making commitments.
 Project Financing
 The funds to pay for the project may come from a variety of sources. Bonds, state aid funds, operating revenue, and user fees are some examples. Discussion of these are beyond the scope of this
book. They are discussed at length in Water Utility Capital Financing (AWWA, 1998).
 Acquisition of Land or Easements
 Once the study phase is completed, enough information is available to begin identifying suitable sites for the project and, in the case of sewers and other utilities, routes for easements. 
1-20 WATER AND WASTEWATER ENGINEERING
In general this is the responsibility of the client because, as noted in the second canon of the
Code of Ethics, it falls outside of the area of competence of the engineer. The client hires some
combination of qualified and experienced people to do this work. A team may consist of a
registered land surveyor, attorney, and government official familiar with the community. The
engineer’s role is to provide guidance with respect to the requirements of the design. If necessary, the engineer may also be called on to perform environmental site investigations to ensure
the site(s) are free of hazardous materials. Of course, this effort should be included in the scope
of work.
 Options on the land to be purchased and freely given easements provide a means of expediting the construction process without making an unalterable commitment before the detailed
design and bid estimate are completed. These are essential for the final design, and they also
provide cost information for the estimate of total funding of the project.
 Once property bids have been accepted, final land acquisition can begin. For those not willing to give or sell land for the treatment facility or easements for the water main or sewer, condemnation proceedings may be instituted. This may cause a substantial delay in the start and
completion of the project and should be anticipated in the bid documents.
 Bid Letting
 Bid documents may be disseminated in a variety of ways. Many municipalities have developed a
program of prequalification of bidders and an invitation to bid is sent only to qualified bidders.
 At some reasonable time interval, after the bid package is disseminated to interested contractors, a prebid meeting is held to answer questions and clarify requirements of the bidders. This
meeting may be either mandatory or optional. The engineer and the owner’s contracting officer
are present at this meeting. Substantive questions are answered, in writing, to all participants by
issuing a bid document addendum.
 When the bids are received, the engineer assists the owner in determining the lowest qualified
bidder. The bid must be responsive in that it meets the specifications without unacceptable substitutions and agrees to meet the stated completion date. In addition, the bidder must have appropriate licenses, bonding, and insurance. A qualified bidder must also be free of outstanding claims
and liens from previous work. Appropriately licensed personnel and people qualified to supervise
the work should also be included in consideration of whether or not the bidder is qualified.
 This is a critical decision point in the project. First, the decision to proceed must be made.
Second, the decision(s) on the awardee(s) must be made. As at all the previous decision points,
the client must be given appropriate information to make informed decisions.
 Construction
 Before construction begins, a preconstruction meeting is held. All parties (engineer, owner, contractor) meet to review the contractor’s schedule, special provisions, sequence of construction,
payment process, and progress meetings schedule.
 During the construction process the engineer determines if the work is proceeding in accordance with the contract documents. For large projects, a full-time resident project representative (RPR) is on site. For small projects, the engineer provides periodic inspection and special
inspection at critical construction milestones. Thus, for small projects it is imperative that critical 
THE DESIGN AND CONSTRUCTION PROCESSES 1-21
points in the construction be identified and that the contractor’s progress be monitored so that
timely inspection can be made.
 The RPR acts as the engineer’s agent at the site. He/she will have various duties as spelled out
in the contract between the owner and the engineer. Some examples include (EJCDC, 2002):
 • Review schedules of progress, schedules of drawing submittals.
 • Attend conferences and meetings.
 • Serve as the engineer’s liaison with the contractor through the contractor’s superintendent.
 • Report to the engineer when clarification and interpretation of the contract documents are
required and transmit these to the contractor.
 • Receive samples and shop drawings for review and approval.
 • Consult with the engineer in advance of scheduled major inspections, tests, and systems
start-ups.
 • Accompany visiting inspectors representing public or other agencies having jurisdiction.
 • Maintain records and daily log book.
 The engineer makes visits to the site at intervals appropriate to the various stages of construction. Based on information obtained during these visits, the engineer will determine if the
work is proceeding in accordance with the contract documents and will keep the owner informed
of the progress of the work. The engineer recommends to the owner that the contractor’s work be
rejected while it is in progress if, on the basis of his/her observations, the engineer believes that
the work will not produce a completed project that conforms to the contract documents or that it
will threaten the integrity of the project (EJCDC, 2002). In addition the engineer
 • Clarifies contract documents for the contractor.
 • Recommends change orders as appropriate.
 • Reviews and approves shop drawings provided by the contractor.
 • Reviews samples and other data submitted by the contractor.
 • Recommends the amounts the contractor be paid based on observation of the progress and
quality of the contractor’s work (EJCDC, 2002).
 As work progresses, it is prudent for the contractor, engineer, and owner to have periodic
progress meetings. These should be scheduled at regular intervals as well as at milestone points.
Typical topics for discussion include percent completion, projections for completion in the next
period, staffing, and unexpected problems.
 Preparation of Project Record Documents
 Progress record documents show the results of the construction process. They record changes
from the design drawings that occurred during the construction process. These are important
documents for the owner as they provide the first step in performing maintenance or repair work. 
1-22 WATER AND WASTEWATER ENGINEERING
The contractor and/or the engineer may be responsible for the “as-built” drawings. This responsibility should be clearly indicated in contract documents or the engineer’s scope of work. The
accuracy of as-built drawings is increased substantially if they are prepared as the work progresses
rather than after it has been completed.
 Preparation of the Operation and Maintenance Manual
 The engineer or the contractor may be responsible for preparing the operation and maintenance
(O&M) manual. Even for a small plant, the O&M manual addresses a large number of items.
A small set of examples include: start-up and shut-down of pumps, preventive maintenance for
pumps and compressors, sampling and analysis methods to meet permit requirements, operation of analytical equipment in the laboratory, emergency procedures in the case of equipment
failure, methods for repair of equipment or procedures for obtaining repair services, procedures
for weatherproofing equipment for winter, building maintenance, sewer maintenance, and other
appurtenances. The O&M manual may also include a computer-based management system (often
called an asset management system ) for maintaining records of preventive maintenance, repair,
and replacement.
 Work on the manual must be complete before start-up and shake-down can commence because “testing” of the manual is part of the start-up and shake-down.
 Start-up and Shake-down
 When the facility construction is substantially complete and functional, the permitting authority
issues a discharge permit. At this point equipment can be started up and checked for performance. The contractor and equipment manufacturers perform the start-up. Routine and nonroutine operation is checked for each individual component and for the components working
together. The engineer provides inspection services to verify that the equipment works as specified and that the O&M manual is adequate.
 Acceptance of the Project
 Substantial completion. When the contractor considers the entire work ready for its intended
use, the engineer in company with the owner and contractor performs an inspection to determine if the work is substantially complete. A “punch list” of deficiencies is created during this
inspection. If after considering any objections of the owner, the engineer considers the work
substantially complete, he/she delivers a Certificate of Substantial Completion to the owner and
contractor.
 Final Notice of Acceptability. The contractor then uses the punch list for final completion of
the work. Once the punch list is completed, the engineer conducts a final inspection to determine
if the completed work of the contractor is acceptable. If he/she agrees that it is, the engineer
recommends final payment to the contractor. In addition, the engineer provides a Notice of
Acceptability of Work to the owner that certifies that the completed work furnished and performed by the contractor under the contract is acceptable (EJCDC, 2002). The notice is not a
guarantee or warranty of the contractor’s performance nor is it an assumption of responsibility
for any failure of the contractor to furnish and perform the work in accordance with the contract 
THE DESIGN AND CONSTRUCTION PROCESSES 1-23
documents (EJCDC, 2002). Not withstanding the engineer’s contract exculpatory provisions,
the courts have insisted that the engineer provide a standard of responsible care (Loulakis and
McLaughlin, 2007).
 1-7 HINTS FROM THE FIELD
 Experienced engineers have provided the following insights on the design and construction
process:
 • The option for a municipal owner to purchase equipment should be considered carefully.
Tax issues should be discussed with appropriate legal counsel. Other issues include potential late or early delivery of equipment. In these cases what is the impact/responsibility for
contract completion? Who stores equipment delivered early? Who insures it?
 • Construction cost estimates should be conservatively high. A low estimate may require
redoing the bond application and authorization including the potential requirement for an
election to approve additional bonding authority.
 Operation and maintenance personnel who have to live with the results of the engineer’s
design have offered the following suggestions:
 • The engineer’s job is not done when the owner accepts the project. Good engineering practice, as well as good client relations, requires that the design team keep in contact with the
facility. Immediately after project completion, a monthly phone call for a status check, and
to hear about problems and/or concerns, is a first step. This is to get issues raised early by
the owner, so they do not become major sore points. After a reasonable time of operation,
generally within six months and perhaps again a year or two later, the design team should
visit the facility. The purpose of the visit is to assess the practical operation of the facility as
well remove the impression that “It’s built, I am paid, so I am gone.” Often these visits will
reveal some enhancement that operators have made to make the operation of the facility
easier or more economical.
 The visit can also serve as an after-action summary of the communications issues that
occurred and corrections to enhance future work. It is also useful at this time to compare the
economic analysis assumptions with actual operating experience.
 • O&M manuals do not give much operational guidance. Their focus is the mechanics of
equipment start-up, shut-down, and maintenance. Frequently, they only include the equipment suppliers’ O&M manuals. In general operators must prepare standard operating procedures (SOPs) for process control. This means the operators should be hired before project
construction is completed so they have a chance to ask questions and prepare the SOPs.
Because hiring is the owner’s responsibility, the need for operators to be on board before
construction is complete should be brought to their attention by the engineer.
Visit the text website at www.mhprofessional.com/wwe for supplementary materials
and a gallery of photos.
1-24 WATER AND WASTEWATER ENGINEERING
 1-8 CHAPTER REVIEW
 When you have completed studying this chapter, you should be able to do the following without
the aid of your textbook or notes:
 1. Select the appropriate client–professional relationship for a given situation that describes the nature of the work and the knowledge/experience of the client.
 2. Decide if any of the ASCE canons of the Code of Ethics may be violated for a given
situation that describes the proposed action.
 3. Describe the five steps of the overall design process to a client that has not had previous experience with the design process for a municipal water or wastewater project.
 4. Explain the role of each of the six elements of the design criteria in setting the boundary conditions of the design.
 5. Identify the critical decision points for a client in the design process.
 6. Describe the six steps of the overall construction process to a client that has not had
previous experience with the construction process for a municipal water or wastewater
project.
 With the aid of the text, you should be able to do the following:
 7. Select the appropriate design alternative based on an engineering economic analysis of
the alternatives given the appropriate cost data, interest rate, and design life.
 1-9 PROBLEMS
NOTE: An engineering economic analysis primer is available at http://www.mhprofessional
.com/wwe .
 1-1. At the end of the preliminary design-stage of a small water treatment system design,
the following three options remain feasible. The consulting firm uses an interest rate
of 6.00% and a design life of 20 years for project evaluation. Based on cost, which
alternative should the engineering firm recommend?
Option Capital cost Annual operation and maintenance cost
Connect to nearby WTP $1,500,000 $300,000a
Membrane A $2,374,000 $209,000
Membrane B $2,162,000 $258,000
a
 The community will not have to provide O&M, but the nearby WTP will charge a monthly service fee
equivalent to this amount.
 1-2. During the conceptual design stage of Problem 1-1, the design firm identifies the
need for iron removal that was not anticipated in the screening of alternatives. 
THE DESIGN AND CONSTRUCTION PROCESSES 1-25
The capital cost for each of the membrane alternatives is now estimated to be an
additional $500,000. Is the Membrane A alternative still the best choice? Use the
interest rate and design life from Problem 1-1.
 1-3. In the design of a water treatment plant, the design engineer has a choice of selecting
a constant speed pump or a adjustable-frequency drive (AFD) pump. The capital and
operating costs for each pump are shown below. Assume an interest rate of 6.00%
and a 10 year life. Which pump should the engineer recommend?
Option Capital cost Annual electric cost
Constant speed pump $10,000 $16,000
AFD pump $20,000 $10,000
 1-4. Using a spreadsheet you have written, by trial and error determine the construction
cost of Alternative B in Table 1-5 that will make its total annual cost equal to the
total annual cost of Alternative A. With the significant figures given, the costs may
be assumed to be “equal” when they are within $1,000 of each other. Note: the
interest during construction and inflation prior to construction used in Table 1-5
was 3.00%.
 1-10 DISCUSSION QUESTIONS
 1-1. The city engineer has called your firm to ask that you review the design of a sewer
that has had periodic flooding. The design was performed by another consulting firm
in the community. What actions should you take before accepting the job?
 1-2. The professional organization that you belong to has been offered the opportunity to
meet in the facilities of a local casino free of charge. As the person in charge of
arrangements, what action would you recommend to the executive committee of your
organization?
 1-3. A small community of lakefront homes believes that the algae bloom in their lake is
the result of leaking septic tanks and tile fields. They retained an engineering firm
to explore alternatives for building a collection system and wastewater treatment
plant. An exhaustive feasibility study of alternative wastewater treatment systems
to replace the existing septic tank and tile field system has been completed. The engineering firm has recommended a sewer system and a wastewater treatment plant
to be operated by the community. After the report and recommendation to build has
been accepted by the client, the Department of Natural Resources and county health
department provide a report that declares that the existing system does not contribute
to pollution of the lake and the likely source of pollution is upstream agricultural
runoff. Should the engineering firm pursue the development of a wastewater
treatment system? Explain your reasoning. 
1-26 WATER AND WASTEWATER ENGINEERING
 1-4. The chairperson of the civil engineering department has asked that a local engineer
teach a one-semester course on engineering economics. The person that he is
recruiting has never taught before but is a registered professional engineer and does
economic analysis routinely. Does the candidate comply with the second canon?
Explain.
 1-5. List three methods to maintain your professional development throughout your
career.
 1-11 REFERENCES
 ASCE (1996) Code of Ethics, American Society of Civil Engineers, Reston, VA.
 AWWA (1998) Water Utility Capital Financing, Manual M29, American Water Works Association
Denver, CO.
 Baum, R. (1983) “The Limits of Professional Responsibility,” reprinted from Values and Public Works
Professional, University of Missouri, proceedings from American Public Works Association
workshop in Engineering Professionalism and Ethics, edited by J. H. Schaub, K. Pavlovic and M. S.
Morris, John Wiley & Sons, New York, p. 293.
 Bayles, M. D. (1991) “Obligations Between Professionals and Clients,” reprinted from Professional
Ethics, by M. D. Bayles, Wadsworth, Boston, 1989 in Ethical Issues in Engineering, edited by D. G.
Johnson, Prentice Hall, Englewood Cliffs, NJ, pp. 305–316.
 Bockrath, J. T. (1986) Dunham and Young’s Contracts, Specifications, and Law for Engineers, 4th ed.,
McGraw-Hill, New York, pp. 141, 330.
 EJCDC (2002) Standard Form of Agreement Between Owner and Engineer for Professional Services,
Engineers Joint Contract Documents Committee, a joint publication of American Council of
Engineering Companies, American Society of Civil Engineers, and National Society of Professional
Engineers.
Firmage, D. A. (1980) Modern Engineering Practice: Ethical, Professional, and Legal Aspects, Garland
STPM Press, New York, pp. 111–114, 126, 144–146, 149.
Foellmi, S. N. (2005) “Intake Facilities,” in E. E Baruth (ed.), Water Treatment Plant Design, McGrawHill, NY, pp. 4.1–4.35.
 GLUMRB (2003) Recommended Standards for Water Works, Great Lakes–Upper Mississippi River
Board of State and Provincial Public Health and Environmental Managers, Health Education
Services, Albany, NY.
 Harris, C. E., M. S. Pritchard and M. J. Rabins (1995) Engineering Ethics: Concepts and Cases,
Wadsworth, Boston, pp. 32, 56–58.
Kemper, J. D. and B. R. Sanders (2001) Engineers and Their Profession, 5th ed., Oxford University Press,
New York, pp. 159–167.
 Ladd, J. (1991) “The Quest for a Code of Professional Ethics: An Intellectual and Moral Confusion”
reprinted from R. Chalk, M. S. Frankel and S. B. Chafer, editors, AAAS Professional Ethics Project:
Professional Activities in the Scientific and Engineering Societies, American Association for the
Advancement of Science, 1980, in Ethical Issues in Engineering, edited by D. G. Johnson, Prentice
Hall, Englewood Cliffs, NJ, pp. 130–136.
 Loulakis, M. C. and L. P McLaughlin (2007) “Court Ignores Engineer’s Contractual Disclaimer for
Inspections,” Civil Engineering, April, p. 88.
 Martin, M. W. and R. Schinzinger (1991) “Engineering as Social Experimentation,” reprinted from
Ethics in Engineering, edited by M. W. Martin and R. Schinzinger, McGraw Hill, 1989, in
Ethical Issues in Engineering, edited by D. G. Johnson, Prentice Hall, Englewood Cliffs, NJ,
pp. 200–201. 
THE DESIGN AND CONSTRUCTION PROCESSES 1-27
 Metcalf & Eddy, Inc. (2003) Wastewater Engineering: Treatment and Reuse, 4th ed., McGraw-Hill,
Boston, pp. 186, 199.
 Newnan, D. G. and B. Johnson (1995) Engineering Economic Analysis, 5th ed., Engineering Press, San
Jose, CA, p. 124.
 Newnan, D. G., J. P. Lavelle and T. G. Eschenbach (2000) Engineering Economic Analysis, 8th ed.,
Engineering Press, Austin, TX.
 Petroski, H. (1985) To Engineer Is Human: The Role of Failure in Successful Design, Barnes & Noble
Books, New York.
 Sternbach, J. (1988) Negotiating and Contracting for Professional Engineering Services, Transportation
Research Board, National Research Council, Washington, D.C., pp. 29–30.
 Thuesen, G. J. and W. J. Fabrycky (2000) Engineering Economy, 9th ed., Prentice-Hall, Englewood
Cliffs, NJ.
 U.S. EPA (1974) Design Criteria for Mechanical, Electrical, and Fluid Systems and Component
Reliability, supplement to Federal Guidelines: Design, Operation, and Maintenance of Wastewater
Treatment Facilities, U.S. Environmental Protection Agency Report No. 430-99-74-001,
Washington, D.C.
 Valle-Riestra, J. (1983) Project Evaluation in the Chemical Process Industries, McGraw-Hill, New York,
pp. 64–65.
 WCED (1987) Our Common Future, World Commission on Environment and Development, Oxford
University Press, Oxford, England.
 WEF (1991) Design of Municipal Wastewater Treatment Plants, vol. 1, Water Environment Federation,
Alexandria, VA, pp.18, 22–23, 132, 155.
WPCF (1977) Wastewater Treatment Plant Design, Water Pollution Control Federation, Lancaster Press,
Lancaster, PA, pp. 19–20.
