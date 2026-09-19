<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iIr896J)"><circle fill="url(#ihfasrb)" class="c3vm8kt4c"/></g><circle fill="url(#iXJSird)" class="c3vm8kt4c"/><g filter="url(#iVQT9Pb)"><circle fill="url(#iakjlHD)" class="n73l6to2h"/></g><g filter="url(#ibPwRDA)"><circle fill="url(#itEQiXd)" class="jvwpinbbf"/><circle fill="url(#icjKeib)" class="jvwpinbbf"/></g><g filter="url(#izD6aad)"><circle class="ojwph191t"/><circle fill="url(#iGvcgQc)" class="xq483lxba"/><circle fill="url(#i908nCd)" class="xq483lxba"/></g><g filter="url(#inaJnwR)"><path fill="url(#iNCB7eb)" class="bhop8fbem"/><path fill="url(#ibdGQ1c)" class="bhop8fbem"/><path fill="url(#ij1LOOT)" class="bhop8fbem"/><path fill="url(#izRpLNc)" class="bhop8fbem"/><path fill="url(#iH2jf2b)" class="bhop8fbem"/><path fill="url(#iXXJ1JO)" class="bhop8fbem"/><path fill="url(#ivkn07d)" class="bhop8fbem"/></g><g filter="url(#iCcafvd)"><path fill="url(#ibLU5IW)" class="y7d3--b_f"/></g><g filter="url(#iKzsGiI)"><path fill="url(#isUxwxM)" class="ynsl3-bvt"/><path fill="url(#iq28ndc)" class="ynsl3-bvt"/><path fill="url(#iaLExbc)" class="ynsl3-bvt"/><path fill="url(#iZXjRPb)" class="ynsl3-bvt"/><path fill="url(#iHC9ARb)" class="ynsl3-bvt"/><path fill="url(#i42KZxc)" class="ynsl3-bvt"/></g><path fill="url(#iFldDEc)" class="ynsl3-bvt"/><path fill="url(#i0riIbb)" class="ynsl3-bvt"/><path fill="url(#iBJdSec)" class="ynsl3-bvt"/><g filter="url(#ij4OoBc)"><path class="dcdmvkblx"/></g><g filter="url(#iKTMDXb)"><path class="eyb42pxde"/><path fill="url(#iW0GKob)" class="bdg888bzf"/><path fill="url(#iNxtiMd)" class="bdg888bzf"/><path fill="url(#iiCeGfF)" class="bdg888bzf"/><path fill="url(#ij9bxDB)" class="bdg888bzf"/></g><path fill="url(#ixHSIGQ)" class="bdg888bzf"/><path fill="url(#iYvVRWZ)" class="bdg888bzf"/><path stroke="url(#ikmSEle)" class="j6ynxe8oa"/><g filter="url(#i8Y63hc)"><path class="bj97t-e-o"/><path fill="url(#ik4osEZ)" class="yz922p82o"/></g><g filter="url(#imBLsWb)"><path class="tfmsqfbci"/><path fill="url(#iHRSQld)" class="m7-ifotee"/></g><path class="pdv4ldbpr"/><path fill="url(#iT72KYv)" class="ysuyqjbga"/><path class="heacg5ncs"/><g filter="url(#if6imAm)"><path class="z98s40bed"/><path fill="url(#iO48bjt)" class="z20bumf_j"/></g><g filter="url(#iw1lEQe)"><path fill="url(#ikMrDfd)" class="i_ux49j5u"/></g><path class="l6wzmlbrw"/><path fill="url(#igY4D7c)" class="pymlyd-1i"/><path class="uozffyiai"/><g filter="url(#iAKJ7Fc)"><path fill="url(#itFLHzb)" class="sow05c3ou"/></g><g filter="url(#ihrcqvU)"><ellipse transform="rotate(-27.914 11.367 16.608)" class="xk1wlybvw"/><ellipse fill="url(#ivdEdNn)" transform="rotate(-27.914 11.367 16.608)" class="bz40dzb6n"/></g><g filter="url(#i1K5KGd)"><path stroke="url(#iBW1Lle)" class="khbuz0hlc"/></g><g filter="url(#iNBkstc)"><path stroke="url(#iZIIH4X)" class="ut7qi9bnx"/></g><defs><radialGradient id="ihfasrb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="n91c-gs8j"/><stop offset="1" class="qo7u-3bcf"/></radialGradient><radialGradient id="iXJSird" cx="0" cy="0" r="1" gradientTransform="rotate(-124.98 9.06 8.74)scale(3.08956)" gradientUnits="userSpaceOnUse"><stop offset=".34" class="ev4-2pfvs"/><stop offset="1" class="w_j-6pbpp"/></radialGradient><radialGradient id="icjKeib" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.564)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="cu-ecjbbc"/><stop offset="1" class="a1ftncccj"/></radialGradient><radialGradient id="iGvcgQc" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".755" class="d66ufbbtl"/><stop offset=".916" class="f7hwkw-sq"/></radialGradient><radialGradient id="i908nCd" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.54 39.223)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="suj-pjbhk"/><stop offset="1" class="dg9o8ubcl"/></radialGradient><radialGradient id="iNCB7eb" cx="0" cy="0" r="1" gradientTransform="matrix(-14.1844 0 0 -27.6939 24.188 20.375)" gradientUnits="userSpaceOnUse"><stop class="x7lp2x0zc"/><stop offset="1" class="ffzvz8jrp"/></radialGradient><radialGradient id="ij1LOOT" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.3495 -27.7163 0 17.216 14.246)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="af56bb4nm"/><stop offset=".955" class="zusd0j8mb"/></radialGradient><radialGradient id="izRpLNc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.9969 0 0 -3.02146 18.111 17.688)" gradientUnits="userSpaceOnUse"><stop class="j0j_1pbxv"/><stop offset="1" class="fde8ih7ep"/></radialGradient><radialGradient id="iH2jf2b" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 2.93253 0 20.321 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="y6q4zbbhp"/><stop offset="1" class="hg6yik0zt"/></radialGradient><radialGradient id="iXXJ1JO" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 15.625)" gradientUnits="userSpaceOnUse"><stop class="dcn54acig"/><stop offset="1" class="c2yq8qy6f"/></radialGradient><radialGradient id="ivkn07d" cx="0" cy="0" r="1" gradientTransform="matrix(-8.16694 4.8677 -4.19823 -7.04371 26.313 10.25)" gradientUnits="userSpaceOnUse"><stop class="misj73bwd"/><stop offset="1" class="y1nh9mz_o"/></radialGradient><radialGradient id="iq28ndc" cx="0" cy="0" r="1" gradientTransform="rotate(-169.032 11.112 3.065)scale(8.21251 6.30254)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="tzxi8pb6h"/><stop offset="1" class="hmx8eit6p"/></radialGradient><radialGradient id="iaLExbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56248 -7.49998 14.07497 -1.05559 26.813 17.017)" gradientUnits="userSpaceOnUse"><stop class="gg3p-v-oi"/><stop offset="1" class="go8dnjb_b"/></radialGradient><radialGradient id="iZXjRPb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.625 1.78488 10.88777 3.813 11.563)" gradientUnits="userSpaceOnUse"><stop class="zk1gozblh"/><stop offset="1" class="o7liw8bnz"/></radialGradient><radialGradient id="iHC9ARb" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 1.40625 -6.20388 5.23883 7.813 4.813)" gradientUnits="userSpaceOnUse"><stop class="hchmvbcwb"/><stop offset="1" class="ei1bt-b0e"/></radialGradient><radialGradient id="i42KZxc" cx="0" cy="0" r="1" gradientTransform="rotate(80.538 7.776 11.423)scale(1.61573 2.88964)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="e_h6jabwf"/><stop offset="1" class="moyyndcqm"/></radialGradient><radialGradient id="iFldDEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 -4.59375 1.72724 -.094 8.219 11.813)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="sn-n94bif"/><stop offset="1" class="vu7vn7bhc"/></radialGradient><radialGradient id="i0riIbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69638 -4.375 1.72998 -.27536 4.196 11.125)" gradientUnits="userSpaceOnUse"><stop class="sdjph8tjs"/><stop offset="1" class="xhmtc9b9f"/></radialGradient><radialGradient id="iBJdSec" cx="0" cy="0" r="1" gradientTransform="matrix(1.11615 -6 2.3152 .43068 27.696 14.375)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="t7o6ccjes"/><stop offset="1" class="kd9fr-txf"/></radialGradient><radialGradient id="iW0GKob" cx="0" cy="0" r="1" gradientTransform="matrix(-.84932 -3.81088 1.17448 -.26175 17.409 20.546)" gradientUnits="userSpaceOnUse"><stop offset=".017" class="ab1vgh_ru"/><stop offset="1" class="f80hfjhpj"/></radialGradient><radialGradient id="ij9bxDB" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45312 0 0 -.40625 16.962 20.94)" gradientUnits="userSpaceOnUse"><stop class="hjp773b9j"/><stop offset="1" class="wh0vrhbzi"/></radialGradient><radialGradient id="iYvVRWZ" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5565 1.75513 -2.1094 -3.07252 16.65 19.831)" gradientUnits="userSpaceOnUse"><stop offset=".778" class="xs9vt_bzp"/><stop offset="1" class="p13423bzd"/><stop offset="1" class="jjvamgr7p"/></radialGradient><radialGradient id="ik4osEZ" cx="0" cy="0" r="1" gradientTransform="matrix(.1943 -1.125 3.32822 .57484 20.502 14.172)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iHRSQld" cx="0" cy="0" r="1" gradientTransform="rotate(-80.2 13.866 .613)scale(1.14166 3.37768)" gradientUnits="userSpaceOnUse"><stop class="fr4wpbo2m"/><stop offset="1" class="xo-sv8bhm"/></radialGradient><radialGradient id="iT72KYv" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="e0-rnofaa"/><stop offset="1" class="qh547r7uu"/></radialGradient><radialGradient id="iO48bjt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.941 3.676)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="igY4D7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="e0-rnofaa"/><stop offset="1" class="qh547r7uu"/></radialGradient><radialGradient id="ivdEdNn" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.134 3.016)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iIr896J" width="6.427" height="6.227" x="3.979" y="14.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.619608 0 0 0 0 0.470588 0 0 0 0 0.407843 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20012"/></filter><filter id="iVQT9Pb" width="4.711" height="4.711" x="4.737" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".25"/></filter><filter id="ibPwRDA" width="6.477" height="6.477" x="21.72" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.584314 0 0 0 0 0.368627 0 0 0 0 0.470588 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20012"/></filter><filter id="izD6aad" width="4.711" height="4.711" x="22.478" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".25"/></filter><filter id="inaJnwR" width="19.345" height="22.73" x="6.327" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".3"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.435294 0 0 0 0 0.231373 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20012"/></filter><filter id="iCcafvd" width="11.918" height="9.719" x="15.009" y="5.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation="1"/></filter><filter id="iKzsGiI" width="23.5" height="15.5" x="4.196" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.262745 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20012"/></filter><filter id="ij4OoBc" width="4.282" height="6" x="13.36" y="16.804" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".25"/></filter><filter id="iKTMDXb" width="4" height="5.5" x="13.946" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".125"/></filter><filter id="i8Y63hc" width="5.34" height="3.147" x="18.151" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20012"/></filter><filter id="imBLsWb" width="5.341" height="3.147" x="8.551" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.156863 0 0 0 0 0.152941 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20012"/></filter><filter id="if6imAm" width="1.294" height="1.125" x="18.727" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".05"/></filter><filter id="iw1lEQe" width="1.316" height="1.357" x="20.38" y="16.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".1"/></filter><filter id="iAKJ7Fc" width="1.493" height="1.594" x="12.097" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".1"/></filter><filter id="ihrcqvU" width="1.529" height="1.141" x="10.603" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".05"/></filter><filter id="i1K5KGd" width="4.949" height="2.304" x="18.293" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".25"/></filter><filter id="iNBkstc" width="5.094" height="2.41" x="8.56" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20012" stdDeviation=".25"/></filter><linearGradient id="iakjlHD" x1="7.092" x2="5.898" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="vo9agqbnp"/><stop offset="1" class="fwwugibmc"/></linearGradient><linearGradient id="itEQiXd" x1="26.859" x2="25.332" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="ix2ytv1nc"/><stop offset="1" class="sla6kib8v"/></linearGradient><linearGradient id="ibdGQ1c" x1="5.688" x2="9.469" y1="23.188" y2="23" gradientUnits="userSpaceOnUse"><stop offset=".323" class="yh8fa0s0y"/><stop offset="1" class="sisw5eb6e"/></linearGradient><linearGradient id="ibLU5IW" x1="15.701" x2="30.889" y1="13.219" y2="7.781" gradientUnits="userSpaceOnUse"><stop class="wph0opaub"/><stop offset="1" class="cvo9a4s4m"/></linearGradient><linearGradient id="isUxwxM" x1="3.433" x2="25.91" y1="11.365" y2="11.365" gradientUnits="userSpaceOnUse"><stop class="z8b5eybgc"/><stop offset=".349" class="rkde3beof"/><stop offset="1" class="q1uq6hbwz"/></linearGradient><linearGradient id="iNxtiMd" x1="14.196" x2="15.946" y1="20.682" y2="20.682" gradientUnits="userSpaceOnUse"><stop class="hm31m3bmo"/><stop offset="1" class="vh12xwf7a"/></linearGradient><linearGradient id="iiCeGfF" x1="15.946" x2="15.946" y1="22" y2="20.831" gradientUnits="userSpaceOnUse"><stop class="us3ue9b4r"/><stop offset="1" class="hxr-reb3g"/></linearGradient><linearGradient id="ixHSIGQ" x1="16.092" x2="16.092" y1="22.123" y2="21.863" gradientUnits="userSpaceOnUse"><stop class="b576ppbxh"/><stop offset="1" class="a_xwx-nqh"/></linearGradient><linearGradient id="ikmSEle" x1="14.012" x2="14.824" y1="25.012" y2="23.73" gradientUnits="userSpaceOnUse"><stop class="ssfga94sp"/><stop offset=".663" class="t-wcrfbaw"/></linearGradient><linearGradient id="ikMrDfd" x1="21.46" x2="20.875" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itFLHzb" x1="13.26" x2="12.675" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iBW1Lle" x1="21.489" x2="20.706" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient><linearGradient id="iZIIH4X" x1="11.597" x2="9.379" y1="12.659" y2="11.729" gradientUnits="userSpaceOnUse"><stop class="bac636b7w"/><stop offset="1" class="eqzjb1bwj"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-red-hair-medium" /></template>
<style>
.a_xwx-nqh {
  stop-color: var(--svg-color--8f5269, #8F5269);
  stop-opacity: 0;
}

.a1ftncccj {
  stop-color: var(--svg-color--8f6459, #8F6459);
  stop-opacity: 0;
}

.ab1vgh_ru {
  stop-color: var(--svg-color--cda38b, #CDA38B);
}

.af56bb4nm {
  stop-color: var(--svg-color--a9717e, #A9717E);
  stop-opacity: 0;
}

.b576ppbxh {
  stop-color: var(--svg-color--8f5269, #8F5269);
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

.bj97t-e-o {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.bz40dzb6n {
  cx: 11.367px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.c2yq8qy6f {
  stop-color: var(--svg-color--8e5c65, #8E5C65);
  stop-opacity: 0;
}

.c3vm8kt4c {
  cx: 7.092px;
  cy: 18.059px;
  r: 3.113px;
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.cu-ecjbbc {
  stop-color: var(--svg-color--8f6459, #8F6459);
}

.cvo9a4s4m {
  stop-color: var(--svg-color--c79e8a, #C79E8A);
  stop-opacity: 0;
}

.d66ufbbtl {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
  stop-opacity: 0;
}

.dcdmvkblx {
  fill: var(--svg-color--88555f, #88555F);
  d: path("M15.433 17.83L13.903 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.dcn54acig {
  stop-color: var(--svg-color--8e5c65, #8E5C65);
}

.dg9o8ubcl {
  stop-color: var(--svg-color--895f52, #895F52);
  stop-opacity: 0;
}

.e_h6jabwf {
  stop-color: var(--svg-color--bd765f, #BD765F);
}

.e0-rnofaa {
  stop-color: var(--svg-color--7d574a, #7D574A);
}

.ei1bt-b0e {
  stop-color: var(--svg-color--af725f, #AF725F);
  stop-opacity: 0;
}

.eqzjb1bwj {
  stop-color: var(--svg-color--5b4545, #5B4545);
  stop-opacity: 0;
}

.ev4-2pfvs {
  stop-color: var(--svg-color--834e63, #834E63);
}

.eyb42pxde {
  fill: var(--svg-color--b38578, #B38578);
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.f7hwkw-sq {
  stop-color: var(--svg-color--8a5d55, #8A5D55);
}

.f80hfjhpj {
  stop-color: var(--svg-color--cda38b, #CDA38B);
  stop-opacity: 0;
}

.fde8ih7ep {
  stop-color: var(--svg-color--c99b83, #C99B83);
  stop-opacity: 0;
}

.ffzvz8jrp {
  stop-color: var(--svg-color--956b63, #956B63);
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

.gg3p-v-oi {
  stop-color: var(--svg-color--d56a42, #D56A42);
}

.go8dnjb_b {
  stop-color: var(--svg-color--d56a42, #D56A42);
  stop-opacity: 0;
}

.hchmvbcwb {
  stop-color: var(--svg-color--af725f, #AF725F);
}

.heacg5ncs {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.hg6yik0zt {
  stop-color: var(--svg-color--ab7772, #AB7772);
  stop-opacity: 0;
}

.hjp773b9j {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
}

.hm31m3bmo {
  stop-color: var(--svg-color--875f54, #875F54);
}

.hmx8eit6p {
  stop-color: var(--svg-color--f78d61, #F78D61);
  stop-opacity: 0;
}

.hxr-reb3g {
  stop-color: var(--svg-color--995c76, #995C76);
  stop-opacity: 0;
}

.i_ux49j5u {
  d: path("M21.496 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.ix2ytv1nc {
  stop-color: var(--svg-color--cca68c, #CCA68C);
}

.j0j_1pbxv {
  stop-color: var(--svg-color--c99b83, #C99B83);
}

.j6ynxe8oa {
  fill: var(--svg-color--88024e, #88024E);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.239a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.jjvamgr7p {
  stop-color: var(--svg-color--815553, #815553);
}

.jvwpinbbf {
  cx: 24.833px;
  cy: 18.059px;
  r: 3.113px;
}

.kd9fr-txf {
  stop-color: var(--svg-color--d57852, #D57852);
  stop-opacity: 0;
}

.khbuz0hlc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.717c.802-.14 2.366-.1 3.449.742");
}

.l6wzmlbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m7-ifotee {
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.misj73bwd {
  stop-color: var(--svg-color--b68c74, #B68C74);
}

.moyyndcqm {
  stop-color: var(--svg-color--bd765f, #BD765F);
  stop-opacity: 0;
}

.n73l6to2h {
  cx: 7.092px;
  cy: 18.059px;
  r: 1.855px;
}

.n91c-gs8j {
  stop-color: var(--svg-color--865d5f, #865D5F);
}

.o7liw8bnz {
  stop-color: var(--svg-color--ba7260, #BA7260);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.ojwph191t {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--a57c70, #A57C70);
}

.p13423bzd {
  stop-color: var(--svg-color--693b40, #693B40);
}

.pdv4ldbpr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.39c1.217 0 2.245.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pymlyd-1i {
  d: path("M11.87 15.897A1.664 1.664 0 0 0 10.266 18h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.q1uq6hbwz {
  stop-color: var(--svg-color--ea8455, #EA8455);
}

.qh547r7uu {
  stop-color: var(--svg-color--5e433e, #5E433E);
}

.qo7u-3bcf {
  stop-color: var(--svg-color--76594a, #76594A);
}

.rkde3beof {
  stop-color: var(--svg-color--c26333, #C26333);
}

.sdjph8tjs {
  stop-color: var(--svg-color--b97362, #B97362);
}

.sisw5eb6e {
  stop-color: var(--svg-color--997366, #997366);
  stop-opacity: 0;
}

.sla6kib8v {
  stop-color: var(--svg-color--ae7f75, #AE7F75);
}

.sn-n94bif {
  stop-color: var(--svg-color--de6f4f, #DE6F4F);
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

.t7o6ccjes {
  stop-color: var(--svg-color--d57852, #D57852);
}

.tfmsqfbci {
  fill: var(--svg-color--4c3230, #4C3230);
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.tzxi8pb6h {
  stop-color: var(--svg-color--f78d61, #F78D61);
}

.uozffyiai {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.us3ue9b4r {
  stop-color: var(--svg-color--995c76, #995C76);
}

.ut7qi9bnx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.684c.61-.54 1.942-1.107 3.593-.844");
}

.vh12xwf7a {
  stop-color: var(--svg-color--875f54, #875F54);
  stop-opacity: 0;
}

.vo9agqbnp {
  stop-color: var(--svg-color--694448, #694448);
}

.vu7vn7bhc {
  stop-color: var(--svg-color--de6f4f, #DE6F4F);
  stop-opacity: 0;
}

.w_j-6pbpp {
  stop-color: var(--svg-color--834e63, #834E63);
  stop-opacity: 0;
}

.wh0vrhbzi {
  stop-color: var(--svg-color--ca9f8c, #CA9F8C);
  stop-opacity: 0;
}

.wph0opaub {
  stop-color: var(--svg-color--c79e8a, #C79E8A);
}

.x7lp2x0zc {
  stop-color: var(--svg-color--c79881, #C79881);
}

.xhmtc9b9f {
  stop-color: var(--svg-color--b97362, #B97362);
  stop-opacity: 0;
}

.xk1wlybvw {
  cx: 11.367px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.xo-sv8bhm {
  stop-color: var(--svg-color--422235, #422235);
  stop-opacity: 0;
}

.xq483lxba {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
}

.xs9vt_bzp {
  stop-color: var(--svg-color--815553, #815553);
  stop-opacity: 0;
}

.y1nh9mz_o {
  stop-color: var(--svg-color--b68c74, #B68C74);
  stop-opacity: 0;
}

.y6q4zbbhp {
  stop-color: var(--svg-color--ab7772, #AB7772);
}

.y7d3--b_f {
  d: path("m24.084 7.57l-5.739 1.913a1.953 1.953 0 0 0 .877 3.788l5.706-.764z");
}

.yh8fa0s0y {
  stop-color: var(--svg-color--997366, #997366);
}

.ynsl3-bvt {
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1.03.513 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.ysuyqjbga {
  d: path("M20.013 15.898A1.664 1.664 0 0 1 21.617 18h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.663");
}

.yz922p82o {
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.z20bumf_j {
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.z8b5eybgc {
  stop-color: var(--svg-color--bc613d, #BC613D);
}

.z98s40bed {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.zk1gozblh {
  stop-color: var(--svg-color--ba7260, #BA7260);
}

.zusd0j8mb {
  stop-color: var(--svg-color--995784, #995784);
}

</style>
