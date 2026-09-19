<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ipZsLCb)"><circle fill="url(#ihfasrb)" class="c3vm8kt4c"/></g><circle fill="url(#iXJSird)" class="c3vm8kt4c"/><g filter="url(#iq0VzMc)"><circle fill="url(#iakjlHD)" class="n73l6to2h"/></g><g filter="url(#iQSaZtb)"><circle fill="url(#itEQiXd)" class="jvwpinbbf"/><circle fill="url(#icjKeib)" class="jvwpinbbf"/></g><g filter="url(#icB4Qeb)"><circle class="ojwph191t"/><circle fill="url(#iGvcgQc)" class="xq483lxba"/><circle fill="url(#i908nCd)" class="xq483lxba"/></g><g filter="url(#ikqj0XT)"><path fill="url(#imCFeze)" class="ynirw2ymx"/><path fill="url(#iVeinvc)" class="ynirw2ymx"/><path fill="url(#idYopyx)" class="ynirw2ymx"/></g><path fill="url(#ivJHCOb)" class="bhop8fbem"/><path fill="url(#iECFD7c)" class="bhop8fbem"/><path fill="url(#iH4EP2s)" class="bhop8fbem"/><path fill="url(#icp8Ssb)" class="bhop8fbem"/><g filter="url(#ijESDod)"><path fill="url(#idiIr3g)" class="e8a_315he"/></g><g filter="url(#iyDQ52b)"><path class="tx0tgqbil"/><path fill="url(#iuju5zb)" class="bicfkub5q"/><path fill="url(#iivwVBb)" class="bicfkub5q"/><path fill="url(#iAjKXcc)" class="bicfkub5q"/><path fill="url(#i6fYkMj)" class="bicfkub5q"/></g><g filter="url(#iLOVjQd)"><path class="u63y8kyjw"/></g><g filter="url(#iPw8zee)"><path class="sil8_ybje"/><path fill="url(#iSkR7be)" class="bdg888bzf"/><path fill="url(#inVfqIb)" class="bdg888bzf"/><path fill="url(#iW23zNb)" class="bdg888bzf"/><path fill="url(#iqoQyFd)" class="bdg888bzf"/></g><path fill="url(#iCOHMsS)" class="bdg888bzf"/><g filter="url(#iVcrIMb)"><path fill="url(#i0iIfob)" class="rfsqqdbgs"/></g><path fill="url(#i7BQ8Mt)" class="rfsqqdbgs"/><path fill="url(#iFbYfNe)" class="rfsqqdbgs"/><path stroke="url(#ivmq2db)" class="vi339ibhm"/><g filter="url(#ia7ohjb)"><path class="bj97t-e-o"/><path fill="url(#ik4osEZ)" class="yz922p82o"/></g><g filter="url(#i0DHl5b)"><path class="tfmsqfbci"/><path fill="url(#iHRSQld)" class="m7-ifotee"/></g><path class="pdv4ldbpr"/><path fill="url(#ixkpixM)" class="m8cdxvtli"/><path class="heacg5ncs"/><g filter="url(#ia2nFkd)"><path class="vxy28rbkx"/><path fill="url(#iO48bjt)" class="y1c__-95e"/></g><g filter="url(#iT0VkOc)"><path fill="url(#ikMrDfd)" class="i_ux49j5u"/></g><path class="l6wzmlbrw"/><path fill="url(#iYkfqQb)" class="pymlyd-1i"/><path class="uozffyiai"/><g filter="url(#iu5Byyd)"><path fill="url(#itFLHzb)" class="sow05c3ou"/></g><g filter="url(#ihuGTzM)"><ellipse transform="rotate(-27.914 11.367 16.608)" class="xk1wlybvw"/><ellipse fill="url(#ivdEdNn)" transform="rotate(-27.914 11.367 16.608)" class="bz40dzb6n"/></g><g filter="url(#iu73Xxb)"><path stroke="url(#iBW1Lle)" class="khbuz0hlc"/></g><g filter="url(#iwoMHad)"><path stroke="url(#iZIIH4X)" class="ut7qi9bnx"/></g><g filter="url(#icE8fue)"><path stroke="url(#i5B9jKc)" class="xg13maboi"/></g><defs><radialGradient id="ihfasrb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iXJSird" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 9.06 8.74)scale(3.08956)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="icjKeib" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.564)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iGvcgQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="i908nCd" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.54 39.223)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iVeinvc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.4375 3 0 20.321 15.688)" gradientUnits="userSpaceOnUse"><stop class="e6v6vrbif"/><stop offset="1" class="qmnjff_ag"/></radialGradient><radialGradient id="idYopyx" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5625 3.1867 0 11.821 15.938)" gradientUnits="userSpaceOnUse"><stop class="c02-eqbxv"/><stop offset="1" class="mmmkqcbgq"/></radialGradient><radialGradient id="iH4EP2s" cx="0" cy="0" r="1" gradientTransform="matrix(0 15.25 -20.7011 0 15.384 14.75)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="kwao9fbqu"/><stop offset="1" class="wv6j595ib"/></radialGradient><radialGradient id="iuju5zb" cx="0" cy="0" r="1" gradientTransform="matrix(1.4878 -5.51363 2.04463 .55172 24.05 10.4)" gradientUnits="userSpaceOnUse"><stop class="ki2rd4v4k"/><stop offset="1" class="tp9jx5j2y"/></radialGradient><radialGradient id="iivwVBb" cx="0" cy="0" r="1" gradientTransform="matrix(7.13272 .65639 -.35293 3.83521 20.986 7.12)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="je_aabb8l"/><stop offset="1" class="ivhsfvmdg"/></radialGradient><radialGradient id="iAjKXcc" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.1314 -4.84965 0 15.946 2.019)" gradientUnits="userSpaceOnUse"><stop class="n7o-m0b5s"/><stop offset="1" class="xp-9f0bqu"/></radialGradient><radialGradient id="i6fYkMj" cx="0" cy="0" r="1" gradientTransform="rotate(-36.235 24.475 1.376)scale(7.1069 11.1342)" gradientUnits="userSpaceOnUse"><stop class="ux7-g74jy"/><stop offset="1" class="dd8hfetks"/></radialGradient><radialGradient id="iqoQyFd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .36719 -1.17969 0 16.556 21.055)" gradientUnits="userSpaceOnUse"><stop class="mifq-tdon"/><stop offset="1" class="n-ko-_w7d"/></radialGradient><radialGradient id="iFbYfNe" cx="0" cy="0" r="1" gradientTransform="matrix(10.27866 11.34214 -10.35892 9.38763 13.532 17.04)" gradientUnits="userSpaceOnUse"><stop offset=".882" class="k2624-bzd"/><stop offset="1" class="j_oxsvb4g"/></radialGradient><radialGradient id="ik4osEZ" cx="0" cy="0" r="1" gradientTransform="matrix(.1943 -1.125 3.32822 .57484 20.502 14.172)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iHRSQld" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 13.866 .613)scale(1.14166 3.37768)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="ixkpixM" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51263 -2.40601 0 20.01 16.787)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="iO48bjt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.941 3.676)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="iYkfqQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.51271 -2.40614 0 11.873 16.787)" gradientUnits="userSpaceOnUse"><stop offset=".802" class="e0-rnofaa"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="l7c47o-wr"/></radialGradient><radialGradient id="ivdEdNn" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.134 3.016)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><linearGradient id="iakjlHD" x1="7.092" x2="5.898" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="itEQiXd" x1="26.859" x2="25.332" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="imCFeze" x1="23.473" x2="9.231" y1="18.785" y2="20.907" gradientUnits="userSpaceOnUse"><stop class="f43nfdclv"/><stop offset="1" class="ixdockwro"/></linearGradient><linearGradient id="ivJHCOb" x1="5.884" x2="9.392" y1="23.813" y2="23.688" gradientUnits="userSpaceOnUse"><stop class="xaj4s_mqh"/><stop offset="1" class="nzdq87b8k"/></linearGradient><linearGradient id="iECFD7c" x1="25.123" x2="23.049" y1="22.243" y2="22.063" gradientUnits="userSpaceOnUse"><stop class="mxfqo-b2y"/><stop offset="1" class="z8_150olp"/></linearGradient><linearGradient id="icp8Ssb" x1="16" x2="16" y1="28.283" y2="30.24" gradientUnits="userSpaceOnUse"><stop offset=".533" class="n3-c-obfq"/><stop offset="1" class="o40bvx3go"/></linearGradient><linearGradient id="idiIr3g" x1="14.955" x2="30.142" y1="13.219" y2="7.781" gradientUnits="userSpaceOnUse"><stop class="m26ledckw"/><stop offset="1" class="yudgedput"/></linearGradient><linearGradient id="iSkR7be" x1="14.335" x2="16.084" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="brzpz-p3w"/><stop offset="1" class="qxphtrj0e"/></linearGradient><linearGradient id="inVfqIb" x1="17.696" x2="15.784" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="hcuo1obkg"/><stop offset="1" class="soj01hbui"/></linearGradient><linearGradient id="iW23zNb" x1="16.309" x2="16.309" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="xk94moblk"/><stop offset="1" class="v1vf9kb3x"/></linearGradient><linearGradient id="iCOHMsS" x1="16.181" x2="16.181" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="kpt7nxbeg"/><stop offset="1" class="c70lx944e"/></linearGradient><linearGradient id="i0iIfob" x1="8.628" x2="23.068" y1="28.288" y2="24.201" gradientUnits="userSpaceOnUse"><stop offset=".314" class="br55lrb1z"/><stop offset="1" class="pkmn19a-q"/></linearGradient><linearGradient id="i7BQ8Mt" x1="6.236" x2="8.846" y1="22.514" y2="22.435" gradientUnits="userSpaceOnUse"><stop class="d8dwzzoam"/><stop offset="1" class="e6w-abbsd"/></linearGradient><linearGradient id="ivmq2db" x1="14.123" x2="14.891" y1="25.364" y2="24.15" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ikMrDfd" x1="21.46" x2="20.875" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itFLHzb" x1="13.26" x2="12.675" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBW1Lle" x1="21.489" x2="20.706" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iZIIH4X" x1="11.597" x2="9.379" y1="12.659" y2="11.729" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="i5B9jKc" x1="7.253" x2="7.253" y1="8.902" y2="12.925" gradientUnits="userSpaceOnUse"><stop offset=".228" class="zw2ljvb-t"/><stop offset="1" class="ohs50t_5m"/></linearGradient><filter id="ipZsLCb" width="6.427" height="6.227" x="3.979" y="14.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19842"/></filter><filter id="iq0VzMc" width="4.711" height="4.711" x="4.737" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".25"/></filter><filter id="iQSaZtb" width="6.477" height="6.477" x="21.72" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19842"/></filter><filter id="icB4Qeb" width="4.711" height="4.711" x="22.478" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".25"/></filter><filter id="ikqj0XT" width="19.345" height="22.68" x="6.327" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.2 0 0 0 0 0.172549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19842"/></filter><filter id="ijESDod" width="11.918" height="9.719" x="14.263" y="5.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation="1"/></filter><filter id="iyDQ52b" width="23.5" height="15.5" x="4.196" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.109804 0 0 0 0 0.109804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19842"/></filter><filter id="iLOVjQd" width="4.782" height="6.5" x="13.11" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".375"/></filter><filter id="iPw8zee" width="4" height="5.5" x="13.946" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".125"/></filter><filter id="iVcrIMb" width="20.086" height="16.516" x="5.936" y="13.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.105882 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19842"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.341176 0 0 0 0 0.266667 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_19842" result="effect2_innerShadow_3987_19842"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".35"/><feGaussianBlur stdDeviation=".175"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.121569 0 0 0 0 0.105882 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_3987_19842" result="effect3_innerShadow_3987_19842"/></filter><filter id="ia7ohjb" width="5.34" height="3.147" x="18.151" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19842"/></filter><filter id="i0DHl5b" width="5.341" height="3.147" x="8.551" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19842"/></filter><filter id="ia2nFkd" width="1.294" height="1.125" x="18.727" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".05"/></filter><filter id="iT0VkOc" width="1.316" height="1.357" x="20.38" y="16.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".1"/></filter><filter id="iu5Byyd" width="1.493" height="1.594" x="12.097" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".1"/></filter><filter id="ihuGTzM" width="1.529" height="1.141" x="10.603" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".05"/></filter><filter id="iu73Xxb" width="4.949" height="2.304" x="18.293" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".25"/></filter><filter id="iwoMHad" width="5.094" height="2.41" x="8.56" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".25"/></filter><filter id="icE8fue" width="1.231" height="3.583" x="6.637" y="8.711" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19842" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-beard-medium" /></template>
<style>
.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.bac636b7w {
  stop-color: var(--svg-color--5b4545, #5B4545);
}

.bdg888bzf {
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.bhop8fbem {
  d: path("M6.327 14.234c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L24.97 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.387-.373-6.785-.683-10.166");
}

.bicfkub5q {
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.bj97t-e-o {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.br55lrb1z {
  stop-color: var(--svg-color--321d2b, #321D2B);
}

.brzpz-p3w {
  stop-color: var(--svg-color--8b6455, #8B6455);
}

.bz40dzb6n {
  cx: 11.367px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.c02-eqbxv {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
}

.c3vm8kt4c {
  cx: 7.092px;
  cy: 18.059px;
  r: 3.113px;
}

.c70lx944e {
  stop-color: var(--svg-color--8e5263, #8E5263);
  stop-opacity: 0;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.d8dwzzoam {
  stop-color: var(--svg-color--5f4b49, #5F4B49);
}

.dd8hfetks {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
  stop-opacity: 0;
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.e6v6vrbif {
  stop-color: var(--svg-color--ab7773, #AB7773);
}

.e6w-abbsd {
  stop-color: var(--svg-color--5f4b49, #5F4B49);
  stop-opacity: 0;
}

.e8a_315he {
  d: path("m23.338 7.57l-5.74 1.913a1.953 1.953 0 0 0 .878 3.788l5.706-.764z");
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.f43nfdclv {
  stop-color: var(--svg-color--c69980, #C69980);
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.fr4wpbo2m {
  stop-color: var(--svg-color--422235, #422235);
}

.ft5dv1b6b {
  fill: none;
}

.fwwugibmc {
  stop-color: var(--svg-color--6e464d, #6E464D);
}

.hcuo1obkg {
  stop-color: var(--svg-color--cda186, #CDA186);
}

.heacg5ncs {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.i_ux49j5u {
  d: path("M21.496 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.ivhsfvmdg {
  stop-color: var(--svg-color--644949, #644949);
  stop-opacity: 0;
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.ixdockwro {
  stop-color: var(--svg-color--916762, #916762);
}

.j_oxsvb4g {
  stop-color: var(--svg-color--504046, #504046);
}

.je_aabb8l {
  stop-color: var(--svg-color--644949, #644949);
}

.jvwpinbbf {
  cx: 24.833px;
  cy: 18.059px;
  r: 3.113px;
}

.k2624-bzd {
  stop-color: var(--svg-color--504046, #504046);
  stop-opacity: 0;
}

.khbuz0hlc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.717c.802-.14 2.366-.1 3.449.742");
}

.ki2rd4v4k {
  stop-color: var(--svg-color--554042, #554042);
}

.kpt7nxbeg {
  stop-color: var(--svg-color--8e5263, #8E5263);
}

.kwao9fbqu {
  stop-color: var(--svg-color--975681, #975681);
  stop-opacity: 0;
}

.l6wzmlbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.l7c47o-wr {
  stop-color: var(--svg-color--664944, #664944);
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m26ledckw {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
}

.m7-ifotee {
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.m8cdxvtli {
  d: path("M20.013 15.897A1.664 1.664 0 0 1 21.617 18h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mifq-tdon {
  stop-color: var(--svg-color--c39787, #C39787);
}

.mmmkqcbgq {
  stop-color: var(--svg-color--8f5d65, #8F5D65);
  stop-opacity: 0;
}

.mxfqo-b2y {
  stop-color: var(--svg-color--c1987f, #C1987F);
}

.n-ko-_w7d {
  stop-color: var(--svg-color--c39787, #C39787);
  stop-opacity: 0;
}

.n3-c-obfq {
  stop-color: var(--svg-color--a66d9f, #A66D9F);
  stop-opacity: 0;
}

.n73l6to2h {
  cx: 7.092px;
  cy: 18.059px;
  r: 1.855px;
}

.n7o-m0b5s {
  stop-color: var(--svg-color--624c49, #624C49);
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.nzdq87b8k {
  stop-color: var(--svg-color--9b7569, #9B7569);
  stop-opacity: 0;
}

.o40bvx3go {
  stop-color: var(--svg-color--a66d9f, #A66D9F);
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ohs50t_5m {
  stop-color: var(--svg-color--4a3236, #4A3236);
  stop-opacity: 0;
}

.ojwph191t {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.pdv4ldbpr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.39c1.217 0 2.245.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pkmn19a-q {
  stop-color: var(--svg-color--4c383b, #4C383B);
}

.pymlyd-1i {
  d: path("M11.87 15.897A1.664 1.664 0 0 0 10.266 18h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.qmnjff_ag {
  stop-color: var(--svg-color--ab7773, #AB7773);
  stop-opacity: 0;
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.qxphtrj0e {
  stop-color: var(--svg-color--8b6455, #8B6455);
  stop-opacity: 0;
}

.rfsqqdbgs {
  d: path("m25.672 14.134l-.703 10.2c-.301 3.3-2.51 5.666-6.023 5.666h-6.024C9.41 30 7.2 27.634 6.9 24.334l-.663-9.345l3.072 8.045c.1.5.703.6 1.004.3l.803-.7c.703-.6 1.506-.8 2.31-.8h5.019c.903 0 1.706.2 2.309.8l.803.7c.301.3.903.1 1.004-.3zm-12.75 11.7c0 .9.803 1.7 1.807 1.7c.201 0 .301-.2.301-.3v-.1c0-.5.402-.9.904-.9s.903.4.903.9v.1c0 .2.201.3.302.3c.903 0 1.807-.7 1.807-1.7v-1.5c0-.5-.347-.9-1.004-.9h-4.016c-.636 0-1.004.4-1.004.9z");
}

.sil8_ybje {
  fill: var(--svg-color--b7877d, #B7877D);
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.soj01hbui {
  stop-color: var(--svg-color--cda186, #CDA186);
  stop-opacity: 0;
}

.sow05c3ou {
  d: path("M13.39 17.366c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.ssfga94sp {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
}

.suj-pjbhk {
  stop-color: var(--svg-color--895f52, #895F52);
}

.t-wcrfbaw {
  stop-color: var(--svg-color--a87d7b, #A87D7B);
  stop-opacity: 0;
}

.tfmsqfbci {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.tp9jx5j2y {
  stop-color: var(--svg-color--554042, #554042);
  stop-opacity: 0;
}

.tx0tgqbil {
  fill: var(--svg-color--4f3332, #4F3332);
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1 .298 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.u63y8kyjw {
  fill: var(--svg-color--87565c, #87565C);
  d: path("M15.433 17.83L13.903 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.uozffyiai {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.ut7qi9bnx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.684c.61-.54 1.942-1.107 3.593-.844");
}

.ux7-g74jy {
  stop-color: var(--svg-color--4e3c3a, #4E3C3A);
}

.v1vf9kb3x {
  stop-color: var(--svg-color--9c6073, #9C6073);
  stop-opacity: 0;
}

.vi339ibhm {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.531 23.683a.32.32 0 0 0-.382.066a.29.29 0 0 0-.032.375a3.39 3.39 0 0 0 2.837 1.515a3.4 3.4 0 0 0 2.837-1.515a.295.295 0 0 0-.033-.379a.32.32 0 0 0-.38-.063h-.001c-.7.366-1.526.575-2.423.575c-.888 0-1.722-.21-2.423-.574Z");
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vxy28rbkx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.wv6j595ib {
  stop-color: var(--svg-color--975681, #975681);
}

.xaj4s_mqh {
  stop-color: var(--svg-color--9b7569, #9B7569);
}

.xg13maboi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M7.493 9.086v1.674c-.014.277-.131.897-.481 1.16");
}

.xk1wlybvw {
  cx: 11.367px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.xk94moblk {
  stop-color: var(--svg-color--9c6073, #9C6073);
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xp-9f0bqu {
  stop-color: var(--svg-color--624c49, #624C49);
  stop-opacity: 0;
}

.xq483lxba {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
}

.y1c__-95e {
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.ynirw2ymx {
  d: path("M6.436 16.916q.045.003.091.003s-.1-1.591-.2-2.685c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L24.97 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6z");
}

.yudgedput {
  stop-color: var(--svg-color--c89f8b, #C89F8B);
  stop-opacity: 0;
}

.yz922p82o {
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.z8_150olp {
  stop-color: var(--svg-color--c1987f, #C1987F);
  stop-opacity: 0;
}

.zw2ljvb-t {
  stop-color: var(--svg-color--4a3236, #4A3236);
}

</style>
