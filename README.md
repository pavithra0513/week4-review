# Literature Review Summary: Assessment of Urban Fabric for Smart Cities

## Background/Motivation
Unprecedented rates of urbanization are occurring, especially in quickly emerging countries like China. Numerous issues, such as urban sprawl, wasteful land usage, a decline in cultural identity, and heightened strain on infrastructure, accompany this expansion. A key factor in determining the sustainability, usability, and aesthetics of cities is the idea of urban fabric, which refers to the structural and physical layout of streets, buildings, and public areas.
Historical town planning theories and architectural observations have frequently been used in qualitative and theoretical frameworks to study urban fabric. Nonetheless, as cities get smarter, there is an increasing demand for quantitative, data-driven approaches to efficiently evaluate and control urban growth. To enhance quality of life, encourage sustainable growth, and optimize urban planning, smart cities make use of technology, data analytics, and computational models.
In order to address a significant gap in urban studies, Xin Li et al. (2016) introduced computational methods for evaluating the properties of urban fabrics in their work Assessment of Urban Fabric for Smart Cities. By using statistical analysis and Geographic Information System (GIS) methods to quantify important urban form variables like density, compactness, variety, fragmentation, and cohesiveness, it expands on earlier research. The way various urban forms interact, change, and impact the development of smart cities is revealed by these indicators.
This study is driven by the goal of creating a scalable and methodical approach to comprehending urban fabric that can be used in various urban settings. For planners and policymakers, traditional qualitative evaluations of urban structure frequently fall short of offering useful information. This study presents data-driven methodologies, which provide a more impartial and repeatable way to assess urban growth trends.
Furthermore, Hankou, China, the study's case study, exemplifies the juxtaposition of historical and contemporary urban structures, a problem that many quickly urbanizing regions face. Without rigorous planning and evaluation, the authors contend, cities run the risk of losing their historical character while falling short of maximizing contemporary urban efficiency. Their method not only makes it possible to comprehend urban morphology more thoroughly, but it also offers useful advice for creating adaptive, sustainable urban settings that adhere to smart city principles.
## Methods Used
Using Geographic Information System (GIS) and statistical tools, this resource offers computational techniques for examining urban fabric with an emphasis on urban blocks, density, compactness, and geographic distribution.

### 1. Geographic Information System (GIS)
- Mapping and analyzing spatial data.
- Visualizing urban block structures.

### 2. Quantitative Shape Indicators

#### - **Density**
  -  It determines the percentage of an urban block that is built up.
  - Formula: 
    \[
    Density = \frac{\sum S_i}{S_B}
    \]
    where:
    - \(S_i\) is the footprint coverage of each building in a given urban block.
    - \(S_B\) is the total area of the block.

#### - **Compactness**
  -  It Evaluates spatial clustering of buildings.
  -The gravity model is used to quantify urban sprawl.
  - Formula:
    \[
    C = \frac{\sum \frac{1}{d(i,j)}}{N (N-1) / 2}
    \]
    where:
    - \(d(i,j)\) is the distance between raster cells.
    - \(N\) is the number of raster cells.

#### - **Variation**
  -  It uses variations in building footprint sizes to examine patterns and rhythm.
  - Formula:
    \[
    Variation = \frac{\sum \sqrt{(S_i - S_{mean})^2}}{(N - 1) S_{mean}}
    \]
    where:
    - \(S_i\) is the footprint size of each building.
    - \(S_{mean}\) is the average building footprint size.
    - \(N\) is the number of buildings.

#### - **Fragmentation**
  -  It determines the urban fabric's complexity by calculating the perimeter-area ratio.
  - Formula:
    \[
    Fragmentation = 1 - \frac{4 \sqrt{S_i}}{P}
    \]
    where:
    - \(S_i\) is the footprint coverage of each building within an urban block.
    - \(P\) is the perimeter of the tested patch composed of buildings.

