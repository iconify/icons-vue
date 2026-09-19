<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iNziMae)"><path fill="url(#iumgDIe)" class="l8jusdr6y"/><path fill="url(#ipmDzYd)" class="l8jusdr6y"/><path fill="url(#irszlCe)" class="l8jusdr6y"/></g><path class="bflc-9bzd"/><path fill="url(#i3MOAve)" class="tx_btybwx"/><path fill="url(#iXVWiWd)" class="tx_btybwx"/><circle fill="url(#iqFLxQd)" class="ckkaoubhy"/><circle fill="url(#i7JWX9h)" class="ckkaoubhy"/><circle fill="url(#iFsNGde)" class="tr559m5ue"/><g filter="url(#ifZ1WTe)"><circle fill="url(#imm4xZd)" class="a1-vqmk_q"/></g><g filter="url(#itAtPgb)" class="mc2zb0bvp"><circle class="j_br2k90i"/></g><g filter="url(#ihTxmOt)"><path fill="url(#icF1urd)" class="rzrvnhrdd"/></g><path fill="url(#itdnD4d)" class="i5i_8mxsj"/><path fill="url(#icPFO8d)" class="i5i_8mxsj"/><g filter="url(#ibja3Pb)"><path fill="url(#ieFcIuN)" class="d0lldcbqg"/></g><g filter="url(#ixFuYPe)"><path fill="url(#i4BD9Ub)" class="ls65_6i-s"/></g><g filter="url(#iXpkMlb)"><path fill="url(#inrxXKe)" class="zsr0l3b0d"/><path fill="url(#iXlQ3uc)" class="zsr0l3b0d"/></g><g filter="url(#izf2oTZ)"><circle fill="url(#iUQRCRb)" class="vh3837gtk"/></g><path stroke="url(#ixOYXne)" class="wupazrada"/><g filter="url(#iKRvv8d)"><path stroke="url(#i4unVWb)" class="g-mr_sgso"/></g><path stroke="url(#ifigOfS)" class="qvye139vd"/><g filter="url(#iPNlZ0A)"><path stroke="url(#ipRrQmb)" class="jednjgv3t"/></g><g filter="url(#iZ94pzb)"><path class="hx3atwwaa"/></g><path class="mvfxgbsxp"/><path fill="url(#iI88bWd)" class="a7__jtqji"/><path fill="url(#iN5o1fc)" class="a7__jtqji"/><path fill="url(#iC9PN3d)" class="a7__jtqji"/><g filter="url(#iPGGHvb)"><path stroke="url(#iM3Z6Cc)" class="q008c2b7r"/></g><path class="s5rkt_jwe"/><g filter="url(#ixidOcT)"><path clip-rule="evenodd" class="cfc3_obcp"/></g><g filter="url(#iMU3zpd)"><path clip-rule="evenodd" class="ksg73c-ow"/></g><g filter="url(#iAcrTMs)"><path stroke="url(#iv8Tjue)" class="zm_gnnmci"/></g><g filter="url(#ioPuxVP)"><path stroke="url(#ihhKjwc)" class="er1ho7c5g"/></g><g filter="url(#ivkGmZd)"><path class="ok5p-1b6w"/><path fill="url(#iZKcQob)" class="g4mky1b_b"/></g><g filter="url(#iDHg1Wd)"><path class="b9onc53-n"/><path fill="url(#i0Sy9re)" class="m2ddouw1w"/></g><g filter="url(#iwcQxXc)"><path class="m1aembrxw"/></g><g filter="url(#ibf4zEn)"><path fill="url(#iD22qEe)" class="zgqgadcdt"/></g><g filter="url(#i0z7ppe)"><path fill="url(#izctZ1X)" class="fy-lwzomh"/></g><g filter="url(#ivh5pVd)"><path fill="url(#i6UMSte)" class="ho6xyol7i"/><path fill="url(#iINqNTm)" class="ho6xyol7i"/></g><defs><radialGradient id="iumgDIe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -9.84375 23.482 28.393)" gradientUnits="userSpaceOnUse"><stop class="mqhcwabvr"/><stop offset=".895" class="n0nsa8bju"/></radialGradient><radialGradient id="ipmDzYd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.857 16.873 9.347)scale(11.1265 12.0118)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="im62pwnwd"/><stop offset="1" class="nwe3t_p9t"/></radialGradient><radialGradient id="irszlCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.71262 -6.48073 0 16 22.123)" gradientUnits="userSpaceOnUse"><stop class="fwaqju75o"/><stop offset="1" class="i3-mvu33h"/></radialGradient><radialGradient id="i3MOAve" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56141 1.88058 -1.34003 -1.82517 18.254 23.435)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="n9i0yrbsm"/><stop offset="1" class="bxhi5-c4p"/></radialGradient><radialGradient id="iXVWiWd" cx="0" cy="0" r="1" gradientTransform="matrix(.73438 2.03125 -7.22514 2.61217 14.68 21.529)" gradientUnits="userSpaceOnUse"><stop offset=".196" class="t1aptbbhu"/><stop offset="1" class="oeevhhbsa"/></radialGradient><radialGradient id="iqFLxQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71564 .7118 -.74967 -.75371 23.221 14.655)" gradientUnits="userSpaceOnUse"><stop class="k377ck8jo"/><stop offset="1" class="x101rabpv"/></radialGradient><radialGradient id="i7JWX9h" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.293 21.28)scale(2.2011)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="o4bfrybwl"/><stop offset="1" class="k3si3xnlp"/></radialGradient><radialGradient id="iFsNGde" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.715 17.502)scale(2.70721)" gradientUnits="userSpaceOnUse"><stop class="m2q2vh2sa"/><stop offset="1" class="he4p8yb1z"/></radialGradient><radialGradient id="imm4xZd" cx="0" cy="0" r="1" gradientTransform="matrix(.61549 0 0 .72614 21.665 15.025)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="k87xpnbmx"/><stop offset="1" class="nk_-g356a"/></radialGradient><radialGradient id="icF1urd" cx="0" cy="0" r="1" gradientTransform="matrix(-6.40084 .5663 -.57862 -6.54 19.71 16.358)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="c_0yu_b0g"/><stop offset="1" class="apsq0tbar"/></radialGradient><radialGradient id="itdnD4d" cx="0" cy="0" r="1" gradientTransform="matrix(-.9065 10.59379 -13.57699 -1.16176 16.899 11.904)" gradientUnits="userSpaceOnUse"><stop offset=".752" class="liypsm9hf"/><stop offset=".985" class="y00gwybat"/></radialGradient><radialGradient id="icPFO8d" cx="0" cy="0" r="1" gradientTransform="matrix(2.03447 -2.12293 1.95657 1.87505 17.86 10.594)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="m73azsb7l"/><stop offset="1" class="x1cie3bog"/></radialGradient><radialGradient id="ieFcIuN" cx="0" cy="0" r="1" gradientTransform="rotate(121.239 7.885 11.166)scale(4.45901 3.87689)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="v8wjp2hus"/><stop offset="1" class="u3cxmmb4z"/></radialGradient><radialGradient id="i4BD9Ub" cx="0" cy="0" r="1" gradientTransform="matrix(.8584 4.94563 -3.25037 .56416 11.053 9.683)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="ou2-vlbjv"/><stop offset="1" class="nz0j9tb8x"/></radialGradient><radialGradient id="inrxXKe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.65625 9.15625 0 16.243 7.933)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="txjubcblb"/><stop offset="1" class="di7h-ab4t"/></radialGradient><radialGradient id="iXlQ3uc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.23535 0 0 -1.91263 18.067 7.847)" gradientUnits="userSpaceOnUse"><stop class="vhyf4cjim"/><stop offset="1" class="xg0nuzb-l"/></radialGradient><radialGradient id="iUQRCRb" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.347 14.352)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="cltcdpbpn"/><stop offset=".902" class="av0tm7_uc"/></radialGradient><radialGradient id="ixOYXne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.559 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="g9mjpo7pf"/><stop offset="1" class="o2l1ytrej"/></radialGradient><radialGradient id="ifigOfS" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.45 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="g9mjpo7pf"/><stop offset="1" class="o2l1ytrej"/></radialGradient><radialGradient id="iN5o1fc" cx="0" cy="0" r="1" gradientTransform="matrix(.19456 -1.08993 4.30796 .769 15.981 17.167)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ay0sr9bls"/><stop offset="1" class="ytd3ey6so"/></radialGradient><radialGradient id="iC9PN3d" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.522 16.368)" gradientUnits="userSpaceOnUse"><stop class="o5qf-ej6a"/><stop offset="1" class="ilt16x1zy"/></radialGradient><radialGradient id="iM3Z6Cc" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39062 1.75486 .91253 14.9 18.753)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="qdxirobsy"/><stop offset="1" class="fjwf4gbrh"/></radialGradient><radialGradient id="iZKcQob" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.778 10.847)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="iclvvachy"/><stop offset="1" class="bc2wedbnb"/></radialGradient><radialGradient id="i0Sy9re" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.487 2.043)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="iD22qEe" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.233 9.994)" gradientUnits="userSpaceOnUse"><stop class="k3jnt_bvt"/><stop offset="1" class="khh_otzli"/></radialGradient><radialGradient id="i6UMSte" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 10.979 6.525)" gradientUnits="userSpaceOnUse"><stop class="b5e_facvp"/><stop offset="1" class="wj0_vcbzm"/></radialGradient><radialGradient id="iINqNTm" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.281 10.004)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="hfhn00bef"/><stop offset="1" class="ws75vab8k"/></radialGradient><filter id="iNziMae" width="21.451" height="8.965" x="5.65" y="20.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.396078 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24264"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.490196 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24264" result="effect2_innerShadow_3987_24264"/></filter><filter id="ifZ1WTe" width="2.689" height="2.689" x="20.081" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".1"/></filter><filter id="itAtPgb" width="2.689" height="2.689" x="9.253" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".1"/></filter><filter id="ihTxmOt" width="12.437" height="14.211" x="10.024" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.380392 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24264"/></filter><filter id="ibja3Pb" width="7.729" height="10.962" x="16.042" y="4.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".5"/></filter><filter id="ixFuYPe" width="7.108" height="9.773" x="8.357" y="5.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".5"/></filter><filter id="iXpkMlb" width="8.297" height="3.863" x="11.832" y="4.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.211765 0 0 0 0 0.109804 0 0 0 0 0.101961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24264"/></filter><filter id="izf2oTZ" width="3.829" height="3.83" x="11.59" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".25"/></filter><filter id="iKRvv8d" width="2.618" height=".92" x="12.249" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".075"/></filter><filter id="iPNlZ0A" width="2.618" height=".92" x="17.14" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".075"/></filter><filter id="iZ94pzb" width="3.122" height="4.211" x="14.143" y="13.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".25"/></filter><filter id="iPGGHvb" width="4.199" height="1.729" x="13.887" y="17.522" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".05"/></filter><filter id="ixidOcT" width="3.191" height="1.873" x="11.514" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.129412 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24264"/></filter><filter id="iMU3zpd" width="3.191" height="1.873" x="17.405" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.239216 0 0 0 0 0.129412 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24264"/></filter><filter id="iAcrTMs" width="3.085" height="1.469" x="17.433" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".15"/></filter><filter id="ioPuxVP" width="3.085" height="1.469" x="11.492" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".15"/></filter><filter id="ivkGmZd" width="6.686" height="12.903" x="8.567" y="1.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.560784 0 0 0 0 0.407843 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24264"/></filter><filter id="iDHg1Wd" width="6.436" height="12.953" x="17.208" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24264"/></filter><filter id="iwcQxXc" width="6.436" height="12.953" x="17.208" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.309804 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24264"/></filter><filter id="ibf4zEn" width="5.843" height="12.292" x="17.799" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".25"/></filter><filter id="i0z7ppe" width="2.811" height="6.368" x="8.687" y="8.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".375"/></filter><filter id="ivh5pVd" width="5.14" height="8.355" x="9.641" y="2.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24264" stdDeviation=".25"/></filter><linearGradient id="i4unVWb" x1="14.916" x2="12.475" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="t94urlgya"/><stop offset=".32" class="zhq7idx2s"/><stop offset=".794" class="r8us_1bpp"/><stop offset="1" class="zfzr_2buk"/></linearGradient><linearGradient id="ipRrQmb" x1="19.807" x2="17.365" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="t94urlgya"/><stop offset=".32" class="zhq7idx2s"/><stop offset=".794" class="r8us_1bpp"/><stop offset="1" class="zfzr_2buk"/></linearGradient><linearGradient id="iI88bWd" x1="16.866" x2="15.829" y1="15.9" y2="15.95" gradientUnits="userSpaceOnUse"><stop offset=".106" class="usxz2na_s"/><stop offset="1" class="n0s808buc"/></linearGradient><linearGradient id="iv8Tjue" x1="19.961" x2="16.539" y1="12.628" y2="12.154" gradientUnits="userSpaceOnUse"><stop class="hvn22cohq"/><stop offset="1" class="zl4b6zbfg"/></linearGradient><linearGradient id="ihhKjwc" x1="14.008" x2="11.43" y1="12.059" y2="13.326" gradientUnits="userSpaceOnUse"><stop class="hvn22cohq"/><stop offset="1" class="zl4b6zbfg"/></linearGradient><linearGradient id="izctZ1X" x1="10.093" x2="10.093" y1="13.506" y2="8.675" gradientUnits="userSpaceOnUse"><stop class="k1tnctvtk"/><stop offset="1" class="ejsfj0d0t"/><stop offset="1" class="hlfpu6bzn"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-massage-medium" /></template>
<style>
.a1-vqmk_q {
  cx: 21.426px;
  cy: 14.831px;
  r: 1.145px;
}

.a7__jtqji {
  d: path("M15.98 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .536-.73l-.678-2.14a.375.375 0 0 0-.358-.263");
}

.apsq0tbar {
  stop-color: var(--svg-color--926762, #926762);
}

.av0tm7_uc {
  stop-color: var(--svg-color--8a5960, #8A5960);
}

.ay0sr9bls {
  stop-color: var(--svg-color--985c6e, #985C6E);
}

.b5e_facvp {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
}

.b9onc53-n {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.bc2wedbnb {
  stop-color: var(--svg-color--986c68, #986C68);
  stop-opacity: 0;
}

.bflc-9bzd {
  fill: var(--svg-color--a87873, #A87873);
  d: path("M13.742 20.41a2.256 2.256 0 0 1 4.512 0v2.102c0 1.245-1.588 1.624-2.256 1.624c-.766 0-2.256-.378-2.256-1.624z");
}

.bxhi5-c4p {
  stop-color: var(--svg-color--bd9482, #BD9482);
  stop-opacity: 0;
}

.c_0yu_b0g {
  stop-color: var(--svg-color--bd9076, #BD9076);
}

.cfc3_obcp {
  fill: var(--svg-color--4b2f2c, #4B2F2C);
  fill-rule: evenodd;
  d: path("M13.932 12.787c-.86-.117-1.389.27-1.521.378a.55.55 0 1 1-.693-.855c.253-.205 1.08-.787 2.361-.614a.55.55 0 1 1-.147 1.09");
}

.ckkaoubhy {
  cx: 21.426px;
  cy: 14.831px;
  r: 1.859px;
}

.cltcdpbpn {
  stop-color: var(--svg-color--996e64, #996E64);
}

.d0lldcbqg {
  d: path("M22.77 7.736h-3.172V5.932c0 .352-.21 1.036-.633 1.43a77 77 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.715c.42.428 1.009.362 1.439-.055l.906-.74a.464.464 0 0 1 .691.044c.08.096.123.22.123.35v3.327c0 .662.497 1.199 1.11 1.199s1.111-.537 1.111-1.2z");
}

.di7h-ab4t {
  stop-color: var(--svg-color--5d423f, #5D423F);
}

.ejsfj0d0t {
  stop-color: var(--svg-color--886361, #886361);
  stop-opacity: 0;
}

.er1ho7c5g {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.942 12.628c.193-.156 1.045-.633 2.186-.562");
}

.fjwf4gbrh {
  stop-color: var(--svg-color--aa827c, #AA827C);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwaqju75o {
  stop-color: var(--svg-color--215286, #215286);
}

.fy-lwzomh {
  d: path("m9.437 9.42l1.311.78v3.433a.656.656 0 0 1-1.31 0z");
}

.g-mr_sgso {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.475 14.394c.145.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.g4mky1b_b {
  d: path("M8.567 2.19h3.426v3.742c0 .352.227 1.036.684 1.43c.375.348 1.095 1.06 1.727 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.g9mjpo7pf {
  stop-color: var(--svg-color--452537, #452537);
}

.he4p8yb1z {
  stop-color: var(--svg-color--824d5a, #824D5A);
}

.hfhn00bef {
  stop-color: var(--svg-color--c29b87, #C29B87);
}

.hlfpu6bzn {
  stop-color: var(--svg-color--b78b7f, #B78B7F);
  stop-opacity: 0;
}

.ho6xyol7i {
  d: path("M10.142 5.548v-2.9h1.468v3.535a1 1 0 0 0 .28.694l2.263 2.348a.46.46 0 0 1-.636.663l-2.365-2.094a3 3 0 0 1-1.01-2.246");
}

.hvn22cohq {
  stop-color: var(--svg-color--5d4646, #5D4646);
}

.hx3atwwaa {
  fill: var(--svg-color--8d5e5f, #8D5E5F);
  d: path("M15.852 14.12c-.163 0-.247.093-.296.254l-.887 2.205a.59.59 0 0 0 .112.554c.106.126.26.198.422.198h1a.55.55 0 0 0 .424-.198a.59.59 0 0 0 .112-.554l-.678-2.205c-.049-.16-.045-.254-.209-.254");
}

.i3-mvu33h {
  stop-color: var(--svg-color--2b7fd5, #2B7FD5);
  stop-opacity: 0;
}

.i5i_8mxsj {
  d: path("M10.375 18.167c.14 1.625.594 3.688 3.594 3.883a64 64 0 0 0 1.984.039h.078c.251 0 1.032-.005 1.985-.039c3-.195 3.453-2.258 3.594-3.883l.492-9.523a31 31 0 0 0-6.07-.765h-.079a31 31 0 0 0-6.07.765z");
}

.iclvvachy {
  stop-color: var(--svg-color--7d4755, #7D4755);
}

.ilt16x1zy {
  stop-color: var(--svg-color--be9586, #BE9586);
  stop-opacity: 0;
}

.im62pwnwd {
  stop-color: var(--svg-color--429efa, #429EFA);
}

.j_br2k90i {
  cx: 10.598px;
  cy: 14.831px;
  r: 1.145px;
  fill: var(--svg-color--734743, #734743);
}

.jednjgv3t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.365 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.k1tnctvtk {
  stop-color: var(--svg-color--b78b7f, #B78B7F);
}

.k377ck8jo {
  stop-color: var(--svg-color--c19883, #C19883);
}

.k3jnt_bvt {
  stop-color: var(--svg-color--bf9886, #BF9886);
}

.k3si3xnlp {
  stop-color: var(--svg-color--9e625e, #9E625E);
}

.k87xpnbmx {
  stop-color: var(--svg-color--ae8472, #AE8472);
}

.khh_otzli {
  stop-color: var(--svg-color--bf9886, #BF9886);
  stop-opacity: 0;
}

.ksg73c-ow {
  fill: var(--svg-color--4b2f2c, #4B2F2C);
  fill-rule: evenodd;
  d: path("M18.029 12.787c.86-.117 1.389.27 1.521.378a.55.55 0 1 0 .693-.855c-.253-.205-1.08-.787-2.362-.614a.55.55 0 1 0 .148 1.09");
}

.l8jusdr6y {
  d: path("M5.65 29.81h20.7c-.493-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.664");
}

.liypsm9hf {
  stop-color: var(--svg-color--996275, #996275);
  stop-opacity: 0;
}

.ls65_6i-s {
  d: path("M9.357 6.856h2.83v.372c0 .291.187.855.564 1.181c.31.287.905.876 1.426 1.398a.987.987 0 0 1-.021 1.415c-.375.354-.899.3-1.282-.045l-.81-.61a.436.436 0 0 0-.726.324v2.748a.99.99 0 1 1-1.98 0z");
}

.m1aembrxw {
  fill: var(--svg-color--a47a6f, #A47A6F);
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.m2ddouw1w {
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.m2q2vh2sa {
  stop-color: var(--svg-color--825856, #825856);
}

.m73azsb7l {
  stop-color: var(--svg-color--9d756f, #9D756F);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqhcwabvr {
  stop-color: var(--svg-color--469afb, #469AFB);
}

.mvfxgbsxp {
  fill: var(--svg-color--a57d6b, #A57D6B);
  d: path("M15.98 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .536-.73l-.678-2.14a.375.375 0 0 0-.358-.263");
}

.n0nsa8bju {
  stop-color: var(--svg-color--2376c8, #2376C8);
}

.n0s808buc {
  stop-color: var(--svg-color--c59e88, #C59E88);
  stop-opacity: 0;
}

.n9i0yrbsm {
  stop-color: var(--svg-color--bd9482, #BD9482);
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.nk_-g356a {
  stop-color: var(--svg-color--a57460, #A57460);
}

.nwe3t_p9t {
  stop-color: var(--svg-color--429efa, #429EFA);
  stop-opacity: 0;
}

.nz0j9tb8x {
  stop-color: var(--svg-color--855b55, #855B55);
}

.o2l1ytrej {
  stop-color: var(--svg-color--4b302e, #4B302E);
}

.o4bfrybwl {
  stop-color: var(--svg-color--9e625e, #9E625E);
  stop-opacity: 0;
}

.o5qf-ej6a {
  stop-color: var(--svg-color--be9586, #BE9586);
}

.oeevhhbsa {
  stop-color: var(--svg-color--7d4c5a, #7D4C5A);
  stop-opacity: 0;
}

.ok5p-1b6w {
  fill: var(--svg-color--a47b6d, #A47B6D);
  d: path("M8.567 2.19h3.426v3.742c0 .352.227 1.036.684 1.43c.375.348 1.095 1.06 1.727 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.ou2-vlbjv {
  stop-color: var(--svg-color--4e2c2d, #4E2C2D);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.q008c2b7r {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.337 17.742c.345.18.879.384 1.65.384s1.304-.204 1.648-.384c.108-.056.242.013.25.135a.2.2 0 0 1-.015.077c-.76 1.471-3.065 1.456-3.768 0a.15.15 0 0 1-.015-.077c.008-.122.142-.191.25-.135Z");
}

.qdxirobsy {
  stop-color: var(--svg-color--aa827c, #AA827C);
}

.qvye139vd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.365 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.r8us_1bpp {
  stop-color: var(--svg-color--4b3135, #4B3135);
}

.rzrvnhrdd {
  d: path("M10.375 18.167c.14 1.625.594 3.688 3.594 3.883a64 64 0 0 0 1.984.039h.078c.251 0 1.032-.005 1.985-.039c3-.195 3.453-2.258 3.594-3.883l.346-6.713c.085-1.627-1.008-3.096-2.622-3.31a30 30 0 0 0-3.303-.265h-.078a30 30 0 0 0-3.302.264c-1.615.215-2.707 1.684-2.623 3.311z");
}

.s5rkt_jwe {
  fill: var(--svg-color--88004e, #88004E);
  d: path("M14.337 17.742c.345.18.879.384 1.65.384s1.304-.204 1.648-.384c.108-.056.242.013.25.135a.2.2 0 0 1-.015.077c-.76 1.471-3.065 1.456-3.768 0a.15.15 0 0 1-.015-.077c.008-.122.142-.191.25-.135");
}

.t1aptbbhu {
  stop-color: var(--svg-color--7d4c5a, #7D4C5A);
}

.t94urlgya {
  stop-color: var(--svg-color--584141, #584141);
}

.tr559m5ue {
  cx: 10.598px;
  cy: 14.831px;
  r: 1.859px;
}

.tx_btybwx {
  d: path("M13.742 20.41a2.256 2.256 0 0 1 4.512 0v2.102c0 1.245-1.588 1.624-2.256 1.624c-.766 0-2.256-.378-2.256-1.624z");
}

.txjubcblb {
  stop-color: var(--svg-color--4f3332, #4F3332);
}

.u3cxmmb4z {
  stop-color: var(--svg-color--7a4d53, #7A4D53);
}

.usxz2na_s {
  stop-color: var(--svg-color--c59e88, #C59E88);
}

.v8wjp2hus {
  stop-color: var(--svg-color--563233, #563233);
}

.vh3837gtk {
  cx: 13.505px;
  cy: 13.651px;
  r: 1.415px;
}

.vhyf4cjim {
  stop-color: var(--svg-color--5e4243, #5E4243);
}

.wj0_vcbzm {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
  stop-opacity: 0;
}

.ws75vab8k {
  stop-color: var(--svg-color--c29b87, #C29B87);
  stop-opacity: 0;
}

.wupazrada {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.475 14.394c.145.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.x101rabpv {
  stop-color: var(--svg-color--b28278, #B28278);
}

.x1cie3bog {
  stop-color: var(--svg-color--9d756f, #9D756F);
  stop-opacity: 0;
}

.xg0nuzb-l {
  stop-color: var(--svg-color--5e4243, #5E4243);
  stop-opacity: 0;
}

.y00gwybat {
  stop-color: var(--svg-color--7c5165, #7C5165);
}

.ytd3ey6so {
  stop-color: var(--svg-color--985c6e, #985C6E);
  stop-opacity: 0;
}

.zfzr_2buk {
  stop-color: var(--svg-color--564040, #564040);
}

.zgqgadcdt {
  d: path("m21.088 8.54l-2.02 1.489c-.245.18-.472.419-.678.196c-.219-.238-.006-.338.23-.56a52 52 0 0 1 1.99-1.786c.875-.733.849-2.108.828-2.57V2.732h1.704v10.713a.579.579 0 0 1-1.158 0V9.208c0-.403-.572-.906-.896-.668");
}

.zhq7idx2s {
  stop-color: var(--svg-color--503839, #503839);
}

.zl4b6zbfg {
  stop-color: var(--svg-color--5d4646, #5D4646);
  stop-opacity: 0;
}

.zm_gnnmci {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.068 12.628c-.193-.156-1.044-.633-2.185-.562");
}

.zsr0l3b0d {
  d: path("M12.015 6.056c.242-.225.546-.508.707-.635l.04-.031c.27-.217.803-.643 2.007-.375c.297.064.506.114.664.151c.282.068.397.095.547.095s.266-.027.548-.095c.158-.037.367-.087.663-.151c1.205-.268 1.737.158 2.008.375l.04.031c.16.127.464.41.707.635l.183.17l-.492 2.316c-2.352-.281-5.024-.265-7.313 0l-.492-2.316z");
}

</style>
