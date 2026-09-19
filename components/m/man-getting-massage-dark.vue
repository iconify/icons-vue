<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iZj6xdc)"><path fill="url(#iumgDIe)" class="l8jusdr6y"/><path fill="url(#ipmDzYd)" class="l8jusdr6y"/><path fill="url(#irszlCe)" class="l8jusdr6y"/></g><path class="ey57nhbje"/><path fill="url(#ivsSaXd)" class="tx_btybwx"/><path fill="url(#ibKUWEd)" class="tx_btybwx"/><circle fill="url(#imLrEMb)" class="ckkaoubhy"/><circle fill="url(#icPF7Me)" class="ckkaoubhy"/><circle fill="url(#iZY4p0b)" class="tr559m5ue"/><g filter="url(#igIWMoe)"><circle fill="url(#iIsQjyd)" class="a1-vqmk_q"/></g><g filter="url(#iHWwOGe)" class="mc2zb0bvp"><circle class="wl6bahxqt"/></g><g filter="url(#ibTLuXc)"><path fill="url(#i5O66od)" class="i5i_8mxsj"/></g><path fill="url(#iZRmAdd)" class="i5i_8mxsj"/><path fill="url(#iHf6Ygd)" class="i5i_8mxsj"/><g filter="url(#iSrPmsc)"><path class="b_2c24cth"/></g><g filter="url(#iXfO9De)"><path fill="url(#iXdZXTd)" class="ls65_6i-s"/><path class="oyksznbjv"/></g><g filter="url(#itRom9u)"><path fill="url(#i3xlFnc)" class="y0ah3rb0p"/><path fill="url(#irL48zE)" class="y0ah3rb0p"/></g><g filter="url(#iW55pue)"><circle fill="url(#icDr1Yb)" class="vh3837gtk"/></g><path stroke="url(#iVusF2c)" class="wupazrada"/><g filter="url(#iWQkjGb)"><path stroke="url(#itoImxc)" class="g-mr_sgso"/></g><path stroke="url(#izla1Je)" class="qvye139vd"/><g filter="url(#idwo5Rb)"><path stroke="url(#igNgCXj)" class="jednjgv3t"/></g><g filter="url(#iZ3BxWd)"><path class="p09lru62c"/></g><path class="z87f0j80w"/><path fill="url(#iceGjmd)" class="a7__jtqji"/><path fill="url(#icM2ujc)" class="a7__jtqji"/><path fill="url(#iwla0Lc)" class="a7__jtqji"/><g filter="url(#il94cSd)"><path stroke="url(#i3sdXhb)" class="phcbxnb1c"/></g><path class="h70pdn1in"/><g filter="url(#iUxaSjd)"><path clip-rule="evenodd" class="bd30y3bkp"/></g><g filter="url(#iPCEdHb)"><path clip-rule="evenodd" class="an3wmq0nm"/></g><g filter="url(#iSR6Eee)"><path class="t305b7bcv"/></g><g filter="url(#iUUAlbb)"><path class="gpr1cwb1i"/></g><g filter="url(#i6ICYpe)"><path class="dxamtdgbr"/><path fill="url(#iV2ZJDc)" class="g4mky1b_b"/></g><g filter="url(#i0iGpHd)"><path class="b9onc53-n"/><path fill="url(#i0Sy9re)" class="m2ddouw1w"/></g><g filter="url(#iv5XY0d)"><path class="g3g2cbblk"/></g><g filter="url(#iKashCe)"><path fill="url(#iNGmkFe)" class="zgqgadcdt"/></g><g filter="url(#iGMv6fd)"><path fill="url(#iQ9p03d)" class="fy-lwzomh"/></g><g filter="url(#i4iXm9c)"><path fill="url(#il3Dfqc)" class="ho6xyol7i"/><path fill="url(#iBZrnfc)" class="ho6xyol7i"/></g><defs><radialGradient id="iumgDIe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -9.84375 23.482 28.393)" gradientUnits="userSpaceOnUse"><stop class="mqhcwabvr"/><stop offset=".895" class="n0nsa8bju"/></radialGradient><radialGradient id="ipmDzYd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.857 16.873 9.347)scale(11.1265 12.0118)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="im62pwnwd"/><stop offset="1" class="nwe3t_p9t"/></radialGradient><radialGradient id="irszlCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.71262 -6.48073 0 16 22.123)" gradientUnits="userSpaceOnUse"><stop class="fwaqju75o"/><stop offset="1" class="i3-mvu33h"/></radialGradient><radialGradient id="ivsSaXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.99223 1.74845 -1.19074 -2.03779 18.685 23.567)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="ydm9ddced"/><stop offset="1" class="n_nhnibbq"/></radialGradient><radialGradient id="ibKUWEd" cx="0" cy="0" r="1" gradientTransform="rotate(61.174 -10.578 22.936)scale(2.86648 9.32132)" gradientUnits="userSpaceOnUse"><stop class="pj2xknbvf"/><stop offset="1" class="dit5vub-g"/></radialGradient><radialGradient id="imLrEMb" cx="0" cy="0" r="1" gradientTransform="matrix(-.88839 .69015 -.72686 -.93565 23.221 14.655)" gradientUnits="userSpaceOnUse"><stop class="my0c8s4fp"/><stop offset="1" class="y581ksbre"/></radialGradient><radialGradient id="icPF7Me" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.293 21.28)scale(2.2011)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="qtf9d8byq"/><stop offset="1" class="j9ig536pv"/></radialGradient><radialGradient id="iZY4p0b" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.715 17.502)scale(2.70721)" gradientUnits="userSpaceOnUse"><stop class="phs3tubib"/><stop offset="1" class="grwnnnb5d"/></radialGradient><radialGradient id="iIsQjyd" cx="0" cy="0" r="1" gradientTransform="matrix(.61549 0 0 .72614 21.665 15.025)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="gh1umgbbt"/><stop offset="1" class="lefbu6b0u"/></radialGradient><radialGradient id="i5O66od" cx="0" cy="0" r="1" gradientTransform="matrix(-6.40084 .5663 -.57862 -6.54 19.71 16.358)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="b1hc77b2b"/><stop offset="1" class="b94-l-y5w"/></radialGradient><radialGradient id="iZRmAdd" cx="0" cy="0" r="1" gradientTransform="scale(13.0818 10.2074)rotate(90 .02 1.203)" gradientUnits="userSpaceOnUse"><stop offset=".841" class="p6161gbqn"/><stop offset="1" class="wz-fbp47a"/></radialGradient><radialGradient id="iHf6Ygd" cx="0" cy="0" r="1" gradientTransform="matrix(2.03447 -2.12293 1.95657 1.87505 17.86 10.594)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="s69j295el"/><stop offset="1" class="y5y2xtbig"/></radialGradient><radialGradient id="iXdZXTd" cx="0" cy="0" r="1" gradientTransform="matrix(.87207 1.75 -1.15013 .57314 11.04 9.878)" gradientUnits="userSpaceOnUse"><stop class="f7m1yfx-m"/><stop offset="1" class="p3lw01bbh"/></radialGradient><radialGradient id="i3xlFnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.65625 9.15625 0 16.243 7.933)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="r2qez3b6z"/><stop offset="1" class="len1xsbgs"/></radialGradient><radialGradient id="irL48zE" cx="0" cy="0" r="1" gradientTransform="matrix(-4.23535 0 0 -1.72656 18.067 7.847)" gradientUnits="userSpaceOnUse"><stop class="yo4_wwpln"/><stop offset="1" class="fnjjkvb8k"/></radialGradient><radialGradient id="icDr1Yb" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.347 14.352)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="bo6sve4_m"/><stop offset=".902" class="aud44laqb"/></radialGradient><radialGradient id="iVusF2c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.559 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="izla1Je" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.45 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="icM2ujc" cx="0" cy="0" r="1" gradientTransform="matrix(.19456 -1.08993 4.30796 .769 15.981 17.167)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="q_3bb9b3h"/><stop offset="1" class="h65c54lsi"/></radialGradient><radialGradient id="iwla0Lc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.522 16.368)" gradientUnits="userSpaceOnUse"><stop class="x_31h1mma"/><stop offset="1" class="c7c54u04z"/></radialGradient><radialGradient id="i3sdXhb" cx="0" cy="0" r="1" gradientTransform="matrix(.20312 -.39062 1.75486 .91253 14.9 18.753)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="j2uqjm0oz"/><stop offset="1" class="qf8pq8giw"/></radialGradient><radialGradient id="iV2ZJDc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.778 10.847)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="e45b6kbci"/><stop offset="1" class="s4dmvvdkq"/></radialGradient><radialGradient id="i0Sy9re" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.487 2.043)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="iNGmkFe" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.233 9.994)" gradientUnits="userSpaceOnUse"><stop class="cbx5-fbbx"/><stop offset="1" class="vfm0_vraw"/></radialGradient><radialGradient id="il3Dfqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 10.979 6.525)" gradientUnits="userSpaceOnUse"><stop class="p7wwt2b_k"/><stop offset="1" class="o1syipbau"/></radialGradient><radialGradient id="iBZrnfc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.281 10.004)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="s4ff5rbng"/><stop offset="1" class="mqv57bcbp"/></radialGradient><filter id="iZj6xdc" width="21.451" height="8.965" x="5.65" y="20.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.396078 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24258"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.490196 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24258" result="effect2_innerShadow_3987_24258"/></filter><filter id="igIWMoe" width="2.689" height="2.689" x="20.081" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".1"/></filter><filter id="iHWwOGe" width="2.689" height="2.689" x="9.253" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".1"/></filter><filter id="ibTLuXc" width="12.719" height="14.211" x="9.883" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.40335 0 0 0 0 0.308846 0 0 0 0 0.287845 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24258"/></filter><filter id="iSrPmsc" width="7.729" height="10.962" x="16.042" y="4.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".5"/></filter><filter id="iXfO9De" width="7.108" height="9.773" x="8.357" y="5.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".5"/></filter><filter id="itRom9u" width="8.297" height="3.863" x="11.832" y="4.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.0156863 0 0 0 0 0.0352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24258"/></filter><filter id="iW55pue" width="3.829" height="3.83" x="11.59" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".25"/></filter><filter id="iWQkjGb" width="2.618" height=".92" x="12.249" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".075"/></filter><filter id="idwo5Rb" width="2.618" height=".92" x="17.14" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".075"/></filter><filter id="iZ3BxWd" width="3.122" height="4.211" x="14.143" y="13.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".25"/></filter><filter id="il94cSd" width="4.199" height="1.729" x="13.887" y="17.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".05"/></filter><filter id="iUxaSjd" width="3.191" height="1.873" x="11.514" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0352941 0 0 0 0 0.0235294 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24258"/></filter><filter id="iPCEdHb" width="3.191" height="1.873" x="17.405" y="11.665" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0352941 0 0 0 0 0.0235294 0 0 0 0 0.0235294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24258"/></filter><filter id="iSR6Eee" width="3.085" height="1.469" x="17.433" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".15"/></filter><filter id="iUUAlbb" width="3.085" height="1.469" x="11.492" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".15"/></filter><filter id="i6ICYpe" width="6.686" height="12.903" x="8.567" y="1.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.235294 0 0 0 0 0.160784 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24258"/></filter><filter id="i0iGpHd" width="6.436" height="12.953" x="17.208" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24258"/></filter><filter id="iv5XY0d" width="6.436" height="12.953" x="17.208" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.160784 0 0 0 0 0.0784314 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24258"/></filter><filter id="iKashCe" width="5.843" height="12.292" x="17.799" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".25"/></filter><filter id="iGMv6fd" width="2.811" height="6.368" x="8.687" y="8.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".375"/></filter><filter id="i4iXm9c" width="5.14" height="8.355" x="9.641" y="2.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24258" stdDeviation=".25"/></filter><linearGradient id="itoImxc" x1="14.916" x2="12.475" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="igNgCXj" x1="19.807" x2="17.365" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="iceGjmd" x1="16.866" x2="15.829" y1="15.9" y2="15.95" gradientUnits="userSpaceOnUse"><stop offset=".106" class="cbx5-fbbx"/><stop offset="1" class="vfm0_vraw"/></linearGradient><linearGradient id="iQ9p03d" x1="10.093" x2="10.093" y1="13.506" y2="8.675" gradientUnits="userSpaceOnUse"><stop class="p-tc_9j4a"/><stop offset="1" class="a4q8d6dqq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-massage-dark" /></template>
<style>
.a1-vqmk_q {
  cx: 21.426px;
  cy: 14.831px;
  r: 1.145px;
}

.a4q8d6dqq {
  stop-color: var(--svg-color--523c3c, #523C3C);
  stop-opacity: 0;
}

.a7__jtqji {
  d: path("M15.98 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .536-.73l-.678-2.14a.375.375 0 0 0-.358-.263");
}

.an3wmq0nm {
  fill: var(--svg-color--130c19, #130C19);
  fill-rule: evenodd;
  d: path("M18.029 12.787c.86-.117 1.389.27 1.521.378a.55.55 0 1 0 .693-.855c-.253-.205-1.08-.787-2.362-.614a.55.55 0 1 0 .148 1.09");
}

.aud44laqb {
  stop-color: var(--svg-color--362325, #362325);
}

.b_2c24cth {
  fill: var(--svg-color--211314, #211314);
  d: path("M22.77 7.736h-3.172V5.932c0 .352-.21 1.036-.633 1.43a77 77 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.715c.42.428 1.009.362 1.439-.055l.906-.74a.464.464 0 0 1 .691.044c.08.096.123.22.123.35v3.327c0 .662.497 1.199 1.11 1.199s1.111-.537 1.111-1.2z");
}

.b1hc77b2b {
  stop-color: var(--svg-color--4d302c, #4D302C);
}

.b94-l-y5w {
  stop-color: var(--svg-color--3c2728, #3C2728);
}

.b9onc53-n {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.bd30y3bkp {
  fill: var(--svg-color--130c19, #130C19);
  fill-rule: evenodd;
  d: path("M13.932 12.787c-.86-.117-1.389.27-1.521.378a.55.55 0 1 1-.693-.855c.253-.205 1.08-.787 2.361-.614a.55.55 0 1 1-.147 1.09");
}

.bo6sve4_m {
  stop-color: var(--svg-color--3f292a, #3F292A);
}

.c7c54u04z {
  stop-color: var(--svg-color--635150, #635150);
  stop-opacity: 0;
}

.cbx5-fbbx {
  stop-color: var(--svg-color--675553, #675553);
}

.ckkaoubhy {
  cx: 21.426px;
  cy: 14.831px;
  r: 1.859px;
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.dit5vub-g {
  stop-color: var(--svg-color--311617, #311617);
  stop-opacity: 0;
}

.dsheu9oxu {
  stop-color: var(--svg-color--0c0b0b, #0C0B0B);
}

.dxamtdgbr {
  fill: var(--svg-color--563c39, #563C39);
  d: path("M8.567 2.19h3.426v3.742c0 .352.227 1.036.684 1.43c.375.348 1.095 1.06 1.727 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.e45b6kbci {
  stop-color: var(--svg-color--2d151b, #2D151B);
}

.ey57nhbje {
  fill: var(--svg-color--482c2f, #482C2F);
  d: path("M13.742 20.41a2.256 2.256 0 0 1 4.512 0v2.102c0 1.245-1.588 1.624-2.256 1.624c-.766 0-2.256-.378-2.256-1.624z");
}

.f7m1yfx-m {
  stop-color: var(--svg-color--9b4607, #9B4607);
}

.fnjjkvb8k {
  stop-color: var(--svg-color--494446, #494446);
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

.g3g2cbblk {
  fill: var(--svg-color--3f2929, #3F2929);
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.g4mky1b_b {
  d: path("M8.567 2.19h3.426v3.742c0 .352.227 1.036.684 1.43c.375.348 1.095 1.06 1.727 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.gh1umgbbt {
  stop-color: var(--svg-color--4c3938, #4C3938);
}

.gpr1cwb1i {
  stroke: var(--svg-color--2e2d2e, #2E2D2E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.942 12.628c.193-.156 1.045-.632 2.186-.562");
}

.grwnnnb5d {
  stop-color: var(--svg-color--301c27, #301C27);
}

.h65c54lsi {
  stop-color: var(--svg-color--3f222e, #3F222E);
  stop-opacity: 0;
}

.h70pdn1in {
  fill: var(--svg-color--290118, #290118);
  d: path("M14.337 17.742c.345.18.879.384 1.65.384s1.304-.203 1.648-.384c.108-.056.242.014.25.135a.2.2 0 0 1-.015.077c-.76 1.471-3.065 1.456-3.768 0a.15.15 0 0 1-.015-.077c.008-.121.142-.191.25-.135");
}

.ho6xyol7i {
  d: path("M10.142 5.548v-2.9h1.468v3.535a1 1 0 0 0 .28.694l2.263 2.348a.46.46 0 0 1-.636.663l-2.365-2.094a3 3 0 0 1-1.01-2.246");
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

.j2uqjm0oz {
  stop-color: var(--svg-color--58494a, #58494A);
}

.j9ig536pv {
  stop-color: var(--svg-color--47232a, #47232A);
}

.jednjgv3t {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.365 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.l8jusdr6y {
  d: path("M5.65 29.81h20.7c-.493-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.664");
}

.lefbu6b0u {
  stop-color: var(--svg-color--3c2221, #3C2221);
}

.len1xsbgs {
  stop-color: var(--svg-color--383335, #383335);
}

.ls65_6i-s {
  d: path("M9.357 6.856h2.83v.372c0 .291.187.855.564 1.181c.31.287.905.876 1.426 1.398a.987.987 0 0 1-.021 1.415c-.375.354-.899.3-1.282-.045l-.81-.61a.436.436 0 0 0-.726.324v2.748a.99.99 0 1 1-1.98 0z");
}

.m2ddouw1w {
  d: path("M23.393 2.19h-3.425v3.742c0 .352-.227 1.036-.684 1.43a79 79 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.454.428 1.09.362 1.555-.055l.978-.74a.527.527 0 0 1 .879.393v3.328a1.2 1.2 0 1 0 2.398 0z");
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mqhcwabvr {
  stop-color: var(--svg-color--469afb, #469AFB);
}

.mqv57bcbp {
  stop-color: var(--svg-color--6a5856, #6A5856);
  stop-opacity: 0;
}

.my0c8s4fp {
  stop-color: var(--svg-color--5b4645, #5B4645);
}

.n_nhnibbq {
  stop-color: var(--svg-color--59403f, #59403F);
  stop-opacity: 0;
}

.n0nsa8bju {
  stop-color: var(--svg-color--2376c8, #2376C8);
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.nwe3t_p9t {
  stop-color: var(--svg-color--429efa, #429EFA);
  stop-opacity: 0;
}

.o1syipbau {
  stop-color: var(--svg-color--685654, #685654);
  stop-opacity: 0;
}

.omc-6wb_b {
  stop-color: var(--svg-color--2e2e2e, #2E2E2E);
}

.oyksznbjv {
  fill: var(--svg-color--1a0a0d, #1A0A0D);
  d: path("M9.357 6.856h2.83v.372c0 .291.187.855.564 1.181c.31.287.905.876 1.426 1.398a.987.987 0 0 1-.021 1.415c-.375.354-.899.3-1.282-.045l-.81-.61a.436.436 0 0 0-.726.324v2.748a.99.99 0 1 1-1.98 0z");
}

.p-tc_9j4a {
  stop-color: var(--svg-color--523c3c, #523C3C);
}

.p09lru62c {
  fill: var(--svg-color--361b29, #361B29);
  d: path("M15.852 14.12c-.163 0-.247.093-.296.254l-.887 2.205a.59.59 0 0 0 .112.554c.106.126.26.198.422.198h1a.55.55 0 0 0 .424-.198a.59.59 0 0 0 .112-.554l-.678-2.205c-.049-.16-.045-.254-.209-.254");
}

.p3lw01bbh {
  stop-color: var(--svg-color--d97513, #D97513);
}

.p6161gbqn {
  stop-color: var(--svg-color--302536, #302536);
  stop-opacity: 0;
}

.p7wwt2b_k {
  stop-color: var(--svg-color--685654, #685654);
}

.phcbxnb1c {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.337 17.742c.345.18.879.384 1.65.384s1.304-.203 1.648-.384c.108-.056.242.014.25.135a.2.2 0 0 1-.015.077c-.76 1.471-3.065 1.456-3.768 0a.15.15 0 0 1-.015-.077c.008-.121.142-.191.25-.135Z");
}

.phs3tubib {
  stop-color: var(--svg-color--332122, #332122);
}

.pj2xknbvf {
  stop-color: var(--svg-color--311617, #311617);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.q_3bb9b3h {
  stop-color: var(--svg-color--3f222e, #3F222E);
}

.qf8pq8giw {
  stop-color: var(--svg-color--58494a, #58494A);
  stop-opacity: 0;
}

.qtf9d8byq {
  stop-color: var(--svg-color--47232a, #47232A);
  stop-opacity: 0;
}

.qvye139vd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.365 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.r2qez3b6z {
  stop-color: var(--svg-color--180f12, #180F12);
}

.rulb4ox_k {
  stop-color: var(--svg-color--242425, #242425);
}

.s4dmvvdkq {
  stop-color: var(--svg-color--58403c, #58403C);
  stop-opacity: 0;
}

.s4ff5rbng {
  stop-color: var(--svg-color--6a5856, #6A5856);
}

.s69j295el {
  stop-color: var(--svg-color--4d3d3d, #4D3D3D);
}

.t305b7bcv {
  stroke: var(--svg-color--2e2d2e, #2E2D2E);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.068 12.628c-.193-.156-1.044-.632-2.185-.562");
}

.tr559m5ue {
  cx: 10.598px;
  cy: 14.831px;
  r: 1.859px;
}

.tx_btybwx {
  d: path("M13.742 20.41a2.256 2.256 0 0 1 4.512 0v2.102c0 1.245-1.588 1.624-2.256 1.624c-.766 0-2.256-.378-2.256-1.624z");
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

.vk3h5kjsq {
  stop-color: var(--svg-color--140a18, #140A18);
}

.wl6bahxqt {
  cx: 10.598px;
  cy: 14.831px;
  r: 1.145px;
  fill: var(--svg-color--261417, #261417);
}

.wupazrada {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.475 14.394c.145.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.wz-fbp47a {
  stop-color: var(--svg-color--2d263c, #2D263C);
}

.x_31h1mma {
  stop-color: var(--svg-color--635150, #635150);
}

.y0ah3rb0p {
  d: path("M12.015 6.056c.242-.225.546-.507.707-.635l.04-.03c.27-.218.803-.644 2.007-.376c.297.064.506.114.664.152c.282.067.397.094.547.094s.266-.027.548-.094c.158-.038.367-.088.663-.152c1.205-.268 1.737.158 2.008.375l.04.031c.16.128.464.41.707.635l.183.17l-.492 2.316c-2.352-.28-5.024-.265-7.313 0l-.492-2.316z");
}

.y581ksbre {
  stop-color: var(--svg-color--462b30, #462B30);
}

.y5y2xtbig {
  stop-color: var(--svg-color--4d3d3d, #4D3D3D);
  stop-opacity: 0;
}

.ydm9ddced {
  stop-color: var(--svg-color--59403f, #59403F);
}

.yo4_wwpln {
  stop-color: var(--svg-color--494446, #494446);
}

.z87f0j80w {
  fill: var(--svg-color--452e2c, #452E2C);
  d: path("M15.98 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .536-.73l-.678-2.14a.375.375 0 0 0-.358-.263");
}

.zgqgadcdt {
  d: path("m21.088 8.54l-2.02 1.489c-.245.18-.472.419-.678.196c-.219-.238-.006-.338.23-.56a52 52 0 0 1 1.99-1.786c.875-.733.849-2.108.828-2.57V2.732h1.704v10.713a.579.579 0 0 1-1.158 0V9.208c0-.403-.572-.906-.896-.668");
}

</style>