#### - **Cohesion**
  - It evaluates the degree of building clustering.
  - Formula:
    \[
    Cohesion = |F - F'|
    \]
    where:
    - \(F\) is the fragmentation before shape aggregation.
    - \(F'\) is the fragmentation after shape aggregation.

## 3. Statistical Analysis
- **Pearson & Spearman Correlation Coefficients**: identifies connections between indicators of the urban fabric.
- **Kolmogorov-Smirnov (KS) Test**: Verifies that the density values are distributed normally..
- **Scatter Plots**:It shows patterns and correlations.

## 4. Computational Techniques
- **Space Syntax**: investigates the impact of spatial arrangement on movement.
- **Isovists Analysis**: investigates visibility fields in cities.
- **Topological Analysis (Data Mining)**: recognizes trends in the urban fabric.

## Case Study: Hankou, China
-GIS and statistical techniques were used to investigate 83 urban blocks.
- Blocks were categorized for comparison study into low, medium, and high density categories.
- According to the findings, overdevelopment and arbitrary demolitions have disrupted the urban fabric.

## Significance of the Work
Smart city development and sustainable city planning depend on an understanding of the urban fabric. This effort advances the field in a number of ways:
- **Improved Urban Planning**: Assists planners in evaluating and improving spatial arrangements to improve usability and livability.
- **Data-Driven Decision Making**: offers quantitative techniques to aid in the formulation of policies and plans for urban renewal.
- **Historical Preservation**: identifies and shields historically important urban patterns against careless destruction.
- **Smart City Development**: Enhances urban growth's sustainability and efficiency by incorporating computational analysis.
- **Sociological Impact**: Investigates how human mobility and community relationships are impacted by urban infrastructure.
- **Environmental Sustainability**: analyzes urban sprawl and spatial density to support the planning of green infrastructure.
- **Economic Benefits**: It helps develop more effective land-use plans that strike a balance between spatial efficiency and economic expansion.
- **Infrastructure Optimization**:Aids in the creation of efficient and accessible transportation networks.

## Connection to Other Work
This study expands and develops on earlier research in computational urban analytics, smart city planning, and urban morphology. Among the important links are
- **Urban Morphology Studies**: It combines quantitative shape indicators with the fundamental work in urban form analysis to evaluate urban fragmentation, density, and compactness. By evaluating urban spatial patterns in a more methodical and scientific manner, this methodology enables researchers to compare past and present urban changes.
- **GIS and Remote Sensing**: It extends the use of classic GIS applications by integrating statistical analysis with geographical data to gain a deeper understanding of the dynamics of the urban fabric. Urban planners are able to track urban expansion, do real-time research, and forecast future land use changes because to this integration.
- **Smart City Frameworks**: Offers data-driven tools to maximize urban growth, sustainability, and livability, which is in line with current smart city models. By increasing the efficiency of resource distribution, transportation, and housing projects, this study supports larger initiatives to integrate technology with urban infrastructure.
- **Machine Learning and Data Mining**: Improves predictive modeling for urban planners by utilizing cutting-edge computer approaches to uncover hidden trends in urban development. Researchers can predict future urban demands, enhance land use rules, and identify trends in urban expansion by utilizing big data analytics.
- **Comparative Urban Studies**: By presenting a case study of Hankou, China, it adds to the larger conversation on urbanization and offers perspective that may be applied to other quickly urbanizing areas. This research makes it easier to find creative solutions and best practices that may be adjusted to a variety of urban settings by comparing various cities.
- **Policy and Planning Implications**: It helps governments and urban planners make evidence-based decisions by providing empirical techniques for assessing development plans and urban actions. For the purpose of drafting legislation that strike a balance between urban growth, sustainability, and historical preservation, this research offers strong analytical tools.

## Relevance to Capstone Project
This study has several important implications for the capstone project on **Data-Driven Analytics for School Location Impacting Urban Traffic Congestion**.
- **Urban Spatial Analysis**: It is possible to evaluate how school sites affect nearby urban structures and traffic flow by using the techniques used in urban fabric analysis.
- **GIS and Data Integration**: The capstone project's requirement to examine spatial data pertaining to school placements and their effects on traffic is in line with the usage of GIS techniques in this study.
- **Quantitative Urban Metrics**: The interaction between various school locations and the current urban fabric and traffic circumstances can be assessed using indicators like density, compactness, and fragmentation.
- **Predictive Analysis**: Based on various school location circumstances, the machine learning and data-driven methodologies covered in this study can help predict future congestion trends.
- **Policy Recommendations**:The results of this study can serve as a foundation for developing evidence-based policies that maximize school placement, ease traffic, and enhance urban mobility.

## Mathematical/Statistical Components and Diagrams
### Density Calculation
\[
\text{Density} = \frac{\sum S_i}{S_B}
\]

### Flowchart of Methodology
![Flowchart](images/methodology_flowchart.png)

### Histogram of Urban Fabric Indicators
![Histogram](images/urban_fabric_histogram.png)

### Scatter Plot of Correlation Between Indicators
![Scatter Plot](images/correlation_scatter_plot.png)

# References

- Li, X., Lv, Z., Hijazi, I. H., Jiao, H., Li, L., & Li, K. (2016). Assessment of Urban Fabric for Smart Cities. *IEEE Access*, 4, 373-382.
- Conzen, M. R. G. (1969). *Alnwick, Northumberland: A Study in Town-Plan Analysis*. London: George Philip.
- Hillier, B., & Hanson, J. (1984). *The Social Logic of Space*. Cambridge: Cambridge University Press.
