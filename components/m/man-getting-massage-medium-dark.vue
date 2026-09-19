<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLTlU7b)"><path fill="url(#iumgDIe)" class="l8jusdr6y"/><path fill="url(#ipmDzYd)" class="l8jusdr6y"/><path fill="url(#irszlCe)" class="l8jusdr6y"/></g><path class="p-p2qp4er"/><path fill="url(#i4hIRmd)" class="tx_btybwx"/><path fill="url(#iIPwcob)" class="tx_btybwx"/><circle fill="url(#iW0BFMc)" class="ckkaoubhy"/><circle fill="url(#iBmSuve)" class="ckkaoubhy"/><circle fill="url(#iLIrFjd)" class="tr559m5ue"/><g filter="url(#idcHuYd)"><circle fill="url(#i1NheEb)" class="a1-vqmk_q"/></g><g filter="url(#i3Sf8Eb)" class="mc2zb0bvp"><circle class="gwq04-bxs"/></g><g filter="url(#iKLbK7c)"><path fill="url(#i6OYsGc)" class="i5i_8mxsj"/></g><path fill="url(#imrHbec)" class="i5i_8mxsj"/><path fill="url(#iAB7cMd)" class="i5i_8mxsj"/><g filter="url(#i4WzWWd)"><path class="y4-l8htii"/></g><g filter="url(#irJSNbc)"><path fill="url(#iXdZXTd)" class="ls65_6i-s"/><path class="mow9wsjnx"/></g><g filter="url(#iAuPQ2o)"><path fill="url(#iWrUlNd)" class="y0ah3rb0p"/><path fill="url(#ixxE1qc)" class="y0ah3rb0p"/></g><g filter="url(#ir8pIqd)"><circle fill="url(#iDO2cAd)" class="vh3837gtk"/></g><path stroke="url(#isgXGzN)" class="wupazrada"/><g filter="url(#itCRWBc)"><path stroke="url(#ijVeiOb)" class="g-mr_sgso"/></g><path stroke="url(#iQoPhCK)" class="qvye139vd"/><g filter="url(#iezCm4b)"><path stroke="url(#iCyus8b)" class="jednjgv3t"/></g><g filter="url(#iaVBsJd)"><path class="qmlpcoaqv"/></g><path class="i0wsvfbpl"/><path fill="url(#i89kQab)" class="a7__jtqji"/><path fill="url(#ilvkEme)" class="a7__jtqji"/><path fill="url(#iZj06XH)" class="a7__jtqji"/><g filter="url(#ifRNlFK)"><path stroke="url(#iA8yELG)" class="phcbxnb1c"/></g><path class="oqgeicb9d"/><g filter="url(#irL9ZDd)"><path clip-rule="evenodd" class="ahkluobut"/></g><g filter="url(#i5QbHla)"><path clip-rule="evenodd" class="x_fn6obii"/></g><g filter="url(#ia7madd)"><path class="ybddoqb1e"/></g><g filter="url(#iYaioVc)"><path class="y24jvv7lv"/></g><g filter="url(#ib29yLb)"><path class="x6_039gpw"/><path fill="url(#iX8r0Yf)" class="g4mky1b_b"/></g><g filter="url(#isSHrLd)"><path class="b9onc53-n"/><path fill="url(#i0Sy9re)" class="m2ddouw1w"/></g><g filter="url(#iDaodcc)"><path class="c_fuwzbbs"/></g><g filter="url(#iXAJJDb)"><path fill="url(#iDM5nqd)" class="zgqgadcdt"/></g><g filter="url(#iYsG5Ib)"><path fill="url(#iYWvKyb)" class="fy-lwzomh"/></g><g filter="url(#ibSeWDM)"><path fill="url(#iEa9O9d)" class="ho6xyol7i"/><path fill="url(#icbOyEb)" class="ho6xyol7i"/></g><defs><radialGradient id="iumgDIe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -9.84375 23.482 28.393)" gradientUnits="userSpaceOnUse"><stop class="mqhcwabvr"/><stop offset=".895" class="n0nsa8bju"/></radialGradient><radialGradient id="ipmDzYd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.857 16.873 9.347)scale(11.1265 12.0118)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="im62pwnwd"/><stop offset="1" class="nwe3t_p9t"/></radialGradient><radialGradient id="irszlCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.71262 -6.48073 0 16 22.123)" gradientUnits="userSpaceOnUse"><stop class="fwaqju75o"/><stop offset="1" class="i3-mvu33h"/></radialGradient><radialGradient id="i4hIRmd" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.115 14.8)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="wzapgli4e"/><stop offset="1" class="vnuk5ibgy"/></radialGradient><radialGradient id="iIPwcob" cx="0" cy="0" r="1" gradientTransform="rotate(69.595 -8.308 21.25)scale(2.36836 7.70153)" gradientUnits="userSpaceOnUse"><stop class="tm33mubmc"/><stop offset="1" class="fxldz-box"/></radialGradient><radialGradient id="iW0BFMc" cx="0" cy="0" r="1" gradientTransform="matrix(-.88839 .69015 -.72686 -.93565 23.221 14.655)" gradientUnits="userSpaceOnUse"><stop class="s9x1nlbef"/><stop offset="1" class="xo4w8qb_a"/></radialGradient><radialGradient id="iBmSuve" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.293 21.28)scale(2.2011)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="w08_jhbkt"/><stop offset="1" class="etv5nzb3o"/></radialGradient><radialGradient id="iLIrFjd" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.715 17.502)scale(2.70721)" gradientUnits="userSpaceOnUse"><stop class="p236k5fti"/><stop offset="1" class="g2vlv9bfh"/></radialGradient><radialGradient id="i1NheEb" cx="0" cy="0" r="1" gradientTransform="matrix(.61549 0 0 .72614 21.665 15.025)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="gq6390b8n"/><stop offset="1" class="htw9qedrj"/></radialGradient><radialGradient id="i6OYsGc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.40084 .5663 -.57862 -6.54 19.71 16.358)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="xrik-2bjb"/><stop offset="1" class="x6-sayl6h"/></radialGradient><radialGradient id="imrHbec" cx="0" cy="0" r="1" gradientTransform="scale(13.0818 10.2074)rotate(90 .02 1.203)" gradientUnits="userSpaceOnUse"><stop offset=".805" class="swoco4bnz"/><stop offset="1" class="yji19nb-g"/></radialGradient><radialGradient id="iAB7cMd" cx="0" cy="0" r="1" gradientTransform="matrix(2.03447 -2.12293 1.95657 1.87505 17.86 10.594)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="l6go20bgd"/><stop offset="1" class="llxs48b2m"/></radialGradient><radialGradient id="iXdZXTd" cx="0" cy="0" r="1" gradientTransform="matrix(.87207 1.75 -1.15013 .57314 11.04 9.878)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="iWrUlNd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.65625 9.15625 0 16.243 7.933)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="q35-e_btj"/><stop offset="1" class="len1xsbgs"/><stop offset="1" class="s8qkyd19g"/></radialGradient><radialGradient id="ixxE1qc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.23535 0 0 -1.91263 18.067 7.847)" gradientUnits="userSpaceOnUse"><stop class="kkc30k1du"/><stop offset="1" class="o-y-c8bpy"/></radialGradient><radialGradient id="iDO2cAd" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.347 14.352)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="q_zq8lcfj"/><stop offset=".902" class="ru61jfres"/></radialGradient><radialGradient id="isgXGzN" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.559 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="tf917uigd"/><stop offset="1" class="e974r34pq"/></radialGradient><radialGradient id="iQoPhCK" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.45 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="tf917uigd"/><stop offset="1" class="e974r34pq"/></radialGradient><radialGradient id="ilvkEme" cx="0" cy="0" r="1" gradientTransform="matrix(.19456 -1.08993 4.30796 .769 15.981 17.167)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="w0_gpw3io"/><stop offset="1" class="kf-afnfjo"/></radialGradient><radialGradient id="iZj06XH" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.522 16.368)" gradientUnits="userSpaceOnUse"><stop class="cbh83mbyh"/><stop offset="1" class="hnph1r6ss"/></radialGradient><radialGradient id="iA8yELG" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39062 1.75486 .91253 14.9 18.753)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="chi8d6bxi"/><stop offset="1" class="y34pxebel"/></radialGradient><radialGradient id="iX8r0Yf" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.778 10.847)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="l25dhacin"/><stop offset="1" class="o0smz_bvt"/></radialGradient><radialGradient id="i0Sy9re" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.487 2.043)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="iDM5nqd" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.233 9.994)" gradientUnits="userSpaceOnUse"><stop class="txpy_zznj"/><stop offset="1" class="vfm0_vraw"/><stop offset="1" class="l5m7qflal"/></radialGradient><radialGradient id="iEa9O9d" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 10.979 6.525)" gradientUnits="userSpaceOnUse"><stop class="l714dnucg"/><stop offset="1" class="mzzxgdkuh"/></radialGradient><radialGradient id="icbOyEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.281 10.004)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="qhhfhnb7p"/><stop offset="1" class="c0ejuub7c"/></radialGradient><filter id="iLTlU7b" width="21.451" height="8.965" x="5.65" y="20.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.396078 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24261"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.490196 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24261" result="effect2_innerShadow_3987_24261"/></filter><filter id="idcHuYd" width="2.689" height="2.689" x="20.081" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".1"/></filter><filter id="i3Sf8Eb" width="2.689" height="2.689" x="9.253" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".1"/></filter><filter id="iKLbK7c" width="12.719" height="14.211" x="9.883" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.380392 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24261"/></filter><filter id="i4WzWWd" width="7.729" height="10.962" x="16.042" y="4.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".5"/></filter><filter id="irJSNbc" width="7.108" height="9.773" x="8.357" y="5.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".5"/></filter><filter id="iAuPQ2o" width="8.297" height="3.863" x="11.832" y="4.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.101961 0 0 0 0 0.027451 0 0 0 0 0.054902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24261"/></filter><filter id="ir8pIqd" width="3.829" height="3.83" x="11.59" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".25"/></filter><filter id="itCRWBc" width="2.618" height=".92" x="12.249" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".075"/></filter><filter id="iezCm4b" width="2.618" height=".92" x="17.14" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".075"/></filter><filter id="iaVBsJd" width="3.122" height="4.211" x="14.143" y="13.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".25"/></filter><filter id="ifRNlFK" width="4.199" height="1.729" x="13.887" y="17.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".05"/></filter><filter id="irL9ZDd" width="3.191" height="1.873" x="11.514" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24261"/></filter><filter id="i5QbHla" width="3.191" height="1.873" x="17.405" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.12549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24261"/></filter><filter id="ia7madd" width="3.085" height="1.469" x="17.433" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".15"/></filter><filter id="iYaioVc" width="3.085" height="1.469" x="11.492" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".15"/></filter><filter id="ib29yLb" width="6.686" height="12.903" x="8.567" y="1.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.454902 0 0 0 0 0.27451 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24261"/></filter><filter id="isSHrLd" width="6.436" height="12.953" x="17.208" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24261"/></filter><filter id="iDaodcc" width="6.436" height="12.953" x="17.208" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.415686 0 0 0 0 0.227451 0 0 0 0 0.270588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24261"/></filter><filter id="iXAJJDb" width="5.843" height="12.292" x="17.799" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".25"/></filter><filter id="iYsG5Ib" width="2.811" height="6.368" x="8.687" y="8.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".375"/></filter><filter id="ibSeWDM" width="5.14" height="8.355" x="9.641" y="2.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24261" stdDeviation=".25"/></filter><linearGradient id="ijVeiOb" x1="14.916" x2="12.475" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="m97csacbr"/><stop offset=".32" class="ppgoehb9j"/><stop offset=".794" class="ppgoehb9j"/><stop offset="1" class="hxk020qex"/></linearGradient><linearGradient id="iCyus8b" x1="19.807" x2="17.365" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="m97csacbr"/><stop offset=".32" class="ppgoehb9j"/><stop offset=".794" class="ppgoehb9j"/><stop offset="1" class="hxk020qex"/></linearGradient><linearGradient id="i89kQab" x1="16.866" x2="15.829" y1="15.9" y2="15.95" gradientUnits="userSpaceOnUse"><stop offset=".106" class="gt5mw9brj"/><stop offset="1" class="wmgou6bmf"/></linearGradient><linearGradient id="iYWvKyb" x1="10.093" x2="10.093" y1="13.506" y2="8.675" gradientUnits="userSpaceOnUse"><stop class="n7gad4bzu"/><stop offset="1" class="ejsfj0d0t"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-massage-medium-dark" /></template>
<style>
.a1-vqmk_q {
  cx: 21.426px;
  cy: 14.831px;
  r: 1.145px;
}

.a7__jtqji {
  d: path("M15.98 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .536-.73l-.678-2.14a.375.375 0 0 0-.358-.263");
}

.ahkluobut {
  fill: var(--svg-color--312120, #312120);
  fill-rule: evenodd;
  d: path("M13.932 12.787c-.86-.117-1.389.27-1.521.378a.55.55 0 1 1-.693-.855c.253-.205 1.08-.787 2.361-.614a.55.55 0 1 1-.147 1.09");
}

.b9onc53-n {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.c_fuwzbbs {
  fill: var(--svg-color--764e49, #764E49);
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.c0ejuub7c {
  stop-color: var(--svg-color--9a7b72, #9A7B72);
  stop-opacity: 0;
}

.cbh83mbyh {
  stop-color: var(--svg-color--97736e, #97736E);
}

.chi8d6bxi {
  stop-color: var(--svg-color--886667, #886667);
}

.ckkaoubhy {
  cx: 21.426px;
  cy: 14.831px;
  r: 1.859px;
}

.e974r34pq {
  stop-color: var(--svg-color--392c2b, #392C2B);
}

.ejsfj0d0t {
  stop-color: var(--svg-color--886361, #886361);
  stop-opacity: 0;
}

.etv5nzb3o {
  stop-color: var(--svg-color--7e4950, #7E4950);
}

.f7m1yfx-m {
  stop-color: var(--svg-color--9b4607, #9B4607);
}

.ft5dv1b6b {
  fill: none;
}

.fwaqju75o {
  stop-color: var(--svg-color--215286, #215286);
}

.fxldz-box {
  stop-color: var(--svg-color--5f333f, #5F333F);
  stop-opacity: 0;
}

.fy-lwzomh {
  d: path("m9.437 9.42l1.311.78v3.433a.656.656 0 0 1-1.31 0z");
}

.g-mr_sgso {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.475 14.394c.145.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.g2vlv9bfh {
  stop-color: var(--svg-color--653747, #653747);
}

.g4mky1b_b {
  d: path("M8.567 2.19h3.426v3.742c0 .352.227 1.036.684 1.43c.375.348 1.095 1.06 1.727 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.gq6390b8n {
  stop-color: var(--svg-color--815f57, #815F57);
}

.gt5mw9brj {
  stop-color: var(--svg-color--98746c, #98746C);
}

.gwq04-bxs {
  cx: 10.598px;
  cy: 14.831px;
  r: 1.145px;
  fill: var(--svg-color--593138, #593138);
}

.hnph1r6ss {
  stop-color: var(--svg-color--97736e, #97736E);
  stop-opacity: 0;
}

.ho6xyol7i {
  d: path("M10.142 5.548v-2.9h1.468v3.535a1 1 0 0 0 .28.694l2.263 2.348a.46.46 0 0 1-.636.663l-2.365-2.094a3 3 0 0 1-1.01-2.246");
}

.htw9qedrj {
  stop-color: var(--svg-color--7d5047, #7D5047);
}

.hxk020qex {
  stop-color: var(--svg-color--3d3133, #3D3133);
}

.i0wsvfbpl {
  fill: var(--svg-color--7e554d, #7E554D);
  d: path("M15.98 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .536-.73l-.678-2.14a.375.375 0 0 0-.358-.263");
}

.i3-mvu33h {
  stop-color: var(--svg-color--2b7fd5, #2B7FD5);
  stop-opacity: 0;
}

.i5i_8mxsj {
  d: path("M10.375 18.167c.14 1.625.594 3.688 3.594 3.883a64 64 0 0 0 1.984.039h.078c.251 0 1.032-.005 1.985-.039c3-.195 3.453-2.258 3.594-3.883l.492-9.523a31 31 0 0 0-6.07-.765h-.079a31 31 0 0 0-6.07.765z");
}

.im62pwnwd {
  stop-color: var(--svg-color--429efa, #429EFA);
}

.jednjgv3t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.365 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.kf-afnfjo {
  stop-color: var(--svg-color--7e4757, #7E4757);
  stop-opacity: 0;
}

.kkc30k1du {
  stop-color: var(--svg-color--3e3035, #3E3035);
}

.l25dhacin {
  stop-color: var(--svg-color--673742, #673742);
}

.l5m7qflal {
  stop-color: var(--svg-color--906f68, #906F68);
  stop-opacity: 0;
}

.l6go20bgd {
  stop-color: var(--svg-color--836461, #836461);
}

.l714dnucg {
  stop-color: var(--svg-color--a07e73, #A07E73);
}

.l8jusdr6y {
  d: path("M5.65 29.81h20.7c-.493-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.664");
}

.len1xsbgs {
  stop-color: var(--svg-color--383335, #383335);
}

.llxs48b2m {
  stop-color: var(--svg-color--836461, #836461);
  stop-opacity: 0;
}

.ls65_6i-s {
  d: path("M9.357 6.856h2.83v.372c0 .291.187.855.564 1.181c.31.287.905.876 1.426 1.398a.987.987 0 0 1-.021 1.415c-.375.354-.899.3-1.282-.045l-.81-.61a.436.436 0 0 0-.726.324v2.748a.99.99 0 1 1-1.98 0z");
}

.m2ddouw1w {
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.m97csacbr {
  stop-color: var(--svg-color--44393a, #44393A);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mow9wsjnx {
  fill: var(--svg-color--3c1b1c, #3C1B1C);
  d: path("M9.357 6.856h2.83v.372c0 .291.187.855.564 1.181c.31.287.905.876 1.426 1.398a.987.987 0 0 1-.021 1.415c-.375.354-.899.3-1.282-.045l-.81-.61a.436.436 0 0 0-.726.324v2.748a.99.99 0 1 1-1.98 0z");
}

.mqhcwabvr {
  stop-color: var(--svg-color--469afb, #469AFB);
}

.mzzxgdkuh {
  stop-color: var(--svg-color--a07e73, #A07E73);
  stop-opacity: 0;
}

.n0nsa8bju {
  stop-color: var(--svg-color--2376c8, #2376C8);
}

.n7gad4bzu {
  stop-color: var(--svg-color--886361, #886361);
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.nwe3t_p9t {
  stop-color: var(--svg-color--429efa, #429EFA);
  stop-opacity: 0;
}

.o-y-c8bpy {
  stop-color: var(--svg-color--3d3035, #3D3035);
  stop-opacity: 0;
}

.o0smz_bvt {
  stop-color: var(--svg-color--754d4c, #754D4C);
  stop-opacity: 0;
}

.oqgeicb9d {
  fill: var(--svg-color--87004d, #87004D);
  d: path("M14.337 17.742c.345.18.879.384 1.65.384s1.304-.203 1.648-.384c.108-.056.242.014.25.135a.2.2 0 0 1-.015.077c-.76 1.471-3.065 1.456-3.768 0a.15.15 0 0 1-.015-.077c.008-.121.142-.191.25-.135");
}

.p-p2qp4er {
  fill: var(--svg-color--824f50, #824F50);
  d: path("M13.742 20.41a2.256 2.256 0 0 1 4.512 0v2.102c0 1.245-1.588 1.624-2.256 1.624c-.766 0-2.256-.378-2.256-1.624z");
}

.p236k5fti {
  stop-color: var(--svg-color--643e41, #643E41);
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.phcbxnb1c {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.337 17.742c.345.18.879.384 1.65.384s1.304-.203 1.648-.384c.108-.056.242.014.25.135a.2.2 0 0 1-.015.077c-.76 1.471-3.065 1.456-3.768 0a.15.15 0 0 1-.015-.077c.008-.121.142-.191.25-.135Z");
}

.ppgoehb9j {
  stop-color: var(--svg-color--3b2e30, #3B2E30);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.q_zq8lcfj {
  stop-color: var(--svg-color--724b4a, #724B4A);
}

.q35-e_btj {
  stop-color: var(--svg-color--2b181f, #2B181F);
}

.qhhfhnb7p {
  stop-color: var(--svg-color--9a7b72, #9A7B72);
}

.qmlpcoaqv {
  fill: var(--svg-color--76434f, #76434F);
  d: path("M15.852 14.12c-.163 0-.247.093-.296.254l-.887 2.205a.59.59 0 0 0 .112.554c.106.126.26.198.422.198h1a.55.55 0 0 0 .424-.198a.59.59 0 0 0 .112-.554l-.678-2.205c-.049-.16-.045-.254-.209-.254");
}

.qvye139vd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.365 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.ru61jfres {
  stop-color: var(--svg-color--6c3e49, #6C3E49);
}

.s8qkyd19g {
  stop-color: var(--svg-color--3f3638, #3F3638);
}

.s9x1nlbef {
  stop-color: var(--svg-color--93736a, #93736A);
}

.swoco4bnz {
  stop-color: var(--svg-color--724158, #724158);
  stop-opacity: 0;
}

.tf917uigd {
  stop-color: var(--svg-color--2f182c, #2F182C);
}

.tm33mubmc {
  stop-color: var(--svg-color--5f333f, #5F333F);
}

.tr559m5ue {
  cx: 10.598px;
  cy: 14.831px;
  r: 1.859px;
}

.tx_btybwx {
  d: path("M13.742 20.41a2.256 2.256 0 0 1 4.512 0v2.102c0 1.245-1.588 1.624-2.256 1.624c-.766 0-2.256-.378-2.256-1.624z");
}

.txpy_zznj {
  stop-color: var(--svg-color--906f68, #906F68);
}

.vfm0_vraw {
  stop-color: var(--svg-color--675553, #675553);
  stop-opacity: 0;
}

.vh3837gtk {
  cx: 13.505px;
  cy: 13.651px;
  r: 1.415px;
}

.vnuk5ibgy {
  stop-color: var(--svg-color--9a6c63, #9A6C63);
  stop-opacity: 0;
}

.w0_gpw3io {
  stop-color: var(--svg-color--7e4757, #7E4757);
}

.w08_jhbkt {
  stop-color: var(--svg-color--7e4950, #7E4950);
  stop-opacity: 0;
}

.wmgou6bmf {
  stop-color: var(--svg-color--98746c, #98746C);
  stop-opacity: 0;
}

.wupazrada {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.475 14.394c.145.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.wzapgli4e {
  stop-color: var(--svg-color--9a6c63, #9A6C63);
}

.x_fn6obii {
  fill: var(--svg-color--312120, #312120);
  fill-rule: evenodd;
  d: path("M18.029 12.787c.86-.117 1.389.27 1.521.378a.55.55 0 1 0 .693-.855c-.253-.205-1.08-.787-2.362-.614a.55.55 0 1 0 .148 1.09");
}

.x6_039gpw {
  fill: var(--svg-color--845a56, #845A56);
  d: path("M8.567 2.19h3.426v3.742c0 .352.227 1.036.684 1.43c.375.348 1.095 1.06 1.727 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.x6-sayl6h {
  stop-color: var(--svg-color--734c49, #734C49);
}

.xo4w8qb_a {
  stop-color: var(--svg-color--815457, #815457);
}

.xrik-2bjb {
  stop-color: var(--svg-color--93655a, #93655A);
}

.y0ah3rb0p {
  d: path("M12.015 6.056c.242-.225.546-.507.707-.635l.04-.03c.27-.218.803-.644 2.007-.376c.297.064.506.114.664.152c.282.067.397.094.547.094s.266-.027.548-.094c.158-.038.367-.088.663-.152c1.205-.268 1.737.158 2.008.375l.04.031c.16.128.464.41.707.635l.183.17l-.492 2.316c-2.352-.28-5.024-.265-7.313 0l-.492-2.316z");
}

.y24jvv7lv {
  stroke: var(--svg-color--463b3b, #463B3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.942 12.628c.193-.156 1.045-.632 2.186-.562");
}

.y34pxebel {
  stop-color: var(--svg-color--886667, #886667);
  stop-opacity: 0;
}

.y4-l8htii {
  fill: var(--svg-color--512e2f, #512E2F);
  d: path("M22.77 7.736h-3.172V5.932c0 .352-.21 1.036-.633 1.43a77 77 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.715c.42.428 1.009.362 1.439-.055l.906-.74a.464.464 0 0 1 .691.044c.08.096.123.22.123.35v3.327c0 .662.497 1.199 1.11 1.199s1.111-.537 1.111-1.2z");
}

.ybddoqb1e {
  stroke: var(--svg-color--463b3b, #463B3B);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.068 12.628c-.193-.156-1.044-.632-2.185-.562");
}

.yji19nb-g {
  stop-color: var(--svg-color--623b51, #623B51);
}

.zgqgadcdt {
  d: path("m21.088 8.54l-2.02 1.489c-.245.18-.472.419-.678.196c-.219-.238-.006-.338.23-.56a52 52 0 0 1 1.99-1.786c.875-.733.849-2.108.828-2.57V2.732h1.704v10.713a.579.579 0 0 1-1.158 0V9.208c0-.403-.572-.906-.896-.668");
}

</style>
