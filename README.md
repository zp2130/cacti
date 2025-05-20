&nbsp;

<hr />

<pre style="text-align: center;"><span style="color: #cc0000; font-family: 'times new roman', times, serif; font-size: 14pt;"><strong><span style="color: #cc0000;">Cacti++</span></strong></span></pre>
<p style="text-align: left;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Github: <a href="https://github.com/zp2130/cacti" target="_blank" rel="noopener">https://github.com/zp2130/cacti</a></span></p>
<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The research project is a collaborative undertaking between the University of Texas at Arlington (UTA) and <span style="color: #009999;"><a style="color: #009999;" href="https://www.imec-int.com/en" target="_blank" rel="noopener">Interuniversity Microelectronics Centre</a> (<a style="color: #009999;" href="https://www.imec-int.com/en" target="_blank" rel="noopener">IMEC</a>).</span> A confidentiality agreement has been duly executed by UTA and IMEC. Under copyright and intellectual property protection regulations, the executable file, technology data file, and source code are not available for online distribution. We appreciate your consideration.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">[News] <a href="https://www.uta.edu/news/news-releases/2021/01/29/pan-microchips" target="_blank" rel="noopener">UTA aims to build a better microchip - Electrical engineer works to improve on-chip interconnect performance</a> - <em>Written by Jeremy Agor, College of Engineering, </em>Jan. 29, 2021.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><a href="https://www.uta.edu/news/news-releases/2021/01/29/pan-microchips" target="_blank" rel="noopener">https://www.uta.edu/news/news-releases/2021/01/29/pan-microchips</a>, <a href="https://blogs.cuit.columbia.edu/zp2130/cacti/news_1/" target="_blank" rel="attachment noopener wp-att-5823">pdf</a>.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">[News] <a href="https://new.newsedge.com/?cmmd=readStory&amp;uurp2=1&amp;key=C1uM33-JuPXT5RFjBhKAdmQqNogjD_jKs6Ty3K98IIW3mujHU5uUkpuhLIqLwCaC-u5ewVOR2I2NFpIvEeg9VEt1Z9-Mg0DTzboFCjE4tLrGens5Ba_47HwwCpCpq-aY&amp;client=rssfeed_25363_s186560&amp;uurp=1" target="_blank" rel="noopener">UTA aims to build a better microchip</a> - <em>Electronic Business Daily</em>, Feb. 11, 2021. <a href="https://blogs.cuit.columbia.edu/zp2130/cacti/news_2/" target="_blank" rel="attachment noopener wp-att-5824">pdf</a>.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><img class="aligncenter size-full wp-image-5750" src="http://blogs.cuit.columbia.edu/zp2130/files/2024/09/3DIC_intsim_pso_10061.png" alt="Cacti++" width="1000" height="519" /></span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><img class="aligncenter wp-image-5600 size-full" src="http://blogs.cuit.columbia.edu/zp2130/files/2024/09/3DIC_intsim_pso_10024.png" alt="" width="1000" height="564" /></span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The open-source <strong>CACTI</strong> simulator, a widely recognized tool, is adopted and modified to optimize the cache memory system. CACTI employs a systematic approach to adjusting SRAM cache memory organization parameters, with the objective of achieving optimal metrics as defined by the users. These metrics may include, for instance, minimum energy-delay product (EDP) or <span class="fontstyle0">energy-delay-area product (EDAP) for performance-power-area (<strong><span style="color: #dc0000;">PPA</span></strong>)</span>. To integrate the <span style="color: #009999;"><a style="color: #009999;" href="https://www.imec-int.com/en" target="_blank" rel="noopener"><strong>IMEC</strong></a></span>-designed subarray, key performance metrics in the original CACTI, such as area, energy, and delay, are incorporated based on true and reliable values extracted from experimental simulations and data in <span style="color: #dc0000;"><a style="color: #dc0000;" href="https://www.cadence.com" target="_blank" rel="noopener">Cadence</a> <strong>Virtuoso</strong>/Spectre</span> and <span style="color: #7030a0;"><a style="color: #7030a0;" href="https://www.synopsys.com" target="_blank" rel="noopener">Synopsys</a> <strong>Hspice</strong>/QuickCap</span>. The Cacti-based framework, <code><span style="color: #cc0000;"><strong>Cacti++</strong></span></code>, incorporates the overhead associated with the tag array within the cache memory system. The extraction of interconnect and device level parameters is conducted using <span style="color: #dc0000;">Cadence <strong>Spectre</strong></span> and <span style="color: #7030a0;">Synopsys <strong>Raphael</strong></span>, with the utilization of state-of-the-art technology nodes from <span style="color: #009999;">IMEC</span>. </span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">In the <strong>Linux operating system</strong>, the <strong><code>Cacti++</code></strong> framework contains <span style="color: #cc0000;"><strong>an executable file</strong></span> developed by <strong><code>C++</code></strong>, as well as <span style="color: #009999;"><strong>technology parameter data files</strong></span> and <strong>code</strong> for performing simulations in a large exploration space with high speed and low resource consumption, generated by <code><strong>Matlab</strong></code>. These are automatically generated to systematically sweep input design parameters for the aforementioned executable file and result extraction. The objective of this process is to comprehensively investigate energy-efficient computing systems, spanning from <span style="color: #009999;"><strong>technology node</strong></span> level to <strong>system</strong> level (a cache memory system), with consideration of both <strong>software</strong> and <strong>hardware</strong>.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The <code><span style="color: #cc0000;"><strong>Cacti++</strong></span></code> framework for co-designing the <strong>cache</strong> memory system with <strong>tag array overhead</strong>, <strong>interconnect</strong>, and technology node in <strong>microarchitecture</strong> exploration has been developed. The framework incorporates validated <strong>experimental subarray designs</strong> under a variety of <strong>ultra-scaled advanced device technology nodes</strong>.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">We put forth a proposal and quantify the benefits and constraints of <strong>E-Tree</strong> design technology with <strong>real workload memory allocation</strong>, with the aim of improving data average access delay and energy efficiency.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The cache array E-/H-Tree is redesigned by placing repeaters in a strategic manner along the path, with a range of delay overheads compared to optimal delay, in order to obtain the true benefit of the device and trees for the SRAM cache system performance.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The impact of cache design parameters, such as the subarray size/design, the number of vertical banks, and the array E-Tree interconnect level, on cache performance is investigated.</span>
<table style="height: 54px; width: 99.8562%; border-collapse: collapse; border-style: dashed; border-color: #000000;"><caption><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Tool</span></caption>
<tbody>
<tr style="height: 22px;">
<td style="width: 15.6716%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Platform:</span></td>
<td style="width: 288.705%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Linux OS</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 15.6716%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Code:</span></td>
<td style="width: 288.705%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong><code>C++</code></strong>; <strong><code>Matlab</code></strong>;<strong><code>Tcl</code></strong>; Slurm; Sbatch.</span></td>
</tr>
<tr style="height: 44px;">
<td style="width: 15.6716%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">EDA:</span></td>
<td style="width: 288.705%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><span style="color: #dc0000;">Cadence Spectre, Virtuoso</span>; <span style="color: #7030a0;">Synopsys Hspice, Raphael, QuickCap.</span></span></td>
</tr>
</tbody>
</table>
<h2><span style="color: #0070c0;"><strong><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Summary of Model Evolution</span></strong></span></h2>
<table style="height: 242px; width: 100%; border-collapse: collapse; border-color: #707070; border-style: dashed;">
<tbody>
<tr style="height: 44px;">
<td style="width: 10%; text-align: center; height: 66px;" rowspan="2"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Interconnect Device Technology</strong></span></td>
<td style="width: 10%; text-align: center; height: 66px;" rowspan="2"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>ASU PTM [10]</strong></span></td>
<td style="width: 30%; text-align: center; height: 66px;" colspan="3" rowspan="2"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>IMEC iN5 [2, 7~9]</strong></span></td>
<td style="width: 57.094%; text-align: center; height: 44px;" colspan="4"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>IMEC iN3/A14 [1, 3, 4, *]</strong></span></td>
<td style="width: 1.45299%; text-align: center; height: 44px;"><span style="font-family: 'times new roman', times, serif;">1</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 38.547%; text-align: center; height: 22px;" colspan="3"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Repeater Insertion</span></td>
<td style="width: 18.547%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Repeater vs DTL</span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">2</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Subarray</strong></span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">PTM-based bitline for materials</span></td>
<td style="width: 30%; text-align: center; height: 22px;" colspan="3"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">High-level Subarray Model</span></td>
<td style="width: 57.094%; text-align: center; height: 22px;" colspan="4"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">IMEC-designed A3~14</span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">3</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Organization</strong></span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Memory Cells/ Subarray/Mat/Bank/Array</span></td>
<td style="width: 87.094%; text-align: center; height: 22px;" colspan="7"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Subarray/Mat/Bank/Array</span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">4</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Pin Type</strong></span></td>
<td style="width: 20%; text-align: center; height: 22px;" colspan="2"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Original Side Pin</span></td>
<td style="width: 77.094%; text-align: center; height: 22px;" colspan="6"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Side Pin or Center Pin or Nonconventional</span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">5</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Tree Type</strong></span></td>
<td style="width: 30%; text-align: center; height: 22px;" colspan="3"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Original H-Tree</span></td>
<td style="width: 67.094%; text-align: center; height: 22px;" colspan="5"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">H-Tree or E-Tree</span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">6</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Cache/Array</strong></span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Original arrays, no logic cores.</span></td>
<td style="width: 40%; text-align: center; height: 22px;" colspan="4"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Data array, A<sub>logic</sub>=A<sub>sum_subarray</sub></span></td>
<td style="width: 47.094%; text-align: center; height: 22px;" colspan="3"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Cache with tag array overhead, A<sub>logic</sub>=A<sub>cache</sub></span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">7</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Interconnect Delay/Energy</strong></span></td>
<td style="width: 60%; text-align: center; height: 22px;" colspan="6"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Original equation-based 30% delay overhead for Tpu/Epu</span></td>
<td style="width: 37.094%; text-align: center; height: 22px;" colspan="2"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Spectre simulation &amp; Matlab fitting</span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">8</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Interconnect RC/RLC</strong></span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Original assumptions</span></td>
<td style="width: 68.547%; text-align: center; height: 22px;" colspan="6"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Cpu is extracted by Synopsys Raphael</span></td>
<td style="width: 18.547%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">DTL adopts RLC</span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">9</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1</span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">2</span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">3</span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">4</span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">5</span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">6</span></td>
<td style="width: 10%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">7</span></td>
<td style="width: 18.547%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">8</span></td>
<td style="width: 18.547%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">9</span></td>
<td style="width: 1.45299%; text-align: center; height: 22px;"><span style="font-family: 'times new roman', times, serif;">10</span></td>
</tr>
</tbody>
</table>
<h2><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong><span style="color: #0070c0;">A single simulation:</span></strong></span></h2>
<pre><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">$./cacti -infile cache.cfg &gt; cache.cfg.log
</span></pre>
<h2><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong><span style="color: #0070c0;">To sweep the design parameters:</span></strong></span></h2>
<table style="height: 20px; width: 99.978%; border-collapse: collapse; border-style: dotted;"><caption><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">This is part of the <strong><code>Cacti++</code></strong> automation sweep code generated using <code><strong>Matlab</strong></code>.</span></caption>
<tbody>
<tr style="height: 24px;">
<td style="width: 21.7324%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">sbatch_slurm_*_xx_folders_imec_*_hetree.sh</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">#SBATCH --nodes=1  --cpus-per-task=2</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">#SBATCH --array=1-xx</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">#SBATCH -p defq</span>
<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">#SBATCH --mem-per-cpu=4096</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">cd /path/cacti_$SLURM_ARRAY_TASK_ID</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">source perform_generateCACTI_imec.tcl</span></td>
<td style="width: 56.2303%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">It is recommended that the sbatch, <code>slurm</code>, and <code>tcl</code> be employed for the sweeping of the design parameters. The sbatch, slurm, and tcl code are automatically generated by <code>Matlab</code>.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 21.7324%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">/path/cacti_xx/perform_generateCACTI_imec.tcl</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">$../cacti -infile cache.cfg -tech_path ../cacti_xx/ &gt; *.log</span></td>
<td style="width: 56.2303%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">A single executable file is located at the root of the simulation folder, which contains xx sub-folders. The file path for the technology is located within each subfolder.</span></td>
</tr>
</tbody>
</table>
<h1><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>cache.cfg contains the following parameters:</strong></span></h1>
<h2><span style="color: #0070c0; font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Software Workload</strong></span></h2>
<table style="height: 67px; width: 100.052%; border-collapse: collapse; border-style: dotted;">
<tbody>
<tr>
<td style="width: 6.71054%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Parameter</strong></span></td>
<td style="width: 3.62895%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Value</strong></span></td>
<td style="width: 42.838%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Explanation</strong></span></td>
</tr>
<tr style="height: 47px;">
<td style="width: 6.71054%; height: 47px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-probability_factor_Lw_n_exp </span></td>
<td style="width: 3.62895%; height: 47px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0.0641</span></td>
<td style="width: 42.838%; height: 47px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">If value &gt;= 0.1, Synthetic Workload; if value &lt; 0.1, 0.0602, 0.0605,  0.0607, 0.0623, 0.0625, 0.0641, 0.0649, 0.0654: Realistic Workload, using corresponding *.txt, including the number of accesses to each bank, located within the current folder. E-Tree works for software workload. The parameter is described in Interconnect and Circuit too. </span></td>
</tr>
<tr style="height: 10px;">
<td style="width: 6.71054%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_he_tree_array_level
</span></td>
<td style="width: 3.62895%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1</span></td>
<td style="width: 42.838%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1: E-tree; 0: H-tree. Note: Array level interconnect technology is the same as the bank level counterpart.</span></td>
</tr>
<tr style="height: 10px;">
<td style="width: 6.71054%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_he_tree_bank_level
</span></td>
<td style="width: 3.62895%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1</span></td>
<td style="width: 42.838%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1: E-tree; 0: H-tree. This parameter is also described in Interconnect and Circuit.</span></td>
</tr>
</tbody>
</table>
<span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><img class="alignnone wp-image-5734 size-medium" src="http://blogs.cuit.columbia.edu/zp2130/files/2024/09/3DIC_intsim_pso_10056-300x132.png" alt="Software workload" width="300" height="132" /></span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> <span class="fontstyle0">If the probability factor α</span><span class="fontstyle2"> </span><span class="fontstyle0">is close to 0, it indicates a uniform workload. As </span><span class="fontstyle2">α </span><span class="fontstyle0">increases, there is more access to data closer to the array root pin. Thus, sweeping </span><span class="fontstyle2">α </span><span class="fontstyle0">provides an efficient way to quantify the potential advantages of E-Tree. <em>P<sub>subarray<span class="fontstyle1">_</span>i</sub></em> <span class="fontstyle1">and </span><em>L<sub>subarray<span class="fontstyle1">_</span>i</sub></em> <span class="fontstyle1">are the access probability to subarray </span><em>i</em> <span class="fontstyle1">and length of interconnect (in the space) to subarray </span><em>i</em> <span class="fontstyle1">from the array root pin, respectively. <em>A<sub>ccessbank_i</sub></em> is the total access number to the bank <em>i</em>. Realistic workloads of non-uniform are executed from SPEC CPU 2017, and a list of benchmarks is shown below:</span></span></span>
<table style="width: 99.9477%; border-collapse: collapse; border-style: dotted; height: 202px;"><caption><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> <span class="fontstyle0">N</span><span class="fontstyle0">ON</span><span class="fontstyle0">-U</span><span class="fontstyle0">NIFORM </span><span class="fontstyle0">W</span><span class="fontstyle0">ORKLOAD </span><span class="fontstyle0">F</span><span class="fontstyle0">ROM </span><span class="fontstyle0">SPEC CPU 2017</span></span></caption>
<tbody>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Benchmark</strong></span></td>
<td style="width: 155.142%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Benchmark Program General Category </strong></span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">602.gcc</span></td>
<td style="width: 155.142%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">GNU C Language optimizing compiler</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">605.mcf</span></td>
<td style="width: 155.142%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Combinatorial Optimization &amp; Vehicle Scheduling</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">607.cactus</span></td>
<td style="width: 155.142%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Physics: General/Numerical Relativity</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">623.xalan</span></td>
<td style="width: 155.142%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">XSLT processor for transforming XML to HTML</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">625.x264</span></td>
<td style="width: 155.142%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Video compression</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">641.leela</span></td>
<td style="width: 155.142%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">AI: Go engine with Monte Carlo &amp; selective tree search</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">649.fotonik</span></td>
<td style="width: 155.142%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Computational Electromagnetics (CEM)</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 12.6714%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">654.roms</span></td>
<td style="width: 155.142%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Regional Ocean Modeling System</span></td>
</tr>
</tbody>
</table>
<h2><span style="color: #0070c0; font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Cache Design</strong></span></h2>
<table style="height: 282px; width: 100.001%; border-collapse: collapse; border-style: dotted;">
<tbody>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Parameter</strong></span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Value</strong></span></td>
<td style="width: 45.2788%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Explanation</strong></span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-size (bytes)</span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">134217728</span></td>
<td style="width: 45.2788%; height: 24px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-UCA bank count</span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">16</span></td>
<td style="width: 45.2788%; height: 24px;"></td>
</tr>
<tr style="height: 22px;">
<td style="width: 8.84418%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-UCA vertical bank count</span></td>
<td style="width: 5.31648%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">4</span></td>
<td style="width: 45.2788%; height: 22px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-access mode (normal, sequential, fast)</span></td>
<td style="width: 5.31648%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">"sequential"</span></td>
<td style="width: 45.2788%; height: 10px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">Timing path: core-to-cache, tag array, and data array loop.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> -tree_space_to_time </span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> 0</span></td>
<td style="width: 45.2788%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1: adopt clock frequency for the interconnect; 0: not adopt.</span></td>
</tr>
<tr style="height: 46px;">
<td style="width: 8.84418%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-frequency_down
</span></td>
<td style="width: 5.31648%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> 0</span></td>
<td style="width: 45.2788%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0: no; 1: yes; 2: fix_max_clock_cycle for Lmax; 3: fix_max_clock_cycle for Laverage.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> -max_benchmark_clock_frequency
</span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> 3e9</span></td>
<td style="width: 45.2788%; height: 24px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-max_clock_cycle
</span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1000</span></td>
<td style="width: 45.2788%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Set the max clock cycle for the worst case of timing path or average length.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-max_clock_frequency
</span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">3e9</span></td>
<td style="width: 45.2788%; height: 24px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-clock_frequency_factor</span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1</span></td>
<td style="width: 45.2788%; height: 24px;"></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-number_of_mats_shared_bits
</span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">4</span></td>
<td style="width: 45.2788%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Default value: 4. 2, 1.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 8.84418%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-data_tag_ratio</span></td>
<td style="width: 5.31648%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">32</span></td>
<td style="width: 45.2788%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> Default value: 32. </span></td>
</tr>
</tbody>
</table>
<h2><span style="color: #0070c0; font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>SRAM Subarray</strong></span></h2>
<table style="height: 168px; width: 100%; border-collapse: collapse; border-style: dotted;">
<tbody>
<tr>
<td style="width: 3.43915%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Parameter</strong></span></td>
<td style="width: 2.26026%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Value</strong></span></td>
<td style="width: 47.4237%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Explanation</strong></span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 3.43915%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-tag_array_overhead_with_min_or_max_delay</span></td>
<td style="width: 2.26026%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">2</span></td>
<td style="width: 47.4237%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1: Select a tag array with a min. delay; 2: select a tag array with a max. delay.</span></td>
</tr>
<tr style="height: 48px;">
<td style="width: 3.43915%; height: 48px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-SHD_SHP_SLP_DC_DAI </span></td>
<td style="width: 2.26026%; height: 48px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0</span></td>
<td style="width: 47.4237%; height: 48px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0~6: Index of device and subarray design from <span style="color: #009999;">IMEC</span>, including standard design: 0 high density, 1 high performance, 2 low power; divided design: 3 conventional, 4 active interconnect A14, 5 active interconnect 22nm FDSOI, 6 A14 Si.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 3.43915%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-SHD_sweep_a14_to_a3 </span></td>
<td style="width: 2.26026%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0</span></td>
<td style="width: 47.4237%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">For high-density subarray, 0: A14, [128~1024]C×[128~512]R; 1: A14, A10, A5, and A3 for 288C×256R, 576C×128R.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 3.43915%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-LBWL_per_subarray
</span></td>
<td style="width: 2.26026%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">4</span></td>
<td style="width: 47.4237%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Number of Local blocks of word line per subarray.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 3.43915%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-LBBL_per_subarray </span></td>
<td style="width: 2.26026%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">8</span></td>
<td style="width: 47.4237%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Number of Local blocks of bit line per subarray.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 3.43915%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-multi_port </span></td>
<td style="width: 2.26026%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0</span></td>
<td style="width: 47.4237%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0 or 1: Not multi-port; 2: dual-port; 4.</span></td>
</tr>
</tbody>
</table>
<h2><span style="color: #0070c0; font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Interconnect and Circuit</strong></span></h2>
<table style="height: 403px; width: 100%; border-collapse: collapse; border-style: dotted;">
<tbody>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Parameter</strong></span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Value</strong></span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Explanation</strong></span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-htree_spacing_type </span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">2</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0: Side-pin access; 1: Non-conventional (active) interconnect; 2: Center-pin access; 3: Non-conventional interconnect + Center-pin access.</span></td>
</tr>
<tr style="height: 133px;">
<td style="width: 5.48747%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-Wire signaling (fullswing, lowswing, default)</span></td>
<td style="width: 2.20589%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">"Global_30"</span></td>
<td style="width: 54.2007%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Global_frequency_down &amp; -dtl_core_to_cache 0: frequency down.</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Global_30 &amp; -dtl_core_to_cache 0: the cache adopts repeater insertion. </span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">lowswing &amp; -dtl_core_to_cache 0: the cache adopts low swing. </span>

