<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#svgIDa)"><path fill="url(#svgIDb)" class="xea0dxb7g"/><path fill="url(#svgIDc)" class="xea0dxb7g"/></g><g filter="url(#svgIDd)"><path fill="url(#svgIDe)" class="lzx3ibbji"/></g><g filter="url(#svgIDf)"><path class="q-x3nobwe"/></g><path fill="url(#svgIDg)" class="a2sw0ubfs"/><path fill="url(#svgIDh)" class="a2sw0ubfs"/><path fill="url(#svgIDi)" class="ignl44ppg"/><path fill="url(#svgIDj)" class="ignl44ppg"/><circle class="fp0kifztp"/><g filter="url(#svgIDk)"><path clip-rule="evenodd" class="t-er1ac6h"/></g><circle fill="url(#svgIDl)" transform="matrix(-1 0 0 1 12.152 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDm)"><path clip-rule="evenodd" class="c9x33ublx"/></g><path fill="url(#svgIDn)" class="a8o9m4b8d"/><path fill="url(#svgIDo)" class="a8o9m4b8d"/><g filter="url(#svgIDp)"><path class="fhalo8wue"/></g><path class="ge5k5tqmg"/><path fill="url(#svgIDq)" class="x69xtn6lh"/><g filter="url(#svgIDr)"><path class="cl5o9mbfr"/></g><path fill="url(#svgIDs)" class="qob7tbcuv"/><path fill="url(#svgIDt)" class="qob7tbcuv"/><path fill="url(#svgIDu)" class="qob7tbcuv"/><path fill="url(#svgIDv)" class="qob7tbcuv"/><path fill="url(#svgIDw)" class="qob7tbcuv"/><path fill="url(#svgIDx)" class="rk7t5obdq"/><g filter="url(#svgIDy)"><path class="ief17kh_e"/></g><g filter="url(#svgIDz)"><circle fill="url(#svgIDA)" class="at-t7hyox"/></g><g filter="url(#svgIDB)"><circle fill="url(#svgIDC)" class="wdihg828b"/></g><g filter="url(#svgIDD)"><circle fill="url(#svgIDE)" class="qorv833xn"/><circle fill="url(#svgIDF)" class="qorv833xn"/></g><g filter="url(#svgIDG)"><circle class="tmz8h560k"/><circle fill="url(#svgIDH)" class="i4s19o7bs"/><circle fill="url(#svgIDI)" class="i4s19o7bs"/></g><g filter="url(#svgIDJ)"><path fill="url(#svgIDK)" class="y6cuvac1l"/><path fill="url(#svgIDL)" class="y6cuvac1l"/><path fill="url(#svgIDM)" class="y6cuvac1l"/></g><path fill="url(#svgIDN)" class="r-19olnun"/><path fill="url(#svgIDO)" class="r-19olnun"/><path fill="url(#svgIDP)" class="r-19olnun"/><g filter="url(#svgIDQ)"><path fill="url(#svgIDR)" class="ww-jf4byh"/></g><g filter="url(#svgIDS)"><path class="w2xzcibjq"/><path fill="url(#svgIDT)" class="hdsfd1t1p"/><path fill="url(#svgIDU)" class="hdsfd1t1p"/><path fill="url(#svgIDV)" class="hdsfd1t1p"/><path fill="url(#svgIDW)" class="hdsfd1t1p"/></g><g filter="url(#svgIDX)"><path class="ktyppgbjv"/></g><g filter="url(#svgIDY)"><path class="eg5zoabzm"/><path fill="url(#svgIDZ)" class="d0br4_dwx"/><path fill="url(#svgIDaa)" class="d0br4_dwx"/><path fill="url(#svgIDab)" class="d0br4_dwx"/><path fill="url(#svgIDac)" class="d0br4_dwx"/></g><path stroke="url(#svgIDad)" class="fbkl4vbrf"/><g filter="url(#svgIDae)"><path class="u41fat2eo"/><path fill="url(#svgIDaf)" class="pe71n5bll"/></g><g filter="url(#svgIDag)"><path class="hb3y0stxa"/><path fill="url(#svgIDah)" class="szmtmhb2k"/></g><path class="izpa95b_j"/><path fill="url(#svgIDai)" class="od6lp0bpn"/><path class="ldrubdbwc"/><g filter="url(#svgIDaj)"><path class="io6xmst8r"/><path fill="url(#svgIDak)" class="set18_82i"/></g><g filter="url(#svgIDal)"><path fill="url(#svgIDam)" class="cm-q_qb_y"/></g><path class="makft8bsk"/><path fill="url(#svgIDan)" class="t5qcs4-cr"/><path class="y686fkbfk"/><g filter="url(#svgIDao)"><path fill="url(#svgIDap)" class="c7lqckvve"/></g><g filter="url(#svgIDaq)" transform="rotate(-27.914 7.779 7.603)"><ellipse class="cc31m69_x"/><ellipse fill="url(#svgIDar)" class="iz_ui50lj"/></g><g filter="url(#svgIDas)"><path stroke="url(#svgIDat)" class="no9iwmb5y"/></g><g filter="url(#svgIDau)"><path stroke="url(#svgIDav)" class="xueoo_b7t"/></g><g filter="url(#svgIDaw)"><path stroke="url(#svgIDax)" class="v2boghbyu"/></g><g filter="url(#svgIDay)"><path class="fpi067y_r"/></g><g filter="url(#svgIDaz)"><path class="cgs16fs6n"/></g><g filter="url(#svgIDaA)"><path fill="url(#svgIDaB)" class="yo62mdbsz"/></g><g filter="url(#svgIDaC)"><path fill="url(#svgIDaD)" class="inapzacic"/><path fill="url(#svgIDaE)" class="inapzacic"/></g><g filter="url(#svgIDaF)"><path fill="url(#svgIDaG)" class="h5v557bwi"/></g><g filter="url(#svgIDaH)"><path class="oyslc6iqn"/></g><path fill="url(#svgIDaI)" class="um-hfqldr"/><path fill="url(#svgIDaJ)" class="um-hfqldr"/><path fill="url(#svgIDaK)" class="san3y2bgz"/><path fill="url(#svgIDaL)" class="san3y2bgz"/><circle class="jxdcpxbzp"/><g filter="url(#svgIDaM)"><path clip-rule="evenodd" class="n7ejtvp_t"/></g><circle fill="url(#svgIDaN)" transform="matrix(-1 0 0 1 25.174 16.739)" class="kr_eiac3t"/><g filter="url(#svgIDaO)"><path clip-rule="evenodd" class="k17hoqbjd"/></g><path fill="url(#svgIDaP)" class="br01foesj"/><path fill="url(#svgIDaQ)" class="br01foesj"/><g filter="url(#svgIDaR)"><path class="mm8xt4wqt"/></g><path class="aq_bxpf1e"/><path fill="url(#svgIDaS)" class="q3t0ieb0g"/><g filter="url(#svgIDaT)"><path class="sdw1mqbop"/></g><path fill="url(#svgIDaU)" class="ov-ewbbff"/><path fill="url(#svgIDaV)" class="ov-ewbbff"/><path fill="url(#svgIDaW)" class="ov-ewbbff"/><path fill="url(#svgIDaX)" class="ov-ewbbff"/><path fill="url(#svgIDaY)" class="ov-ewbbff"/><path fill="url(#svgIDaZ)" class="oj978cc-p"/><g filter="url(#svgIDba)"><path class="j84b5mglu"/></g><g filter="url(#svgIDbb)"><circle fill="url(#svgIDbc)" class="dmw8_tb9t"/></g><g filter="url(#svgIDbd)"><circle fill="url(#svgIDbe)" class="v1h6b222s"/></g><g filter="url(#svgIDbf)"><circle fill="url(#svgIDbg)" class="b04ylqb9n"/><circle fill="url(#svgIDbh)" class="b04ylqb9n"/></g><g filter="url(#svgIDbi)"><circle class="wz6aoebid"/><circle fill="url(#svgIDbj)" class="n7go475sx"/><circle fill="url(#svgIDbk)" class="n7go475sx"/></g><g filter="url(#svgIDbl)"><path fill="url(#svgIDbm)" class="r4y5nyr8s"/><path fill="url(#svgIDbn)" class="r4y5nyr8s"/><path fill="url(#svgIDbo)" class="r4y5nyr8s"/></g><path fill="url(#svgIDbp)" class="a6c33c9wm"/><path fill="url(#svgIDbq)" class="a6c33c9wm"/><path fill="url(#svgIDbr)" class="a6c33c9wm"/><g filter="url(#svgIDbs)"><path fill="url(#svgIDbt)" class="o275ejy5b"/></g><g filter="url(#svgIDbu)"><path class="whtk90yvk"/><path fill="url(#svgIDbv)" class="mpsb33bcg"/><path fill="url(#svgIDbw)" class="mpsb33bcg"/><path fill="url(#svgIDbx)" class="mpsb33bcg"/><path fill="url(#svgIDby)" class="mpsb33bcg"/></g><g filter="url(#svgIDbz)"><path class="b73w46b7p"/></g><g filter="url(#svgIDbA)"><path class="czszgvb8t"/><path fill="url(#svgIDbB)" class="uxhfb-jhr"/><path fill="url(#svgIDbC)" class="uxhfb-jhr"/><path fill="url(#svgIDbD)" class="uxhfb-jhr"/><path fill="url(#svgIDbE)" class="uxhfb-jhr"/></g><path stroke="url(#svgIDbF)" class="ds-nb1m8m"/><g filter="url(#svgIDbG)"><path class="fgi5rxb7u"/><path fill="url(#svgIDbH)" class="e10h3ubfd"/></g><g filter="url(#svgIDbI)"><path class="ywtlfpbwi"/><path fill="url(#svgIDbJ)" class="s1mekvlnk"/></g><path class="c4yp206wx"/><path fill="url(#svgIDbK)" class="w5m8_ub1v"/><path class="o42q5u8nw"/><g filter="url(#svgIDbL)"><path class="stzeoeagu"/><path fill="url(#svgIDbM)" class="te5ywwx6i"/></g><g filter="url(#svgIDbN)"><path fill="url(#svgIDbO)" class="xwcmpmiep"/></g><path class="ik3jwybfc"/><path fill="url(#svgIDbP)" class="ub-hlrbbg"/><path class="bp_j3b9pe"/><g filter="url(#svgIDbQ)"><path fill="url(#svgIDbR)" class="a56xrccts"/></g><g filter="url(#svgIDbS)" transform="rotate(-27.914 20.8 7.603)"><ellipse class="e5vlpilql"/><ellipse fill="url(#svgIDbT)" class="stn8jkb-w"/></g><g filter="url(#svgIDbU)"><path stroke="url(#svgIDbV)" class="hxcmniq-c"/></g><g filter="url(#svgIDbW)"><path stroke="url(#svgIDbX)" class="c8rqv8b3d"/></g><g filter="url(#svgIDbY)"><path stroke="url(#svgIDbZ)" class="tpqc8ubgu"/></g><g filter="url(#svgIDca)"><path class="uxa1b_6nv"/></g><g filter="url(#svgIDcb)"><path class="r6f_m1hjh"/></g><g filter="url(#svgIDcc)"><path fill="url(#svgIDcd)" class="p5-0skusn"/></g><defs><filter id="svgIDa" width="3.097" height="9.794" x="5.827" y="20.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.360784 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDd" width="6.578" height="10.091" x="10.037" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDf" width="4.976" height="9.579" x="11.007" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".25"/></filter><filter id="svgIDk" width="5.896" height="7.11" x="2.763" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.290196 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.305882 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDm" width="5.996" height="6.96" x="9.279" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.266667 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.298039 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDp" width="2.703" height="2.68" x="12.211" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".2"/></filter><filter id="svgIDr" width="9.692" height="11.056" x="4.677" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDy" width="2.793" height="3.034" x="3.333" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".2"/></filter><filter id="svgIDz" width="1.614" height="1.414" x="6.1" y="7.225" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDB" width="1.843" height="1.843" x="5.886" y="7.011" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".25"/></filter><filter id="svgIDD" width="1.664" height="1.664" x="10.13" y="6.975" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDG" width="1.843" height="1.843" x="9.916" y="7.011" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".25"/></filter><filter id="svgIDJ" width="4.394" height="5.195" x="6.634" y="5.55" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDQ" width="5.799" height="5.299" x="6.891" y="3.55" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation="1"/></filter><filter id="svgIDS" width="5.338" height="3.907" x="6.15" y="3.789" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDX" width="2.246" height="2.636" x="7.595" y="7.011" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".375"/></filter><filter id="svgIDY" width=".895" height="1.236" x="8.371" y="7.642" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".025"/></filter><filter id="svgIDae" width="1.406" height="1.024" x="9.32" y="6.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDag" width="1.406" height="1.024" x="7.139" y="6.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDaj" width=".449" height=".41" x="9.373" y="7.4" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".05"/></filter><filter id="svgIDal" width=".608" height=".617" x="9.671" y="7.374" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".1"/></filter><filter id="svgIDao" width=".648" height=".671" x="7.79" y="7.347" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".1"/></filter><filter id="svgIDaq" width=".502" height=".414" x="7.528" y="7.396" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".05"/></filter><filter id="svgIDas" width="1.133" height=".533" x="9.347" y="6.53" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".05"/></filter><filter id="svgIDau" width="1.166" height=".557" x="7.136" y="6.557" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".05"/></filter><filter id="svgIDaw" width=".859" height="1.394" x="6.414" y="5.519" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".125"/></filter><filter id="svgIDay" width="1.73" height="2.911" x="6.695" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDaz" width="1.73" height="2.911" x="9.405" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDaA" width="4.792" height="2.36" x="6.669" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDaC" width="3.097" height="9.794" x="18.849" y="20.239" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.360784 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDaF" width="6.578" height="10.091" x="23.059" y="19.942" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.282353 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDaH" width="4.976" height="9.579" x="24.029" y="19.362" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".25"/></filter><filter id="svgIDaM" width="5.896" height="7.11" x="15.785" y="10.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.470588 0 0 0 0 0.290196 0 0 0 0 0.337255 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.462745 0 0 0 0 0.305882 0 0 0 0 0.282353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDaO" width="5.996" height="6.96" x="22.3" y="10.306" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.266667 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.443137 0 0 0 0 0.298039 0 0 0 0 0.258824 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDaR" width="2.703" height="2.68" x="25.233" y="11.784" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".2"/></filter><filter id="svgIDaT" width="9.692" height="11.056" x="17.698" y="9.943" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDba" width="2.793" height="3.034" x="16.355" y="13.392" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".2"/></filter><filter id="svgIDbb" width="1.614" height="1.414" x="19.123" y="7.225" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.384314 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDbd" width="1.843" height="1.843" x="18.908" y="7.011" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".25"/></filter><filter id="svgIDbf" width="1.664" height="1.664" x="23.153" y="6.975" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.482353 0 0 0 0 0.278431 0 0 0 0 0.372549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDbi" width="1.843" height="1.843" x="22.938" y="7.011" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".25"/></filter><filter id="svgIDbl" width="4.394" height="5.195" x="19.656" y="5.55" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.137255 0 0 0 0 0.113725 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDbs" width="5.799" height="5.299" x="19.913" y="3.55" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation="1"/></filter><filter id="svgIDbu" width="5.338" height="3.907" x="19.172" y="3.789" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDbz" width="2.246" height="2.636" x="20.617" y="7.011" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".375"/></filter><filter id="svgIDbA" width=".895" height="1.236" x="21.394" y="7.642" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".025"/></filter><filter id="svgIDbG" width="1.406" height="1.024" x="22.342" y="6.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDbI" width="1.406" height="1.024" x="20.161" y="6.156" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.0784314 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/></filter><filter id="svgIDbL" width=".449" height=".41" x="22.395" y="7.4" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".05"/></filter><filter id="svgIDbN" width=".608" height=".617" x="22.693" y="7.374" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".1"/></filter><filter id="svgIDbQ" width=".648" height=".671" x="20.812" y="7.347" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".1"/></filter><filter id="svgIDbS" width=".502" height=".414" x="20.55" y="7.396" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".05"/></filter><filter id="svgIDbU" width="1.133" height=".533" x="22.369" y="6.53" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".05"/></filter><filter id="svgIDbW" width="1.166" height=".557" x="20.158" y="6.557" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".05"/></filter><filter id="svgIDbY" width=".859" height="1.394" x="19.436" y="5.519" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_711" stdDeviation=".125"/></filter><filter id="svgIDca" width="1.73" height="2.911" x="19.717" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDcb" width="1.73" height="2.911" x="22.428" y="1.767" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><filter id="svgIDcc" width="4.792" height="2.36" x="19.691" y="3.749" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_711"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_711" result="effect2_innerShadow_4002_711"/></filter><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.553 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.579 21.066) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.215 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.506 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDl" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="ya-pfekwl"/><stop offset="1" class="lr5tnibbk"/></radialGradient><radialGradient id="svgIDs" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.522 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDu" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.976 7.274) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.768 7.84) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 16.504 5.682) scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDx" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.345 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="y2o07bc4o"/><stop offset=".902" class="m0vc0tb7f"/></radialGradient><radialGradient id="svgIDA" cx="0" cy="0" r="1" gradientTransform="matrix(.74335 0 0 1.30087 6.1 7.933)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="svgIDF" cx="0" cy="0" r="1" gradientTransform="matrix(.35019 -.255 .29104 .3997 10.995 7.82)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="svgIDH" cx="0" cy="0" r="1" gradientTransform="matrix(.34788 -.63985 .3745 .20362 10.82 8.28)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(.10983 .10872 -.14015 .1416 10.838 7.933)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="svgIDL" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55367 .68144 0 9.813 7.394)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58207 .72385 0 7.882 7.45)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.74736 -5.08684 0 8.691 7.181)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="svgIDT" cx="0" cy="0" r="1" gradientTransform="matrix(.33795 -1.25241 .60303 .16272 10.66 6.193)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="svgIDU" cx="0" cy="0" r="1" gradientTransform="matrix(1.62018 .1491 -.08017 .87116 9.964 5.448)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="svgIDV" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7113 -1.10159 0 8.819 4.29)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="matrix(1.30211 -.95422 1.49495 2.03998 6.087 7.177)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="svgIDac" cx="0" cy="0" r="1" gradientTransform="matrix(0 .0834 -.26796 0 8.957 8.613)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="svgIDaf" cx="0" cy="0" r="1" gradientTransform="matrix(.04414 -.25554 .756 .13057 9.854 7.05)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="svgIDah" cx="0" cy="0" r="1" gradientTransform="matrix(.04414 -.25555 .75602 .13059 7.673 7.05)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3436 -.54652 0 9.742 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDak" cx="0" cy="0" r="1" gradientTransform="matrix(-.09822 -.12656 .17425 -.13523 9.645 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDan" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34361 -.54655 0 7.894 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDar" cx="0" cy="0" r="1" gradientTransform="matrix(-.00328 -.20924 .25152 -.00394 7.772 7.736)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.575 28.114)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDaJ" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.068 34.613) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDaK" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.237 29.864)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDaL" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.528 28.41)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDaN" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="ya-pfekwl"/><stop offset="1" class="lr5tnibbk"/></radialGradient><radialGradient id="svgIDaU" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.544 21.848)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.487 3.119) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.279 10.166) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDaY" cx="0" cy="0" r="1" gradientTransform="matrix(.45766 -2.68928 1.12443 .19135 21.155 21)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDaZ" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.368 10.27)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="y2o07bc4o"/><stop offset=".902" class="m0vc0tb7f"/></radialGradient><radialGradient id="svgIDbc" cx="0" cy="0" r="1" gradientTransform="matrix(.74335 0 0 1.30087 19.123 7.933)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="gsgzrwbpm"/><stop offset="1" class="nhrtbwabt"/></radialGradient><radialGradient id="svgIDbh" cx="0" cy="0" r="1" gradientTransform="matrix(.35019 -.255 .29104 .3997 24.017 7.82)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ywu0pr7ii"/><stop offset="1" class="pw1h71b2a"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(.34788 -.63985 .3745 .20362 23.842 8.28)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="evklql54e"/><stop offset=".916" class="ppo67rb9b"/></radialGradient><radialGradient id="svgIDbk" cx="0" cy="0" r="1" gradientTransform="matrix(.10983 .10872 -.14015 .1416 23.86 7.933)" gradientUnits="userSpaceOnUse"><stop class="o45oetbxg"/><stop offset="1" class="mfyy4ibhn"/></radialGradient><radialGradient id="svgIDbn" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.55367 .68144 0 22.835 7.394)" gradientUnits="userSpaceOnUse"><stop class="q3kvcibxc"/><stop offset="1" class="kz100sbcz"/></radialGradient><radialGradient id="svgIDbo" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.58207 .72385 0 20.904 7.45)" gradientUnits="userSpaceOnUse"><stop class="z_g0j449a"/><stop offset="1" class="s5xtkwbhw"/></radialGradient><radialGradient id="svgIDbr" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.74736 -5.08684 0 21.713 7.181)" gradientUnits="userSpaceOnUse"><stop offset=".619" class="rko8b-bmk"/><stop offset="1" class="whxihzpaf"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(.33795 -1.25241 .60303 .16272 23.682 6.193)" gradientUnits="userSpaceOnUse"><stop offset=".372" class="v4bc9u3un"/><stop offset="1" class="o90gcpqxu"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(1.62018 .1491 -.08017 .87116 22.986 5.448)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="tti32obdt"/><stop offset="1" class="cpvxurbrw"/></radialGradient><radialGradient id="svgIDbx" cx="0" cy="0" r="1" gradientTransform="matrix(0 .7113 -1.10159 0 21.841 4.29)" gradientUnits="userSpaceOnUse"><stop class="vpyj0s_ar"/><stop offset="1" class="lkn2u3bae"/></radialGradient><radialGradient id="svgIDby" cx="0" cy="0" r="1" gradientTransform="matrix(1.30211 -.95422 1.49495 2.03998 19.11 7.177)" gradientUnits="userSpaceOnUse"><stop class="zk3m83b4g"/><stop offset="1" class="gey-evbzc"/></radialGradient><radialGradient id="svgIDbE" cx="0" cy="0" r="1" gradientTransform="matrix(0 .0834 -.26796 0 21.98 8.613)" gradientUnits="userSpaceOnUse"><stop class="w-44tpbkk"/><stop offset="1" class="d52rddbnb"/></radialGradient><radialGradient id="svgIDbH" cx="0" cy="0" r="1" gradientTransform="matrix(.04414 -.25554 .756 .13057 22.876 7.05)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="svgIDbJ" cx="0" cy="0" r="1" gradientTransform="matrix(.04414 -.25555 .75602 .13059 20.695 7.05)" gradientUnits="userSpaceOnUse"><stop class="ne4llzbvb"/><stop offset="1" class="vgfjqtbdb"/></radialGradient><radialGradient id="svgIDbK" cx="0" cy="0" r="1" gradientTransform="matrix(0 .3436 -.54652 0 22.764 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDbM" cx="0" cy="0" r="1" gradientTransform="matrix(-.09822 -.12656 .17425 -.13523 22.667 7.68)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(0 .34361 -.54655 0 20.916 7.644)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDbT" cx="0" cy="0" r="1" gradientTransform="matrix(-.00328 -.20924 .25152 -.00394 20.794 7.736)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="svgIDb" x1="5.927" x2="7.827" y1="24.13" y2="24.279" gradientUnits="userSpaceOnUse"><stop class="mch9zegwt"/><stop offset="1" class="x4y51kb4t"/></linearGradient><linearGradient id="svgIDc" x1="5.818" x2="6.365" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="w2ejlbckb"/><stop offset="1" class="s_plahh6j"/></linearGradient><linearGradient id="svgIDe" x1="12.139" x2="14.327" y1="24.154" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="dx14qxbsv"/><stop offset="1" class="ce26eet6g"/></linearGradient><linearGradient id="svgIDn" x1="5.349" x2="6.271" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDo" x1="5.865" x2="5.506" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDq" x1="12.1" x2="12.537" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDt" x1="5.74" x2="6.412" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDC" x1="6.808" x2="6.536" y1="8.051" y2="8.051" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="svgIDE" x1="11.298" x2="10.951" y1="7.47" y2="8.545" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="svgIDK" x1="10.529" x2="7.294" y1="8.098" y2="8.58" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="svgIDN" x1="6.533" x2="7.33" y1="9.24" y2="9.211" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="svgIDO" x1="10.879" x2="10.432" y1="8.885" y2="8.842" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="svgIDR" x1="8.594" x2="12.043" y1="6.833" y2="5.598" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="svgIDZ" x1="8.453" x2="8.85" y1="8.377" y2="8.377" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="svgIDaa" x1="9.216" x2="8.782" y1="8.513" y2="8.507" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="svgIDab" x1="8.901" x2="8.901" y1="8.828" y2="8.585" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="svgIDad" x1="8.38" x2="8.564" y1="9.512" y2="9.221" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="svgIDam" x1="10.071" x2="9.938" y1="7.666" y2="7.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDap" x1="8.209" x2="8.076" y1="7.666" y2="7.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDat" x1="10.078" x2="9.9" y1="6.76" y2="6.397" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="svgIDav" x1="7.831" x2="7.327" y1="6.706" y2="6.495" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="svgIDax" x1="6.844" x2="6.844" y1="5.853" y2="6.766" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="svgIDaB" x1="10.709" x2="7.209" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaD" x1="18.948" x2="20.849" y1="24.13" y2="24.279" gradientUnits="userSpaceOnUse"><stop class="mch9zegwt"/><stop offset="1" class="x4y51kb4t"/></linearGradient><linearGradient id="svgIDaE" x1="18.84" x2="19.387" y1="24.817" y2="24.817" gradientUnits="userSpaceOnUse"><stop class="w2ejlbckb"/><stop offset="1" class="s_plahh6j"/></linearGradient><linearGradient id="svgIDaG" x1="25.162" x2="27.349" y1="24.154" y2="23.31" gradientUnits="userSpaceOnUse"><stop class="dx14qxbsv"/><stop offset="1" class="ce26eet6g"/></linearGradient><linearGradient id="svgIDaP" x1="18.372" x2="19.294" y1="11.458" y2="13.39" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDaQ" x1="18.887" x2="18.528" y1="13.177" y2="12.552" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDaS" x1="25.122" x2="25.559" y1="13.176" y2="12.083" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDaV" x1="18.762" x2="19.434" y1="19.255" y2="19.239" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDbe" x1="19.83" x2="19.559" y1="8.051" y2="8.051" gradientUnits="userSpaceOnUse"><stop class="jrtbzwbyo"/><stop offset="1" class="xh6agdcni"/></linearGradient><linearGradient id="svgIDbg" x1="24.32" x2="23.973" y1="7.47" y2="8.545" gradientUnits="userSpaceOnUse"><stop class="z3o7w4-ew"/><stop offset="1" class="uddso4bed"/></linearGradient><linearGradient id="svgIDbm" x1="23.55" x2="20.316" y1="8.098" y2="8.58" gradientUnits="userSpaceOnUse"><stop class="ah-u2v6vh"/><stop offset="1" class="hp2sktbkw"/></linearGradient><linearGradient id="svgIDbp" x1="19.555" x2="20.352" y1="9.24" y2="9.211" gradientUnits="userSpaceOnUse"><stop class="wgn2-qn3r"/><stop offset="1" class="cyilnmbju"/></linearGradient><linearGradient id="svgIDbq" x1="23.901" x2="23.454" y1="8.885" y2="8.842" gradientUnits="userSpaceOnUse"><stop class="y91wuhb_y"/><stop offset="1" class="dfnybco8z"/></linearGradient><linearGradient id="svgIDbt" x1="21.616" x2="25.066" y1="6.833" y2="5.598" gradientUnits="userSpaceOnUse"><stop offset=".109" class="fxywcj73h"/><stop offset="1" class="c0g7wdubv"/></linearGradient><linearGradient id="svgIDbB" x1="21.475" x2="21.872" y1="8.377" y2="8.377" gradientUnits="userSpaceOnUse"><stop class="tye5yqhfq"/><stop offset="1" class="rb8odhbtu"/></linearGradient><linearGradient id="svgIDbC" x1="22.239" x2="21.804" y1="8.513" y2="8.507" gradientUnits="userSpaceOnUse"><stop class="w6mxzsbgv"/><stop offset="1" class="ylom6naui"/></linearGradient><linearGradient id="svgIDbD" x1="21.924" x2="21.924" y1="8.828" y2="8.585" gradientUnits="userSpaceOnUse"><stop class="hlulkvo5l"/><stop offset="1" class="y_z4ite8v"/></linearGradient><linearGradient id="svgIDbF" x1="21.402" x2="21.586" y1="9.512" y2="9.221" gradientUnits="userSpaceOnUse"><stop class="lwz87437z"/><stop offset=".663" class="c7jfumw-i"/></linearGradient><linearGradient id="svgIDbO" x1="23.093" x2="22.96" y1="7.666" y2="7.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbR" x1="21.231" x2="21.098" y1="7.666" y2="7.748" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbV" x1="23.1" x2="22.922" y1="6.76" y2="6.397" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="svgIDbX" x1="20.853" x2="20.349" y1="6.706" y2="6.495" gradientUnits="userSpaceOnUse"><stop class="v9-6-sbuc"/><stop offset="1" class="q8x82vmoe"/></linearGradient><linearGradient id="svgIDbZ" x1="19.866" x2="19.866" y1="5.853" y2="6.766" gradientUnits="userSpaceOnUse"><stop offset=".228" class="tkijdf1cs"/><stop offset="1" class="wg8zzjbli"/></linearGradient><linearGradient id="svgIDcd" x1="23.731" x2="20.231" y1="5.208" y2="5.395" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-bunny-ears-medium-dark" /></template>
<style>
.a2sw0ubfs {
  d: path("m7.895 28.192l-.035.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.121-.122v-1.719h1.968Z");
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a56xrccts {
  d: path("M21.26 7.775c0-.122-.1-.203-.126-.228l-.122.118l.075.153l.173-.043Z");
}

.a6c33c9wm {
  d: path("M19.656 7.064c0-.113.045-.249.136-.316l.068-.068a.448.448 0 0 0 .16-.362v-.361a.22.22 0 0 1 .181-.226c.273-.068.841-.18 1.659-.18c.818 0 1.386.112 1.659.18c.09.022.181.113.181.226v.361c0 .136.069.271.16.362c.212.149.199.23.181.406c-.023.226-.045.61-.045.61h.008l-.113 1.677c-.068.75-.657 1.272-1.36 1.272h-1.36c-.725 0-1.292-.522-1.36-1.272c-.059-.77-.085-1.541-.155-2.31Z");
}

.a8o9m4b8d {
  d: path("m5.272 13.39l2.827-1.586a.8.8 0 0 0-.78-1.396L4.457 12.02l.814 1.37Z");
}

.ah-u2v6vh {
  stop-color: var(--svg-color--9b6c5e, #9B6C5E);
}

.aq_bxpf1e {
  fill: var(--svg-color--605071, #605071);
  d: path("m25.537 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.at-t7hyox {
  cx: 6.808px;
  cy: 7.933px;
  r: 0.707px;
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.b04ylqb9n {
  cx: 23.86px;
  cy: 7.933px;
  r: 0.707px;
}

.b1pd8upnt {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
}

.b73w46b7p {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m21.724 7.88l-.347.72c-.043.149.06.297.207.297h.312c.146 0 .25-.15.207-.296l-.212-.72c-.045-.16-.12-.16-.167 0Z");
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bp_j3b9pe {
  fill: var(--svg-color--000, #000);
  d: path("M21.131 7.82a.216.216 0 0 0-.216-.217a.216.216 0 0 0-.192.316h.383a.215.215 0 0 0 .025-.1Z");
}

.bqhl8ltyr {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
}

.br01foesj {
  d: path("m18.294 13.39l2.827-1.586a.8.8 0 0 0-.78-1.396L17.48 12.02l.814 1.37Z");
}

.c0g7wdubv {
  stop-color: var(--svg-color--a27b71, #A27B71);
  stop-opacity: 0;
}

.c4yp206wx {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.852 7.327c.277 0 .51.19.574.448a.116.116 0 0 1-.113.144h-.945a.097.097 0 0 1-.096-.115a.592.592 0 0 1 .58-.477Z");
}

.c7jfumw-i {
  stop-color: var(--svg-color--865e63, #865E63);
  stop-opacity: 0;
}

.c7lqckvve {
  d: path("M8.238 7.775c0-.122-.1-.203-.126-.228l-.122.118l.075.153l.173-.043Z");
}

.c8rqv8b3d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M20.333 6.939c.139-.123.442-.252.817-.192");
}

.c9x33ublx {
  fill: var(--svg-color--815a5c, #815A5C);
  fill-rule: evenodd;
  d: path("M9.38 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.069 1.19l1.973-1.72c.93-.82.855-2.148-.348-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.cc31m69_x {
  cx: 7.779px;
  cy: 7.603px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.165px;
  ry: 0.084px;
}

.ce26eet6g {
  stop-color: var(--svg-color--967267, #967267);
}

.cgs16fs6n {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.783 3.273c-.222.71-.522 1.166-.645 1.305l-.633-.242c.013-.183.096-.709.325-1.356c.285-.808.578-1.09.875-.996c.21.086.355.403.078 1.29Z");
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cl5o9mbfr {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M8.798 9.943a2.872 2.872 0 0 0-2.871 2.871V21h2.931l.207-1.55a.175.175 0 0 1 .33-.055L10.186 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.cm-q_qb_y {
  d: path("M10.08 7.77a.356.356 0 0 0-.099-.196l-.11.12l.05.097l.158-.021Z");
}

.cpvxurbrw {
  stop-color: var(--svg-color--46383d, #46383D);
  stop-opacity: 0;
}

.cyilnmbju {
  stop-color: var(--svg-color--84615a, #84615A);
  stop-opacity: 0;
}

.czszgvb8t {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m21.68 7.812l-.226.72a.228.228 0 0 0 .22.296h.334a.23.23 0 0 0 .22-.296l-.225-.72c-.048-.16-.273-.16-.324 0Z");
}

.d0br4_dwx {
  d: path("m8.657 7.812l-.225.72a.228.228 0 0 0 .22.296h.333a.23.23 0 0 0 .22-.296l-.224-.72c-.048-.16-.273-.16-.324 0Z");
}

.d52rddbnb {
  stop-color: var(--svg-color--976f6a, #976F6A);
  stop-opacity: 0;
}

.dfnybco8z {
  stop-color: var(--svg-color--966d5f, #966D5F);
  stop-opacity: 0;
}

.dmw8_tb9t {
  cx: 19.83px;
  cy: 7.933px;
  r: 0.707px;
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.ds-nb1m8m {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M22.553 9.235a.109.109 0 0 0-.012-.138a.115.115 0 0 0-.136-.022a1.216 1.216 0 0 1-.564.133c-.207 0-.401-.048-.564-.133a.115.115 0 0 0-.137.023a.108.108 0 0 0-.011.138m1.424 0l-.042-.028l.042.027Zm0 0a.852.852 0 0 1-.712.38a.852.852 0 0 1-.712-.38m0 0l.041-.028m-.041.028l.041-.028m0 0a.802.802 0 0 0 .67.358a.802.802 0 0 0 .671-.358c.037-.055-.025-.118-.083-.089c-.17.089-.37.14-.587.14c-.215 0-.417-.051-.587-.14c-.058-.03-.12.036-.084.089Z");
}

.dx14qxbsv {
  stop-color: var(--svg-color--84565a, #84565A);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e10h3ubfd {
  d: path("m23.416 6.78l-.003-.002l-.005-.004l-.015-.012a1.097 1.097 0 0 0-.228-.123a1.2 1.2 0 0 0-.633-.067a.226.226 0 0 0 .07.446a.748.748 0 0 1 .5.093a.45.45 0 0 1 .024.016l.003.002a.226.226 0 0 0 .287-.349Z");
}

.e5vlpilql {
  cx: 20.801px;
  cy: 7.603px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.165px;
  ry: 0.084px;
}

.eg5zoabzm {
  fill: var(--svg-color--8c5f5e, #8C5F5E);
  d: path("m8.657 7.812l-.225.72a.228.228 0 0 0 .22.296h.333a.23.23 0 0 0 .22-.296l-.224-.72c-.048-.16-.273-.16-.324 0Z");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.evklql54e {
  stop-color: var(--svg-color--73443e, #73443E);
  stop-opacity: 0;
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fbkl4vbrf {
  fill: var(--svg-color--88014f, #88014F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M9.531 9.235a.109.109 0 0 0-.012-.138a.115.115 0 0 0-.136-.022a1.216 1.216 0 0 1-.564.133c-.207 0-.401-.048-.564-.133a.115.115 0 0 0-.136.023a.108.108 0 0 0-.012.138m1.424 0l-.042-.028l.042.027Zm0 0a.852.852 0 0 1-.712.38a.852.852 0 0 1-.712-.38m0 0l.041-.028m-.041.028l.041-.028m0 0a.802.802 0 0 0 .67.358a.802.802 0 0 0 .671-.358c.037-.055-.025-.118-.083-.089c-.17.089-.37.14-.587.14c-.215 0-.417-.051-.587-.14c-.058-.03-.12.036-.084.089Z");
}

.fgi5rxb7u {
  fill: var(--svg-color--352827, #352827);
  d: path("m23.416 6.78l-.003-.002l-.005-.004l-.015-.012a1.097 1.097 0 0 0-.228-.123a1.2 1.2 0 0 0-.633-.067a.226.226 0 0 0 .07.446a.748.748 0 0 1 .5.093a.45.45 0 0 1 .024.016l.003.002a.226.226 0 0 0 .287-.349Z");
}

.fhalo8wue {
  stroke: var(--svg-color--8d6d67, #8D6D67);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.736 12.31l1.083.627c.193.1.579.44.569 1.002");
}

.fp0kifztp {
  cx: 5.525px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--693a42, #693A42);
}

.fpi067y_r {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.948 3.273c.222.71.522 1.166.644 1.305l.633-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.211.086-.356.403-.078 1.29Z");
}

.ft5dv1b6b {
  fill: none;
}

.fxywcj73h {
  stop-color: var(--svg-color--a47f73, #A47F73);
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.ge5k5tqmg {
  fill: var(--svg-color--605071, #605071);
  d: path("m12.515 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.gey-evbzc {
  stop-color: var(--svg-color--453938, #453938);
  stop-opacity: 0;
}

.gsgzrwbpm {
  stop-color: var(--svg-color--664249, #664249);
}

.h5v557bwi {
  d: path("m25.762 19.942l-2.703.719l3.605 7.838a2.64 2.64 0 0 0 2.397 1.534c.122 0 .206-.12.166-.234l-3.465-9.857Z");
}

.hb3y0stxa {
  fill: var(--svg-color--352827, #352827);
  d: path("M7.22 6.78h.001l.003-.002l.005-.004a.593.593 0 0 1 .065-.046a1.2 1.2 0 0 1 .81-.156a.226.226 0 0 1-.07.446a.748.748 0 0 0-.5.093a.391.391 0 0 0-.026.018a.226.226 0 0 1-.288-.349Z");
}

.hdsfd1t1p {
  d: path("m10.86 5.189l.182.09c.318.158.5.52.432.904l-.25 1.287c-.023.133-.11.223-.243.226h-.007s.022-.384.045-.61c.019-.183-.013-.239-.182-.406a.532.532 0 0 1-.159-.362v-.361a.244.244 0 0 0-.181-.226a6.941 6.941 0 0 0-1.66-.18c-.817 0-1.385.112-1.658.18a.22.22 0 0 0-.181.226v.361a.448.448 0 0 1-.16.362l-.068.068c-.09.067-.136.203-.136.316c.023.248.045.61.045.61h-.02a.268.268 0 0 1-.252-.226l-.25-1.288a.865.865 0 0 1 .454-.88l.182-.091c.114-.068.227-.158.34-.249l.41-.43a.83.83 0 0 1 .931-.135c.228.068.478.068.705 0c.34-.113.727-.022 1 .226l.34.34c.091.112.205.18.341.248Z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hlulkvo5l {
  stop-color: var(--svg-color--7c4559, #7C4559);
}

.hp2sktbkw {
  stop-color: var(--svg-color--744d4a, #744D4A);
}

.hxcmniq-c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M22.544 6.72c.182-.033.538-.023.784.168");
}

.i4s19o7bs {
  cx: 10.838px;
  cy: 7.933px;
  r: 0.421px;
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.ief17kh_e {
  stroke: var(--svg-color--866a64, #866A64);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.952 13.917c-.089.073-.194.29.094.57A70.94 70.94 0 0 0 5.6 15.902");
}

.ignl44ppg {
  d: path("M15.641 28.192H13.5l.142.307a2.64 2.64 0 0 0 2.397 1.534c.121 0 .206-.12.166-.234l-.564-1.607Z");
}

.ik3jwybfc {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.827 7.327c-.276 0-.51.19-.574.448a.116.116 0 0 0 .114.144h.945c.06 0 .108-.055.096-.115a.593.593 0 0 0-.58-.477Z");
}

.inapzacic {
  d: path("m18.948 20.239l2.998.27l-1.064 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122V20.24Z");
}

.io6xmst8r {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.715 7.521c.027.036-.03.08-.094.128s-.111.082-.138.046c-.027-.036.003-.104.067-.152s.138-.058.165-.022Z");
}

.iz_ui50lj {
  cx: 7.779px;
  cy: 7.603px;
  rx: 0.165px;
  ry: 0.084px;
}

.izpa95b_j {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.83 7.327c.277 0 .51.19.574.448a.116.116 0 0 1-.113.144h-.945a.097.097 0 0 1-.096-.115a.592.592 0 0 1 .58-.477Z");
}

.j84b5mglu {
  stroke: var(--svg-color--866a64, #866A64);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.974 13.917c-.088.073-.194.29.094.57a70.98 70.98 0 0 0 1.554 1.415");
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jrtbzwbyo {
  stop-color: var(--svg-color--553038, #553038);
}

.jum30v1nu {
  stop-color: var(--svg-color--42384b, #42384B);
}

.jxdcpxbzp {
  cx: 18.548px;
  cy: 16.61px;
  r: 0.766px;
  fill: var(--svg-color--693a42, #693A42);
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k17hoqbjd {
  fill: var(--svg-color--815a5c, #815A5C);
  fill-rule: evenodd;
  d: path("M22.402 10.716a.8.8 0 0 0 .308 1.088l3.527 1.978a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.069 1.19l1.973-1.72c.93-.82.855-2.148-.348-2.917l-3.574-2.015a.8.8 0 0 0-1.089.308Z");
}

.kr_eiac3t {
  r: 0.766px;
}

.ktyppgbjv {
  fill: var(--svg-color--71404a, #71404A);
  d: path("m8.702 7.88l-.347.72c-.043.149.06.297.207.297h.312c.146 0 .25-.15.207-.296l-.211-.72c-.046-.16-.12-.16-.168 0Z");
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.kz100sbcz {
  stop-color: var(--svg-color--855354, #855354);
  stop-opacity: 0;
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.ldrubdbwc {
  fill: var(--svg-color--000, #000);
  d: path("M9.526 7.82c0-.12.096-.217.217-.217a.216.216 0 0 1 .192.316h-.383a.196.196 0 0 1-.026-.1Z");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lkn2u3bae {
  stop-color: var(--svg-color--3e3034, #3E3034);
  stop-opacity: 0;
}

.lr5tnibbk {
  stop-color: var(--svg-color--744160, #744160);
}

.lwz87437z {
  stop-color: var(--svg-color--865e63, #865E63);
}

.lzx3ibbji {
  d: path("m12.74 19.942l-2.703.719l3.605 7.838a2.64 2.64 0 0 0 2.397 1.534c.121 0 .206-.12.166-.234l-3.465-9.857Z");
}

.m0vc0tb7f {
  stop-color: var(--svg-color--825f59, #825F59);
}

.makft8bsk {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.805 7.327c-.276 0-.51.19-.574.448a.116.116 0 0 0 .114.144h.945c.06 0 .108-.055.096-.115a.593.593 0 0 0-.58-.477Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mch9zegwt {
  stop-color: var(--svg-color--7b504e, #7B504E);
}

.mfyy4ibhn {
  stop-color: var(--svg-color--6c443e, #6C443E);
  stop-opacity: 0;
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mm8xt4wqt {
  stroke: var(--svg-color--8d6d67, #8D6D67);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.758 12.31l1.083.627c.194.1.578.44.569 1.002");
}

.mpsb33bcg {
  d: path("m23.882 5.189l.182.09c.318.158.5.52.432.904l-.25 1.287c-.022.133-.11.223-.242.226h-.008s.023-.384.045-.61c.019-.183-.013-.239-.181-.406a.532.532 0 0 1-.16-.362v-.361a.244.244 0 0 0-.181-.226a6.941 6.941 0 0 0-1.659-.18c-.818 0-1.386.112-1.659.18a.22.22 0 0 0-.181.226v.361a.448.448 0 0 1-.16.362l-.067.068c-.091.067-.137.203-.137.316c.023.248.046.61.046.61h-.021a.268.268 0 0 1-.252-.226l-.25-1.288a.865.865 0 0 1 .455-.88l.181-.091c.114-.068.227-.158.341-.249l.409-.43a.83.83 0 0 1 .932-.135c.227.068.477.068.704 0c.34-.113.727-.022 1 .226l.34.34c.091.112.205.18.341.248Z");
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.n366y7b2s {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
  stop-opacity: 0;
}

.n7ejtvp_t {
  fill: var(--svg-color--745249, #745249);
  fill-rule: evenodd;
  d: path("M21.43 10.716a.8.8 0 0 1-.309 1.088l-3.526 1.978a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.973-1.72c-.93-.82-.856-2.148.347-2.917l3.574-2.015a.8.8 0 0 1 1.09.308Z");
}

.n7go475sx {
  cx: 23.86px;
  cy: 7.933px;
  r: 0.421px;
}

.ne4llzbvb {
  stop-color: var(--svg-color--301a2d, #301A2D);
}

.nhrtbwabt {
  stop-color: var(--svg-color--613641, #613641);
}

.no9iwmb5y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M9.522 6.72c.182-.033.538-.023.784.168");
}

.o275ejy5b {
  d: path("m23.52 5.55l-1.304.435a.444.444 0 0 0 .2.86l1.296-.173l-.192-1.122Z");
}

.o42q5u8nw {
  fill: var(--svg-color--000, #000);
  d: path("M22.548 7.82c0-.12.097-.217.217-.217a.216.216 0 0 1 .192.316h-.383a.196.196 0 0 1-.026-.1Z");
}

.o45oetbxg {
  stop-color: var(--svg-color--6c443e, #6C443E);
}

.o90gcpqxu {
  stop-color: var(--svg-color--3d3437, #3D3437);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.od6lp0bpn {
  d: path("M9.743 7.442a.378.378 0 0 1 .364.477h-.73a.38.38 0 0 1 .366-.478Z");
}

.oj978cc-p {
  d: path("m21.65 11.775l-.864-1.505h2.125l-.825 1.5a.25.25 0 0 1-.436.005Z");
}

.ov-ewbbff {
  d: path("M21.82 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.208 21h2.932l-1.33-3.705a1.998 1.998 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.oyslc6iqn {
  fill: var(--svg-color--9c7870, #9C7870);
  d: path("m24.53 20.164l.822-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.p5-0skusn {
  d: path("M24.081 5.75c.02.097-.101.145-.166.071c-.453-.513-1.133-1.01-2.023-1.01c-.839 0-1.554.532-2.033 1.063c-.065.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.388-.053Z");
}

.pe71n5bll {
  d: path("m10.394 6.78l-.003-.002l-.005-.004a.498.498 0 0 0-.066-.046a1.2 1.2 0 0 0-.81-.156a.226.226 0 0 0 .07.446a.748.748 0 0 1 .5.093a.374.374 0 0 1 .024.016l.003.002a.226.226 0 0 0 .287-.349Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.ppo67rb9b {
  stop-color: var(--svg-color--73443e, #73443E);
}

.pw1h71b2a {
  stop-color: var(--svg-color--7c524c, #7C524C);
  stop-opacity: 0;
}

.q-x3nobwe {
  fill: var(--svg-color--9c7870, #9C7870);
  d: path("m11.507 20.164l.823-.302l3.153 8.579h-.758l-3.218-8.277Z");
}

.q3kvcibxc {
  stop-color: var(--svg-color--855354, #855354);
}

.q3t0ieb0g {
  d: path("m25.537 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.q8x82vmoe {
  stop-color: var(--svg-color--483e3e, #483E3E);
  stop-opacity: 0;
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qhg47wyku {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
  stop-opacity: 0;
}

.qob7tbcuv {
  d: path("M8.798 9.943a2.872 2.872 0 0 0-2.871 2.871V21h2.931l.207-1.55a.175.175 0 0 1 .33-.055L10.186 21h2.932l-1.33-3.705a2 2 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.qorv833xn {
  cx: 10.838px;
  cy: 7.933px;
  r: 0.707px;
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r-19olnun {
  d: path("M6.634 7.064c0-.113.045-.249.136-.316l.069-.068a.448.448 0 0 0 .159-.362v-.361a.22.22 0 0 1 .181-.226a6.94 6.94 0 0 1 1.659-.18c.818 0 1.386.112 1.659.18c.09.022.181.113.181.226v.361c0 .136.069.271.16.362c.212.149.199.23.181.406c-.022.226-.045.61-.045.61h.008l-.113 1.677c-.068.75-.657 1.272-1.36 1.272h-1.36c-.725 0-1.292-.522-1.36-1.272c-.059-.77-.085-1.541-.155-2.31Z");
}

.r4y5nyr8s {
  d: path("M19.68 7.673h.021s-.022-.36-.045-.61c0-.112.045-.248.136-.315l.068-.068a.448.448 0 0 0 .16-.362v-.361a.22.22 0 0 1 .181-.226c.273-.068.841-.18 1.659-.18c.818 0 1.386.112 1.659.18c.09.022.181.113.181.226v.361c0 .136.069.271.16.362c.212.149.199.23.181.406c-.023.226-.045.61-.045.61h.008l-.113 1.677c-.068.75-.657 1.272-1.36 1.272h-1.36c-.725 0-1.292-.522-1.36-1.272l-.13-1.7Z");
}

.r6f_m1hjh {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.805 3.273c-.222.71-.522 1.166-.645 1.305l-.632-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.21.086.355.403.078 1.29Z");
}

.rb8odhbtu {
  stop-color: var(--svg-color--754e46, #754E46);
  stop-opacity: 0;
}

.rk7t5obdq {
  d: path("m8.628 11.775l-.864-1.505h2.125l-.825 1.5a.25.25 0 0 1-.436.005Z");
}

.rko8b-bmk {
  stop-color: var(--svg-color--714250, #714250);
  stop-opacity: 0;
}

.s_plahh6j {
  stop-color: var(--svg-color--774d4a, #774D4A);
  stop-opacity: 0;
}

.s1mekvlnk {
  d: path("M20.242 6.78h.002l.002-.002l.005-.004a.704.704 0 0 1 .066-.046a1.14 1.14 0 0 1 .177-.09a1.2 1.2 0 0 1 .633-.066a.226.226 0 0 1-.07.446a.748.748 0 0 0-.5.093a.396.396 0 0 0-.024.016l-.003.002a.226.226 0 0 1-.288-.349Z");
}

.s5xtkwbhw {
  stop-color: var(--svg-color--6f414d, #6F414D);
  stop-opacity: 0;
}

.san3y2bgz {
  d: path("M28.663 28.192h-2.141l.142.307a2.64 2.64 0 0 0 2.397 1.534c.121 0 .206-.12.166-.234l-.564-1.607Z");
}

.sdw1mqbop {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M21.82 9.943a2.872 2.872 0 0 0-2.872 2.871V21h2.932l.207-1.55a.175.175 0 0 1 .33-.055L23.208 21h2.932l-1.33-3.705a1.998 1.998 0 0 1-.118-.676v-3.804a2.872 2.872 0 0 0-2.872-2.871Z");
}

.set18_82i {
  d: path("M9.715 7.521c.027.036-.03.08-.094.128s-.111.082-.138.046c-.027-.036.003-.104.067-.152s.138-.058.165-.022Z");
}

.stn8jkb-w {
  cx: 20.801px;
  cy: 7.603px;
  rx: 0.165px;
  ry: 0.084px;
}

.stzeoeagu {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.737 7.521c.027.036-.03.08-.093.128c-.064.048-.112.082-.139.046c-.027-.036.003-.104.067-.152s.138-.058.165-.022Z");
}

.szmtmhb2k {
  d: path("M7.22 6.78h.001l.003-.002l.005-.004a.593.593 0 0 1 .065-.046a1.2 1.2 0 0 1 .81-.156a.226.226 0 0 1-.07.446a.748.748 0 0 0-.5.093a.391.391 0 0 0-.026.018a.226.226 0 0 1-.288-.349Z");
}

.t-er1ac6h {
  fill: var(--svg-color--745249, #745249);
  fill-rule: evenodd;
  d: path("M8.407 10.716a.8.8 0 0 1-.308 1.088l-3.527 1.978a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 1 1-1.068 1.19l-1.974-1.72c-.93-.82-.855-2.148.348-2.917l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.t5qcs4-cr {
  d: path("M7.893 7.442a.378.378 0 0 0-.364.477h.73a.38.38 0 0 0-.366-.478Z");
}

.te5ywwx6i {
  d: path("M22.737 7.521c.027.036-.03.08-.093.128c-.064.048-.112.082-.139.046c-.027-.036.003-.104.067-.152s.138-.058.165-.022Z");
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.tkijdf1cs {
  stop-color: var(--svg-color--32272d, #32272D);
}

.tmz8h560k {
  cx: 10.838px;
  cy: 7.933px;
  r: 0.421px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.tpqc8ubgu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.92 5.894v.38c-.003.064-.029.204-.109.264");
}

.tti32obdt {
  stop-color: var(--svg-color--46383d, #46383D);
}

.tye5yqhfq {
  stop-color: var(--svg-color--754e46, #754E46);
}

.u41fat2eo {
  fill: var(--svg-color--352827, #352827);
  d: path("m10.394 6.78l-.003-.002l-.005-.004a.498.498 0 0 0-.066-.046a1.2 1.2 0 0 0-.81-.156a.226.226 0 0 0 .07.446a.748.748 0 0 1 .5.093a.374.374 0 0 1 .024.016l.003.002a.226.226 0 0 0 .287-.349Z");
}

.ub-hlrbbg {
  d: path("M20.915 7.442a.378.378 0 0 0-.364.477h.73a.38.38 0 0 0-.366-.478Z");
}

.uddso4bed {
  stop-color: var(--svg-color--855a5b, #855A5B);
}

.um-hfqldr {
  d: path("m20.917 28.192l-.035.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.719h1.969Z");
}

.uxa1b_6nv {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.97 3.273c.222.71.522 1.166.644 1.305l.633-.242c-.013-.183-.096-.709-.324-1.356c-.285-.808-.578-1.09-.875-.996c-.211.086-.356.403-.078 1.29Z");
}

.uxhfb-jhr {
  d: path("m21.68 7.812l-.226.72a.228.228 0 0 0 .22.296h.334a.23.23 0 0 0 .22-.296l-.225-.72c-.048-.16-.273-.16-.324 0Z");
}

.v1h6b222s {
  cx: 19.83px;
  cy: 7.933px;
  r: 0.421px;
}

.v2boghbyu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.899 5.894v.38c-.004.064-.03.204-.11.264");
}

.v4bc9u3un {
  stop-color: var(--svg-color--3d3437, #3D3437);
}

.v9-6-sbuc {
  stop-color: var(--svg-color--483e3e, #483E3E);
}

.vgfjqtbdb {
  stop-color: var(--svg-color--301a2d, #301A2D);
  stop-opacity: 0;
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vpyj0s_ar {
  stop-color: var(--svg-color--3e3034, #3E3034);
}

.w-44tpbkk {
  stop-color: var(--svg-color--976f6a, #976F6A);
}

.w2ejlbckb {
  stop-color: var(--svg-color--876058, #876058);
}

.w2xzcibjq {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m10.86 5.189l.182.09c.318.158.5.52.432.904l-.25 1.287c-.023.133-.11.223-.243.226h-.007s.022-.384.045-.61c.019-.183-.013-.239-.182-.406a.532.532 0 0 1-.159-.362v-.361a.244.244 0 0 0-.181-.226a6.941 6.941 0 0 0-1.66-.18c-.817 0-1.385.112-1.658.18a.22.22 0 0 0-.181.226v.361a.448.448 0 0 1-.16.362l-.068.068c-.09.067-.136.203-.136.316c.023.248.045.61.045.61h-.02a.268.268 0 0 1-.252-.226l-.25-1.288a.865.865 0 0 1 .454-.88l.182-.091c.114-.068.227-.158.34-.249l.41-.43a.83.83 0 0 1 .931-.135c.228.068.478.068.705 0c.34-.113.727-.022 1 .226l.34.34c.091.112.205.18.341.248Z");
}

.w5m8_ub1v {
  d: path("M22.765 7.442a.378.378 0 0 1 .364.477h-.73a.38.38 0 0 1 .366-.478Z");
}

.w6mxzsbgv {
  stop-color: var(--svg-color--9d766b, #9D766B);
}

.wdihg828b {
  cx: 6.808px;
  cy: 7.933px;
  r: 0.421px;
}

.wg8zzjbli {
  stop-color: var(--svg-color--32272d, #32272D);
  stop-opacity: 0;
}

.wgn2-qn3r {
  stop-color: var(--svg-color--84615a, #84615A);
}

.whtk90yvk {
  fill: var(--svg-color--27151c, #27151C);
  d: path("m23.882 5.189l.182.09c.318.158.5.52.432.904l-.25 1.287c-.022.133-.11.223-.242.226h-.008s.023-.384.045-.61c.019-.183-.013-.239-.181-.406a.532.532 0 0 1-.16-.362v-.361a.244.244 0 0 0-.181-.226a6.941 6.941 0 0 0-1.659-.18c-.818 0-1.386.112-1.659.18a.22.22 0 0 0-.181.226v.361a.448.448 0 0 1-.16.362l-.067.068c-.091.067-.137.203-.137.316c.023.248.046.61.046.61h-.021a.268.268 0 0 1-.252-.226l-.25-1.288a.865.865 0 0 1 .455-.88l.181-.091c.114-.068.227-.158.341-.249l.409-.43a.83.83 0 0 1 .932-.135c.227.068.477.068.704 0c.34-.113.727-.022 1 .226l.34.34c.091.112.205.18.341.248Z");
}

.whxihzpaf {
  stop-color: var(--svg-color--5f3e52, #5F3E52);
}

.ww-jf4byh {
  d: path("m10.498 5.55l-1.304.435a.444.444 0 0 0 .2.86l1.296-.173l-.192-1.122Z");
}

.wz6aoebid {
  cx: 23.86px;
  cy: 7.933px;
  r: 0.421px;
  fill: var(--svg-color--7a5654, #7A5654);
}

.x4y51kb4t {
  stop-color: var(--svg-color--906665, #906665);
}

.x69xtn6lh {
  d: path("m12.515 13.39l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.505l3.202 1.809l-.814 1.37Z");
}

.xea0dxb7g {
  d: path("m5.927 20.239l2.997.27l-1.064 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.121-.122V20.24Z");
}

.xh6agdcni {
  stop-color: var(--svg-color--59323c, #59323C);
}

.xueoo_b7t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.311 6.939c.139-.123.442-.252.817-.192");
}

.xwcmpmiep {
  d: path("M23.101 7.77a.356.356 0 0 0-.098-.196l-.11.12l.05.097l.158-.021Z");
}

.y_z4ite8v {
  stop-color: var(--svg-color--7c4559, #7C4559);
  stop-opacity: 0;
}

.y2o07bc4o {
  stop-color: var(--svg-color--5d302d, #5D302D);
}

.y686fkbfk {
  fill: var(--svg-color--000, #000);
  d: path("M8.11 7.82a.216.216 0 0 0-.217-.217a.216.216 0 0 0-.192.316h.383a.215.215 0 0 0 .025-.1Z");
}

.y6cuvac1l {
  d: path("M6.659 7.673h.02s-.022-.36-.045-.61c0-.112.045-.248.136-.315l.069-.068a.448.448 0 0 0 .159-.362v-.361a.22.22 0 0 1 .181-.226a6.94 6.94 0 0 1 1.659-.18c.818 0 1.386.112 1.659.18c.09.022.181.113.181.226v.361c0 .136.069.271.16.362c.212.149.199.23.181.406c-.022.226-.045.61-.045.61h.008l-.113 1.677c-.068.75-.657 1.272-1.36 1.272h-1.36c-.725 0-1.292-.522-1.36-1.272l-.13-1.7Z");
}

.y91wuhb_y {
  stop-color: var(--svg-color--966d5f, #966D5F);
}

.ya-pfekwl {
  stop-color: var(--svg-color--7b575a, #7B575A);
}

.ylom6naui {
  stop-color: var(--svg-color--9d766b, #9D766B);
  stop-opacity: 0;
}

.yo62mdbsz {
  d: path("M11.06 5.75c.018.097-.102.145-.168.071c-.453-.513-1.132-1.01-2.022-1.01c-.839 0-1.554.532-2.033 1.063c-.065.072-.182.026-.166-.07a2.231 2.231 0 0 1 4.388-.053Z");
}

.ywtlfpbwi {
  fill: var(--svg-color--352827, #352827);
  d: path("M20.242 6.78h.002l.002-.002l.005-.004a.704.704 0 0 1 .066-.046a1.14 1.14 0 0 1 .177-.09a1.2 1.2 0 0 1 .633-.066a.226.226 0 0 1-.07.446a.748.748 0 0 0-.5.093a.396.396 0 0 0-.024.016l-.003.002a.226.226 0 0 1-.288-.349Z");
}

.ywu0pr7ii {
  stop-color: var(--svg-color--7c524c, #7C524C);
}

.z_g0j449a {
  stop-color: var(--svg-color--6f414d, #6F414D);
}

.z3o7w4-ew {
  stop-color: var(--svg-color--96776b, #96776B);
}

.zk3m83b4g {
  stop-color: var(--svg-color--453938, #453938);
}

.zoz3lmrqj {
  stop-color: var(--svg-color--453457, #453457);
}

</style>
