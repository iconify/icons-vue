<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBdjLzp)" class="cvy9mqbkm"/><path fill="url(#i1vA0jb)" class="cvy9mqbkm"/><path fill="url(#ibemRiy)" class="cvy9mqbkm"/><rect fill="url(#iVRrwbb)" class="f3uroqbmf"/><rect fill="url(#inBpnac)" class="f3uroqbmf"/><path fill="url(#ibSl6Qd)" class="xyy_16buk"/><path fill="url(#iVPF8he)" class="xyy_16buk"/><path fill="url(#it85hjb)" class="r-1s1yb6h"/><path fill="url(#iv4ypVb)" class="r-1s1yb6h"/><g filter="url(#imxFt2d)"><path fill="url(#itOob7i)" class="lwxkvcbow"/></g><path fill="url(#iaB3gPb)" class="lwxkvcbow"/><path fill="url(#iNxI6Cc)" class="lwxkvcbow"/><g filter="url(#i8pbOVc)"><path fill="url(#iEzTAwc)" class="pqo_8gkno"/></g><circle fill="url(#iYORe4c)" class="edvoszjad"/><g filter="url(#iu7nRkA)"><circle fill="url(#i9HT6Id)" class="tu2iar-cn"/></g><g filter="url(#iMi13yP)"><circle fill="url(#iufYqDb)" class="pp8306fvf"/><circle fill="url(#ilrYPBb)" class="pp8306fvf"/></g><g filter="url(#irksNGe)"><circle class="rjjb8xtpq"/><circle fill="url(#iExj6sD)" class="agmax-b2r"/><circle fill="url(#iAogDub)" class="agmax-b2r"/></g><path fill="url(#iQNAxPb)" class="maft1s56r"/><path fill="url(#i39em3b)" class="maft1s56r"/><path fill="url(#iODZnab)" class="maft1s56r"/><path fill="url(#ixbcnid)" class="maft1s56r"/><path fill="url(#iZG9Gab)" class="maft1s56r"/><path fill="url(#iIqWLDq)" class="maft1s56r"/><g filter="url(#iNRiWLT)"><path class="tmtvk7b7b"/><path fill="url(#iJuuMIc)" class="puxl4wv8k"/><path fill="url(#ijoTkEc)" class="puxl4wv8k"/><path fill="url(#iNHIEYb)" class="puxl4wv8k"/><path fill="url(#iRQiiti)" class="puxl4wv8k"/><path fill="url(#i0e5kEc)" class="puxl4wv8k"/><path fill="url(#im1vGAe)" class="puxl4wv8k"/></g><path fill="url(#ihrZ9Wd)" class="puxl4wv8k"/><path fill="url(#iEveZKc)" class="puxl4wv8k"/><g filter="url(#igqVshb)"><path class="rkmtjxb1z"/></g><g filter="url(#id22wVd)"><path class="hq60sqbor"/><path fill="url(#iuvCKim)" class="cjjammb3c"/><path fill="url(#iH76ard)" class="cjjammb3c"/><path fill="url(#i8AyV5G)" class="cjjammb3c"/></g><path fill="url(#iOo9eLc)" class="cjjammb3c"/><path class="jrhyj5bci"/><path fill="url(#i9lZt9C)" class="kyj9p6wbz"/><path class="l88hcqbyy"/><g filter="url(#iLrTPSN)"><path class="c-tzt4b3k"/><path fill="url(#iuos4Pd)" class="moozr4hvt"/></g><g filter="url(#iFZHSAe)"><path fill="url(#ipSLV9b)" class="i-_4mpyaz"/></g><path class="oqobvmmda"/><path fill="url(#i86BEqc)" class="cvxlkhb7c"/><path class="ba32yjk5r"/><g filter="url(#iDL75cb)"><path fill="url(#iQSWqJb)" class="qebaiod6s"/></g><g filter="url(#iq1YBEc)"><ellipse transform="rotate(-27.914 13.5 9.807)" class="escjjib2z"/><ellipse fill="url(#i4eKQ2c)" transform="rotate(-27.914 13.5 9.807)" class="ntgltub2d"/></g><path clip-rule="evenodd" class="lg2mkobts"/><g filter="url(#i4SO8Nb)"><path fill="url(#ia0YUrd)" class="uqqvqrblp"/></g><rect fill="url(#iGO2iHb)" class="ppr-vzbuq"/><rect fill="url(#igVeCue)" class="ppr-vzbuq"/><rect fill="url(#iMXXViu)" class="ppr-vzbuq"/><rect fill="url(#iYUrRhr)" class="q_r3twb-e"/><rect fill="url(#izRyNFc)" class="q_r3twb-e"/><rect fill="url(#iCOucGb)" class="q_r3twb-e"/><g filter="url(#iIBIdNb)"><path class="osv9ion7h"/></g><g filter="url(#iJWhSAd)"><path class="cyh2vdo_u"/></g><defs><radialGradient id="iBdjLzp" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.31345 -13.7312 0 14.936 15.28)" gradientUnits="userSpaceOnUse"><stop offset=".09" class="cpaal-ufa"/><stop offset=".584" class="kv7ch_ylm"/></radialGradient><radialGradient id="i1vA0jb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -8.71875 5.76446 0 21.688 24.318)" gradientUnits="userSpaceOnUse"><stop class="x1h71jpye"/><stop offset="1" class="s8c4474kl"/></radialGradient><radialGradient id="iVRrwbb" cx="0" cy="0" r="1" gradientTransform="rotate(41.877 -14.277 28.478)scale(2.73492 3.36385)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="obgwgsb_d"/><stop offset=".962" class="gs5mi4b0h"/></radialGradient><radialGradient id="inBpnac" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 1 -1.28354 1.60442 13.876 16.63)" gradientUnits="userSpaceOnUse"><stop class="wuv1_cbce"/><stop offset="1" class="q7gy-8gmb"/></radialGradient><radialGradient id="ibSl6Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-.74874 -4.29684 1.65204 -.28787 24.838 23.36)" gradientUnits="userSpaceOnUse"><stop offset=".033" class="k-uja4b-f"/><stop offset="1" class="gqtlvubnf"/></radialGradient><radialGradient id="it85hjb" cx="0" cy="0" r="1" gradientTransform="matrix(2.97917 .60514 -1.64345 8.09081 5.758 22.771)" gradientUnits="userSpaceOnUse"><stop class="cj4u9zbng"/><stop offset="1" class="a5wnorbzm"/></radialGradient><radialGradient id="iv4ypVb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.91264 .5297 0 8.658 24.718)" gradientUnits="userSpaceOnUse"><stop class="i0qjgacez"/><stop offset="1" class="k1t-ffcus"/></radialGradient><radialGradient id="itOob7i" cx="0" cy="0" r="1" gradientTransform="matrix(14.39624 1.34674 -.46749 4.99726 16.668 24.847)" gradientUnits="userSpaceOnUse"><stop class="oqshz6brn"/><stop offset="1" class="b2e5ellij"/></radialGradient><radialGradient id="iaB3gPb" cx="0" cy="0" r="1" gradientTransform="matrix(.70684 1.42914 -5.7496 2.8437 17.494 26.622)" gradientUnits="userSpaceOnUse"><stop offset=".178" class="r_7vpcbwu"/><stop offset="1" class="rxem520qy"/></radialGradient><radialGradient id="iNxI6Cc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.59375 2.52356 -.6861 -1.52084 26.47 24.099)" gradientUnits="userSpaceOnUse"><stop class="kw313ubae"/><stop offset="1" class="rf5xkc8ne"/></radialGradient><radialGradient id="iEzTAwc" cx="0" cy="0" r="1" gradientTransform="rotate(78.93 -7.06 22.372)scale(2.92951 16.093)" gradientUnits="userSpaceOnUse"><stop offset=".17" class="u44n60b3i"/><stop offset=".834" class="wokjsbbtp"/></radialGradient><radialGradient id="iYORe4c" cx="0" cy="0" r="1" gradientTransform="matrix(1.75001 0 0 3.06254 9.55 10.583)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="ilrYPBb" cx="0" cy="0" r="1" gradientTransform="matrix(.82442 -.6003 .68517 .94097 21.072 10.319)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iExj6sD" cx="0" cy="0" r="1" gradientTransform="matrix(.819 -1.50636 .88167 .47936 20.66 11.402)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="iAogDub" cx="0" cy="0" r="1" gradientTransform="rotate(44.707 -2.517 30.461)scale(.36382 .46903)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iODZnab" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.24756 -11.1956 0 16.313 8.72)" gradientUnits="userSpaceOnUse"><stop offset=".591" class="psh6lubus"/><stop offset=".996" class="z1tcbhznh"/></radialGradient><radialGradient id="ixbcnid" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.30347 1.60427 0 18.288 9.315)" gradientUnits="userSpaceOnUse"><stop class="qvori65vn"/><stop offset="1" class="l_2mr6b5e"/></radialGradient><radialGradient id="iZG9Gab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.38702 1.72489 0 13.743 9.281)" gradientUnits="userSpaceOnUse"><stop class="waf9s5hfu"/><stop offset="1" class="qibk7dfmm"/></radialGradient><radialGradient id="iJuuMIc" cx="0" cy="0" r="1" gradientTransform="rotate(127.807 9.107 6.253)scale(5.59068 9.50745)" gradientUnits="userSpaceOnUse"><stop class="ck410xb1o"/><stop offset="1" class="qeh0r4bjq"/></radialGradient><radialGradient id="iNHIEYb" cx="0" cy="0" r="1" gradientTransform="matrix(-.06664 -1.85633 .91168 -.03273 11.767 7.136)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="euj6xpbnj"/><stop offset="1" class="hchnd0bsx"/></radialGradient><radialGradient id="iRQiiti" cx="0" cy="0" r="1" gradientTransform="matrix(.85676 -1.96105 1.59938 .69875 20.164 8.85)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="ghdrqrbfe"/><stop offset="1" class="d7zypgbet"/></radialGradient><radialGradient id="i0e5kEc" cx="0" cy="0" r="1" gradientTransform="matrix(.99004 1.22846 -1.08464 .87414 15.176 2.005)" gradientUnits="userSpaceOnUse"><stop class="wn92vfpti"/><stop offset="1" class="t4clght5m"/></radialGradient><radialGradient id="im1vGAe" cx="0" cy="0" r="1" gradientTransform="matrix(1.44698 -3.02724 1.04596 .49995 20.126 6.375)" gradientUnits="userSpaceOnUse"><stop class="hye_w5bmk"/><stop offset="1" class="f2dz70yyi"/></radialGradient><radialGradient id="ihrZ9Wd" cx="0" cy="0" r="1" gradientTransform="matrix(.21257 1.03452 -2.20746 .45359 16.669 1.923)" gradientUnits="userSpaceOnUse"><stop offset=".32" class="zh9-5mu_z"/><stop offset="1" class="g_vzvy58m"/></radialGradient><radialGradient id="iEveZKc" cx="0" cy="0" r="1" gradientTransform="matrix(1.10538 1.41715 -2.28266 1.78047 11.68 3.226)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="pb3_oi83v"/><stop offset="1" class="jsr2_sbwr"/></radialGradient><radialGradient id="i9lZt9C" cx="0" cy="0" r="1" gradientTransform="matrix(0 .90066 -1.06571 0 18.122 10.235)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iuos4Pd" cx="0" cy="0" r="1" gradientTransform="matrix(-.23122 -.29796 .41023 -.31834 17.895 9.986)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i86BEqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .9007 -1.06577 0 13.77 10.235)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="i4eKQ2c" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 11.725 -1.577)scale(.49266 .59221)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="ia0YUrd" cx="0" cy="0" r="1" gradientTransform="matrix(.66016 -.256 .1891 .48764 15.625 14.697)" gradientUnits="userSpaceOnUse"><stop class="nf7icz-9n"/><stop offset="1" class="w_wpqlbxc"/></radialGradient><linearGradient id="ibemRiy" x1="15.683" x2="15.683" y1="29.943" y2="26.349" gradientUnits="userSpaceOnUse"><stop class="rzj2y-urr"/><stop offset="1" class="kwhfuzi9l"/></linearGradient><linearGradient id="iVPF8he" x1="22.679" x2="23.656" y1="23.399" y2="23.329" gradientUnits="userSpaceOnUse"><stop offset=".197" class="k5eoekors"/><stop offset="1" class="ay58lpbqf"/></linearGradient><linearGradient id="i9HT6Id" x1="11.214" x2="10.575" y1="10.861" y2="10.861" gradientUnits="userSpaceOnUse"><stop class="kyv4qretn"/><stop offset="1" class="twg2szokh"/></linearGradient><linearGradient id="iufYqDb" x1="21.785" x2="20.968" y1="9.494" y2="12.024" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iQNAxPb" x1="19.974" x2="12.358" y1="10.971" y2="12.106" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset="1" class="x2e45tbep"/></linearGradient><linearGradient id="i39em3b" x1="10.568" x2="12.874" y1="13.66" y2="13.359" gradientUnits="userSpaceOnUse"><stop class="a99w59rao"/><stop offset="1" class="x2u305zwp"/></linearGradient><linearGradient id="iIqWLDq" x1="15.702" x2="15.702" y1="17.109" y2="16.338" gradientUnits="userSpaceOnUse"><stop class="g07i4ob3p"/><stop offset="1" class="ep-4tdl_o"/></linearGradient><linearGradient id="ijoTkEc" x1="11.101" x2="13.995" y1="10.316" y2="5.176" gradientUnits="userSpaceOnUse"><stop class="kyzs66gfi"/><stop offset="1" class="zsx4vmb0f"/></linearGradient><linearGradient id="iuvCKim" x1="15.087" x2="16.023" y1="11.629" y2="11.629" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iH76ard" x1="16.885" x2="15.862" y1="11.95" y2="11.936" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="i8AyV5G" x1="16.143" x2="16.143" y1="12.69" y2="12.119" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="iOo9eLc" x1="16.074" x2="16.074" y1="12.732" y2="12.565" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="ipSLV9b" x1="18.897" x2="18.584" y1="9.956" y2="10.149" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iQSWqJb" x1="14.512" x2="14.2" y1="9.956" y2="10.149" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iGO2iHb" x1="13.608" x2="13.608" y1="7.931" y2="8.891" gradientUnits="userSpaceOnUse"><stop class="bu3bd7x5c"/><stop offset="1" class="l4--xqxgw"/></linearGradient><linearGradient id="igVeCue" x1="13.853" x2="13.853" y1="8.932" y2="8.69" gradientUnits="userSpaceOnUse"><stop class="mnrxn5b7y"/><stop offset="1" class="yvn9wabqe"/></linearGradient><linearGradient id="iMXXViu" x1="12.062" x2="12.607" y1="8.444" y2="8.447" gradientUnits="userSpaceOnUse"><stop offset=".344" class="cbl57ub5t"/><stop offset="1" class="iedqpib7a"/></linearGradient><linearGradient id="iYUrRhr" x1="18.366" x2="18.366" y1="7.931" y2="8.891" gradientUnits="userSpaceOnUse"><stop class="bu3bd7x5c"/><stop offset="1" class="l4--xqxgw"/></linearGradient><linearGradient id="izRyNFc" x1="18.61" x2="18.61" y1="8.932" y2="8.69" gradientUnits="userSpaceOnUse"><stop class="mnrxn5b7y"/><stop offset="1" class="yvn9wabqe"/></linearGradient><linearGradient id="iCOucGb" x1="16.82" x2="17.364" y1="8.444" y2="8.447" gradientUnits="userSpaceOnUse"><stop offset=".344" class="cbl57ub5t"/><stop offset="1" class="iedqpib7a"/></linearGradient><filter id="imxFt2d" width="19.161" height="7.244" x="8.163" y="22.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.486275 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4593"/></filter><filter id="i8pbOVc" width="19.009" height="7.177" x="5.176" y="22.818" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.3"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.494118 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4593"/></filter><filter id="iu7nRkA" width="2.985" height="2.984" x="9.722" y="9.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".25"/></filter><filter id="iMi13yP" width="3.58" height="3.58" x="19.036" y="8.668" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4593"/></filter><filter id="irksNGe" width="2.985" height="2.984" x="19.209" y="9.091" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".25"/></filter><filter id="iNRiWLT" width="12.567" height="8.521" x="9.666" y="1.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.984314 0 0 0 0 0.584314 0 0 0 0 0.129412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_13036_4593"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.572549 0 0 0 0 0.0156863 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_13036_4593" result="effect2_innerShadow_13036_4593"/></filter><filter id="igqVshb" width="3.255" height="4.174" x="14.083" y="9.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".375"/></filter><filter id="id22wVd" width="2.372" height="3.174" x="14.763" y="9.767" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".125"/></filter><filter id="iLrTPSN" width=".785" height=".695" x="17.39" y="9.464" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".05"/></filter><filter id="iFZHSAe" width=".89" height=".912" x="18.227" y="9.538" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".1"/></filter><filter id="iDL75cb" width=".985" height="1.038" x="13.797" y="9.475" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".1"/></filter><filter id="iq1YBEc" width=".911" height=".703" x="13.045" y="9.456" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".05"/></filter><filter id="i4SO8Nb" width="1.224" height=".712" x="15.35" y="14.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".05"/></filter><filter id="iIBIdNb" width="2.984" height=".75" x="16.934" y="7.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".125"/></filter><filter id="iJWhSAd" width="2.984" height=".75" x="12.224" y="7.955" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_13036_4593" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-pouting" /></template>
<style>
.a5wnorbzm {
  stop-color: var(--svg-color--376c9c, #376C9C);
}

.a99w59rao {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
}

.agmax-b2r {
  cx: 20.701px;
  cy: 10.583px;
  r: 0.992px;
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.ay58lpbqf {
  stop-color: var(--svg-color--2887d7, #2887D7);
  stop-opacity: 0;
}

.b2e5ellij {
  stop-color: var(--svg-color--eba81f, #EBA81F);
}

.ba32yjk5r {
  fill: var(--svg-color--000, #000);
  d: path("M14.278 10.317a.51.51 0 0 0-.51-.51a.508.508 0 0 0-.452.744h.902a.5.5 0 0 0 .06-.234");
}

.bu3bd7x5c {
  stop-color: var(--svg-color--c6562f, #C6562F);
}

.c-tzt4b3k {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M18.058 9.615c.064.085-.069.188-.22.301c-.15.113-.262.192-.325.107c-.064-.085.007-.245.158-.357c.15-.113.324-.136.387-.05");
}

.cbl57ub5t {
  stop-color: var(--svg-color--bf4625, #BF4625);
}

.cj4u9zbng {
  stop-color: var(--svg-color--4c81bc, #4C81BC);
}

.cjjammb3c {
  d: path("m15.568 10.298l-.53 1.695a.538.538 0 0 0 .519.697h.784a.54.54 0 0 0 .519-.697l-.53-1.695c-.113-.375-.643-.375-.762 0");
}

.ck410xb1o {
  stop-color: var(--svg-color--ffe336, #FFE336);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cpaal-ufa {
  stop-color: var(--svg-color--2e69ab, #2E69AB);
}

.cvxlkhb7c {
  d: path("M13.769 9.427a.89.89 0 0 0-.858 1.124h1.72a1 1 0 0 0 .032-.234a.896.896 0 0 0-.894-.89");
}

.cvy9mqbkm {
  d: path("m9.157 24.755l-3.906.184c.578-5.253 5.03-9.34 10.437-9.34h.625c5.414 0 9.872 4.098 10.439 9.362l-4.377-.206v5.188H9.157z");
}

.cyh2vdo_u {
  stroke: var(--svg-color--d1725e, #D1725E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.599 8.33h2.234");
}

.d7zypgbet {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
  stop-opacity: 0;
}

.edvoszjad {
  cx: 11.214px;
  cy: 10.583px;
  r: 1.665px;
}

.ep-4tdl_o {
  stop-color: var(--svg-color--f9a53f, #F9A53F);
  stop-opacity: 0;
}

.escjjib2z {
  cx: 13.5px;
  cy: 9.807px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.388px;
  ry: 0.197px;
}

.euj6xpbnj {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f2dz70yyi {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
  stop-opacity: 0;
}

.f3uroqbmf {
  width: 4.223px;
  height: 6.028px;
  x: 13.876px;
  y: 12.693px;
  rx: 2.111px;
}

.ft5dv1b6b {
  fill: none;
}

.g_vzvy58m {
  stop-color: var(--svg-color--ffd831, #FFD831);
  stop-opacity: 0;
}

.g07i4ob3p {
  stop-color: var(--svg-color--de8775, #DE8775);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.ghdrqrbfe {
  stop-color: var(--svg-color--e57d1c, #E57D1C);
}

.gqtlvubnf {
  stop-color: var(--svg-color--5198d7, #5198D7);
}

.gs5mi4b0h {
  stop-color: var(--svg-color--ffb812, #FFB812);
}

.hchnd0bsx {
  stop-color: var(--svg-color--ffb42c, #FFB42C);
  stop-opacity: 0;
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.hq60sqbor {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.568 10.298l-.53 1.695a.538.538 0 0 0 .519.697h.784a.54.54 0 0 0 .519-.697l-.53-1.695c-.113-.375-.643-.375-.762 0");
}

.hye_w5bmk {
  stop-color: var(--svg-color--ffd93a, #FFD93A);
}

.i-_4mpyaz {
  d: path("M18.916 10.2a.84.84 0 0 0-.23-.462l-.26.285l.117.227z");
}

.i0qjgacez {
  stop-color: var(--svg-color--4870b0, #4870B0);
}

.iedqpib7a {
  stop-color: var(--svg-color--bf4625, #BF4625);
  stop-opacity: 0;
}

.jrhyj5bci {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.33 9.156c.651 0 1.201.449 1.35 1.056a.273.273 0 0 1-.266.34h-2.225a.23.23 0 0 1-.226-.272a1.394 1.394 0 0 1 1.367-1.124");
}

.jsr2_sbwr {
  stop-color: var(--svg-color--ffb01f, #FFB01F);
  stop-opacity: 0;
}

.k-uja4b-f {
  stop-color: var(--svg-color--61abfa, #61ABFA);
}

.k1t-ffcus {
  stop-color: var(--svg-color--4870b0, #4870B0);
  stop-opacity: 0;
}

.k5eoekors {
  stop-color: var(--svg-color--2887d7, #2887D7);
}

.kv7ch_ylm {
  stop-color: var(--svg-color--4d8ce2, #4D8CE2);
}

.kw313ubae {
  stop-color: var(--svg-color--ffe548, #FFE548);
}

.kwhfuzi9l {
  stop-color: var(--svg-color--406ce3, #406CE3);
  stop-opacity: 0;
}

.kyj9p6wbz {
  d: path("M18.124 9.427a.89.89 0 0 1 .857 1.124h-1.719a.893.893 0 0 1 .861-1.124");
}

.kyv4qretn {
  stop-color: var(--svg-color--df7f27, #DF7F27);
}

.kyzs66gfi {
  stop-color: var(--svg-color--e07027, #E07027);
}

.l_2mr6b5e {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
  stop-opacity: 0;
}

.l4--xqxgw {
  stop-color: var(--svg-color--bf452e, #BF452E);
}

.l88hcqbyy {
  fill: var(--svg-color--000, #000);
  d: path("M17.614 10.317c0-.283.227-.51.51-.51a.507.507 0 0 1 .453.744h-.902a.46.46 0 0 1-.06-.234");
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lg2mkobts {
  fill: var(--svg-color--890050, #890050);
  fill-rule: evenodd;
  d: path("M16.846 14.027a1.54 1.54 0 0 0-1.673 0a.2.2 0 1 1-.226-.33c.616-.423 1.504-.423 2.124 0a.2.2 0 0 1-.226.33");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.lwxkvcbow {
  d: path("M26.375 28.537c.6-1.05.453-2.813.375-3.598l-3.938-.168c-.413.212-1.526.088-2.031 0l-8.898-1.406c-.617-.118-2.096-.232-2.773.132c-.766.413-1 1.193-.938 1.579c4.271 1.53 12.632 4.562 13.757 4.812c1.82.313 3.696-.039 4.446-1.352");
}

.maft1s56r {
  d: path("m10.863 9.972l.049.001s-.054-.85-.107-1.436c0-.266.107-.585.321-.744l.16-.16c.268-.213.375-.532.375-.85V5.93c0-.266.16-.479.428-.532c.642-.16 1.979-.425 3.905-.425s3.263.266 3.905.425c.213.053.427.266.427.532v.851c0 .32.161.638.375.851c.5.351.47.544.428.958c-.054.531-.107 1.436-.107 1.436h.018l-.265 3.947c-.16 1.765-1.548 2.994-3.202 2.994h-3.201c-1.708 0-3.042-1.23-3.202-2.994z");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mnrxn5b7y {
  stop-color: var(--svg-color--c55365, #C55365);
}

.moozr4hvt {
  d: path("M18.058 9.615c.064.085-.069.188-.22.301c-.15.113-.262.192-.325.107c-.064-.085.007-.245.158-.357c.15-.113.324-.136.387-.05");
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.nf7icz-9n {
  stop-color: var(--svg-color--ffb026, #FFB026);
}

.ntgltub2d {
  cx: 13.5px;
  cy: 9.807px;
  rx: 0.388px;
  ry: 0.197px;
}

.obgwgsb_d {
  stop-color: var(--svg-color--ed7f14, #ED7F14);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.oqobvmmda {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.563 9.156c-.652 0-1.202.449-1.351 1.056a.273.273 0 0 0 .267.34h2.224a.23.23 0 0 0 .227-.272a1.4 1.4 0 0 0-1.367-1.124");
}

.oqshz6brn {
  stop-color: var(--svg-color--ffd03d, #FFD03D);
}

.osv9ion7h {
  stroke: var(--svg-color--d1725e, #D1725E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M17.31 8.33h2.234");
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pb3_oi83v {
  stop-color: var(--svg-color--c9993e, #C9993E);
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pp8306fvf {
  cx: 20.701px;
  cy: 10.583px;
  r: 1.665px;
}

.ppr-vzbuq {
  width: 3.092px;
  height: 0.96px;
  x: 12.062px;
  y: 7.931px;
  rx: 0.48px;
}

.pqo_8gkno {
  d: path("M5.625 28.537c-.6-1.05-.453-2.813-.375-3.598l3.938-.168c.412.212 1.526.088 2.031 0l9.672-1.563c.617-.117 1.448-.177 2.125.188c.728.392.7.965.642 1.352a.1.1 0 0 1-.063.078c-4.286 1.54-12.404 4.813-13.524 5.062c-1.82.313-3.696-.039-4.446-1.352");
}

.psh6lubus {
  stop-color: var(--svg-color--ffbd3a, #FFBD3A);
  stop-opacity: 0;
}

.puxl4wv8k {
  d: path("m20.755 4.123l.427.213c.75.372 1.177 1.223 1.017 2.127l-.589 3.032c-.052.313-.26.524-.57.531h-.018s.053-.904.107-1.435c.043-.432-.032-.564-.428-.958c-.214-.213-.374-.532-.374-.85V5.93c0-.266-.214-.478-.428-.532c-.642-.16-1.98-.425-3.905-.425c-1.926 0-3.263.266-3.905.425a.52.52 0 0 0-.428.532v.851c0 .32-.107.638-.374.851l-.16.16c-.215.16-.322.478-.322.744c.054.585.107 1.436.107 1.436l-.049-.001a.63.63 0 0 1-.593-.53L9.682 6.41c-.107-.851.32-1.702 1.07-2.074l.428-.213c.267-.16.534-.372.802-.585l.963-1.01c.588-.533 1.444-.692 2.193-.32c.535.16 1.123.16 1.658 0c.803-.266 1.712-.053 2.354.532l.802.798c.214.266.481.425.802.585");
}

.q_r3twb-e {
  width: 3.092px;
  height: 0.96px;
  x: 16.82px;
  y: 7.931px;
  rx: 0.48px;
}

.q7gy-8gmb {
  stop-color: var(--svg-color--d77817, #D77817);
  stop-opacity: 0;
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qebaiod6s {
  d: path("M14.582 10.212c0-.287-.234-.479-.297-.537l-.288.278l.177.36z");
}

.qeh0r4bjq {
  stop-color: var(--svg-color--ffe336, #FFE336);
  stop-opacity: 0;
}

.qibk7dfmm {
  stop-color: var(--svg-color--ee911a, #EE911A);
  stop-opacity: 0;
}

.qvori65vn {
  stop-color: var(--svg-color--ffba0d, #FFBA0D);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.r_7vpcbwu {
  stop-color: var(--svg-color--c26b2d, #C26B2D);
}

.r-1s1yb6h {
  d: path("m5.251 24.939l3.847-.16l.059.182h.031v-7.109a10.5 10.5 0 0 0-3.937 7.087");
}

.rf5xkc8ne {
  stop-color: var(--svg-color--ffe548, #FFE548);
  stop-opacity: 0;
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.rjjb8xtpq {
  cx: 20.701px;
  cy: 10.583px;
  r: 0.992px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.rkmtjxb1z {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("m15.674 10.46l-.818 1.696c-.101.348.142.697.487.697h.735c.345 0 .588-.354.487-.697l-.497-1.695c-.107-.376-.282-.376-.394 0");
}

.rxem520qy {
  stop-color: var(--svg-color--c26b2d, #C26B2D);
  stop-opacity: 0;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.rzj2y-urr {
  stop-color: var(--svg-color--406ce3, #406CE3);
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.s8c4474kl {
  stop-color: var(--svg-color--5ea9fc, #5EA9FC);
  stop-opacity: 0;
}

.t4clght5m {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
  stop-opacity: 0;
}

.tmtvk7b7b {
  fill: var(--svg-color--ffa91b, #FFA91B);
  d: path("m20.755 4.123l.427.213c.75.372 1.177 1.223 1.017 2.127l-.589 3.032c-.052.313-.26.524-.57.531h-.018s.053-.904.107-1.435c.043-.432-.032-.564-.428-.958c-.214-.213-.374-.532-.374-.85V5.93c0-.266-.214-.478-.428-.532c-.642-.16-1.98-.425-3.905-.425c-1.926 0-3.263.266-3.905.425a.52.52 0 0 0-.428.532v.851c0 .32-.107.638-.374.851l-.16.16c-.215.16-.322.478-.322.744c.054.585.107 1.436.107 1.436l-.049-.001a.63.63 0 0 1-.593-.53L9.682 6.41c-.107-.851.32-1.702 1.07-2.074l.428-.213c.267-.16.534-.372.802-.585l.963-1.01c.588-.533 1.444-.692 2.193-.32c.535.16 1.123.16 1.658 0c.803-.266 1.712-.053 2.354.532l.802.798c.214.266.481.425.802.585");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tu2iar-cn {
  cx: 11.214px;
  cy: 10.583px;
  r: 0.992px;
}

.twg2szokh {
  stop-color: var(--svg-color--e38523, #E38523);
}

.u44n60b3i {
  stop-color: var(--svg-color--ffe243, #FFE243);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.uqqvqrblp {
  d: path("M16.474 14.697a.512.512 0 0 0-1.024 0z");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.w_wpqlbxc {
  stop-color: var(--svg-color--ff912c, #FF912C);
}

.waf9s5hfu {
  stop-color: var(--svg-color--ee911a, #EE911A);
}

.wn92vfpti {
  stop-color: var(--svg-color--ffce2c, #FFCE2C);
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.wokjsbbtp {
  stop-color: var(--svg-color--fcad40, #FCAD40);
}

.wuv1_cbce {
  stop-color: var(--svg-color--d77817, #D77817);
}

.x1h71jpye {
  stop-color: var(--svg-color--5ea9fc, #5EA9FC);
}

.x2e45tbep {
  stop-color: var(--svg-color--ffac1b, #FFAC1B);
}

.x2u305zwp {
  stop-color: var(--svg-color--d19c3a, #D19C3A);
  stop-opacity: 0;
}

.xyy_16buk {
  d: path("M22.925 17.942a10.48 10.48 0 0 1 3.827 7.019l-3.827-.18z");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.yvn9wabqe {
  stop-color: var(--svg-color--c55365, #C55365);
  stop-opacity: 0;
}

.z1tcbhznh {
  stop-color: var(--svg-color--f59743, #F59743);
}

.zh9-5mu_z {
  stop-color: var(--svg-color--e4ba41, #E4BA41);
}

.zsx4vmb0f {
  stop-color: var(--svg-color--e07027, #E07027);
  stop-opacity: 0;
}

</style>
