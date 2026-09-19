<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#svgIDa)"><path fill="url(#svgIDb)" class="illwuijpb"/><path fill="url(#svgIDc)" class="illwuijpb"/></g><g filter="url(#svgIDd)"><path fill="url(#svgIDe)" class="qvr533bky"/></g><g filter="url(#svgIDf)"><path class="bv1nxdbzt"/></g><path fill="url(#svgIDg)" class="pwy6vijbg"/><path fill="url(#svgIDh)" class="pwy6vijbg"/><path fill="url(#svgIDi)" class="c6yk-db4t"/><path fill="url(#svgIDj)" class="c6yk-db4t"/><circle fill="url(#svgIDk)" class="a31e5bbcm"/><g filter="url(#svgIDl)"><path clip-rule="evenodd" class="ptt69tewf"/></g><circle fill="url(#svgIDm)" transform="matrix(-1 0 0 1 12.14 16.734)" class="kr_eiac3t"/><g filter="url(#svgIDn)"><path clip-rule="evenodd" class="jy_02gl6p"/></g><path fill="url(#svgIDo)" class="pzx6ybcwl"/><path fill="url(#svgIDp)" class="pzx6ybcwl"/><g filter="url(#svgIDq)"><path class="va8879bri"/></g><path class="b_3cxzxav"/><path fill="url(#svgIDr)" class="c436txzks"/><g filter="url(#svgIDs)"><path class="xl-haubxn"/></g><path fill="url(#svgIDt)" class="l2oc9lblk"/><path fill="url(#svgIDu)" class="l2oc9lblk"/><path fill="url(#svgIDv)" class="l2oc9lblk"/><path fill="url(#svgIDw)" class="l2oc9lblk"/><path fill="url(#svgIDx)" class="l2oc9lblk"/><path fill="url(#svgIDy)" class="h0qg2efcl"/><g filter="url(#svgIDz)"><path class="kivjlybrc"/></g><g filter="url(#svgIDA)"><circle fill="url(#svgIDB)" class="z_xanemog"/></g><g filter="url(#svgIDC)"><circle fill="url(#svgIDD)" class="orwbiqbjn"/></g><g filter="url(#svgIDE)"><circle fill="url(#svgIDF)" class="toalqabes"/><circle fill="url(#svgIDG)" class="toalqabes"/></g><g filter="url(#svgIDH)"><circle class="a45ekswwx"/><circle fill="url(#svgIDI)" class="o4ba0lb3g"/><circle fill="url(#svgIDJ)" class="o4ba0lb3g"/></g><g filter="url(#svgIDK)"><path fill="url(#svgIDL)" class="szlhq7bky"/><path fill="url(#svgIDM)" class="szlhq7bky"/><path fill="url(#svgIDN)" class="szlhq7bky"/><path fill="url(#svgIDO)" class="szlhq7bky"/><path fill="url(#svgIDP)" class="szlhq7bky"/><path fill="url(#svgIDQ)" class="szlhq7bky"/></g><g filter="url(#svgIDR)"><path fill="url(#svgIDS)" class="kce6eo76s"/></g><g filter="url(#svgIDT)"><path class="sf9xar_rm"/><path fill="url(#svgIDU)" class="xnlhc5b9k"/><path fill="url(#svgIDV)" class="xnlhc5b9k"/><path fill="url(#svgIDW)" class="xnlhc5b9k"/><path fill="url(#svgIDX)" class="xnlhc5b9k"/></g><g filter="url(#svgIDY)"><path class="ju60xvb_w"/></g><g filter="url(#svgIDZ)"><path class="y-jrw0bve"/><path fill="url(#svgIDaa)" class="hf6ya-78y"/><path fill="url(#svgIDab)" class="hf6ya-78y"/><path fill="url(#svgIDac)" class="hf6ya-78y"/><path fill="url(#svgIDad)" class="hf6ya-78y"/></g><path class="ddi51x23l"/><g filter="url(#svgIDae)"><path class="oz57i7b8n"/></g><g filter="url(#svgIDaf)"><path class="dddkg9bco"/></g><path class="twmi8xbgq"/><path fill="url(#svgIDag)" class="ga_g0mbtv"/><path class="vf96q7bmi"/><g filter="url(#svgIDah)"><path class="a7p2cwbsk"/><path fill="url(#svgIDai)" class="r3zsrtbkv"/></g><g filter="url(#svgIDaj)"><path fill="url(#svgIDak)" class="jg0ys8bve"/></g><path class="j_-bt5bql"/><path fill="url(#svgIDal)" class="emmdm4tab"/><path class="gaiz25zts"/><g filter="url(#svgIDam)"><path fill="url(#svgIDan)" class="gqetaabex"/></g><g filter="url(#svgIDao)" transform="rotate(-27.914 7.787 7.489)"><ellipse class="lb24jvbmc"/><ellipse fill="url(#svgIDap)" class="paegc_b1d"/></g><g filter="url(#svgIDaq)"><path stroke="url(#svgIDar)" class="ktwvf2juy"/></g><g filter="url(#svgIDas)"><path stroke="url(#svgIDat)" class="yi3aunbmr"/></g><g filter="url(#svgIDau)"><path stroke="url(#svgIDav)" class="ybvc-8bjc"/></g><g filter="url(#svgIDaw)"><path class="ma4xxac9i"/></g><g filter="url(#svgIDax)"><path class="u-ra5zb4n"/></g><g filter="url(#svgIDay)"><path fill="url(#svgIDaz)" class="jjhk_ub7b"/></g><g filter="url(#svgIDaA)"><path fill="url(#svgIDaB)" class="ys5rm3ubl"/><path fill="url(#svgIDaC)" class="ys5rm3ubl"/></g><g filter="url(#svgIDaD)"><path fill="url(#svgIDaE)" class="p7-gc9bxa"/></g><g filter="url(#svgIDaF)"><path class="su6zcqbzj"/></g><path fill="url(#svgIDaG)" class="z4ybrvo8l"/><path fill="url(#svgIDaH)" class="z4ybrvo8l"/><path fill="url(#svgIDaI)" class="g86ebhm-i"/><path fill="url(#svgIDaJ)" class="g86ebhm-i"/><circle fill="url(#svgIDaK)" class="chzdakbfj"/><g filter="url(#svgIDaL)"><path clip-rule="evenodd" class="e5rbzbc9h"/></g><circle fill="url(#svgIDaM)" transform="matrix(-1 0 0 1 25.185 16.744)" class="kr_eiac3t"/><g filter="url(#svgIDaN)"><path clip-rule="evenodd" class="mmbdc7bdg"/></g><path fill="url(#svgIDaO)" class="iaojdrboj"/><path fill="url(#svgIDaP)" class="iaojdrboj"/><g filter="url(#svgIDaQ)"><path class="yvh--yb5o"/></g><path class="oxrspmbko"/><path fill="url(#svgIDaR)" class="ec5o9fi_k"/><g filter="url(#svgIDaS)"><path class="yriep8b8t"/></g><path fill="url(#svgIDaT)" class="gejqw6b6o"/><path fill="url(#svgIDaU)" class="gejqw6b6o"/><path fill="url(#svgIDaV)" class="gejqw6b6o"/><path fill="url(#svgIDaW)" class="gejqw6b6o"/><path fill="url(#svgIDaX)" class="gejqw6b6o"/><path fill="url(#svgIDaY)" class="w9k9d9dcq"/><g filter="url(#svgIDaZ)"><path class="y1yyvab7v"/></g><g filter="url(#svgIDba)"><circle fill="url(#svgIDbb)" class="yk-93wl_k"/></g><g filter="url(#svgIDbc)"><circle fill="url(#svgIDbd)" class="ze_b5eb-w"/></g><g filter="url(#svgIDbe)"><circle fill="url(#svgIDbf)" class="krimkgb2b"/><circle fill="url(#svgIDbg)" class="krimkgb2b"/></g><g filter="url(#svgIDbh)"><circle class="a24dx2blu"/><circle fill="url(#svgIDbi)" class="zaq85lb5o"/><circle fill="url(#svgIDbj)" class="zaq85lb5o"/></g><g filter="url(#svgIDbk)"><path fill="url(#svgIDbl)" class="rflev1o0y"/><path fill="url(#svgIDbm)" class="rflev1o0y"/><path fill="url(#svgIDbn)" class="rflev1o0y"/><path fill="url(#svgIDbo)" class="rflev1o0y"/><path fill="url(#svgIDbp)" class="rflev1o0y"/><path fill="url(#svgIDbq)" class="rflev1o0y"/></g><g filter="url(#svgIDbr)"><path fill="url(#svgIDbs)" class="gsvpturxo"/></g><g filter="url(#svgIDbt)"><path class="dmgj2ab3m"/><path fill="url(#svgIDbu)" class="cg8d3hbra"/><path fill="url(#svgIDbv)" class="cg8d3hbra"/><path fill="url(#svgIDbw)" class="cg8d3hbra"/><path fill="url(#svgIDbx)" class="cg8d3hbra"/></g><g filter="url(#svgIDby)"><path class="pkeuj4blr"/></g><g filter="url(#svgIDbz)"><path class="d2ocy-wbg"/><path fill="url(#svgIDbA)" class="pqm31jbvw"/><path fill="url(#svgIDbB)" class="pqm31jbvw"/><path fill="url(#svgIDbC)" class="pqm31jbvw"/><path fill="url(#svgIDbD)" class="pqm31jbvw"/></g><path class="k7gu39gbr"/><g filter="url(#svgIDbE)"><path class="mq51c-mtw"/></g><g filter="url(#svgIDbF)"><path class="d6frd9j_o"/></g><path class="zcu_1v8no"/><path fill="url(#svgIDbG)" class="n5-yy2b4d"/><path class="jpy6mubxx"/><g filter="url(#svgIDbH)"><path class="royd6tbgi"/><path fill="url(#svgIDbI)" class="x0dkyshlp"/></g><g filter="url(#svgIDbJ)"><path fill="url(#svgIDbK)" class="njika_bez"/></g><path class="a9_e-eb8f"/><path fill="url(#svgIDbL)" class="v9qmesogf"/><path class="ljlsb5bcz"/><g filter="url(#svgIDbM)"><path fill="url(#svgIDbN)" class="b0ifysqff"/></g><g filter="url(#svgIDbO)" transform="rotate(-27.914 20.832 7.499)"><ellipse class="r9fi4lm9m"/><ellipse fill="url(#svgIDbP)" class="vwv_1xbpr"/></g><g filter="url(#svgIDbQ)"><path stroke="url(#svgIDbR)" class="xwtxp-byo"/></g><g filter="url(#svgIDbS)"><path stroke="url(#svgIDbT)" class="mrnjlr-cv"/></g><g filter="url(#svgIDbU)"><path stroke="url(#svgIDbV)" class="qpup5zbhe"/></g><g filter="url(#svgIDbW)"><path class="rjudgtb2f"/></g><g filter="url(#svgIDbX)"><path class="vudhj94wy"/></g><g filter="url(#svgIDbY)"><path fill="url(#svgIDbZ)" class="i3o02bcmw"/></g><defs><filter id="svgIDa" width="3.097" height="9.794" x="5.815" y="20.234" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.709804 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDd" width="6.578" height="10.091" x="10.026" y="19.937" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.584314 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDf" width="5.976" height="10.579" x="10.496" y="18.857" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".5"/></filter><filter id="svgIDl" width="5.896" height="7.109" x="2.601" y="10.151" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.603922 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.564706 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDn" width="5.996" height="7.109" x="9.267" y="10.151" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.596078 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.54902 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDq" width="2.703" height="2.68" x="12.199" y="11.779" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".2"/></filter><filter id="svgIDs" width="9.692" height="11.056" x="4.665" y="9.937" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDz" width="2.793" height="3.034" x="3.321" y="13.387" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".2"/></filter><filter id="svgIDA" width="1.641" height="1.441" x="6.077" y="7.104" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDC" width="1.859" height="1.859" x="5.868" y="6.895" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".25"/></filter><filter id="svgIDE" width="1.691" height="1.691" x="10.184" y="6.854" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDH" width="1.859" height="1.859" x="9.975" y="6.895" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".25"/></filter><filter id="svgIDK" width="4.478" height="5.442" x="6.621" y="5.396" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDR" width="3.833" height="3.324" x="7.921" y="4.396" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".5"/></filter><filter id="svgIDT" width="5.44" height="3.622" x="6.127" y="3.961" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDY" width="2.26" height="2.657" x="7.614" y="6.9" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".375"/></filter><filter id="svgIDZ" width=".91" height="1.257" x="8.392" y="7.529" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".025"/></filter><filter id="svgIDae" width="1.428" height="1.036" x="9.357" y="6.022" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDaf" width="1.428" height="1.036" x="7.135" y="6.022" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDah" width=".453" height=".414" x="9.414" y="7.283" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".05"/></filter><filter id="svgIDaj" width=".612" height=".622" x="9.72" y="7.259" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".1"/></filter><filter id="svgIDam" width=".653" height=".676" x="7.802" y="7.231" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".1"/></filter><filter id="svgIDao" width=".508" height=".418" x="7.533" y="7.28" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".05"/></filter><filter id="svgIDaq" width="1.148" height=".536" x="9.389" y="6.398" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".05"/></filter><filter id="svgIDas" width="1.182" height=".561" x="7.136" y="6.426" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".05"/></filter><filter id="svgIDau" width=".861" height="1.406" x="6.404" y="5.372" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".125"/></filter><filter id="svgIDaw" width="1.73" height="2.911" x="6.683" y="1.762" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDax" width="1.73" height="2.911" x="9.394" y="1.762" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDay" width="4.792" height="2.36" x="6.658" y="3.744" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDaA" width="3.097" height="9.794" x="18.86" y="20.244" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.905882 0 0 0 0 0.709804 0 0 0 0 0.643137 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDaD" width="6.578" height="10.091" x="23.071" y="19.947" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.584314 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDaF" width="5.976" height="10.579" x="23.541" y="18.867" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".5"/></filter><filter id="svgIDaL" width="5.896" height="7.109" x="15.646" y="10.161" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.603922 0 0 0 0 0.521569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.564706 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDaN" width="5.996" height="7.109" x="22.312" y="10.161" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.596078 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.803922 0 0 0 0 0.54902 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDaQ" width="2.703" height="2.68" x="25.244" y="11.79" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".2"/></filter><filter id="svgIDaS" width="9.692" height="11.056" x="17.71" y="9.948" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.192157 0 0 0 0 0.137255 0 0 0 0 0.25098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1.25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.384314 0 0 0 0 0.501961 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDaZ" width="2.793" height="3.034" x="16.366" y="13.397" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".2"/></filter><filter id="svgIDba" width="1.641" height="1.441" x="19.122" y="7.114" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.694118 0 0 0 0 0.607843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDbc" width="1.859" height="1.859" x="18.913" y="6.905" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".25"/></filter><filter id="svgIDbe" width="1.691" height="1.691" x="23.229" y="6.864" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.843137 0 0 0 0 0.623529 0 0 0 0 0.580392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDbh" width="1.859" height="1.859" x="23.02" y="6.905" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".25"/></filter><filter id="svgIDbk" width="4.478" height="5.442" x="19.666" y="5.407" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDbr" width="3.833" height="3.324" x="20.966" y="4.407" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".5"/></filter><filter id="svgIDbt" width="5.44" height="3.622" x="19.172" y="3.971" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.15"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0392157 0 0 0 0 0.00784314 0 0 0 0 0.0196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDby" width="2.26" height="2.657" x="20.659" y="6.91" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".375"/></filter><filter id="svgIDbz" width=".91" height="1.257" x="21.437" y="7.539" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".025"/></filter><filter id="svgIDbE" width="1.428" height="1.036" x="22.403" y="6.032" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDbF" width="1.428" height="1.036" x="20.18" y="6.032" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0431373 0 0 0 0 0.0196078 0 0 0 0 0.027451 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/></filter><filter id="svgIDbH" width=".453" height=".414" x="22.459" y="7.293" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".05"/></filter><filter id="svgIDbJ" width=".612" height=".622" x="22.765" y="7.269" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".1"/></filter><filter id="svgIDbM" width=".653" height=".676" x="20.847" y="7.242" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".1"/></filter><filter id="svgIDbO" width=".508" height=".418" x="20.578" y="7.29" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".05"/></filter><filter id="svgIDbQ" width="1.148" height=".536" x="22.434" y="6.409" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".05"/></filter><filter id="svgIDbS" width="1.182" height=".561" x="20.181" y="6.436" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".05"/></filter><filter id="svgIDbU" width=".861" height="1.406" x="19.449" y="5.383" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_4002_720" stdDeviation=".125"/></filter><filter id="svgIDbW" width="1.73" height="2.911" x="19.728" y="1.772" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDbX" width="1.73" height="2.911" x="22.439" y="1.772" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.439216 0 0 0 0 0.380392 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><filter id="svgIDbY" width="4.792" height="2.36" x="19.703" y="3.754" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.188235 0 0 0 0 0.109804 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_4002_720"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy=".2"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.223529 0 0 0 0 0.184314 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_4002_720" result="effect2_innerShadow_4002_720"/></filter><radialGradient id="svgIDg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 7.541 28.109)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDh" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -26.58 21.051) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDi" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 16.203 29.859)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDj" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 15.494 28.406)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDm" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="pwv_6m0ax"/><stop offset="1" class="ndirioote"/></radialGradient><radialGradient id="svgIDt" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 9.51 21.843)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDv" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 11.969 7.275) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDw" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 3.763 7.835) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDx" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 16.495 5.687) scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDy" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 8.334 10.265)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ktrjcib4u"/><stop offset="1" class="ghyxkccjw"/></radialGradient><radialGradient id="svgIDB" cx="0" cy="0" r="1" gradientTransform="matrix(.75756 0 0 1.32574 6.077 7.824)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="svgIDG" cx="0" cy="0" r="1" gradientTransform="matrix(.35688 -.25986 .2966 .40733 11.065 7.71)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="svgIDI" cx="0" cy="0" r="1" gradientTransform="matrix(.35453 -.65208 .38167 .2075 10.886 8.179)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="svgIDJ" cx="0" cy="0" r="1" gradientTransform="matrix(.11193 .1108 -.14283 .1443 10.904 7.824)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="svgIDM" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.07313 -5.52906 0 8.86 6.993)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="svgIDP" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56426 .69447 0 9.86 7.275)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="svgIDQ" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60043 .74668 0 7.892 7.26)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="svgIDU" cx="0" cy="0" r="1" gradientTransform="matrix(.3444 -1.27635 .47331 .12772 10.723 6.052)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="svgIDV" cx="0" cy="0" r="1" gradientTransform="matrix(1.65115 .15195 -.0817 .88781 10.014 5.292)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="svgIDW" cx="0" cy="0" r="1" gradientTransform="matrix(0 .72489 -1.12264 0 8.847 4.111)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="svgIDX" cx="0" cy="0" r="1" gradientTransform="matrix(1.327 -.97246 1.52352 2.07897 6.063 7.055)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="svgIDad" cx="0" cy="0" r="1" gradientTransform="matrix(0 .085 -.27309 0 8.988 8.518)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="svgIDag" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35016 -.55697 0 9.788 7.53)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDai" cx="0" cy="0" r="1" gradientTransform="matrix(-.1001 -.12898 .17758 -.1378 9.69 7.566)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDal" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35018 -.557 0 7.904 7.53)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDap" cx="0" cy="0" r="1" gradientTransform="matrix(-.00334 -.21324 .25633 -.00401 7.78 7.624)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDaG" cx="0" cy="0" r="1" gradientTransform="matrix(-1.04689 2.23436 -1.0009 -.46896 20.586 28.119)" gradientUnits="userSpaceOnUse"><stop class="i7j8_4zgt"/><stop offset="1" class="g4nv9obue"/></radialGradient><radialGradient id="svgIDaH" cx="0" cy="0" r="1" gradientTransform="rotate(51.34 -20.067 34.628) scale(1.30063 3.1796)" gradientUnits="userSpaceOnUse"><stop offset=".522" class="enwi01lgk"/><stop offset="1" class="mta_69bbu"/></radialGradient><radialGradient id="svgIDaI" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3576 -2.25 .95212 -.57449 29.249 29.869)" gradientUnits="userSpaceOnUse"><stop class="kuw77jfnz"/><stop offset="1" class="boon_rjzq"/></radialGradient><radialGradient id="svgIDaJ" cx="0" cy="0" r="1" gradientTransform="matrix(-.81249 1.26563 -2.71996 -1.74612 28.54 28.416)" gradientUnits="userSpaceOnUse"><stop offset=".737" class="hi3bu5i6r"/><stop offset="1" class="atfd_nb4o"/></radialGradient><radialGradient id="svgIDaM" cx="0" cy="0" r="1" gradientTransform="rotate(38.794 -1.108 .325) scale(1.30308)" gradientUnits="userSpaceOnUse"><stop class="pwv_6m0ax"/><stop offset="1" class="ndirioote"/></radialGradient><radialGradient id="svgIDaT" cx="0" cy="0" r="1" gradientTransform="matrix(-.36017 -5.09375 2.6333 -.1862 22.556 21.853)" gradientUnits="userSpaceOnUse"><stop offset=".189" class="jdxsh3blt"/><stop offset="1" class="drixk4bdm"/></radialGradient><radialGradient id="svgIDaV" cx="0" cy="0" r="1" gradientTransform="rotate(-114.905 18.494 3.118) scale(2.97425 .93316)" gradientUnits="userSpaceOnUse"><stop offset=".36" class="eox5rpbuq"/><stop offset="1" class="g1mnylbkn"/></radialGradient><radialGradient id="svgIDaW" cx="0" cy="0" r="1" gradientTransform="rotate(140.681 10.283 10.17) scale(3.2691 3.07426)" gradientUnits="userSpaceOnUse"><stop class="k0aq2sbpu"/><stop offset="1" class="a3709fbcn"/></radialGradient><radialGradient id="svgIDaX" cx="0" cy="0" r="1" gradientTransform="rotate(-80.342 23.024 -2.035) scale(2.72794 1.1406)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="vobictbgt"/><stop offset="1" class="f97z0ccja"/></radialGradient><radialGradient id="svgIDaY" cx="0" cy="0" r="1" gradientTransform="matrix(.39369 1.63031 -2.125 .51315 21.38 10.275)" gradientUnits="userSpaceOnUse"><stop offset=".218" class="ktrjcib4u"/><stop offset="1" class="ghyxkccjw"/></radialGradient><radialGradient id="svgIDbb" cx="0" cy="0" r="1" gradientTransform="matrix(.75756 0 0 1.32574 19.122 7.835)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="crp6d4bqv"/><stop offset="1" class="lu78seb9e"/></radialGradient><radialGradient id="svgIDbg" cx="0" cy="0" r="1" gradientTransform="matrix(.35688 -.25986 .2966 .40733 24.11 7.72)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="wdqn7tq-u"/><stop offset="1" class="r3t82tbzk"/></radialGradient><radialGradient id="svgIDbi" cx="0" cy="0" r="1" gradientTransform="matrix(.35453 -.65208 .38167 .2075 23.932 8.19)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="n7c5lw_4k"/><stop offset=".916" class="bw8j_5egh"/></radialGradient><radialGradient id="svgIDbj" cx="0" cy="0" r="1" gradientTransform="matrix(.11193 .1108 -.14283 .1443 23.95 7.835)" gradientUnits="userSpaceOnUse"><stop class="fa9i5bbvu"/><stop offset="1" class="x8d9utbsu"/></radialGradient><radialGradient id="svgIDbm" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.07313 -5.52906 0 21.905 7.004)" gradientUnits="userSpaceOnUse"><stop offset=".557" class="p7jmmxb2h"/><stop offset="1" class="uzkpn5btf"/></radialGradient><radialGradient id="svgIDbp" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.56426 .69447 0 22.905 7.286)" gradientUnits="userSpaceOnUse"><stop class="m459pab_j"/><stop offset="1" class="rcuz4uefu"/></radialGradient><radialGradient id="svgIDbq" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.60043 .74668 0 20.938 7.271)" gradientUnits="userSpaceOnUse"><stop class="hplqxft1w"/><stop offset="1" class="ay1rn8bxh"/></radialGradient><radialGradient id="svgIDbu" cx="0" cy="0" r="1" gradientTransform="matrix(.3444 -1.27635 .47331 .12772 23.768 6.062)" gradientUnits="userSpaceOnUse"><stop class="ui2kgq2tt"/><stop offset="1" class="bumyo9b5s"/></radialGradient><radialGradient id="svgIDbv" cx="0" cy="0" r="1" gradientTransform="matrix(1.65115 .15195 -.0817 .88781 23.059 5.302)" gradientUnits="userSpaceOnUse"><stop offset=".335" class="d4d293bim"/><stop offset="1" class="yf9erdbmk"/></radialGradient><radialGradient id="svgIDbw" cx="0" cy="0" r="1" gradientTransform="matrix(0 .72489 -1.12264 0 21.892 4.121)" gradientUnits="userSpaceOnUse"><stop class="qc5tyzrav"/><stop offset="1" class="m_1e2qbpe"/></radialGradient><radialGradient id="svgIDbx" cx="0" cy="0" r="1" gradientTransform="matrix(1.327 -.97246 1.52352 2.07897 19.108 7.065)" gradientUnits="userSpaceOnUse"><stop class="gg1n47rtb"/><stop offset="1" class="uk24qccae"/></radialGradient><radialGradient id="svgIDbD" cx="0" cy="0" r="1" gradientTransform="matrix(0 .085 -.27309 0 22.034 8.528)" gradientUnits="userSpaceOnUse"><stop class="a7vfdrbiy"/><stop offset="1" class="x6mjr8bji"/></radialGradient><radialGradient id="svgIDbG" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35016 -.55697 0 22.833 7.54)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDbI" cx="0" cy="0" r="1" gradientTransform="matrix(-.1001 -.12898 .17758 -.1378 22.735 7.576)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="svgIDbL" cx="0" cy="0" r="1" gradientTransform="matrix(0 .35018 -.557 0 20.95 7.54)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="svgIDbP" cx="0" cy="0" r="1" gradientTransform="matrix(-.00334 -.21324 .25633 -.00401 20.826 7.635)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="svgIDb" x1="5.915" x2="7.815" y1="24.124" y2="24.274" gradientUnits="userSpaceOnUse"><stop class="rw6zcv7ej"/><stop offset="1" class="k-0qdfh_d"/></linearGradient><linearGradient id="svgIDc" x1="5.807" x2="6.354" y1="24.812" y2="24.812" gradientUnits="userSpaceOnUse"><stop class="bx7xnhbtf"/><stop offset="1" class="psdxqmvzz"/></linearGradient><linearGradient id="svgIDe" x1="12.128" x2="14.315" y1="24.149" y2="23.305" gradientUnits="userSpaceOnUse"><stop class="kl81nmxpg"/><stop offset="1" class="k8t65cc0e"/></linearGradient><linearGradient id="svgIDk" x1="4.972" x2="5.831" y1="16.706" y2="17.37" gradientUnits="userSpaceOnUse"><stop class="lw10mib7m"/><stop offset="1" class="c3j04svyu"/></linearGradient><linearGradient id="svgIDo" x1="5.338" x2="6.26" y1="11.453" y2="13.384" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDp" x1="5.854" x2="5.494" y1="13.171" y2="12.546" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDr" x1="12.088" x2="12.526" y1="13.171" y2="12.078" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDu" x1="5.729" x2="6.401" y1="19.249" y2="19.234" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDD" x1="6.798" x2="6.521" y1="7.944" y2="7.944" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="svgIDF" x1="11.373" x2="11.02" y1="7.353" y2="8.448" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="svgIDL" x1="10.59" x2="7.293" y1="7.992" y2="8.484" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="svgIDN" x1="6.411" x2="7.861" y1="8.652" y2="8.701" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="svgIDO" x1="6.518" x2="7.33" y1="9.156" y2="9.127" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="svgIDS" x1="8.618" x2="12.134" y1="6.704" y2="5.445" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="svgIDaa" x1="8.474" x2="8.879" y1="8.277" y2="8.277" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="svgIDab" x1="9.252" x2="8.81" y1="8.416" y2="8.41" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="svgIDac" x1="8.931" x2="8.931" y1="8.737" y2="8.489" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="svgIDak" x1="10.124" x2="9.988" y1="7.553" y2="7.636" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDan" x1="8.226" x2="8.09" y1="7.553" y2="7.636" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDar" x1="10.13" x2="9.949" y1="6.629" y2="6.259" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="svgIDat" x1="7.84" x2="7.327" y1="6.574" y2="6.359" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="svgIDav" x1="6.835" x2="6.835" y1="5.705" y2="6.636" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="svgIDaz" x1="10.697" x2="7.197" y1="5.203" y2="5.39" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient><linearGradient id="svgIDaB" x1="18.96" x2="20.861" y1="24.135" y2="24.284" gradientUnits="userSpaceOnUse"><stop class="rw6zcv7ej"/><stop offset="1" class="k-0qdfh_d"/></linearGradient><linearGradient id="svgIDaC" x1="18.852" x2="19.399" y1="24.822" y2="24.822" gradientUnits="userSpaceOnUse"><stop class="bx7xnhbtf"/><stop offset="1" class="psdxqmvzz"/></linearGradient><linearGradient id="svgIDaE" x1="25.173" x2="27.361" y1="24.159" y2="23.315" gradientUnits="userSpaceOnUse"><stop class="kl81nmxpg"/><stop offset="1" class="k8t65cc0e"/></linearGradient><linearGradient id="svgIDaK" x1="18.017" x2="18.876" y1="16.716" y2="17.381" gradientUnits="userSpaceOnUse"><stop class="lw10mib7m"/><stop offset="1" class="c3j04svyu"/></linearGradient><linearGradient id="svgIDaO" x1="18.383" x2="19.305" y1="11.463" y2="13.395" gradientUnits="userSpaceOnUse"><stop class="jum30v1nu"/><stop offset=".527" class="zoz3lmrqj"/></linearGradient><linearGradient id="svgIDaP" x1="18.899" x2="18.539" y1="13.182" y2="12.557" gradientUnits="userSpaceOnUse"><stop class="b1pd8upnt"/><stop offset="1" class="n366y7b2s"/></linearGradient><linearGradient id="svgIDaR" x1="25.133" x2="25.571" y1="13.181" y2="12.088" gradientUnits="userSpaceOnUse"><stop class="bqhl8ltyr"/><stop offset="1" class="qhg47wyku"/></linearGradient><linearGradient id="svgIDaU" x1="18.774" x2="19.446" y1="19.26" y2="19.244" gradientUnits="userSpaceOnUse"><stop offset=".262" class="mlh1k8r8i"/><stop offset="1" class="tigrkbwnp"/></linearGradient><linearGradient id="svgIDbd" x1="19.843" x2="19.566" y1="7.955" y2="7.955" gradientUnits="userSpaceOnUse"><stop class="wachewblq"/><stop offset="1" class="px4pa2bzd"/></linearGradient><linearGradient id="svgIDbf" x1="24.419" x2="24.065" y1="7.363" y2="8.458" gradientUnits="userSpaceOnUse"><stop class="fuy988_rs"/><stop offset="1" class="h2u-65bda"/></linearGradient><linearGradient id="svgIDbl" x1="23.635" x2="20.338" y1="8.003" y2="8.494" gradientUnits="userSpaceOnUse"><stop class="z8y6fgvmn"/><stop offset="1" class="tqgh1edwg"/></linearGradient><linearGradient id="svgIDbn" x1="19.457" x2="20.906" y1="8.662" y2="8.711" gradientUnits="userSpaceOnUse"><stop class="z3n_1mwef"/><stop offset="1" class="rvf3-0bfj"/></linearGradient><linearGradient id="svgIDbo" x1="19.563" x2="20.375" y1="9.167" y2="9.138" gradientUnits="userSpaceOnUse"><stop class="hmo3unbrx"/><stop offset="1" class="yyvs3obha"/></linearGradient><linearGradient id="svgIDbs" x1="21.663" x2="25.178" y1="6.714" y2="5.456" gradientUnits="userSpaceOnUse"><stop class="sbbw_6vcc"/><stop offset="1" class="b7cutjkii"/></linearGradient><linearGradient id="svgIDbA" x1="21.519" x2="21.924" y1="8.287" y2="8.287" gradientUnits="userSpaceOnUse"><stop class="h7h6nwjtb"/><stop offset="1" class="btip4dbzo"/></linearGradient><linearGradient id="svgIDbB" x1="22.297" x2="21.855" y1="8.426" y2="8.42" gradientUnits="userSpaceOnUse"><stop class="ag4c77bht"/><stop offset="1" class="qb120pbsb"/></linearGradient><linearGradient id="svgIDbC" x1="21.976" x2="21.976" y1="8.747" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="rlzetx3ey"/><stop offset="1" class="zf2atv-8x"/></linearGradient><linearGradient id="svgIDbK" x1="23.169" x2="23.033" y1="7.563" y2="7.647" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbN" x1="21.27" x2="21.135" y1="7.564" y2="7.647" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="svgIDbR" x1="23.175" x2="22.994" y1="6.64" y2="6.269" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="svgIDbT" x1="20.886" x2="20.372" y1="6.585" y2="6.369" gradientUnits="userSpaceOnUse"><stop class="wi8di0b_n"/><stop offset="1" class="zx1idre_k"/></linearGradient><linearGradient id="svgIDbV" x1="19.88" x2="19.88" y1="5.715" y2="6.646" gradientUnits="userSpaceOnUse"><stop class="nc1ak66ax"/><stop offset="1" class="vpvekld5v"/></linearGradient><linearGradient id="svgIDbZ" x1="23.743" x2="20.243" y1="5.213" y2="5.4" gradientUnits="userSpaceOnUse"><stop class="jj65vhdzq"/><stop offset="1" class="qgz62l2ld"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-with-bunny-ears-light" /></template>
<style>
.a24dx2blu {
  cx: 23.95px;
  cy: 7.835px;
  r: 0.43px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.a31e5bbcm {
  cx: 5.514px;
  cy: 16.605px;
  r: 0.766px;
}

.a3709fbcn {
  stop-color: var(--svg-color--6f597b, #6F597B);
  stop-opacity: 0;
}

.a45ekswwx {
  cx: 10.904px;
  cy: 7.824px;
  r: 0.43px;
  fill: var(--svg-color--e4af9a, #E4AF9A);
}

.a7p2cwbsk {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M9.76 7.405c.028.037-.03.082-.095.13c-.065.05-.113.084-.14.047c-.028-.037.002-.106.068-.155c.065-.049.14-.058.167-.022Z");
}

.a7vfdrbiy {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
}

.a9_e-eb8f {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.86 7.217a.603.603 0 0 0-.585.457a.118.118 0 0 0 .115.147h.963a.1.1 0 0 0 .098-.117a.605.605 0 0 0-.592-.487Z");
}

.ag4c77bht {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
}

.atfd_nb4o {
  stop-color: var(--svg-color--4c266b, #4C266B);
}

.ay1rn8bxh {
  stop-color: var(--svg-color--d0958d, #D0958D);
  stop-opacity: 0;
}

.b_3cxzxav {
  fill: var(--svg-color--605071, #605071);
  d: path("M12.504 13.384L9.676 11.8a.8.8 0 0 1-.307-1.089c.216-.385.36-.72.747-.504l3.202 1.809l-.814 1.37Z");
}

.b0ifysqff {
  d: path("M21.3 7.674c0-.124-.1-.207-.128-.232l-.125.12l.077.156l.176-.044Z");
}

.b1pd8upnt {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
}

.b7cutjkii {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
  stop-opacity: 0;
}

.boon_rjzq {
  stop-color: var(--svg-color--4c2d62, #4C2D62);
}

.bqhl8ltyr {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
}

.btip4dbzo {
  stop-color: var(--svg-color--dfa790, #DFA790);
  stop-opacity: 0;
}

.bumyo9b5s {
  stop-color: var(--svg-color--464344, #464344);
  stop-opacity: 0;
}

.bv1nxdbzt {
  fill: var(--svg-color--ffdac4, #FFDAC4);
  d: path("m11.496 20.16l.823-.303l3.153 8.579h-.758l-3.218-8.277Z");
}

.bw8j_5egh {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
}

.bx7xnhbtf {
  stop-color: var(--svg-color--edb29b, #EDB29B);
}

.c3j04svyu {
  stop-color: var(--svg-color--ad717c, #AD717C);
}

.c436txzks {
  d: path("M12.504 13.384L9.676 11.8a.8.8 0 0 1-.307-1.089c.216-.385.36-.72.747-.504l3.202 1.809l-.814 1.37Z");
}

.c6yk-db4t {
  d: path("M15.63 28.187h-2.142l.142.307a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.166-.234l-.563-1.607Z");
}

.cg8d3hbra {
  d: path("m23.973 5.038l.185.092c.324.161.51.53.44.921l-.255 1.313c-.023.135-.112.226-.247.23a.29.29 0 0 1-.008 0s.024-.392.047-.622c.018-.187-.014-.244-.186-.414a.542.542 0 0 1-.162-.369v-.368a.248.248 0 0 0-.185-.23a7.075 7.075 0 0 0-1.69-.184c-.834 0-1.413.115-1.69.184a.224.224 0 0 0-.186.23v.368a.457.457 0 0 1-.162.369l-.07.069c-.092.069-.138.207-.138.322c.023.253.046.622.046.622h-.021a.273.273 0 0 1-.257-.23l-.255-1.313a.881.881 0 0 1 .463-.898l.186-.092c.116-.069.231-.161.347-.253l.417-.438a.848.848 0 0 1 .95-.138c.23.07.486.07.717 0a1.041 1.041 0 0 1 1.019.23l.347.346a.967.967 0 0 0 .348.253Z");
}

.chzdakbfj {
  cx: 18.559px;
  cy: 16.615px;
  r: 0.766px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.crp6d4bqv {
  stop-color: var(--svg-color--cf9888, #CF9888);
}

.d2ocy-wbg {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m21.727 7.711l-.229.734a.233.233 0 0 0 .225.302h.34c.158 0 .27-.153.224-.302l-.23-.734c-.049-.162-.278-.162-.33 0Z");
}

.d4d293bim {
  stop-color: var(--svg-color--4a4648, #4A4648);
}

.d6frd9j_o {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M20.263 6.66h.001l.003-.002l.005-.004l.016-.012a1.116 1.116 0 0 1 .232-.126c.155-.061.376-.11.644-.068a.23.23 0 0 1-.072.455a.762.762 0 0 0-.509.095a.38.38 0 0 0-.023.015l-.004.003a.23.23 0 0 1-.293-.356Z");
}

.dddkg9bco {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m7.218 6.65l.002-.001l.002-.002l.005-.004a.592.592 0 0 1 .067-.046a1.223 1.223 0 0 1 .826-.16a.23.23 0 0 1-.073.456a.762.762 0 0 0-.509.094a.396.396 0 0 0-.023.016l-.004.003a.23.23 0 0 1-.293-.356Z");
}

.ddi51x23l {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M8.847 9.175a1.3 1.3 0 0 1-.598-.141c-.059-.03-.122.036-.085.09a.816.816 0 0 0 .683.365a.817.817 0 0 0 .684-.365c.037-.056-.027-.12-.086-.09a1.29 1.29 0 0 1-.598.141Z");
}

.dmgj2ab3m {
  fill: var(--svg-color--242324, #242324);
  d: path("m23.973 5.038l.185.092c.324.161.51.53.44.921l-.255 1.313c-.023.135-.112.226-.247.23a.29.29 0 0 1-.008 0s.024-.392.047-.622c.018-.187-.014-.244-.186-.414a.542.542 0 0 1-.162-.369v-.368a.248.248 0 0 0-.185-.23a7.075 7.075 0 0 0-1.69-.184c-.834 0-1.413.115-1.69.184a.224.224 0 0 0-.186.23v.368a.457.457 0 0 1-.162.369l-.07.069c-.092.069-.138.207-.138.322c.023.253.046.622.046.622h-.021a.273.273 0 0 1-.257-.23l-.255-1.313a.881.881 0 0 1 .463-.898l.186-.092c.116-.069.231-.161.347-.253l.417-.438a.848.848 0 0 1 .95-.138c.23.07.486.07.717 0a1.041 1.041 0 0 1 1.019.23l.347.346a.967.967 0 0 0 .348.253Z");
}

.drixk4bdm {
  stop-color: var(--svg-color--423153, #423153);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e5rbzbc9h {
  fill: var(--svg-color--e4b49e, #E4B49E);
  fill-rule: evenodd;
  d: path("M21.44 10.72a.8.8 0 0 1-.307 1.09l-3.527 1.977a.2.2 0 0 0-.034.325l1.9 1.763a.8.8 0 0 1-1.069 1.191l-1.973-1.72c-.93-.821-.855-2.149.348-2.918l3.574-2.015a.8.8 0 0 1 1.089.308Z");
}

.ec5o9fi_k {
  d: path("m25.549 13.395l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.504l3.202 1.808l-.814 1.37Z");
}

.emmdm4tab {
  d: path("M7.904 7.324a.385.385 0 0 0-.372.487h.744a.388.388 0 0 0-.373-.487Z");
}

.enwi01lgk {
  stop-color: var(--svg-color--522e71, #522E71);
  stop-opacity: 0;
}

.eox5rpbuq {
  stop-color: var(--svg-color--463049, #463049);
}

.f97z0ccja {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
  stop-opacity: 0;
}

.fa9i5bbvu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
}

.ft5dv1b6b {
  fill: none;
}

.fuy988_rs {
  stop-color: var(--svg-color--fbd3bd, #FBD3BD);
}

.g1mnylbkn {
  stop-color: var(--svg-color--463049, #463049);
  stop-opacity: 0;
}

.g4nv9obue {
  stop-color: var(--svg-color--44384d, #44384D);
}

.g86ebhm-i {
  d: path("M28.675 28.197h-2.142l.142.308a2.64 2.64 0 0 0 2.398 1.533c.12 0 .206-.12.166-.234l-.564-1.607Z");
}

.ga_g0mbtv {
  d: path("M9.789 7.324a.385.385 0 0 1 .37.487h-.743a.387.387 0 0 1 .373-.487Z");
}

.gaiz25zts {
  fill: var(--svg-color--000, #000);
  d: path("M8.124 7.709a.22.22 0 0 0-.22-.22a.22.22 0 0 0-.197.322h.39a.219.219 0 0 0 .027-.102Z");
}

.gejqw6b6o {
  d: path("M21.832 9.948a2.872 2.872 0 0 0-2.872 2.871v8.185h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.791 1.605h2.932l-1.33-3.705a2.002 2.002 0 0 1-.118-.676V12.82a2.872 2.872 0 0 0-2.872-2.871Z");
}

.gg1n47rtb {
  stop-color: var(--svg-color--463c39, #463C39);
}

.ghyxkccjw {
  stop-color: var(--svg-color--f7c2ae, #F7C2AE);
}

.gqetaabex {
  d: path("M8.255 7.664c0-.125-.1-.208-.128-.233l-.125.12l.077.157l.176-.044Z");
}

.gsvpturxo {
  d: path("m23.603 5.407l-1.328.443a.452.452 0 0 0 .203.876l1.32-.176l-.195-1.143Z");
}

.h0qg2efcl {
  d: path("m8.617 11.77l-.865-1.505h2.125l-.825 1.5a.25.25 0 0 1-.435.005Z");
}

.h2u-65bda {
  stop-color: var(--svg-color--f0b8a4, #F0B8A4);
}

.h7h6nwjtb {
  stop-color: var(--svg-color--dfa790, #DFA790);
}

.hf6ya-78y {
  d: path("m8.682 7.701l-.23.734a.233.233 0 0 0 .226.302h.339c.16 0 .271-.154.225-.302l-.23-.734c-.049-.162-.278-.162-.33 0Z");
}

.hi3bu5i6r {
  stop-color: var(--svg-color--4c266b, #4C266B);
  stop-opacity: 0;
}

.hmo3unbrx {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
}

.hplqxft1w {
  stop-color: var(--svg-color--d0958d, #D0958D);
}

.i3o02bcmw {
  d: path("M24.093 5.756c.019.097-.102.144-.167.07c-.453-.513-1.132-1.01-2.022-1.01c-.84 0-1.554.532-2.034 1.064c-.064.071-.182.025-.166-.07a2.231 2.231 0 0 1 4.389-.054Z");
}

.i7j8_4zgt {
  stop-color: var(--svg-color--59436a, #59436A);
}

.iaojdrboj {
  d: path("m18.305 13.395l2.828-1.585a.8.8 0 1 0-.781-1.397l-2.86 1.612l.813 1.37Z");
}

.illwuijpb {
  d: path("m5.915 20.234l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-9.672Z");
}

.j_-bt5bql {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.814 7.207a.603.603 0 0 0-.585.457a.118.118 0 0 0 .116.147h.963a.1.1 0 0 0 .098-.118a.605.605 0 0 0-.592-.486Z");
}

.jdxsh3blt {
  stop-color: var(--svg-color--221630, #221630);
}

.jg0ys8bve {
  d: path("M10.132 7.658a.363.363 0 0 0-.1-.2l-.112.124l.05.098l.162-.022Z");
}

.jj65vhdzq {
  stop-color: var(--svg-color--635a6d, #635A6D);
}

.jjhk_ub7b {
  d: path("M11.048 5.746c.018.096-.102.144-.167.07c-.453-.513-1.133-1.011-2.023-1.011c-.838 0-1.553.533-2.033 1.064c-.064.072-.182.025-.166-.07a2.231 2.231 0 0 1 4.389-.053Z");
}

.jpy6mubxx {
  fill: var(--svg-color--000, #000);
  d: path("M22.613 7.72a.22.22 0 0 1 .22-.221a.22.22 0 0 1 .197.322h-.39a.2.2 0 0 1-.027-.101Z");
}

.ju60xvb_w {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m8.728 7.771l-.354.734c-.044.151.062.302.211.302h.318c.15 0 .255-.153.211-.302l-.215-.734c-.046-.162-.122-.162-.17 0Z");
}

.jum30v1nu {
  stop-color: var(--svg-color--42384b, #42384B);
}

.jy_02gl6p {
  fill: var(--svg-color--ecbaa9, #ECBAA9);
  fill-rule: evenodd;
  d: path("M9.369 10.71a.8.8 0 0 0 .308 1.09l3.527 1.977a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 1 0 1.068 1.19l1.973-1.72c.93-.82.856-2.148-.347-2.918l-3.574-2.014a.8.8 0 0 0-1.089.307Z");
}

.k-0qdfh_d {
  stop-color: var(--svg-color--ffcdbb, #FFCDBB);
}

.k0aq2sbpu {
  stop-color: var(--svg-color--6f597b, #6F597B);
}

.k7gu39gbr {
  fill: var(--svg-color--88024e, #88024E);
  d: path("M21.892 9.186a1.3 1.3 0 0 1-.598-.142c-.059-.03-.122.036-.085.09c.144.22.396.365.683.365a.817.817 0 0 0 .684-.365c.037-.056-.027-.12-.086-.09a1.29 1.29 0 0 1-.598.142Z");
}

.k8t65cc0e {
  stop-color: var(--svg-color--f6c0b0, #F6C0B0);
}

.kce6eo76s {
  d: path("M10.558 5.396L9.23 5.84a.452.452 0 0 0 .203.877l1.32-.177l-.195-1.143Z");
}

.kivjlybrc {
  stroke: var(--svg-color--f1c2b0, #F1C2B0);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M3.94 13.912c-.088.073-.193.289.094.57c.288.282 1.156 1.06 1.555 1.414");
}

.kl81nmxpg {
  stop-color: var(--svg-color--dfa69c, #DFA69C);
}

.kr_eiac3t {
  r: 0.766px;
}

.krimkgb2b {
  cx: 23.95px;
  cy: 7.835px;
  r: 0.721px;
}

.ktrjcib4u {
  stop-color: var(--svg-color--bd7a68, #BD7A68);
}

.ktwvf2juy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M9.564 6.588c.186-.033.548-.023.798.171");
}

.kuw77jfnz {
  stop-color: var(--svg-color--645a6f, #645A6F);
}

.l2oc9lblk {
  d: path("M8.787 9.937a2.872 2.872 0 0 0-2.872 2.872v8.185h2.932l.207-1.551a.175.175 0 0 1 .33-.054l.79 1.605h2.933l-1.33-3.705a2.001 2.001 0 0 1-.118-.676V12.81a2.872 2.872 0 0 0-2.872-2.872Z");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lb24jvbmc {
  cx: 7.787px;
  cy: 7.489px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.ljlsb5bcz {
  fill: var(--svg-color--000, #000);
  d: path("M21.17 7.72a.22.22 0 0 0-.221-.221a.22.22 0 0 0-.197.322h.391a.22.22 0 0 0 .026-.101Z");
}

.lu78seb9e {
  stop-color: var(--svg-color--be8c77, #BE8C77);
}

.lw10mib7m {
  stop-color: var(--svg-color--d79988, #D79988);
}

.m_1e2qbpe {
  stop-color: var(--svg-color--423d3f, #423D3F);
  stop-opacity: 0;
}

.m459pab_j {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
}

.ma4xxac9i {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M6.936 3.268c.222.71.522 1.166.645 1.305l.633-.242c-.013-.183-.096-.709-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.402-.078 1.29Z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mlh1k8r8i {
  stop-color: var(--svg-color--656069, #656069);
}

.mmbdc7bdg {
  fill: var(--svg-color--ecbaa9, #ECBAA9);
  fill-rule: evenodd;
  d: path("M22.414 10.72a.8.8 0 0 0 .308 1.09l3.527 1.977a.2.2 0 0 1 .034.325l-1.9 1.763a.8.8 0 0 0 1.068 1.191l1.973-1.72c.93-.821.856-2.149-.347-2.918l-3.574-2.015a.8.8 0 0 0-1.09.308Z");
}

.mq51c-mtw {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("M23.498 6.66h-.001l-.002-.002l-.006-.004a.597.597 0 0 0-.066-.047a1.223 1.223 0 0 0-.826-.16a.23.23 0 0 0 .072.456a.763.763 0 0 1 .51.095l.023.015l.003.003a.23.23 0 0 0 .293-.356Z");
}

.mrnjlr-cv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M20.356 6.822c.141-.125.45-.256.832-.195");
}

.mta_69bbu {
  stop-color: var(--svg-color--522e71, #522E71);
}

.n366y7b2s {
  stop-color: var(--svg-color--2c1c3e, #2C1C3E);
  stop-opacity: 0;
}

.n5-yy2b4d {
  d: path("M22.834 7.334a.385.385 0 0 1 .37.487h-.743a.387.387 0 0 1 .373-.487Z");
}

.n7c5lw_4k {
  stop-color: var(--svg-color--d6a38d, #D6A38D);
  stop-opacity: 0;
}

.nc1ak66ax {
  stop-color: var(--svg-color--3c393a, #3C393A);
}

.ndirioote {
  stop-color: var(--svg-color--b27a85, #B27A85);
}

.njika_bez {
  d: path("M23.177 7.669a.363.363 0 0 0-.1-.2l-.112.123l.05.099l.162-.022Z");
}

.o4ba0lb3g {
  cx: 10.904px;
  cy: 7.824px;
  r: 0.43px;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.orwbiqbjn {
  cx: 6.798px;
  cy: 7.824px;
  r: 0.43px;
}

.oxrspmbko {
  fill: var(--svg-color--605071, #605071);
  d: path("m25.549 13.395l-2.827-1.586a.8.8 0 0 1-.308-1.088c.216-.386.361-.72.747-.504l3.202 1.808l-.814 1.37Z");
}

.oz57i7b8n {
  fill: var(--svg-color--1e1e1e, #1E1E1E);
  d: path("m10.453 6.65l-.002-.001l-.002-.002l-.005-.004a.554.554 0 0 0-.067-.046a1.223 1.223 0 0 0-.826-.16a.23.23 0 0 0 .073.456a.762.762 0 0 1 .509.094l.024.016l.003.003a.23.23 0 0 0 .293-.356Z");
}

.p7-gc9bxa {
  d: path("m25.774 19.947l-2.703.719l3.604 7.839a2.64 2.64 0 0 0 2.398 1.533c.121 0 .206-.12.166-.234l-3.465-9.857Z");
}

.p7jmmxb2h {
  stop-color: var(--svg-color--d7a09d, #D7A09D);
  stop-opacity: 0;
}

.paegc_b1d {
  cx: 7.787px;
  cy: 7.489px;
  rx: 0.168px;
  ry: 0.085px;
}

.pkeuj4blr {
  fill: var(--svg-color--d89992, #D89992);
  d: path("m21.773 7.782l-.354.734c-.044.15.062.301.21.301h.32c.148 0 .254-.153.21-.301l-.215-.734c-.046-.163-.122-.163-.17 0Z");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pqm31jbvw {
  d: path("m21.727 7.711l-.229.734a.233.233 0 0 0 .225.302h.34c.158 0 .27-.153.224-.302l-.23-.734c-.049-.162-.278-.162-.33 0Z");
}

.psdxqmvzz {
  stop-color: var(--svg-color--dba493, #DBA493);
  stop-opacity: 0;
}

.ptt69tewf {
  fill: var(--svg-color--e4b49e, #E4B49E);
  fill-rule: evenodd;
  d: path("M8.395 10.71a.8.8 0 0 1-.307 1.09L4.56 13.776a.2.2 0 0 0-.035.325l1.9 1.763a.8.8 0 0 1-1.068 1.19l-1.973-1.72c-.93-.82-.855-2.148.347-2.918l3.575-2.014a.8.8 0 0 1 1.088.307Z");
}

.pwv_6m0ax {
  stop-color: var(--svg-color--d9a79f, #D9A79F);
}

.pwy6vijbg {
  d: path("m7.883 28.187l-.034.257a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-1.72h1.968Z");
}

.px4pa2bzd {
  stop-color: var(--svg-color--be8474, #BE8474);
}

.pzx6ybcwl {
  d: path("M5.26 13.384L8.088 11.8a.8.8 0 1 0-.781-1.396l-2.86 1.612l.813 1.37Z");
}

.qb120pbsb {
  stop-color: var(--svg-color--ffdfc4, #FFDFC4);
  stop-opacity: 0;
}

.qc5tyzrav {
  stop-color: var(--svg-color--423d3f, #423D3F);
}

.qgz62l2ld {
  stop-color: var(--svg-color--443553, #443553);
}

.qhg47wyku {
  stop-color: var(--svg-color--2d1b3f, #2D1B3F);
  stop-opacity: 0;
}

.qpup5zbhe {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M19.936 5.758v.387c-.004.064-.03.208-.112.269");
}

.qvr533bky {
  d: path("m12.729 19.937l-2.703.719l3.604 7.838a2.64 2.64 0 0 0 2.397 1.534c.122 0 .207-.12.167-.234l-3.465-9.857Z");
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r3t82tbzk {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
  stop-opacity: 0;
}

.r3zsrtbkv {
  d: path("M9.76 7.405c.028.037-.03.082-.095.13c-.065.05-.113.084-.14.047c-.028-.037.002-.106.068-.155c.065-.049.14-.058.167-.022Z");
}

.r9fi4lm9m {
  cx: 20.832px;
  cy: 7.499px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.168px;
  ry: 0.085px;
}

.rcuz4uefu {
  stop-color: var(--svg-color--f5b7a7, #F5B7A7);
  stop-opacity: 0;
}

.rflev1o0y {
  d: path("M19.666 6.95c0-.116.046-.254.139-.323l.07-.07a.457.457 0 0 0 .161-.368v-.368c0-.115.07-.207.185-.23c.278-.07.857-.184 1.69-.184c.834 0 1.413.115 1.691.184a.248.248 0 0 1 .186.23v.368a.54.54 0 0 0 .162.369c.216.152.203.235.185.414c-.023.23-.047.622-.047.622a.29.29 0 0 0 .008 0l-.114 1.709c-.07.763-.67 1.296-1.386 1.296H21.21c-.74 0-1.317-.533-1.386-1.296c-.06-.785-.087-1.571-.158-2.354Z");
}

.rjudgtb2f {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M19.981 3.278c.222.71.522 1.166.645 1.305l.633-.242a6.047 6.047 0 0 0-.325-1.356c-.285-.808-.578-1.09-.875-.996c-.21.086-.355.403-.078 1.29Z");
}

.rlzetx3ey {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
}

.royd6tbgi {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M22.806 7.416c.027.036-.03.081-.096.13c-.065.049-.113.083-.14.046c-.028-.036.003-.106.068-.155c.065-.048.14-.058.168-.021Z");
}

.rvf3-0bfj {
  stop-color: var(--svg-color--dead9d, #DEAD9D);
  stop-opacity: 0;
}

.rw6zcv7ej {
  stop-color: var(--svg-color--dea798, #DEA798);
}

.sbbw_6vcc {
  stop-color: var(--svg-color--ffdec4, #FFDEC4);
}

.sf9xar_rm {
  fill: var(--svg-color--242324, #242324);
  d: path("m10.928 5.028l.185.092c.324.161.51.53.44.92l-.255 1.313c-.023.136-.112.227-.247.23a.29.29 0 0 1-.008 0s.023-.39.047-.621c.018-.187-.014-.244-.186-.415a.542.542 0 0 1-.162-.368v-.368a.248.248 0 0 0-.185-.23a7.074 7.074 0 0 0-1.69-.185c-.834 0-1.413.115-1.69.184a.225.225 0 0 0-.186.23v.37a.457.457 0 0 1-.162.367l-.07.07c-.092.069-.138.207-.138.322c.023.253.046.622.046.622a.273.273 0 0 1-.278-.23l-.255-1.313a.881.881 0 0 1 .463-.898l.186-.092c.115-.07.231-.161.347-.253l.417-.438c.254-.23.625-.3.95-.138c.23.07.485.07.717 0a1.04 1.04 0 0 1 1.019.23l.347.346a.967.967 0 0 0 .348.253Z");
}

.su6zcqbzj {
  fill: var(--svg-color--ffdac4, #FFDAC4);
  d: path("m24.54 20.17l.824-.303l3.153 8.579h-.758l-3.218-8.276Z");
}

.szlhq7bky {
  d: path("M6.62 6.939c0-.115.047-.254.14-.323l.069-.069a.457.457 0 0 0 .162-.368V5.81c0-.116.07-.208.185-.23c.278-.07.857-.185 1.69-.185c.834 0 1.413.115 1.691.184a.248.248 0 0 1 .185.23v.369c0 .138.07.276.162.368c.217.152.204.236.186.415c-.024.23-.047.621-.047.621h.008l-.115 1.71c-.069.763-.67 1.296-1.386 1.296H8.165c-.74 0-1.317-.533-1.386-1.297c-.06-.784-.087-1.57-.158-2.353Z");
}

.tigrkbwnp {
  stop-color: var(--svg-color--47364e, #47364E);
  stop-opacity: 0;
}

.toalqabes {
  cx: 10.904px;
  cy: 7.824px;
  r: 0.721px;
}

.tqgh1edwg {
  stop-color: var(--svg-color--eaab97, #EAAB97);
}

.twmi8xbgq {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.878 7.207c.282 0 .52.194.585.457a.118.118 0 0 1-.116.147h-.963a.1.1 0 0 1-.098-.118a.603.603 0 0 1 .592-.486Z");
}

.u-ra5zb4n {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M10.771 3.268c-.222.71-.522 1.166-.644 1.305l-.633-.242c.013-.183.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.402.078 1.29Z");
}

.ui2kgq2tt {
  stop-color: var(--svg-color--464344, #464344);
}

.uk24qccae {
  stop-color: var(--svg-color--463c39, #463C39);
  stop-opacity: 0;
}

.uzkpn5btf {
  stop-color: var(--svg-color--b07f87, #B07F87);
}

.v9qmesogf {
  d: path("M20.949 7.334a.385.385 0 0 0-.372.487h.745a.388.388 0 0 0-.373-.487Z");
}

.va8879bri {
  stroke: var(--svg-color--fccbb5, #FCCBB5);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m12.724 12.304l1.083.628c.194.1.579.44.57 1.002");
}

.vf96q7bmi {
  fill: var(--svg-color--000, #000);
  d: path("M9.568 7.71a.22.22 0 0 1 .221-.221a.22.22 0 0 1 .196.322h-.39a.2.2 0 0 1-.027-.102Z");
}

.vobictbgt {
  stop-color: var(--svg-color--5c4c68, #5C4C68);
}

.vpvekld5v {
  stop-color: var(--svg-color--3c393a, #3C393A);
  stop-opacity: 0;
}

.vudhj94wy {
  fill: var(--svg-color--4f415e, #4F415E);
  d: path("M23.816 3.278c-.221.71-.522 1.166-.644 1.305l-.633-.242c.013-.182.096-.709.324-1.356c.285-.808.578-1.09.875-.996c.211.086.356.403.078 1.29Z");
}

.vwv_1xbpr {
  cx: 20.832px;
  cy: 7.499px;
  rx: 0.168px;
  ry: 0.085px;
}

.w9k9d9dcq {
  d: path("m21.662 11.78l-.865-1.505h2.125l-.824 1.501a.25.25 0 0 1-.436.004Z");
}

.wachewblq {
  stop-color: var(--svg-color--ba7c6b, #BA7C6B);
}

.wdqn7tq-u {
  stop-color: var(--svg-color--d9aa94, #D9AA94);
}

.wi8di0b_n {
  stop-color: var(--svg-color--353435, #353435);
}

.x0dkyshlp {
  d: path("M22.806 7.416c.027.036-.03.081-.096.13c-.065.049-.113.083-.14.046c-.028-.036.003-.106.068-.155c.065-.048.14-.058.168-.021Z");
}

.x6mjr8bji {
  stop-color: var(--svg-color--ffd7c1, #FFD7C1);
  stop-opacity: 0;
}

.x8d9utbsu {
  stop-color: var(--svg-color--d5a58e, #D5A58E);
  stop-opacity: 0;
}

.xl-haubxn {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M8.787 9.937a2.872 2.872 0 0 0-2.872 2.872v8.185h2.932l.207-1.551a.175.175 0 0 1 .33-.054l.79 1.605h2.933l-1.33-3.705a2.001 2.001 0 0 1-.118-.676V12.81a2.872 2.872 0 0 0-2.872-2.872Z");
}

.xnlhc5b9k {
  d: path("m10.928 5.028l.185.092c.324.161.51.53.44.92l-.255 1.313c-.023.136-.112.227-.247.23a.29.29 0 0 1-.008 0s.023-.39.047-.621c.018-.187-.014-.244-.186-.415a.542.542 0 0 1-.162-.368v-.368a.248.248 0 0 0-.185-.23a7.074 7.074 0 0 0-1.69-.185c-.834 0-1.413.115-1.69.184a.225.225 0 0 0-.186.23v.37a.457.457 0 0 1-.162.367l-.07.07c-.092.069-.138.207-.138.322c.023.253.046.622.046.622a.273.273 0 0 1-.278-.23l-.255-1.313a.881.881 0 0 1 .463-.898l.186-.092c.115-.07.231-.161.347-.253l.417-.438c.254-.23.625-.3.95-.138c.23.07.485.07.717 0a1.04 1.04 0 0 1 1.019.23l.347.346a.967.967 0 0 0 .348.253Z");
}

.xwtxp-byo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M22.61 6.598c.185-.033.547-.023.797.172");
}

.y-jrw0bve {
  fill: var(--svg-color--fbc4b1, #FBC4B1);
  d: path("m8.682 7.701l-.23.734a.233.233 0 0 0 .226.302h.339c.16 0 .271-.154.225-.302l-.23-.734c-.049-.162-.278-.162-.33 0Z");
}

.y1yyvab7v {
  stroke: var(--svg-color--f1c2b0, #F1C2B0);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M16.985 13.922c-.088.073-.193.29.094.57a70.98 70.98 0 0 0 1.555 1.415");
}

.ybvc-8bjc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M6.89 5.747v.388c-.003.064-.03.207-.11.268");
}

.yf9erdbmk {
  stop-color: var(--svg-color--4a4648, #4A4648);
  stop-opacity: 0;
}

.yi3aunbmr {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M7.31 6.811c.142-.124.45-.256.833-.195");
}

.yk-93wl_k {
  cx: 19.843px;
  cy: 7.835px;
  r: 0.721px;
}

.yriep8b8t {
  fill: var(--svg-color--4e3f60, #4E3F60);
  d: path("M21.832 9.948a2.872 2.872 0 0 0-2.872 2.871v8.185h2.932l.207-1.55a.175.175 0 0 1 .33-.055l.791 1.605h2.932l-1.33-3.705a2.002 2.002 0 0 1-.118-.676V12.82a2.872 2.872 0 0 0-2.872-2.871Z");
}

.ys5rm3ubl {
  d: path("m18.96 20.244l2.997.27l-1.063 7.94a1.828 1.828 0 0 1-1.812 1.584a.122.122 0 0 1-.122-.122v-9.672Z");
}

.yvh--yb5o {
  stroke: var(--svg-color--fccbb5, #FCCBB5);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("m25.77 12.315l1.083.627c.193.1.578.44.569 1.002");
}

.yyvs3obha {
  stop-color: var(--svg-color--e8ad97, #E8AD97);
  stop-opacity: 0;
}

.z_xanemog {
  cx: 6.797px;
  cy: 7.824px;
  r: 0.721px;
}

.z3n_1mwef {
  stop-color: var(--svg-color--a58787, #A58787);
}

.z4ybrvo8l {
  d: path("m20.928 28.197l-.034.258a1.828 1.828 0 0 1-1.812 1.583a.122.122 0 0 1-.122-.122v-1.719h1.968Z");
}

.z8y6fgvmn {
  stop-color: var(--svg-color--ffdabf, #FFDABF);
}

.zaq85lb5o {
  cx: 23.95px;
  cy: 7.835px;
  r: 0.43px;
}

.zcu_1v8no {
  fill: var(--svg-color--fff, #fff);
  d: path("M22.923 7.217c.282 0 .52.194.585.457a.118.118 0 0 1-.116.147h-.963a.1.1 0 0 1-.098-.117a.603.603 0 0 1 .592-.487Z");
}

.ze_b5eb-w {
  cx: 19.843px;
  cy: 7.835px;
  r: 0.43px;
}

.zf2atv-8x {
  stop-color: var(--svg-color--dc9c96, #DC9C96);
  stop-opacity: 0;
}

.zoz3lmrqj {
  stop-color: var(--svg-color--453457, #453457);
}

.zx1idre_k {
  stop-color: var(--svg-color--353435, #353435);
  stop-opacity: 0;
}

</style>