<span style="font-size: 14pt; font-family: 'times new roman', times, serif;">Fix_max_clock_cycle: fix max clock cycle for the worst case of timing path or average length.</span>

<span style="font-size: 14pt; font-family: 'times new roman', times, serif;">differential_transmission_line &amp; -dtl_core_to_cache 1: the data array and core-to-cache adopt DTL.</span>

<span style="font-size: 14pt; font-family: 'times new roman', times, serif;">Global_30 &amp; -dtl_core_to_cache 1: the data array adopts repeater insertion, core-to-cache adopts DTL.</span>

<span style="font-size: 14pt; font-family: 'times new roman', times, serif;">Global_30 &amp; -dtl_core_to_cache 2: the data array intra-bank adopts repeater insertion, inter-bank and core-to-cache adopt DTL.</span></td>
</tr>
<tr style="height: 10px;">
<td style="width: 5.48747%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-dtl_core_to_cache
</span></td>
<td style="width: 2.20589%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> 2</span></td>
<td style="width: 54.2007%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0: the cache adopts repeater insertion. </span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> -dtl_aspect_ratio
</span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> 2</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">Data array DTL aspect ratio.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-force_bits </span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">0: The number of data and address bits is based on Cacti computation. 288: force the value as 288 by the user.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-delay_overhead</span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">0.3</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">Global_30 &amp; 0.3: Adopt Cacti repeater insertion interconnect circuit model based on the delay overhead of 30%; Global_30 &amp; 1e12: low power; Global_30 &amp; 1e15: adopt repeater insertion based on Spectre simulation. It is important to note that when comparing DTL with repeater insertion, the latter should be based on Spectre simulation in order to ensure consistency.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-Interconnect material</span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">"cu"</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Cu, graphene-capped Ru, graphene-capped Cu, thick graphene, combination of graphene-capped Cu and thick graphene.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-grain_eff</span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">3</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">The grain effect factor for graphene-capped Cu. </span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-mfp_scale </span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The mean free path scale factor for graphene is as follows: As the factor increases, the resistance decreases.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-gracu_nlayer</span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">7</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The number of layers of graphene for graphene-capped Cu interconnect.</span></td>
</tr>
<tr style="height: 10px;">
<td style="width: 5.48747%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-graRcon0</span></td>
<td style="width: 2.20589%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">100</span></td>
<td style="width: 54.2007%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Graphene contact resistance, 100Ω⋅μm.</span></td>
</tr>
<tr style="height: 10px;">
<td style="width: 5.48747%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-wire_level </span></td>
<td style="width: 2.20589%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">5</span></td>
<td style="width: 54.2007%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Interconnect metal layer. The geometry is based on the instructions from <span style="color: #009999;">IMEC</span>.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 5.48747%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-output_wire_distribution</span></td>
<td style="width: 2.20589%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0</span></td>
<td style="width: 54.2007%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1: output wire distributions, including wire length, delay, energy, access probability to each subarray for data array and tag array.</span></td>
</tr>
<tr style="height: 47px;">
<td style="width: 5.48747%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_he_tree_array_level
</span></td>
<td style="width: 2.20589%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1</span></td>
<td style="width: 54.2007%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1: E-tree; 0: H-tree. Note: Array level interconnect technology is the same as the bank level counterpart.</span></td>
</tr>
<tr style="height: 23px;">
<td style="width: 5.48747%; height: 23px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_he_tree_bank_level
</span></td>
<td style="width: 2.20589%; height: 23px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1</span></td>
<td style="width: 54.2007%; height: 23px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1: E-tree; 0: H-tree. This parameter is also described in Software Workload.</span></td>
</tr>
<tr style="height: 47px;">
<td style="width: 5.48747%; height: 47px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-probability_factor_Lw_n_exp </span></td>
<td style="width: 2.20589%; height: 47px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">5</span></td>
<td style="width: 54.2007%; height: 47px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">If value &gt;= 0.1, Synthetic Workload; if value &lt; 0.1, 0.0602, 0.0605,  0.0607, 0.0623, 0.0625, 0.0641, 0.0649, 0.0654: Realistic Workload, using corresponding *.txt, including the number of accesses to each bank, located within the current folder. E-Tree works for software workload. The parameter is described in Software Workload too.</span></td>
</tr>
<tr style="height: 71px;">
<td style="width: 5.48747%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-wire_core_to_cache_cu </span></td>
<td style="width: 2.20589%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"> 1 </span></td>
<td style="width: 54.2007%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">1: core-to-cache interconnect adopts Cu only; 0: core-to-cache interconnect uses the same material as the cache.</span></td>
</tr>
<tr style="height: 23px;">
<td style="width: 5.48747%; height: 23px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-wire_core_to_cache_width
</span></td>
<td style="width: 2.20589%; height: 23px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">2</span></td>
<td style="width: 54.2007%; height: 23px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Core-to-cache interconnect width, unit: μm.</span></td>
</tr>
<tr style="height: 23px;">
<td style="width: 5.48747%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-wire_core_to_cache_ar </span></td>
<td style="width: 2.20589%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0.1</span></td>
<td style="width: 54.2007%; height: 10px;"></td>
</tr>
</tbody>
</table>
<h2><span style="color: #0070c0; font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Technology Nodes and Device</strong></span></h2>
<table style="width: 99.8426%; border-collapse: collapse; border-style: dotted;">
<tbody>
<tr>
<td style="width: 10.8919%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Parameter</strong></span></td>
<td style="width: 10.1267%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Value</strong></span></td>
<td style="width: 88.0732%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Explanation</strong></span></td>
</tr>
<tr>
<td style="width: 10.8919%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-technology (u)</span></td>
<td style="width: 10.1267%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">0.0014</span></td>
<td style="width: 88.0732%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Interconnect repeater technology node from <span style="color: #009999;">IMEC</span>.</span></td>
</tr>
</tbody>
</table>
<h2><span style="color: #0070c0; font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Target </strong></span></h2>
<table style="width: 99.8327%; border-collapse: collapse; border-style: dotted;">
<tbody>
<tr>
<td style="width: 20.5818%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Parameter</strong></span></td>
<td style="width: 5.44457%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Value</strong></span></td>
<td style="width: 49.8133%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Explanation</strong></span></td>
</tr>
<tr>
<td style="width: 20.5818%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-Optimize ED or ED^2 (ED, ED^2, NONE): </span></td>
<td style="width: 5.44457%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">"ED"</span></td>
<td style="width: 49.8133%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">ED: minimize EDP; EAD: minimize EDAP.</span></td>
</tr>
</tbody>
</table>
<h2><span style="color: #009999; font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>/tech_params/*.dat</strong></span></h2>
<table style="height: 422px; width: 100%; border-collapse: collapse; border-style: dotted;">
<tbody>
<tr>
<td style="width: 16.8374%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Parameter</strong></span></td>
<td style="width: 49.8292%;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><strong>Explanation</strong></span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">-C_drain (F/um)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">Repeater drain capacitance.</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">-C_gate (F/um)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">Repeater gate capacitance.</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">-Vdd (V)</span></td>
<td style="width: 49.8292%; height: 22px;"></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">-Vth (V)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Threshold voltage.</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">-I_on_n (A/um)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The current required for the repeater to achieve the desired output resistance is referred to as the "repeater ON current."</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-size: 14pt; font-family: 'times new roman', times, serif;">-I_off_n (A/um)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Leakage current under a variety of temperatures.</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-I_g_on_n (A/um)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Gate leakage current under a variety of temperatures.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 16.8374%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-area_cell (um^2)</span></td>
<td style="width: 49.8292%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Area of <span style="color: #009999;">IMEC</span>-designed subarray.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 16.8374%; height: 24px;">
<div>
<div><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-asp_ratio_cell</span></div>
</div></td>
<td style="width: 49.8292%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Aspect ratio of <span style="color: #009999;">IMEC</span>-designed subarray.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 16.8374%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_workload_I_on_n_drv (A/um)</span></td>
<td style="width: 49.8292%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">This designation is reserved for non-conventional interconnects.</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_subarray_column_choice (s_J)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Number of columns of <span style="color: #009999;">IMEC</span>-designed subarray.</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_subarray_read_latency (s)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Read latency of <span style="color: #009999;">IMEC</span>-designed subarray.</span></td>
</tr>
<tr style="height: 22px;">
<td style="width: 16.8374%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_subarray_write_latency (s)</span></td>
<td style="width: 49.8292%; height: 22px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Write latency of <span style="color: #009999;">IMEC</span>-designed subarray.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 16.8374%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_subarray_read_energy (J)</span></td>
<td style="width: 49.8292%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Read energy of <span style="color: #009999;">IMEC</span>-designed subarray.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 16.8374%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-imec_subarray_write_energy (J)</span></td>
<td style="width: 49.8292%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Write energy of <span style="color: #009999;">IMEC</span>-designed subarray.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 16.8374%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-wire_pitch (um)</span></td>
<td style="width: 49.8292%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Interconnect pitch.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 16.8374%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-wire_width (um)</span></td>
<td style="width: 49.8292%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Interconnect width.</span></td>
</tr>
<tr style="height: 24px;">
<td style="width: 16.8374%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-barrier_thickness (um)</span></td>
<td style="width: 49.8292%; height: 24px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Cu interconnect barrier thickness.</span></td>
</tr>
<tr style="height: 10px;">
<td style="width: 16.8374%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">-aspect_ratio (-)</span></td>
<td style="width: 49.8292%; height: 10px;"><span style="font-family: 'times new roman', times, serif; font-size: 14pt;">Interconnect aspect ratio.</span></td>
</tr>
</tbody>
</table>

