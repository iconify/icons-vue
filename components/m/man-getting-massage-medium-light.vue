<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iEHaabc)"><path fill="url(#ijQ3tOe)" class="w7n-e9bxs"/><path fill="url(#ipmDzYd)" class="w7n-e9bxs"/><path fill="url(#irszlCe)" class="w7n-e9bxs"/></g><path class="h1g5gubea"/><path fill="url(#ie2UnRb)" class="bjy-r9bnv"/><path fill="url(#iQISpjh)" class="bjy-r9bnv"/><circle fill="url(#iglOdQd)" class="d47um_b6p"/><circle fill="url(#iXTaJwd)" class="d47um_b6p"/><circle fill="url(#iLUCLDb)" class="w-wp4cc4n"/><g filter="url(#i9GAbmd)"><circle fill="url(#i1ZZUvP)" class="abu3ckb3o"/></g><g filter="url(#iaNu5Qd)" class="mc2zb0bvp"><circle class="vskuj4b5p"/></g><g filter="url(#iTsrhLb)"><path fill="url(#itbBoxx)" class="o_xnlqwzy"/></g><path fill="url(#idwe5Gc)" class="o_xnlqwzy"/><path fill="url(#iXxBnOb)" class="o_xnlqwzy"/><g filter="url(#ikzihxb)"><path fill="url(#iALjTdd)" class="wt6f_i56x"/></g><g filter="url(#iBDRqfc)"><path fill="url(#itUdhLb)" class="fljabgyyi"/></g><g filter="url(#iYQ0ASd)"><path class="ntxiqebzh"/><path fill="url(#it0ukOe)" class="d5z0wwbgz"/><path fill="url(#ihjXSxc)" class="d5z0wwbgz"/><path fill="url(#ib4w5fd)" class="d5z0wwbgz"/><path fill="url(#i2L8Z2b)" class="d5z0wwbgz"/></g><g filter="url(#ivm39Gd)"><circle fill="url(#iLigmrc)" class="ofs95m95p"/></g><path stroke="url(#ivQAcxe)" class="e_mlqkb2c"/><g filter="url(#iBhoe8c)"><path stroke="url(#ix2L82d)" class="she8s5bah"/></g><path stroke="url(#ik9kbkb)" class="vobb5v3lq"/><g filter="url(#i4jIY1c)"><path stroke="url(#iP2SGzc)" class="kyu15mbci"/></g><g filter="url(#iClotWc)"><path class="a-9sh10eq"/></g><path class="o_o2nfuhr"/><path fill="url(#iyFH4kc)" class="mu03sbbql"/><path fill="url(#iKdLFPe)" class="mu03sbbql"/><path fill="url(#iLwuoVd)" class="mu03sbbql"/><g filter="url(#iP0v3LD)"><path stroke="url(#ikctsne)" class="zbnzybbvq"/></g><path class="fm5qefb5x"/><g filter="url(#isgq6fd)"><path clip-rule="evenodd" class="kk2gzkpnp"/></g><g filter="url(#i5UBGsd)"><path clip-rule="evenodd" class="mmt-ahp3a"/></g><g filter="url(#iRGtNid)"><path stroke="url(#ii2NhDe)" class="w9gyhnbqy"/></g><g filter="url(#ilxkx7s)"><path stroke="url(#iaXcpRc)" class="n20a-lbuf"/></g><g filter="url(#iKwMrHc)"><path class="rpgwgiivx"/><path fill="url(#iAzrmgb)" class="puhtnu2na"/></g><g filter="url(#i9zB0xc)"><path class="j0g71ox6t"/><path fill="url(#idux1te)" class="f3gz6exmy"/></g><g filter="url(#i1HMbfb)"><path class="wio6qjbis"/></g><g filter="url(#i7kxLjd)"><path fill="url(#ioUXmNw)" class="pi9ly9nbp"/></g><g filter="url(#izdZSnc)"><path fill="url(#iEAwsvb)" class="xpw1soq4x"/></g><g filter="url(#iXT1vZO)"><path fill="url(#i2r7A0c)" class="uowsxabwy"/><path fill="url(#iFOkwze)" class="uowsxabwy"/></g><defs><radialGradient id="ijQ3tOe" cx="0" cy="0" r="1" gradientTransform="matrix(-18.0313 0 0 -9.84375 23.481 28.393)" gradientUnits="userSpaceOnUse"><stop class="mqhcwabvr"/><stop offset=".895" class="n0nsa8bju"/></radialGradient><radialGradient id="ipmDzYd" cx="0" cy="0" r="1" gradientTransform="rotate(-143.857 16.873 9.347)scale(11.1265 12.0118)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="im62pwnwd"/><stop offset="1" class="nwe3t_p9t"/></radialGradient><radialGradient id="irszlCe" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.71262 -6.48073 0 16 22.123)" gradientUnits="userSpaceOnUse"><stop class="fwaqju75o"/><stop offset="1" class="i3-mvu33h"/></radialGradient><radialGradient id="ie2UnRb" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 5.124 14.803)scale(3.24973 2.31564)" gradientUnits="userSpaceOnUse"><stop offset=".186" class="iy28akclu"/><stop offset="1" class="ge27cewfp"/></radialGradient><radialGradient id="iQISpjh" cx="0" cy="0" r="1" gradientTransform="matrix(.92506 2.1194 -6.89194 3.00815 14.525 21.628)" gradientUnits="userSpaceOnUse"><stop offset=".085" class="t8meycbcj"/><stop offset="1" class="mmszrqtpt"/></radialGradient><radialGradient id="iglOdQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.71564 .7118 -.74967 -.75371 23.241 14.655)" gradientUnits="userSpaceOnUse"><stop class="kew95vbbt"/><stop offset="1" class="qmajx1z3l"/></radialGradient><radialGradient id="iXTaJwd" cx="0" cy="0" r="1" gradientTransform="rotate(75.315 1.303 21.293)scale(2.2011)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="bitta5b4f"/><stop offset="1" class="qfofjhlvk"/></radialGradient><radialGradient id="iLUCLDb" cx="0" cy="0" r="1" gradientTransform="rotate(46.621 -12.706 17.524)scale(2.70721)" gradientUnits="userSpaceOnUse"><stop class="eusqnibct"/><stop offset="1" class="hkkpz-bpt"/></radialGradient><radialGradient id="i1ZZUvP" cx="0" cy="0" r="1" gradientTransform="matrix(.61549 0 0 .72614 21.685 15.025)" gradientUnits="userSpaceOnUse"><stop offset=".188" class="eevz_mbba"/><stop offset="1" class="xtumd7buv"/></radialGradient><radialGradient id="itbBoxx" cx="0" cy="0" r="1" gradientTransform="matrix(-6.40084 .5663 -.57862 -6.54 19.73 16.358)" gradientUnits="userSpaceOnUse"><stop offset=".283" class="k12aqibrq"/><stop offset="1" class="dfqtmwbvu"/></radialGradient><radialGradient id="idwe5Gc" cx="0" cy="0" r="1" gradientTransform="rotate(94.877 2.994 13.72)scale(10.6636 13.6665)" gradientUnits="userSpaceOnUse"><stop offset=".752" class="oxok84bav"/><stop offset=".979" class="vj3qknbmu"/></radialGradient><radialGradient id="iXxBnOb" cx="0" cy="0" r="1" gradientTransform="matrix(2.03447 -2.12293 1.95657 1.87505 17.879 10.594)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="z4gay0bfu"/><stop offset="1" class="n17dl3bou"/></radialGradient><radialGradient id="iALjTdd" cx="0" cy="0" r="1" gradientTransform="matrix(-1 3.6875 -3.2061 -.86946 21.51 9.433)" gradientUnits="userSpaceOnUse"><stop offset=".072" class="top4m_b9w"/><stop offset="1" class="gd06x8-mu"/></radialGradient><radialGradient id="itUdhLb" cx="0" cy="0" r="1" gradientTransform="matrix(.8584 4.94563 -3.25037 .56416 11.073 9.683)" gradientUnits="userSpaceOnUse"><stop offset=".118" class="ac4xzzbrr"/><stop offset="1" class="cpmy9wdkn"/></radialGradient><radialGradient id="it0ukOe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24908 -1.8848 1.70253 -2.03159 18.78 8.115)" gradientUnits="userSpaceOnUse"><stop offset=".322" class="jcq5gvbam"/><stop offset="1" class="h94hj6bho"/></radialGradient><radialGradient id="ihjXSxc" cx="0" cy="0" r="1" gradientTransform="rotate(-153.435 9.172 1.844)scale(4.68293 9.81511)" gradientUnits="userSpaceOnUse"><stop offset=".618" class="hn01h3b5n"/><stop offset=".971" class="gfuhu9buw"/></radialGradient><radialGradient id="ib4w5fd" cx="0" cy="0" r="1" gradientTransform="rotate(165.129 8.961 3.48)scale(2.86147 1.10395)" gradientUnits="userSpaceOnUse"><stop offset=".293" class="tca1gr03j"/><stop offset="1" class="hx-kvdl8d"/></radialGradient><radialGradient id="i2L8Z2b" cx="0" cy="0" r="1" gradientTransform="rotate(-132.421 11.64 -1.29)scale(4.66658 2.21064)" gradientUnits="userSpaceOnUse"><stop offset=".096" class="nz6v-s-ag"/><stop offset="1" class="uk_m77_tv"/></radialGradient><radialGradient id="iLigmrc" cx="0" cy="0" r="1" gradientTransform="matrix(.92789 -1.80184 1.99143 1.02552 13.366 14.352)" gradientUnits="userSpaceOnUse"><stop offset=".347" class="n_pf1oy7u"/><stop offset=".902" class="e0nbxjblq"/></radialGradient><radialGradient id="ivQAcxe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 13.578 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="i6h5s3y2e"/><stop offset="1" class="r-0_iwkut"/></radialGradient><radialGradient id="ik9kbkb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.07812 3.27721 0 18.469 14.988)" gradientUnits="userSpaceOnUse"><stop offset=".251" class="i6h5s3y2e"/><stop offset="1" class="r-0_iwkut"/></radialGradient><radialGradient id="iKdLFPe" cx="0" cy="0" r="1" gradientTransform="matrix(.19455 -1.08993 4.30797 .76898 16 17.167)" gradientUnits="userSpaceOnUse"><stop offset=".03" class="csb315wui"/><stop offset="1" class="c2okx_q2g"/></radialGradient><radialGradient id="iLwuoVd" cx="0" cy="0" r="1" gradientTransform="matrix(.90625 0 0 .26563 16.542 16.368)" gradientUnits="userSpaceOnUse"><stop class="yp6fmsbhu"/><stop offset="1" class="ea054pq6c"/></radialGradient><radialGradient id="ikctsne" cx="0" cy="0" r="1" gradientTransform="rotate(-62.526 22.904 -2.91)scale(.44028 1.97794)" gradientUnits="userSpaceOnUse"><stop offset=".156" class="gl9j5ld5z"/><stop offset="1" class="b3ziilbku"/></radialGradient><radialGradient id="iAzrmgb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.79686 -2.67189 1.32522 -.89122 11.798 10.847)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="xk4wwk53d"/><stop offset="1" class="b0gopucow"/></radialGradient><radialGradient id="idux1te" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.14314 -1.29371 0 22.507 2.043)" gradientUnits="userSpaceOnUse"><stop class="pra7rq0gk"/><stop offset="1" class="na9kkhbsz"/></radialGradient><radialGradient id="ioUXmNw" cx="0" cy="0" r="1" gradientTransform="matrix(5.8706 -6.28124 5.4446 5.08866 18.253 9.994)" gradientUnits="userSpaceOnUse"><stop class="zpoasobui"/><stop offset="1" class="ss3psybpi"/></radialGradient><radialGradient id="i2r7A0c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.21875 .78125 0 10.998 6.525)" gradientUnits="userSpaceOnUse"><stop class="xms_-vb8m"/><stop offset="1" class="wj0_vcbzm"/><stop offset="1" class="dpgj0fl2i"/></radialGradient><radialGradient id="iFOkwze" cx="0" cy="0" r="1" gradientTransform="matrix(-.95862 -1.07283 .90655 -.81004 14.3 10.004)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="cbcg1h21f"/><stop offset="1" class="ecsgmuy6m"/></radialGradient><filter id="iEHaabc" width="21.451" height="8.965" x="5.649" y="20.845" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.396078 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24267"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.270588 0 0 0 0 0.490196 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_24267" result="effect2_innerShadow_3987_24267"/></filter><filter id="i9GAbmd" width="2.689" height="2.689" x="20.101" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".1"/></filter><filter id="iaNu5Qd" width="2.689" height="2.689" x="9.273" y="13.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".1"/></filter><filter id="iTsrhLb" width="12.719" height="14.211" x="9.903" y="7.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.847059 0 0 0 0 0.615686 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24267"/></filter><filter id="ikzihxb" width="7.729" height="10.962" x="16.061" y="4.932" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".5"/></filter><filter id="iBDRqfc" width="7.108" height="9.773" x="8.377" y="5.856" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".5"/></filter><filter id="iYQ0ASd" width="8.297" height="3.863" x="11.852" y="4.679" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.721569 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24267"/></filter><filter id="ivm39Gd" width="3.829" height="3.83" x="11.609" y="11.736" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".25"/></filter><filter id="iBhoe8c" width="2.618" height=".92" x="12.269" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".075"/></filter><filter id="i4jIY1c" width="2.618" height=".92" x="17.16" y="14.169" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".075"/></filter><filter id="iClotWc" width="3.122" height="4.211" x="14.162" y="13.62" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".25"/></filter><filter id="iP0v3LD" width="4.199" height="1.729" x="13.906" y="17.523" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".05"/></filter><filter id="isgq6fd" width="3.191" height="1.773" x="11.534" y="11.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24267"/></filter><filter id="i5UBGsd" width="3.191" height="1.773" x="17.425" y="11.515" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.47451 0 0 0 0 0.262745 0 0 0 0 0.164706 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24267"/></filter><filter id="iRGtNid" width="3.085" height="1.469" x="17.453" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".15"/></filter><filter id="ilxkx7s" width="3.085" height="1.469" x="11.512" y="11.609" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".15"/></filter><filter id="iKwMrHc" width="6.686" height="12.903" x="8.587" y="1.991" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.2"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.819608 0 0 0 0 0.592157 0 0 0 0 0.478431 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24267"/></filter><filter id="i9zB0xc" width="6.436" height="12.953" x="17.227" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.917647 0 0 0 0 0.541176 0 0 0 0 0.160784 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24267"/></filter><filter id="i1HMbfb" width="6.436" height="12.953" x="17.227" y="1.941" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.447059 0 0 0 0 0.356863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_24267"/></filter><filter id="i7kxLjd" width="5.843" height="12.292" x="17.818" y="2.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".25"/></filter><filter id="izdZSnc" width="2.811" height="6.368" x="8.707" y="8.671" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".375"/></filter><filter id="iXT1vZO" width="5.14" height="8.355" x="9.661" y="2.149" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_24267" stdDeviation=".25"/></filter><linearGradient id="ix2L82d" x1="14.936" x2="12.494" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="vmf5ti4hh"/><stop offset=".32" class="niae35b7q"/><stop offset=".794" class="lphhh6b5o"/><stop offset="1" class="ojzo1eq0m"/></linearGradient><linearGradient id="iP2SGzc" x1="19.826" x2="17.385" y1="14.394" y2="14.394" gradientUnits="userSpaceOnUse"><stop offset=".045" class="vmf5ti4hh"/><stop offset=".32" class="niae35b7q"/><stop offset=".794" class="lphhh6b5o"/><stop offset="1" class="ojzo1eq0m"/></linearGradient><linearGradient id="iyFH4kc" x1="16.886" x2="15.849" y1="15.9" y2="15.95" gradientUnits="userSpaceOnUse"><stop offset=".106" class="y_s895zcx"/><stop offset="1" class="gd4v4obak"/></linearGradient><linearGradient id="ii2NhDe" x1="19.981" x2="16.559" y1="12.628" y2="12.154" gradientUnits="userSpaceOnUse"><stop class="y7usumbmg"/><stop offset="1" class="r8ovdgbln"/></linearGradient><linearGradient id="iaXcpRc" x1="13.918" x2="11.418" y1="12.059" y2="13.279" gradientUnits="userSpaceOnUse"><stop class="y7usumbmg"/><stop offset="1" class="r8ovdgbln"/></linearGradient><linearGradient id="iEAwsvb" x1="10.112" x2="10.112" y1="13.506" y2="8.675" gradientUnits="userSpaceOnUse"><stop class="ow5lwmmzq"/><stop offset="1" class="t4_yy204v"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-getting-massage-medium-light" /></template>
<style>
.a-9sh10eq {
  fill: var(--svg-color--cb8a7c, #CB8A7C);
  d: path("M15.872 14.12c-.163 0-.248.093-.297.254l-.887 2.205a.59.59 0 0 0 .112.554a.56.56 0 0 0 .423.198h1a.56.56 0 0 0 .423-.198a.59.59 0 0 0 .112-.554l-.677-2.205c-.05-.16-.045-.254-.209-.254");
}

.abu3ckb3o {
  cx: 21.446px;
  cy: 14.831px;
  r: 1.145px;
}

.ac4xzzbrr {
  stop-color: var(--svg-color--97523e, #97523E);
}

.b0gopucow {
  stop-color: var(--svg-color--d39c86, #D39C86);
  stop-opacity: 0;
}

.b3ziilbku {
  stop-color: var(--svg-color--d49d8f, #D49D8F);
  stop-opacity: 0;
}

.bitta5b4f {
  stop-color: var(--svg-color--da9779, #DA9779);
  stop-opacity: 0;
}

.bjy-r9bnv {
  d: path("M13.762 20.41a2.256 2.256 0 1 1 4.512 0v2.102c0 1.245-1.588 1.624-2.257 1.624c-.765 0-2.255-.378-2.255-1.624z");
}

.c2okx_q2g {
  stop-color: var(--svg-color--d39186, #D39186);
  stop-opacity: 0;
}

.cbcg1h21f {
  stop-color: var(--svg-color--edbfa5, #EDBFA5);
}

.cpmy9wdkn {
  stop-color: var(--svg-color--ab6a5f, #AB6A5F);
}

.csb315wui {
  stop-color: var(--svg-color--d39186, #D39186);
}

.d47um_b6p {
  cx: 21.446px;
  cy: 14.831px;
  r: 1.859px;
}

.d5z0wwbgz {
  d: path("M12.035 6.056c.242-.225.546-.507.707-.635l.04-.03c.27-.218.802-.644 2.007-.376c.297.064.506.114.663.152c.283.067.398.094.548.094s.265-.027.548-.094c.157-.038.367-.088.663-.152c1.205-.268 1.737.158 2.008.375l.039.031c.161.128.465.41.707.635l.183.17l-.492 2.316c-2.351-.28-5.023-.265-7.312 0l-.492-2.316z");
}

.dfqtmwbvu {
  stop-color: var(--svg-color--c9907d, #C9907D);
}

.dpgj0fl2i {
  stop-color: var(--svg-color--fbc8a8, #FBC8A8);
  stop-opacity: 0;
}

.e_mlqkb2c {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M12.494 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.e0nbxjblq {
  stop-color: var(--svg-color--c6867c, #C6867C);
}

.ea054pq6c {
  stop-color: var(--svg-color--f2bea5, #F2BEA5);
  stop-opacity: 0;
}

.ecsgmuy6m {
  stop-color: var(--svg-color--edbfa5, #EDBFA5);
  stop-opacity: 0;
}

.eevz_mbba {
  stop-color: var(--svg-color--e2a786, #E2A786);
}

.eusqnibct {
  stop-color: var(--svg-color--c4836f, #C4836F);
}

.f3gz6exmy {
  d: path("M23.413 2.19h-3.426v3.742c0 .352-.226 1.036-.683 1.43a80 80 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 0 0 2.398 0z");
}

.fljabgyyi {
  d: path("M9.377 6.856h2.83v.372c0 .291.186.855.564 1.181c.31.287.904.876 1.426 1.398a.987.987 0 0 1-.022 1.415c-.374.354-.898.3-1.282-.045l-.81-.61a.435.435 0 0 0-.725.324v2.748a.99.99 0 0 1-1.981 0z");
}

.fm5qefb5x {
  fill: var(--svg-color--88014e, #88014E);
  d: path("M14.357 17.742c.344.18.879.384 1.649.384s1.304-.203 1.648-.384c.108-.056.243.014.25.135a.15.15 0 0 1-.014.077c-.76 1.471-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.121.142-.191.25-.135");
}

.ft5dv1b6b {
  fill: none;
}

.fwaqju75o {
  stop-color: var(--svg-color--215286, #215286);
}

.gd06x8-mu {
  stop-color: var(--svg-color--c5836c, #C5836C);
}

.gd4v4obak {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
  stop-opacity: 0;
}

.ge27cewfp {
  stop-color: var(--svg-color--e2b099, #E2B099);
  stop-opacity: 0;
}

.gfuhu9buw {
  stop-color: var(--svg-color--ddbd86, #DDBD86);
}

.gl9j5ld5z {
  stop-color: var(--svg-color--d49d8f, #D49D8F);
}

.h1g5gubea {
  fill: var(--svg-color--dc9e8a, #DC9E8A);
  d: path("M13.762 20.41a2.256 2.256 0 1 1 4.512 0v2.102c0 1.245-1.588 1.624-2.257 1.624c-.765 0-2.255-.378-2.255-1.624z");
}

.h94hj6bho {
  stop-color: var(--svg-color--ffe8b4, #FFE8B4);
  stop-opacity: 0;
}

.hkkpz-bpt {
  stop-color: var(--svg-color--c37a6b, #C37A6B);
}

.hn01h3b5n {
  stop-color: var(--svg-color--efcc88, #EFCC88);
  stop-opacity: 0;
}

.hx-kvdl8d {
  stop-color: var(--svg-color--ded2ab, #DED2AB);
  stop-opacity: 0;
}

.i3-mvu33h {
  stop-color: var(--svg-color--2b7fd5, #2B7FD5);
  stop-opacity: 0;
}

.i6h5s3y2e {
  stop-color: var(--svg-color--7e4630, #7E4630);
}

.im62pwnwd {
  stop-color: var(--svg-color--429efa, #429EFA);
}

.iy28akclu {
  stop-color: var(--svg-color--e2b099, #E2B099);
}

.j0g71ox6t {
  fill: var(--svg-color--ffb62d, #FFB62D);
  d: path("M23.413 2.19h-3.426v3.742c0 .352-.226 1.036-.683 1.43a80 80 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 0 0 2.398 0z");
}

.jcq5gvbam {
  stop-color: var(--svg-color--ffe8b4, #FFE8B4);
}

.k12aqibrq {
  stop-color: var(--svg-color--f4bc97, #F4BC97);
}

.kew95vbbt {
  stop-color: var(--svg-color--ecb99c, #ECB99C);
}

.kk2gzkpnp {
  fill: var(--svg-color--814c31, #814C31);
  fill-rule: evenodd;
  d: path("M13.952 12.787c-.86-.117-1.39.27-1.522.378a.55.55 0 1 1-.692-.855c.253-.205 1.08-.787 2.361-.614a.55.55 0 1 1-.147 1.09");
}

.kyu15mbci {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M17.385 14.394c.146.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.lphhh6b5o {
  stop-color: var(--svg-color--925d35, #925D35);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mmszrqtpt {
  stop-color: var(--svg-color--ad706d, #AD706D);
  stop-opacity: 0;
}

.mmt-ahp3a {
  fill: var(--svg-color--814c31, #814C31);
  fill-rule: evenodd;
  d: path("M18.048 12.787c.86-.117 1.39.27 1.522.378a.55.55 0 1 0 .692-.855c-.253-.205-1.08-.787-2.361-.614a.55.55 0 1 0 .147 1.09");
}

.mqhcwabvr {
  stop-color: var(--svg-color--469afb, #469AFB);
}

.mu03sbbql {
  d: path("M16 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.263");
}

.n_pf1oy7u {
  stop-color: var(--svg-color--d09580, #D09580);
}

.n0nsa8bju {
  stop-color: var(--svg-color--2376c8, #2376C8);
}

.n17dl3bou {
  stop-color: var(--svg-color--e0a993, #E0A993);
  stop-opacity: 0;
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

.niae35b7q {
  stop-color: var(--svg-color--98623a, #98623A);
}

.ntxiqebzh {
  fill: var(--svg-color--ffe6a6, #FFE6A6);
  d: path("M12.035 6.056c.242-.225.546-.507.707-.635l.04-.03c.27-.218.802-.644 2.007-.376c.297.064.506.114.663.152c.283.067.398.094.548.094s.265-.027.548-.094c.157-.038.367-.088.663-.152c1.205-.268 1.737.158 2.008.375l.039.031c.161.128.465.41.707.635l.183.17l-.492 2.316c-2.351-.28-5.023-.265-7.312 0l-.492-2.316z");
}

.nwe3t_p9t {
  stop-color: var(--svg-color--429efa, #429EFA);
  stop-opacity: 0;
}

.nz6v-s-ag {
  stop-color: var(--svg-color--c4a469, #C4A469);
}

.o_o2nfuhr {
  fill: var(--svg-color--dfa789, #DFA789);
  d: path("M16 14.034a.375.375 0 0 0-.357.262l-.678 2.14a.56.56 0 0 0 .535.731h1a.56.56 0 0 0 .535-.73l-.677-2.14a.375.375 0 0 0-.358-.263");
}

.o_xnlqwzy {
  d: path("M10.395 18.167c.14 1.625.594 3.688 3.594 3.883c.952.034 1.733.038 1.984.039h.078c.25 0 1.031-.005 1.984-.039c3-.195 3.453-2.258 3.594-3.883l.492-9.523a31 31 0 0 0-6.07-.765h-.078a31 31 0 0 0-6.07.765z");
}

.ofs95m95p {
  cx: 13.524px;
  cy: 13.651px;
  r: 1.415px;
}

.ojzo1eq0m {
  stop-color: var(--svg-color--a06b42, #A06B42);
}

.ow5lwmmzq {
  stop-color: var(--svg-color--e1ad98, #E1AD98);
}

.oxok84bav {
  stop-color: var(--svg-color--be8182, #BE8182);
  stop-opacity: 0;
}

.pi9ly9nbp {
  d: path("m21.108 8.54l-2.021 1.489c-.244.18-.471.419-.677.196c-.22-.238-.007-.338.23-.56a52 52 0 0 1 1.99-1.786c.875-.733.849-2.108.827-2.57V2.732h1.705v10.713a.579.579 0 0 1-1.158 0V9.208c0-.403-.572-.906-.896-.668");
}

.pra7rq0gk {
  stop-color: var(--svg-color--ffe041, #FFE041);
}

.puhtnu2na {
  d: path("M8.587 2.19h3.426v3.742c0 .352.226 1.036.683 1.43a80 80 0 0 1 1.728 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.qfofjhlvk {
  stop-color: var(--svg-color--da9779, #DA9779);
}

.qmajx1z3l {
  stop-color: var(--svg-color--de9f87, #DE9F87);
}

.r-0_iwkut {
  stop-color: var(--svg-color--834f26, #834F26);
}

.r8ovdgbln {
  stop-color: var(--svg-color--a57045, #A57045);
  stop-opacity: 0;
}

.rpgwgiivx {
  fill: var(--svg-color--e1aa8e, #E1AA8E);
  d: path("M8.587 2.19h3.426v3.742c0 .352.226 1.036.683 1.43a80 80 0 0 1 1.728 1.692a1.195 1.195 0 0 1-.027 1.715c-.453.428-1.088.362-1.552-.055l-.98-.74a.527.527 0 0 0-.88.393v3.328a1.2 1.2 0 0 1-2.398 0z");
}

.she8s5bah {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M12.494 14.394c.146.164.536.45 1.024.469c.617.023.949-.305 1.144-.47");
}

.ss3psybpi {
  stop-color: var(--svg-color--e7b79d, #E7B79D);
  stop-opacity: 0;
}

.t4_yy204v {
  stop-color: var(--svg-color--e1ad98, #E1AD98);
  stop-opacity: 0;
}

.t8meycbcj {
  stop-color: var(--svg-color--ad706d, #AD706D);
}

.tca1gr03j {
  stop-color: var(--svg-color--ded2ab, #DED2AB);
}

.top4m_b9w {
  stop-color: var(--svg-color--a66046, #A66046);
}

.uk_m77_tv {
  stop-color: var(--svg-color--e0c68d, #E0C68D);
  stop-opacity: 0;
}

.uowsxabwy {
  d: path("M10.161 5.548v-2.9h1.469v3.535a1 1 0 0 0 .28.694l2.262 2.348a.46.46 0 0 1-.636.663l-2.364-2.094a3 3 0 0 1-1.01-2.246");
}

.vj3qknbmu {
  stop-color: var(--svg-color--a16d7a, #A16D7A);
}

.vmf5ti4hh {
  stop-color: var(--svg-color--9d683d, #9D683D);
}

.vobb5v3lq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-55px, 0.55px);
  d: path("M17.385 14.394c.146.164.536.45 1.023.469c.617.023.95-.305 1.145-.47");
}

.vskuj4b5p {
  cx: 10.617px;
  cy: 14.831px;
  r: 1.145px;
  fill: var(--svg-color--ba765f, #BA765F);
}

.w-wp4cc4n {
  cx: 10.617px;
  cy: 14.831px;
  r: 1.859px;
}

.w7n-e9bxs {
  d: path("M5.65 29.81h20.7c-.494-4.932-5.203-8.665-10.39-8.665c-5.189 0-9.713 3.764-10.31 8.664");
}

.w9gyhnbqy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.088 12.628c-.193-.156-1.045-.633-2.185-.562");
}

.wio6qjbis {
  fill: var(--svg-color--d2997d, #D2997D);
  d: path("M23.413 2.19h-3.426v3.742c0 .352-.226 1.036-.683 1.43a80 80 0 0 0-1.727 1.692a1.195 1.195 0 0 0 .026 1.715c.453.428 1.09.362 1.554-.055l.978-.74a.527.527 0 0 1 .88.393v3.328a1.2 1.2 0 0 0 2.398 0z");
}

.wj0_vcbzm {
  stop-color: var(--svg-color--c9a18c, #C9A18C);
  stop-opacity: 0;
}

.wt6f_i56x {
  d: path("M22.79 7.736h-3.173V5.932c0 .352-.21 1.036-.633 1.43a77 77 0 0 0-1.6 1.692a1.263 1.263 0 0 0 .025 1.715c.42.428 1.01.362 1.44-.055l.905-.74a.464.464 0 0 1 .692.044c.08.096.123.22.123.35v3.327c0 .662.497 1.199 1.11 1.199s1.111-.537 1.111-1.2z");
}

.xk4wwk53d {
  stop-color: var(--svg-color--be7d75, #BE7D75);
}

.xms_-vb8m {
  stop-color: var(--svg-color--fbc8a8, #FBC8A8);
}

.xpw1soq4x {
  d: path("m9.457 9.42l1.31.78v3.433a.656.656 0 0 1-1.31 0z");
}

.xtumd7buv {
  stop-color: var(--svg-color--e2a481, #E2A481);
}

.y_s895zcx {
  stop-color: var(--svg-color--f3c0a4, #F3C0A4);
}

.y7usumbmg {
  stop-color: var(--svg-color--a57045, #A57045);
}

.yp6fmsbhu {
  stop-color: var(--svg-color--f2bea5, #F2BEA5);
}

.z4gay0bfu {
  stop-color: var(--svg-color--e0a993, #E0A993);
}

.zbnzybbvq {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M14.357 17.742c.344.18.879.384 1.649.384s1.304-.203 1.648-.384c.108-.056.243.014.25.135a.15.15 0 0 1-.014.077c-.76 1.471-3.066 1.456-3.769 0a.15.15 0 0 1-.014-.077c.008-.121.142-.191.25-.135Z");
}

.zpoasobui {
  stop-color: var(--svg-color--e7b79d, #E7B79D);
}

</style>
