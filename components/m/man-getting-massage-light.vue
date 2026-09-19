<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ihwaqWg)"><path fill="url(#ijQ3tOe)" class="w7n-e9bxs"/><path fill="url(#ipmDzYd)" class="w7n-e9bxs"/><path fill="url(#irszlCe)" class="w7n-e9bxs"/></g><path class="axg0e-2nj"/><path fill="url(#isFqv1S)" class="bjy-r9bnv"/><path fill="url(#iCLR1zb)" class="bjy-r9bnv"/><circle fill="url(#iqQWhge)" class="d47um_b6p"/><circle fill="url(#iWCY2yW)" class="w-wp4cc4n"/><g filter="url(#iESe9ib)"><circle fill="url(#iDyNUic)" class="abu3ckb3o"/></g><g filter="url(#ibwZ6vd)" class="mc2zb0bvp"><circle class="s-iuqmugs"/></g><g filter="url(#iDtw8yb)"><path fill="url(#iawQtth)" class="o_xnlqwzy"/></g><path fill="url(#iiYHsOc)" class="o_xnlqwzy"/><path fill="url(#imIJmeb)" class="o_xnlqwzy"/><g filter="url(#iYin8Ae)"><path fill="url(#iijUlid)" class="wt6f_i56x"/></g><g filter="url(#ia1xgOc)"><path fill="url(#iSNwXlk)" class="fljabgyyi"/></g><g filter="url(#iClXcrb)"><path fill="url(#iSZkLHb)" class="d5z0wwbgz"/><path fill="url(#iC2FEZb)" class="d5z0wwbgz"/></g><g filter="url(#i93NKoe)"><circle fill="url(#iad48pc)" class="ofs95m95p"/></g><path stroke="url(#iZdedSz)" class="e_mlqkb2c"/><g filter="url(#igHnsLb)"><path stroke="url(#iDD8Boe)" class="she8s5bah"/></g><path stroke="url(#iLrhDfH)" class="vobb5v3lq"/><g filter="url(#iUPW61W)"><path stroke="url(#i00tyde)" class="kyu15mbci"/></g><g filter="url(#i4Ik8Md)"><path class="mjdr-0bjc"/></g><path class="l706htesd"/><path fill="url(#iGqHv6d)" class="mu03sbbql"/><path fill="url(#iG5pZNb)" class="mu03sbbql"/><path fill="url(#iVfnwKc)" class="mu03sbbql"/><g filter="url(#icojnrd)"><path stroke="url(#ir2nPgc)" class="zbnzybbvq"/></g><path class="qr6qwwtal"/><g filter="url(#iuvaLgc)"><path clip-rule="evenodd" class="nxkp12x9o"/></g><g filter="url(#iNp8MKc)"><path clip-rule="evenodd" class="b4s_vui0j"/></g><g filter="url(#iBPiBDc)"><path stroke="url(#iG1Mqrv)" class="w9gyhnbqy"/></g><g filter="url(#iciU1ob)"><path stroke="url(#iXPm7Ac)" class="n20a-lbuf"/></g><g filter="url(#i0otN9d)"><path class="svhjdwdjk"/><path fill="url(#iKmi1ac)" class="puhtnu2na"/></g><g filter="url(#ilLPPQW)"><path class="j0g71ox6t"/><path fill="url(#idux1te)" class="f3gz6exmy"/></g><g filter="url(#i7Bni0b)"><path class="q7oxj3osz"/></g><g filter="url(#iGwaose)"><path fill="url(#iWrfkhb)" class="pi9ly9nbp"/></g><g filter="url(#i586a4b)"><path fill="url(#il8NZud)" class="xpw1soq4x"/></g><g filter="url(#iiGenhb)"><path fill="url(#ime92Fe)" class="uowsxabwy"/><path fill="url(#ikxNtPc)" class="uowsxabwy"/></g><defs><radialGradient id="ijQ3tOe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -9.84375 23.481 28.393)" gradientUnits="userSpaceOnUse"><stop class="mqhcwabvr"/><stop offset=".895" class="n0nsa8bju"/></radialGradient><radialGradient id="ipmDzYd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.857 16.873 9.347)scale(11.1265 12.0118)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="im62pwnwd"/><stop offset="1" class="nwe3t_p9t"/></radialGradient><radialGradient id="irszlCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.71262 -6.48073 0 16 22.123)" gradientUnits="userSpaceOnUse"><stop class="fwaqju75o"/><stop offset="1" class="i3-mvu33h"/></radialGradient><radialGradient id="isFqv1S" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.124 14.803)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="xvnj-hbwa"/><stop offset="1" class="t5vj9jb1c"/></radialGradient><radialGradient id="iCLR1zb" cx="0" cy="0" r="1" gradientTransform="matrix(1.0188 2.1819 -7.0952 3.31297 14.525 21.628)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="fdd7nnyox"/><stop offset="1" class="h3iuv7d3b"/></radialGradient><radialGradient id="iqQWhge" cx="0" cy="0" r="1" gradientTransform="matrix(-.88839 .69015 -.72686 -.93565 23.241 14.655)" gradientUnits="userSpaceOnUse"><stop class="k06as4b5x"/><stop offset="1" class="y8ctrfbhv"/></radialGradient><radialGradient id="iWCY2yW" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.706 17.524)scale(2.70721)" gradientUnits="userSpaceOnUse"><stop class="e7bgiqbpe"/><stop offset="1" class="y5enf2lbe"/></radialGradient><radialGradient id="iDyNUic" cx="0" cy="0" r="1" gradientTransform="matrix(.61549 0 0 .72614 21.685 15.025)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="l30itz4xv"/><stop offset="1" class="e55xysc8j"/></radialGradient><radialGradient id="iawQtth" cx="0" cy="0" r="1" gradientTransform="matrix(-6.40084 .5663 -.57862 -6.54 19.73 16.358)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="v573aej4q"/><stop offset="1" class="deyujzbbk"/><stop offset="1" class="tk5wo9bhf"/></radialGradient><radialGradient id="iiYHsOc" cx="0" cy="0" r="1" gradientTransform="rotate(94.877 2.994 13.72)scale(10.6636 13.6665)" gradientUnits="userSpaceOnUse"><stop offset=".752" class="kw7x3egiw"/><stop offset=".979" class="k945anbua"/></radialGradient><radialGradient id="imIJmeb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03447 -2.12293 1.95657 1.87505 17.879 10.594)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="ulc1d0bsf"/><stop offset="1" class="xh3hmcb7x"/></radialGradient><radialGradient id="iijUlid" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09373 4.4375 -2.83652 -.69913 21.447 9.12)" gradientUnits="userSpaceOnUse"><stop class="fa_fs_x-q"/><stop offset="1" class="ae1yswm3l"/></radialGradient><radialGradient id="iSNwXlk" cx="0" cy="0" r="1" gradientTransform="matrix(1 5.875 -3.86118 .65722 11.198 9.777)" gradientUnits="userSpaceOnUse"><stop class="jzb-3db0i"/><stop offset="1" class="kht_rqe3g"/></radialGradient><radialGradient id="iSZkLHb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.65625 9.15625 0 16.262 7.933)" gradientUnits="userSpaceOnUse"><stop offset=".235" class="r2qez3b6z"/><stop offset="1" class="len1xsbgs"/></radialGradient><radialGradient id="iC2FEZb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.23535 0 0 -1.72656 18.086 7.847)" gradientUnits="userSpaceOnUse"><stop class="yo4_wwpln"/><stop offset="1" class="fnjjkvb8k"/></radialGradient><radialGradient id="iad48pc" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 14.352)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="ppxf2wb8c"/><stop offset=".902" class="o8xc6acii"/></radialGradient><radialGradient id="iZdedSz" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="iLrhDfH" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="vk3h5kjsq"/><stop offset="1" class="dsheu9oxu"/></radialGradient><radialGradient id="iG5pZNb" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 17.167)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="cs32zggkd"/><stop offset="1" class="dcjgnwb2v"/></radialGradient><radialGradient id="iVfnwKc" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.542 16.368)" gradientUnits="userSpaceOnUse"><stop class="yg-4rg1sf"/><stop offset="1" class="un62bb-pj"/></radialGradient><radialGradient id="ir2nPgc" cx="0" cy="0" r="1" gradientTransform="rotate(-62.526 22.904 -2.91)scale(.44028 1.97794)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="ngif3bbvk"/><stop offset="1" class="m-1tuk47l"/></radialGradient><radialGradient id="iKmi1ac" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.798 10.847)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="d66hexbdz"/><stop offset="1" class="byqhg5beh"/></radialGradient><radialGradient id="idux1te" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.507 2.043)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="iWrfkhb" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.253 9.994)" gradientUnits="userSpaceOnUse"><stop class="w4lyng61b"/><stop offset="1" class="zynodvyrc"/></radialGradient><radialGradient id="ime92Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 10.998 6.525)" gradientUnits="userSpaceOnUse"><stop class="zjgm0sbfy"/><stop offset="1" class="kkhw_2bmh"/></radialGradient><radialGradient id="ikxNtPc" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.3 10.004)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="hti255bkb"/><stop offset="1" class="u0_qivupy"/></radialGradient><filter id="ihwaqWg" width="21.451" height="8.965" x="5.649" y="20.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.396078 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24270"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.490196 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24270" result="effect2_innerShadow_3987_24270"/></filter><filter id="iESe9ib" width="2.689" height="2.689" x="20.101" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".1"/></filter><filter id="ibwZ6vd" width="2.689" height="2.689" x="9.273" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".1"/></filter><filter id="iDtw8yb" width="12.719" height="14.211" x="9.903" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.890196 0 0 0 0 0.658824 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24270"/></filter><filter id="iYin8Ae" width="7.729" height="10.962" x="16.061" y="4.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".5"/></filter><filter id="ia1xgOc" width="7.108" height="9.773" x="8.377" y="5.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".5"/></filter><filter id="iClXcrb" width="8.297" height="3.863" x="11.852" y="4.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.0156863 0 0 0 0 0.0352941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24270"/></filter><filter id="i93NKoe" width="3.829" height="3.83" x="11.609" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".25"/></filter><filter id="igHnsLb" width="2.618" height=".92" x="12.269" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".075"/></filter><filter id="iUPW61W" width="2.618" height=".92" x="17.16" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".075"/></filter><filter id="i4Ik8Md" width="3.122" height="4.211" x="14.162" y="13.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".25"/></filter><filter id="icojnrd" width="4.199" height="1.729" x="13.906" y="17.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".05"/></filter><filter id="iuvaLgc" width="3.191" height="1.773" x="11.534" y="11.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0941176 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24270"/></filter><filter id="iNp8MKc" width="3.191" height="1.773" x="17.425" y="11.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.0941176 0 0 0 0 0.0980392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24270"/></filter><filter id="iBPiBDc" width="3.085" height="1.469" x="17.453" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".15"/></filter><filter id="iciU1ob" width="3.085" height="1.469" x="11.512" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".15"/></filter><filter id="i0otN9d" width="6.686" height="12.903" x="8.587" y="1.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.580392 0 0 0 0 0.556863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24270"/></filter><filter id="ilLPPQW" width="6.436" height="12.953" x="17.227" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24270"/></filter><filter id="i7Bni0b" width="6.436" height="12.953" x="17.227" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.580392 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24270"/></filter><filter id="iGwaose" width="5.843" height="12.292" x="17.818" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".25"/></filter><filter id="i586a4b" width="2.811" height="6.368" x="8.707" y="8.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".375"/></filter><filter id="iiGenhb" width="5.14" height="8.355" x="9.661" y="2.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24270" stdDeviation=".25"/></filter><linearGradient id="iDD8Boe" x1="14.936" x2="12.494" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="i00tyde" x1="19.826" x2="17.385" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="d3bth9bgz"/><stop offset=".32" class="rulb4ox_k"/><stop offset=".794" class="rulb4ox_k"/><stop offset="1" class="omc-6wb_b"/></linearGradient><linearGradient id="iGqHv6d" x1="16.886" x2="15.849" y1="15.9" y2="15.95" gradientUnits="userSpaceOnUse"><stop offset=".106" class="z2ocpzy1c"/><stop offset="1" class="ez54n3brs"/></linearGradient><linearGradient id="iG1Mqrv" x1="19.981" x2="16.559" y1="12.628" y2="12.154" gradientUnits="userSpaceOnUse"><stop class="miok1ubch"/><stop offset="1" class="eyzjjpo3w"/></linearGradient><linearGradient id="iXPm7Ac" x1="13.921" x2="10.919" y1="12.059" y2="13.387" gradientUnits="userSpaceOnUse"><stop class="miok1ubch"/><stop offset="1" class="eyzjjpo3w"/></linearGradient><linearGradient id="il8NZud" x1="10.112" x2="10.112" y1="13.506" y2="8.675" gradientUnits="userSpaceOnUse"><stop class="ow0nrh1za"/><stop offset="1" class="rmft38b6n"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-massage-light" /></template>
<style>
.abu3ckb3o {
  cx: 21.446px;
  cy: 14.831px;
  r: 1.145px;
}

.ae1yswm3l {
  stop-color: var(--svg-color--db9883, #DB9883);
}

.axg0e-2nj {
  fill: var(--svg-color--eeb3a7, #EEB3A7);
  d: path("M13.762 20.41a2.256 2.256 0 1 1 4.512 0v2.102c0 1.245-1.588 1.624-2.257 1.624c-.765 0-2.255-.378-2.255-1.624z");
}

.b4s_vui0j {
  fill: var(--svg-color--170e18, #170E18);
  fill-rule: evenodd;
  d: path("M18.048 12.787c.86-.117 1.39.27 1.522.378a.55.55 0 1 0 .692-.855c-.253-.205-1.08-.787-2.361-.614a.55.55 0 1 0 .147 1.09");
}

.bjy-r9bnv {
  d: path("M13.762 20.41a2.256 2.256 0 1 1 4.512 0v2.102c0 1.245-1.588 1.624-2.257 1.624c-.765 0-2.255-.378-2.255-1.624z");
}

.byqhg5beh {
  stop-color: var(--svg-color--dfaa9c, #DFAA9C);
  stop-opacity: 0;
}

.cs32zggkd {
  stop-color: var(--svg-color--dea097, #DEA097);
}

.d3bth9bgz {
  stop-color: var(--svg-color--2d2d2d, #2D2D2D);
}

.d47um_b6p {
  cx: 21.446px;
  cy: 14.831px;
  r: 1.859px;
}

.d5z0wwbgz {
  d: path("M12.035 6.056c.242-.225.546-.507.707-.635l.04-.03c.27-.218.802-.644 2.007-.376c.297.064.506.114.663.152c.283.067.398.094.548.094s.265-.027.548-.094c.157-.038.367-.088.663-.152c1.205-.268 1.737.158 2.008.375l.039.031c.161.128.465.41.707.635l.183.17l-.492 2.316c-2.351-.28-5.023-.265-7.312 0l-.492-2.316z");
}

.d66hexbdz {
  stop-color: var(--svg-color--c6857e, #C6857E);
}

.dcjgnwb2v {
  stop-color: var(--svg-color--dea097, #DEA097);
  stop-opacity: 0;
}

.deyujzbbk {
  stop-color: var(--svg-color--de9e8b, #DE9E8B);
}

.dsheu9oxu {
  stop-color: var(--svg-color--0c0b0b, #0C0B0B);
}

.e_mlqkb2c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.e55xysc8j {
  stop-color: var(--svg-color--f1b69c, #F1B69C);
}

.e7bgiqbpe {
  stop-color: var(--svg-color--d09281, #D09281);
}

.eyzjjpo3w {
  stop-color: var(--svg-color--2b2a2b, #2B2A2B);
  stop-opacity: 0;
}

.ez54n3brs {
  stop-color: var(--svg-color--ffd3bd, #FFD3BD);
  stop-opacity: 0;
}

.f3gz6exmy {
  d: path("M23.413 2.19h-3.426v3.742c0 .352-.226 1.036-.683 1.43a80 80 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 0 0 2.398 0z");
}

.fa_fs_x-q {
  stop-color: var(--svg-color--b4725c, #B4725C);
}

.fdd7nnyox {
  stop-color: var(--svg-color--be8484, #BE8484);
}

.fljabgyyi {
  d: path("M9.377 6.856h2.83v.372c0 .291.186.855.564 1.181c.31.287.904.876 1.426 1.398a.987.987 0 0 1-.022 1.415c-.374.354-.898.3-1.282-.045l-.81-.61a.435.435 0 0 0-.725.324v2.748a.99.99 0 0 1-1.981 0z");
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

.h3iuv7d3b {
  stop-color: var(--svg-color--be8484, #BE8484);
  stop-opacity: 0;
}

.hti255bkb {
  stop-color: var(--svg-color--fed1be, #FED1BE);
}

.i3-mvu33h {
  stop-color: var(--svg-color--2b7fd5, #2B7FD5);
  stop-opacity: 0;
}

.im62pwnwd {
  stop-color: var(--svg-color--429efa, #429EFA);
}

.j0g71ox6t {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.413 2.19h-3.426v3.742c0 .352-.226 1.036-.683 1.43a80 80 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 0 0 2.398 0z");
}

.jzb-3db0i {
  stop-color: var(--svg-color--a8624e, #A8624E);
}

.k06as4b5x {
  stop-color: var(--svg-color--fccbb6, #FCCBB6);
}

.k945anbua {
  stop-color: var(--svg-color--af7f91, #AF7F91);
}

.kht_rqe3g {
  stop-color: var(--svg-color--e19a83, #E19A83);
}

.kkhw_2bmh {
  stop-color: var(--svg-color--ffdbc3, #FFDBC3);
  stop-opacity: 0;
}

.kw7x3egiw {
  stop-color: var(--svg-color--cd9793, #CD9793);
  stop-opacity: 0;
}

.kyu15mbci {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14.394c.146.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.l30itz4xv {
  stop-color: var(--svg-color--f3baa1, #F3BAA1);
}

.l706htesd {
  fill: var(--svg-color--edb7a0, #EDB7A0);
  d: path("M16 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.263");
}

.len1xsbgs {
  stop-color: var(--svg-color--383335, #383335);
}

.m-1tuk47l {
  stop-color: var(--svg-color--e2aea5, #E2AEA5);
  stop-opacity: 0;
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.miok1ubch {
  stop-color: var(--svg-color--2b2a2b, #2B2A2B);
}

.mjdr-0bjc {
  fill: var(--svg-color--dc9f93, #DC9F93);
  d: path("M15.872 14.12c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.mqhcwabvr {
  stop-color: var(--svg-color--469afb, #469AFB);
}

.mu03sbbql {
  d: path("M16 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.263");
}

.n0nsa8bju {
  stop-color: var(--svg-color--2376c8, #2376C8);
}

.n20a-lbuf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.962 12.628c.193-.156 1.045-.633 2.185-.562");
}

.na9kkhbsz {
  stop-color: var(--svg-color--ffe041, #FFE041);
  stop-opacity: 0;
}

.ngif3bbvk {
  stop-color: var(--svg-color--e2aea5, #E2AEA5);
}

.nwe3t_p9t {
  stop-color: var(--svg-color--429efa, #429EFA);
  stop-opacity: 0;
}

.nxkp12x9o {
  fill: var(--svg-color--170e18, #170E18);
  fill-rule: evenodd;
  d: path("M13.952 12.787c-.86-.117-1.39.27-1.522.378a.55.55 0 1 1-.692-.855c.253-.205 1.08-.787 2.361-.614a.55.55 0 1 1-.147 1.09");
}

.o_xnlqwzy {
  d: path("M10.395 18.167c.14 1.625.594 3.688 3.594 3.883c.952.034 1.733.038 1.984.039h.078c.25 0 1.031-.005 1.984-.039c3-.195 3.453-2.258 3.594-3.883l.492-9.523a31 31 0 0 0-6.07-.765h-.078a31 31 0 0 0-6.07.765z");
}

.o8xc6acii {
  stop-color: var(--svg-color--d5988c, #D5988C);
}

.ofs95m95p {
  cx: 13.524px;
  cy: 13.651px;
  r: 1.415px;
}

.omc-6wb_b {
  stop-color: var(--svg-color--2e2e2e, #2E2E2E);
}

.ow0nrh1za {
  stop-color: var(--svg-color--f2beb0, #F2BEB0);
}

.pi9ly9nbp {
  d: path("m21.108 8.54l-2.021 1.489c-.244.18-.471.419-.677.196c-.22-.238-.007-.338.23-.56a52 52 0 0 1 1.99-1.786c.875-.733.849-2.108.827-2.57V2.732h1.705v10.713a.579.579 0 0 1-1.158 0V9.208c0-.403-.572-.906-.896-.668");
}

.ppxf2wb8c {
  stop-color: var(--svg-color--e3a998, #E3A998);
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.puhtnu2na {
  d: path("M8.587 2.19h3.426v3.742c0 .352.226 1.036.683 1.43a80 80 0 0 1 1.728 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.q7oxj3osz {
  fill: var(--svg-color--edb9a5, #EDB9A5);
  d: path("M23.413 2.19h-3.426v3.742c0 .352-.226 1.036-.683 1.43a80 80 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 0 0 2.398 0z");
}

.qr6qwwtal {
  fill: var(--svg-color--87014d, #87014D);
  d: path("M14.357 17.742c.344.18.879.384 1.649.384s1.304-.203 1.648-.384c.108-.056.243.014.25.135a.15.15 0 0 1-.014.077c-.76 1.471-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.121.142-.191.25-.135");
}

.r2qez3b6z {
  stop-color: var(--svg-color--180f12, #180F12);
}

.rmft38b6n {
  stop-color: var(--svg-color--f2beb0, #F2BEB0);
  stop-opacity: 0;
}

.rulb4ox_k {
  stop-color: var(--svg-color--242425, #242425);
}

.s-iuqmugs {
  cx: 10.617px;
  cy: 14.831px;
  r: 1.145px;
  fill: var(--svg-color--c88773, #C88773);
}

.she8s5bah {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.svhjdwdjk {
  fill: var(--svg-color--f1bca6, #F1BCA6);
  d: path("M8.587 2.19h3.426v3.742c0 .352.226 1.036.683 1.43a80 80 0 0 1 1.728 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.t5vj9jb1c {
  stop-color: var(--svg-color--f8c6b7, #F8C6B7);
  stop-opacity: 0;
}

.tk5wo9bhf {
  stop-color: var(--svg-color--d8a294, #D8A294);
}

.u0_qivupy {
  stop-color: var(--svg-color--fed1be, #FED1BE);
  stop-opacity: 0;
}

.ulc1d0bsf {
  stop-color: var(--svg-color--e9b8a1, #E9B8A1);
}

.un62bb-pj {
  stop-color: var(--svg-color--ffd0be, #FFD0BE);
  stop-opacity: 0;
}

.uowsxabwy {
  d: path("M10.161 5.548v-2.9h1.469v3.535a1 1 0 0 0 .28.694l2.262 2.348a.46.46 0 0 1-.636.663l-2.364-2.094a3 3 0 0 1-1.01-2.246");
}

.v573aej4q {
  stop-color: var(--svg-color--ffd6bc, #FFD6BC);
}

.vk3h5kjsq {
  stop-color: var(--svg-color--140a18, #140A18);
}

.vobb5v3lq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14.394c.146.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.w-wp4cc4n {
  cx: 10.617px;
  cy: 14.831px;
  r: 1.859px;
}

.w4lyng61b {
  stop-color: var(--svg-color--f8cab8, #F8CAB8);
}

.w7n-e9bxs {
  d: path("M5.65 29.81h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.664");
}

.w9gyhnbqy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.088 12.628c-.193-.156-1.045-.633-2.185-.562");
}

.wt6f_i56x {
  d: path("M22.79 7.736h-3.173V5.932c0 .352-.21 1.036-.633 1.43a77 77 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.715c.42.428 1.01.362 1.44-.055l.905-.74a.464.464 0 0 1 .692.044c.08.096.123.22.123.35v3.327c0 .662.497 1.199 1.11 1.199s1.111-.537 1.111-1.2z");
}

.xh3hmcb7x {
  stop-color: var(--svg-color--e9b8a1, #E9B8A1);
  stop-opacity: 0;
}

.xpw1soq4x {
  d: path("m9.457 9.42l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.xvnj-hbwa {
  stop-color: var(--svg-color--f8c6b7, #F8C6B7);
}

.y5enf2lbe {
  stop-color: var(--svg-color--cf8b7b, #CF8B7B);
}

.y8ctrfbhv {
  stop-color: var(--svg-color--edb3a0, #EDB3A0);
}

.yg-4rg1sf {
  stop-color: var(--svg-color--ffd0be, #FFD0BE);
}

.yo4_wwpln {
  stop-color: var(--svg-color--494446, #494446);
}

.z2ocpzy1c {
  stop-color: var(--svg-color--ffd3bd, #FFD3BD);
}

.zbnzybbvq {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.742c.344.18.879.384 1.649.384s1.304-.203 1.648-.384c.108-.056.243.014.25.135a.15.15 0 0 1-.014.077c-.76 1.471-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.121.142-.191.25-.135Z");
}

.zjgm0sbfy {
  stop-color: var(--svg-color--ffdbc3, #FFDBC3);
}

.zynodvyrc {
  stop-color: var(--svg-color--f8cab8, #F8CAB8);
  stop-opacity: 0;
}

</style>
