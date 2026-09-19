<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iUWkDLe)" transform="rotate(39.16 14.713 7.665)" class="rrd7rxqch"/><path fill="url(#iwzUYNb)" class="uecjt6-ya"/><g filter="url(#iXra0ye)"><path fill="url(#ivkJnZV)" class="dqhsfdbqc"/><path fill="url(#icn8kLV)" class="dqhsfdbqc"/><path fill="url(#ilLEUBE)" class="dqhsfdbqc"/></g><path clip-rule="evenodd" class="z6ud28wib"/><g filter="url(#iTjoOLb)"><path clip-rule="evenodd" class="jbfg2bc5e"/></g><g filter="url(#i7hPHtL)"><path fill="url(#iXHfpZK)" class="amjnrylcs"/><path fill="url(#i6tHTab)" class="amjnrylcs"/></g><path fill="url(#i911Lne)" class="jvo0x_9jg"/><g filter="url(#ikZUg1b)"><path class="bd17vdbyu"/><path fill="url(#iv2Lxwd)" class="v80-hbb8u"/></g><path fill="url(#ieIGhAF)" class="mqqn1vb3r"/><path fill="url(#iNXa3re)" class="fqihh4bqw"/><path fill="url(#iF10YAb)" class="fqihh4bqw"/><path fill="url(#iEGUdqz)" class="fqihh4bqw"/><path fill="url(#ihuqSRn)" class="fqihh4bqw"/><g filter="url(#iu6Xnsc)"><path fill="url(#i6XUtte)" class="uen83-bab"/><path fill="url(#iXhbTqI)" class="uen83-bab"/><path fill="url(#indTnPZ)" class="uen83-bab"/></g><g filter="url(#ibVJpBe)"><rect fill="url(#iaLRvxb)" class="xz_nrebbp"/><rect fill="url(#iMY1cKP)" class="xz_nrebbp"/><rect fill="url(#ieLuxad)" class="xz_nrebbp"/><rect fill="url(#ipJOj2d)" class="xz_nrebbp"/></g><rect fill="url(#iI4Fm3b)" transform="rotate(-21.787 19.523 13.023)" class="mq16gsbnt"/><path fill="url(#inEH0le)" class="ob3ms9o6m"/><path fill="url(#i4ahhUb)" class="ob3ms9o6m"/><path fill="url(#iz3aofe)" class="ob3ms9o6m"/><g filter="url(#ijf88Rb)"><path fill="url(#iGmlt8P)" class="c2tm1ojel"/></g><g filter="url(#iI9xvTc)"><path fill="url(#i9z51rQ)" class="vpva1obir"/><path fill="url(#ijVRYbR)" class="vpva1obir"/><path fill="url(#ilphFac)" class="vpva1obir"/></g><g filter="url(#iZnltNc)"><path class="ixktmib9m"/><path fill="url(#ibvR9gb)" class="osvvk56wr"/></g><g filter="url(#iVLoxOe)"><path stroke="url(#iyq3Oob)" class="xblvjf0zf"/></g><g filter="url(#iSmJniX)"><path fill="url(#iUthgzd)" class="e6b0qcb4d"/></g><path class="qgvh60b9t"/><path fill="url(#iojOxic)" class="os4q-jbxt"/><path fill="url(#iYVD7Db)" class="z1k4z2bhw"/><path class="uboyb380j"/><defs><radialGradient id="iUWkDLe" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.33 9.636)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="bbppnek8h"/><stop offset="1" class="wj36x1bhr"/></radialGradient><radialGradient id="iwzUYNb" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.276 10.502)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="i531rrbeb"/><stop offset="1" class="zto3p_lef"/></radialGradient><radialGradient id="ivkJnZV" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.176 5.258)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="gyymo5b9p"/><stop offset="1" class="ikvhpob1k"/></radialGradient><radialGradient id="icn8kLV" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.885 10.166)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="v5j-79bqk"/><stop offset="1" class="r5lh8e62q"/></radialGradient><radialGradient id="ilLEUBE" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.06)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="uee_89odc"/><stop offset="1" class="g491cdewz"/></radialGradient><radialGradient id="iXHfpZK" cx="0" cy="0" r="1" gradientTransform="matrix(-4.31333 1.068 -1.15703 -4.67289 18.613 5.648)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="pb023zb_t"/><stop offset="1" class="t-gnmrvnp"/></radialGradient><radialGradient id="i6tHTab" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.09453 1.35194 0 14.823 6.835)" gradientUnits="userSpaceOnUse"><stop class="baj5svbcv"/><stop offset="1" class="od3gao5lw"/></radialGradient><radialGradient id="i911Lne" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 6.892)" gradientUnits="userSpaceOnUse"><stop class="arf1s8bxe"/><stop offset="1" class="zyktje01y"/></radialGradient><radialGradient id="iv2Lxwd" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.02 15.22)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ynstgccdl"/><stop offset="1" class="ph7rypboq"/></radialGradient><radialGradient id="ieIGhAF" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -48.974 48.634)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iEGUdqz" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 21.986)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="ihuqSRn" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.892)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="i6XUtte" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.229 15.07)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iXhbTqI" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.883 10.386)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="indTnPZ" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.08)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iMY1cKP" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.11)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="ieLuxad" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.582)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="ipJOj2d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.36)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="iI4Fm3b" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.283)" gradientUnits="userSpaceOnUse"><stop class="yj2immbwm"/><stop offset="1" class="g-0n7qbjd"/></radialGradient><radialGradient id="inEH0le" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.321 10.75)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iGmlt8P" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 20.923)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="ijVRYbR" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.892)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="ibvR9gb" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 13.871)" gradientUnits="userSpaceOnUse"><stop class="roxpyebqa"/><stop offset="1" class="xi66vkmon"/></radialGradient><radialGradient id="iUthgzd" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.11)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="v0g3nqbgo"/><stop offset="1" class="mcj2tdbkt"/></radialGradient><radialGradient id="iojOxic" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .53901 .14229 17.543 7.72)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="iYVD7Db" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.455)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="iXra0ye" width="4.17" height="4.439" x="14.414" y="5.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.458824 0 0 0 0 0.294118 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><filter id="iTjoOLb" width=".763" height=".367" x="17.245" y="6.551" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.243137 0 0 0 0 0.121569 0 0 0 0 0.192157 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><filter id="i7hPHtL" width="5.17" height="3.72" x="13.955" y="4.134" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.207843 0 0 0 0 0.0901961 0 0 0 0 0.141176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><filter id="ikZUg1b" width="6.377" height="6.141" x="9.574" y="8.915" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.203922 0 0 0 0 0.447059 0 0 0 0 0.780392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.447059 0 0 0 0 0.627451 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23072" result="effect2_innerShadow_3987_23072"/></filter><filter id="iu6Xnsc" width="27.983" height="6.037" x="2.059" y="20.486" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><filter id="ibVJpBe" width="24.059" height="2.191" x="3.886" y="15.487" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><filter id="ijf88Rb" width="6.802" height="6.803" x="8.337" y="19.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><filter id="iI9xvTc" width="27.983" height="6.037" x="1.959" y="23.986" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><filter id="iZnltNc" width="6.678" height="4.108" x="14.785" y="10.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.419608 0 0 0 0 0.462745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><filter id="iVLoxOe" width="5.181" height="3.008" x="14.805" y="11.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23072" stdDeviation=".2"/></filter><filter id="iSmJniX" width="3.882" height="3.705" x="12.803" y="9.211" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0941176 0 0 0 0 0.392157 0 0 0 0 0.709804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23072"/></filter><linearGradient id="iNXa3re" x1="25.051" x2="7.801" y1="18.83" y2="24.205" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iF10YAb" x1="27.145" x2="26.441" y1="20.392" y2="20.392" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="iaLRvxb" x1="16.015" x2="16.395" y1="15.236" y2="18.767" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="i4ahhUb" x1="17.168" x2="17.582" y1="16.271" y2="16.666" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="iz3aofe" x1="19.52" x2="19.184" y1="15.955" y2="15.603" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="i9z51rQ" x1="18.457" x2="12.738" y1="23.361" y2="33.455" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="ilphFac" x1="18.02" x2="18.02" y1="29.923" y2="29.642" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iyq3Oob" x1="15.734" x2="20.015" y1="12.216" y2="13.934" gradientUnits="userSpaceOnUse"><stop class="lhom_fbjg"/><stop offset="1" class="s09h4qbjb"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-rowing-boat-medium" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.amjnrylcs {
  d: path("M13.992 7.217c-.16-1.207.231-2.071.46-2.418a.98.98 0 0 1 .867-.515c.324-.004.493.168.75.12c.103-.018.474-.156.77.028c.246.153.445.234.605.234c.227 0 .557-.044.797.301c.25.36.543.332.695.574c.152.243.137.774-.277.97s-1.313-.212-1.641-.345s-.55-.074-.752.247c-.163.256-.462.31-.592.316c-.093.193-.307.696-.61.992c-.322.317-1 .035-1.072-.504");
}