<hr />

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><a href="https://scholar.google.com/citations?hl=en&amp;user=-pdAvr4AAAAJ&amp;view_op=list_works&amp;sortby=pubdate" target="_blank" rel="noopener">Google Scholar</a></span>

<span style="font-size: 14pt; font-family: 'times new roman', times, serif;"><strong>Selected Publications </strong>(as of May 2025)</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">The <span style="color: #0000ff;">corresponding <code>Cacti++</code> papers in blue</span> are as follows: </span>

<span style="font-family: 'times new roman', times, serif; color: #0000ff; font-size: 14pt;">[*] Z. Pei, H.-H. Liu, M. Mayahinia, M. Tahoori, F. Catthoor, Z. Tokei, P. Dubey, and C. Pan, "Interconnect/Memory Co-Design and Co-Optimization Using Differential Transmission Lines," <em>IEEE Transactions on Very Large Scale Integration (VLSI) Systems</em>, (*under review after revision).</span>

<span style="color: #0000ff; font-family: 'times new roman', times, serif; font-size: 14pt;">[1] Z. Pei, H.-H. Liu, M. Mayahinia, M. B. Tahoori, F. Catthoor, Z. Tőkei, D. B. Abdi, J. Myers, and C. Pan, "Ultra-Scaled E-Tree-Based SRAM Design and Optimization With Interconnect Focus," <em>IEEE Transactions on Circuits and Systems I: Regular Papers, </em>2024. DOI: 10.1109/TCSI.2024.3438164</span>

<span style="color: #0000ff; font-family: 'times new roman', times, serif; font-size: 14pt;">[2] Mayahinia, T. Marinelli, Z. Pei, H.-H. Liu, C. Pan, Z. Tokei, F. Catthoor, and M. B. Tahoori, "Dynamic Segmented Bus for Energy-efficient Last-level Cache in Advanced Interconnect-dominant Nodes", <em>IEEE Embedded Systems Letters</em>, 2024. DOI: 10.1109/LES.2024.3444711</span>

<span style="color: #0000ff; font-family: 'times new roman', times, serif; font-size: 14pt;">[3] H.-H. Liu, C. Gilardi, S. M. Salahuddin, Z. Pei, P. Schuddinck, Y. Xiang, P. Weckx, G. Hellings, M. G. Bardon, and J. Ryckaert, "Future Design Direction for SRAM Data Array: Hierarchical Subarray With Active Interconnect," <em>IEEE Transactions on Circuits and Systems I: Regular Papers, </em>2024. DOI: 10.1109/TCSI.2024.3410518</span>

<span style="color: #0000ff; font-family: 'times new roman', times, serif; font-size: 14pt;">[4] H.-H. Liu, P. Schuddinck, Z. Pei, L. Verschueren, H. Mertens, S. M. Salahuddin, G. Hiblot, Y. Xiang, B. T. Chan, and S. Subramanian, "CFET SRAM With Double-Sided Interconnect Design and DTCO Benchmark," <em>IEEE Transactions on Electron Devices, </em>2023. DOI: 10.1109/TED.2023.3305322</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">[5] S. Lu, Z. Pei, L. Shang, S. Jung, Q. Liang, and C. Pan, "Graphene-Based FPGA Design and Optimization at the 7nm FinFET Technology Node", in<em> 2025 26th International Symposium on Quality Electronic Design (ISQED)</em>, 2025. </span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">[6] S. Lu, Z. Pei, L. Shang, S. Jung, and C. Pan, "A Technology/Circuit Co-design Framework for Emerging Reconfigurable Devices," in <em>2023 IEEE 66th International Midwest Symposium on Circuits and Systems (MWSCAS)</em>, 2023, pp. 1123-1127. DOI: 10.1109/MWSCAS57524.2023.10406005</span>