.arf1s8bxe {
  stop-color: var(--svg-color--b69281, #B69281);
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.baj5svbcv {
  stop-color: var(--svg-color--4f3f3c, #4F3F3C);
}

.bbppnek8h {
  stop-color: var(--svg-color--8c4f4f, #8C4F4F);
}

.bd17vdbyu {
  fill: var(--svg-color--338ae5, #338AE5);
  d: path("M11.168 10.533c-1.006 1.23-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.719 1.172-3.375s.489-.871.555-1.347c.066-.477-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.c2tm1ojel {
  d: path("M11.366 20.287a1.917 1.917 0 0 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 1 1-2.712-2.711z");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.dqhsfdbqc {
  d: path("M15.931 9.626a4.2 4.2 0 0 1-1.203-.91c-.38-.408-.386-1-.172-1.514l.327-.786a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.003.372.067c.288.182.576.644.369 1.475c-.229 1.081-.501 1.744-.749 2.227c-.177.344-.533.572-.916.505a3.2 3.2 0 0 1-.718-.216");
}

.dzuixsuao {
  stop-color: var(--svg-color--55beff, #55BEFF);
  stop-opacity: 0;
}

.e_s-6on8g {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
  stop-opacity: 0;
}

.e21-2rm4b {
  stop-color: var(--svg-color--659941, #659941);
}

.e6b0qcb4d {
  d: path("M13.004 11.033a93 93 0 0 0 1.625 1.883l1.656-1.485c-.33-.396-1.117-1.303-1.617-1.765c-.625-.579-1.27-.192-1.469 0c-.172.165-.672.687-.195 1.367");
}

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.fqihh4bqw {
  d: path("m5.232 16.945l21.725-.022v6.25l-18.008-.117z");
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g-0n7qbjd {
  stop-color: var(--svg-color--a28169, #A28169);
}

.g491cdewz {
  stop-color: var(--svg-color--b68e7e, #B68E7E);
  stop-opacity: 0;
}

.gyymo5b9p {
  stop-color: var(--svg-color--bc907a, #BC907A);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.i531rrbeb {
  stop-color: var(--svg-color--bf937d, #BF937D);
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ikvhpob1k {
  stop-color: var(--svg-color--ae7d72, #AE7D72);
}

.ixktmib9m {
  fill: var(--svg-color--b59073, #B59073);
  d: path("M16.504 13.744c-.713-.332-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.278 2.684 1.352c.395.093 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.399a10 10 0 0 1-2.246-.718");
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jbfg2bc5e {
  fill: var(--svg-color--594343, #594343);
  fill-rule: evenodd;
  d: path("M17.866 6.909a.72.72 0 0 0-.488-.028a.1.1 0 0 1-.066-.189a.92.92 0 0 1 .637.035a.1.1 0 1 1-.083.182");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.jvo0x_9jg {
  d: path("M15.919 6.535a.625.625 0 0 0-.373 1.175z");
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.lhom_fbjg {
  stop-color: var(--svg-color--ba9080, #BA9080);
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mcj2tdbkt {
  stop-color: var(--svg-color--397bd7, #397BD7);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mq16gsbnt {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.023px;
  rx: 0.318px;
}

.mqqn1vb3r {
  d: path("M9.598 13.689c-.243.895-.203 1.762-.11 2.023l6.309-.062z");
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.ob3ms9o6m {
  d: path("M21.334 12.238a.59.59 0 1 1 .829.84l-8.439 8.331a.59.59 0 0 1-.829-.84z");
}

.od3gao5lw {
  stop-color: var(--svg-color--4f3f3c, #4F3F3C);
  stop-opacity: 0;
}

.os4q-jbxt {
  d: path("M17.72 7.763c.02-.037.038-.064.051-.113c.048-.178-.02-.355-.169-.394c-.138-.037-.296.079-.343.256a.5.5 0 0 0-.012.124z");
}

.osvvk56wr {
  d: path("M16.504 13.744c-.713-.332-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.278 2.684 1.352c.395.093 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.399a10 10 0 0 1-2.246-.718");
}

.pb023zb_t {
  stop-color: var(--svg-color--5e413e, #5E413E);
}

.ph7rypboq {
  stop-color: var(--svg-color--275dc4, #275DC4);
  stop-opacity: 0;
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.qgvh60b9t {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.742c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.05-.434.031-.5.277l-.003.01c-.015.06.01.119.066.134z");
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.r5lh8e62q {
  stop-color: var(--svg-color--c9a289, #C9A289);
  stop-opacity: 0;
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.roxpyebqa {
  stop-color: var(--svg-color--c59e89, #C59E89);
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.rrd7rxqch {
  d: path("M14.713 7.665h1.744v2h-1.744z");
}

.s09h4qbjb {
  stop-color: var(--svg-color--ba9080, #BA9080);
  stop-opacity: 0;
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.t-gnmrvnp {
  stop-color: var(--svg-color--422b32, #422B32);
}

.uboyb380j {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.37c.016-.037.07-.048.119-.026s.075.069.059.106c-.017.036-.07.048-.119.026s-.075-.07-.059-.106");
}

.uecjt6-ya {
  d: path("M18.232 8.021c-.081-.147-.066-.411-.047-.504l-.445 1.02c.14.074.378.139.515-.032c.098-.12.079-.3-.023-.484");
}

.uee_89odc {
  stop-color: var(--svg-color--b68e7e, #B68E7E);
}

.uen83-bab {
  d: path("M3.504 20.908c-.775-.425-1.254-.422-1.445-.422v5.937H29.94v-5.937c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.203-2-.734");
}

.v0g3nqbgo {
  stop-color: var(--svg-color--579ff0, #579FF0);
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5j-79bqk {
  stop-color: var(--svg-color--c9a289, #C9A289);
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.v80-hbb8u {
  d: path("M11.168 10.533c-1.006 1.23-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.719 1.172-3.375s.489-.871.555-1.347c.066-.477-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.vpva1obir {
  d: path("M3.504 24.408c-.775-.425-1.254-.422-1.445-.422v5.937H29.94v-5.937c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.003c-.57.29-1.031.516-1.656.516s-1.031-.203-2-.734");
}

.wj36x1bhr {
  stop-color: var(--svg-color--9c7060, #9C7060);
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.xblvjf0zf {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.359 11.684c.291.35.889.87 1.804 1.164c1.438.461 1.735.516 2.36.727");
}

.xi66vkmon {
  stop-color: var(--svg-color--c59e89, #C59E89);
  stop-opacity: 0;
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.xz_nrebbp {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.487px;
  rx: 1.095px;
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.yj2immbwm {
  stop-color: var(--svg-color--ac8d79, #AC8D79);
}

.ynstgccdl {
  stop-color: var(--svg-color--275dc4, #275DC4);
}

.z1k4z2bhw {
  d: path("M17.641 7.741q.045-.05.061-.11c.027-.099-.019-.206-.097-.227c-.08-.021-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.z6ud28wib {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M16.98 8.43a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.426a.1.1 0 0 1 .05-.132");
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zto3p_lef {
  stop-color: var(--svg-color--b68375, #B68375);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

.zyktje01y {
  stop-color: var(--svg-color--a37c6b, #A37C6B);
}

</style>