<span style="color: #0000ff; font-family: 'times new roman', times, serif; font-size: 14pt;">[7] Z. Pei, M. Mayahinia, H.-H. Liu, M. Tahoori, F. Catthoor, Z. Tokei, and C. Pan, "Technology/Memory Co-Design and Co-Optimization Using E-Tree Interconnect," in <em>Proceedings of the Great Lakes Symposium on VLSI 2023</em>, 2023, pp. 159-162. DOI: 10.1145/3583781.3590311</span>

<span style="color: #0000ff; font-family: 'times new roman', times, serif; font-size: 14pt;">[8] Z. Pei, M. Mayahinia, H.-H. Liu, M. Tahoori, S. M. Salahuddin, F. Catthoor, Z. Tokei, and C. Pan, "Emerging Interconnect Exploration for SRAM Application Using Nonconventional H-Tree and Center-Pin Access," in <em>2023 24th International Symposium on Quality Electronic Design (ISQED)</em>, 2023, pp. 1-1. DOI: 10.1109/ISQED57927.2023.10129316</span>

<span style="color: #0000ff; font-family: 'times new roman', times, serif; font-size: 14pt;">[9] Z. Pei, M. Mayahinia, H.-H. Liu, M. Tahoori, F. Catthoor, Z. Tokei, and C. Pan, "Graphene-Based Interconnect Exploration for Large SRAM Caches for Ultrascaled Technology Nodes," <em>IEEE Transactions on Electron Devices, </em>vol. 70, pp. 230-238, 2022. DOI: 10.1109/TED.2022.3225512</span>

<span style="color: #0000ff; font-family: 'times new roman', times, serif; font-size: 14pt;">[10] Z. Pei, F. Catthoor, Z. Tokei, and C. Pan, "Beyond-Cu Intermediate-Length Interconnect Exploration for SRAM Application," <em>IEEE Transactions on Nanotechnology, </em>2022. DOI: 10.1109/TNANO.2022.3157952</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">[11] Z. Pei, A. Dutta, L. Shang, S. Jung, and C. Pan, "Interconnect Technology/System Co-Optimization for Low-Power VLSI Applications Using Ballistic Materials," <em>IEEE Transactions on Electron Devices, </em>vol. 68, pp. 3513-3519, 2021. DOI: 10.1109/TED.2021.3077210</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">[12] Z. Pei, L. Shang, S. Jung, and C. Pan, "Deep Pipeline Circuit for Low-Power Spintronic Devices," <em>IEEE Transactions on Electron Devices, </em>vol. 68, pp. 1962-1968, 2021. DOI: 10.1109/TED.2021.3059601</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">[13] G. Jalilvand, O. Ahmed, K. Bosworth, C. Fitzgerald, Z. Pei, and T. Jaing, "Application of a metallic cap layer to control Cu TSV extrusion," in <em>2017 IEEE 67th Electronic Components and Technology Conference (ECTC)</em>, 2017, pp. 61-66. DOI: 10.1109/ECTC.2017.290</span>

<span style="font-family: 'times new roman', times, serif; font-size: 14pt;">[14] Y. Yuan, M. Du, S. Zhang, and Z. Pei, "Effects of BiNbO<sub>4</sub> on the microstructure and dielectric properties of BaTiO<sub>3</sub>-based ceramics," <em>Journal of Materials Science: Materials in Electronics, </em>vol. 20, pp. 157-162, 2009. DOI: 10.1007/s10854-008-9674-5</span>
<pre><span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><span style="color: #0000ff;"><span style="color: #000000;">The macro-level data utilized in the research presented in the <strong>book</strong> was generated using</span> <span style="color: #b30000;"><code>Cacti++</code></span></span>: </span></pre>
<span style="font-family: 'times new roman', times, serif; font-size: 14pt;"><a href="https://link.springer.com/book/10.1007/978-3-031-76109-6" target="_blank" rel="noopener">Circuit-Technology Co-Optimization of SRAM Design in Advanced CMOS Nodes</a></span>

<span style="font-size: 14pt; font-family: 'times new roman', times, serif;">H.-H. Liu and F. Catthoor, "Circuit-Technology Co-Optimization of SRAM Design in Advanced CMOS Nodes," ed: <em>Springer</em>, 2024. DOI: 10.1007/978-3-031-76109-6</span>
