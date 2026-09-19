<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iuKK32c)" transform="rotate(39.16 14.713 7.737)" class="ts4iqoiql"/><path fill="url(#ifkieRc)" class="qbq_r7z0v"/><g filter="url(#i3yxZ4d)"><path fill="url(#itKokxd)" class="ra-yeyb6h"/><path fill="url(#iHPgPMc)" class="ra-yeyb6h"/><path fill="url(#iWfKTde)" class="ra-yeyb6h"/></g><path clip-rule="evenodd" class="gkk2nqbvv"/><g filter="url(#iP8d9Zw)"><path clip-rule="evenodd" class="yjndchflo"/></g><g filter="url(#iuGCosb)"><path class="jetgdcccn"/><path fill="url(#i6AJn6q)" class="mk11lyvpk"/></g><path fill="url(#in15nDb)" class="u9xuenddo"/><path fill="url(#iDttQVc)" class="rxnk0mb-a"/><path fill="url(#iV38a5d)" class="rxnk0mb-a"/><path fill="url(#ipP1i0d)" class="rxnk0mb-a"/><path fill="url(#iTz6iCc)" class="rxnk0mb-a"/><g filter="url(#ic8YFlc)"><path fill="url(#iiPa8By)" class="q997x_xdd"/><path fill="url(#iOKt81d)" class="q997x_xdd"/><path fill="url(#iIhloRb)" class="q997x_xdd"/></g><g filter="url(#iWaASMd)"><rect fill="url(#iRfIqYc)" class="nxy7strzm"/><rect fill="url(#iwJekkb)" class="nxy7strzm"/><rect fill="url(#iSVzhKe)" class="nxy7strzm"/><rect fill="url(#iwfspQc)" class="nxy7strzm"/></g><rect fill="url(#ihfjYAH)" transform="rotate(-21.787 19.523 13.095)" class="a6nmdpb1p"/><path fill="url(#icN7VEe)" class="mv33nqbby"/><path fill="url(#iOhWdvb)" class="mv33nqbby"/><path fill="url(#iJIIHMd)" class="mv33nqbby"/><g filter="url(#i177Hvt)"><path fill="url(#i4uDKYd)" class="xh2rvubci"/></g><g filter="url(#in5xUcb)"><path fill="url(#irJ7Vxc)" class="n8-p0qbof"/><path fill="url(#iRbYZ5d)" class="n8-p0qbof"/><path fill="url(#iMQS5Qc)" class="n8-p0qbof"/></g><g filter="url(#i1fS4Jc)"><path class="n_ztzrvjl"/><path fill="url(#iOIHnsc)" class="k_ryov6vn"/></g><g filter="url(#i8qL6xb)"><path stroke="url(#ifDLX1c)" class="ie5qbrb2e"/></g><g filter="url(#i3IY2db)"><path fill="url(#iuc8cSc)" class="p6u7oov3z"/></g><path fill="url(#ifer9hc)" class="gvpqnsbmz"/><path class="rq7ko3t2v"/><path fill="url(#iYQJhju)" class="m97a0dbfl"/><path fill="url(#ieB3yce)" class="pi5kqwe0j"/><path class="zg7-mji4k"/><g filter="url(#iUi1Fye)"><path fill="url(#iRLYuvs)" class="bvugaob1h"/><path fill="url(#iSRKvMc)" class="bvugaob1h"/></g><defs><radialGradient id="iuKK32c" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.306 9.672)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="zavz50bxt"/><stop offset="1" class="q265kokej"/></radialGradient><radialGradient id="ifkieRc" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.25 10.538)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="nt8xhhbat"/><stop offset="1" class="tyyfqbc6n"/></radialGradient><radialGradient id="itKokxd" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.167 5.314)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="hm38bnbpu"/><stop offset="1" class="wxw4scccx"/></radialGradient><radialGradient id="iHPgPMc" cx="0" cy="0" r="1" gradientTransform="rotate(107.289 5.844 10.221)scale(.61776 .64399)" gradientUnits="userSpaceOnUse"><stop class="so3lhcy0s"/><stop offset="1" class="flid1wbse"/></radialGradient><radialGradient id="iWfKTde" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.171)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="lwhkutxfi"/><stop offset="1" class="hi76xjbam"/></radialGradient><radialGradient id="i6AJn6q" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.07 15.257)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ik1b347lr"/><stop offset="1" class="fyswmcz3l"/></radialGradient><radialGradient id="in15nDb" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.247 48.67)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="ipP1i0d" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.058)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iTz6iCc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.965)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iiPa8By" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.213 15.107)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="iOKt81d" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.899 10.423)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="iIhloRb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.152)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iwJekkb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.183)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="iSVzhKe" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.654)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iwfspQc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .8125 -9.78125 0 17.957 16.433)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="ihfjYAH" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.356)" gradientUnits="userSpaceOnUse"><stop class="zvi39h0vi"/><stop offset="1" class="y8vzjr5cn"/></radialGradient><radialGradient id="icN7VEe" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.307 10.787)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="i4uDKYd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 20.996)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="iRbYZ5d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.965)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iOIHnsc" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 13.944)" gradientUnits="userSpaceOnUse"><stop class="bj1143m9c"/><stop offset="1" class="y32gqkb3q"/></radialGradient><radialGradient id="iuc8cSc" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.183)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="d8l2uy9_q"/><stop offset="1" class="ml-wi-9ur"/></radialGradient><radialGradient id="ifer9hc" cx="0" cy="0" r="1" gradientTransform="matrix(-.36061 .26664 -.28066 -.37957 17.457 7.304)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="iYQJhju" cx="0" cy="0" r="1" gradientTransform="rotate(-75.213 13.83 -7.49)scale(.49693 .55747)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="ieB3yce" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.527)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="iRLYuvs" cx="0" cy="0" r="1" gradientTransform="rotate(163.724 8.88 4.33)scale(5.51064 6.88411)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="cw1qesbgk"/><stop offset="1" class="r_f_eghxz"/></radialGradient><radialGradient id="iSRKvMc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35938 .17969 -.15962 -1.20756 18.854 5.35)" gradientUnits="userSpaceOnUse"><stop class="ifa22jgjv"/><stop offset="1" class="n_9nxnb3u"/></radialGradient><filter id="i3yxZ4d" width="4.364" height="4.439" x="14.22" y="5.527" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.705882 0 0 0 0 0.505882 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="iP8d9Zw" width=".763" height=".367" x="17.245" y="6.624" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.509804 0 0 0 0 0.301961 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="iuGCosb" width="6.377" height="6.141" x="9.574" y="8.987" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.321569 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="ic8YFlc" width="27.983" height="6.037" x="2.059" y="20.558" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="iWaASMd" width="24.059" height="2.191" x="3.886" y="15.559" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="i177Hvt" width="6.802" height="6.803" x="8.337" y="19.297" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="in5xUcb" width="27.983" height="6.037" x="1.959" y="24.058" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="i1fS4Jc" width="6.678" height="4.108" x="14.785" y="10.883" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.592157 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="i8qL6xb" width="5.181" height="3.008" x="14.876" y="11.229" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23074" stdDeviation=".2"/></filter><filter id="i3IY2db" width="3.882" height="3.705" x="12.803" y="9.283" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.243137 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><filter id="iUi1Fye" width="6.317" height="5.313" x="12.906" y="3.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.831373 0 0 0 0 0.682353 0 0 0 0 0.513726 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23074"/></filter><linearGradient id="iDttQVc" x1="25.051" x2="7.801" y1="18.902" y2="24.277" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="iV38a5d" x1="27.145" x2="26.441" y1="20.465" y2="20.465" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="iRfIqYc" x1="16.015" x2="16.395" y1="15.308" y2="18.84" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="iOhWdvb" x1="17.168" x2="17.582" y1="16.343" y2="16.738" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="iJIIHMd" x1="19.52" x2="19.184" y1="16.027" y2="15.675" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="irJ7Vxc" x1="18.457" x2="12.738" y1="23.433" y2="33.527" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="iMQS5Qc" x1="18.02" x2="18.02" y1="29.996" y2="29.715" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="ifDLX1c" x1="15.804" x2="20.086" y1="12.288" y2="14.007" gradientUnits="userSpaceOnUse"><stop class="o5cz0x_yz"/><stop offset="1" class="uwp25_jkx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-rowing-boat-medium-light" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.a6nmdpb1p {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.095px;
  rx: 0.318px;
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bj1143m9c {
  stop-color: var(--svg-color--e8bea3, #E8BEA3);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.bvugaob1h {
  d: path("M13.6 6.817c.332-.227.418-.442.515-1.094c.219-1.094.542-1.306.969-1.547c.449-.254 1.195-.187 1.703.196c.558.42.668.34 1.348.363c.722.023.972.496.988.91c.015.414-.207.98-.934 1.031c-.834.058-.875-.687-1.574-.531c-.596.133-.727 1.316-.976 1.797c-.159.305-.3 1.013-1.165 1.21c-.921.212-1.68-.562-1.554-1.327c.1-.613.382-.805.68-1.008");
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.cw1qesbgk {
  stop-color: var(--svg-color--ffe3b1, #FFE3B1);
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.d8l2uy9_q {
  stop-color: var(--svg-color--9178d3, #9178D3);
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

.espuh9d_f {
  stop-color: var(--svg-color--8d8695, #8D8695);
}

.f3ogmdbgo {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
}

.f6scwccnd {
  stop-color: var(--svg-color--4d8c4e, #4D8C4E);
}

.flid1wbse {
  stop-color: var(--svg-color--f2c2a3, #F2C2A3);
  stop-opacity: 0;
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fyswmcz3l {
  stop-color: var(--svg-color--57399f, #57399F);
  stop-opacity: 0;
}

.gkk2nqbvv {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M16.98 8.503a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.183a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.132");
}

.gvpqnsbmz {
  d: path("m16.914 7.512l.116.063l.57-.29c-.28-.16-.543-.126-.722.026c-.068.057-.042.16.036.201");
}

.hi76xjbam {
  stop-color: var(--svg-color--eeb597, #EEB597);
  stop-opacity: 0;
}

.hm38bnbpu {
  stop-color: var(--svg-color--efbb9e, #EFBB9E);
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.ie5qbrb2e {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.43 11.757c.291.349.889.87 1.804 1.164c1.438.46 1.734.516 2.36.727");
}

.ifa22jgjv {
  stop-color: var(--svg-color--fff2bb, #FFF2BB);
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ik1b347lr {
  stop-color: var(--svg-color--57399f, #57399F);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jetgdcccn {
  fill: var(--svg-color--7355bd, #7355BD);
  d: path("M11.168 10.605c-1.006 1.231-1.414 2.668-1.594 3.274l3.992 1.25c.125-1.024.75-2.72 1.172-3.375c.422-.657.489-.871.555-1.348s-.256-1.194-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k_ryov6vn {
  d: path("M16.504 13.816c-.713-.331-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.109 2.375 1.278 2.684 1.351c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.lwhkutxfi {
  stop-color: var(--svg-color--eeb597, #EEB597);
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.m97a0dbfl {
  d: path("M17.72 7.835c.02-.037.038-.063.051-.113c.048-.177-.02-.354-.169-.394c-.138-.037-.296.08-.343.257a.5.5 0 0 0-.012.123z");
}

.mk11lyvpk {
  d: path("M11.168 10.605c-1.006 1.231-1.414 2.668-1.594 3.274l3.992 1.25c.125-1.024.75-2.72 1.172-3.375c.422-.657.489-.871.555-1.348s-.256-1.194-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.ml-wi-9ur {
  stop-color: var(--svg-color--7151be, #7151BE);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mv33nqbby {
  d: path("M21.334 12.31a.59.59 0 1 1 .829.84l-8.439 8.332a.59.59 0 0 1-.829-.84z");
}

.n_9nxnb3u {
  stop-color: var(--svg-color--fff2bb, #FFF2BB);
  stop-opacity: 0;
}

.n_ztzrvjl {
  fill: var(--svg-color--e6b694, #E6B694);
  d: path("M16.504 13.816c-.713-.331-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.109 2.375 1.278 2.684 1.351c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
}

.n8-p0qbof {
  d: path("M3.504 24.48c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.157-3.53 1.157c-1.317 0-2.188-1.157-3.548-1.157c-1.117 0-2.242 1.157-3.508 1.157c-.972 0-2.203-1.157-3.39-1.157c-1.258 0-2.262 1.157-3.399 1.157c-.558 0-.836-.102-1.539-.438s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.516-1.656.516s-1.031-.203-2-.735");
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.nt8xhhbat {
  stop-color: var(--svg-color--e2b496, #E2B496);
}

.nxy7strzm {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.559px;
  rx: 1.095px;
}

.o5cz0x_yz {
  stop-color: var(--svg-color--e8b79d, #E8B79D);
}

.p6u7oov3z {
  d: path("M13.004 11.105c.6.719 1.333 1.555 1.625 1.883l1.656-1.484c-.33-.396-1.117-1.303-1.617-1.766c-.625-.578-1.27-.191-1.469 0c-.172.166-.672.688-.195 1.367");
}

.pi5kqwe0j {
  d: path("M17.641 7.813q.045-.05.061-.11c.027-.098-.019-.205-.097-.226c-.08-.022-.17.039-.198.147a.3.3 0 0 0-.002.126z");
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.q265kokej {
  stop-color: var(--svg-color--b77f62, #B77F62);
}

.q997x_xdd {
  d: path("M3.504 20.98c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.157-3.53 1.157c-1.317 0-2.188-1.157-3.548-1.157c-1.117 0-2.242 1.157-3.508 1.157c-.972 0-2.203-1.157-3.39-1.157c-1.258 0-2.262 1.157-3.399 1.157c-.558 0-.836-.102-1.539-.438s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.516-1.656.516s-1.031-.203-2-.735");
}

.qbq_r7z0v {
  d: path("M18.232 8.094c-.081-.147-.066-.412-.047-.504l-.445 1.02c.14.073.378.138.515-.032c.098-.121.079-.3-.023-.484");
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.r_f_eghxz {
  stop-color: var(--svg-color--ffd9ac, #FFD9AC);
}

.ra-yeyb6h {
  d: path("M15.931 9.738c-.914-.453-1.535-1.235-1.71-1.617l.662-1.593a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.003.372.066c.288.183.576.645.369 1.476c-.229 1.08-.501 1.744-.749 2.227c-.177.344-.533.572-.916.505a3.2 3.2 0 0 1-.718-.216");
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.rq7ko3t2v {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.815c.048.012.099-.027.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.051-.434.03-.5.277l-.003.01c-.015.059.01.118.066.133z");
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.rxnk0mb-a {
  d: path("m5.232 17.017l21.725-.021v6.25l-18.008-.117z");
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.so3lhcy0s {
  stop-color: var(--svg-color--f2c2a3, #F2C2A3);
}

.ts4iqoiql {
  d: path("M14.713 7.737h1.744v2h-1.744z");
}

.tyyfqbc6n {
  stop-color: var(--svg-color--d29e83, #D29E83);
}

.u9xuenddo {
  d: path("M9.598 13.762c-.243.894-.203 1.761-.11 2.023l6.309-.063z");
}

.uwp25_jkx {
  stop-color: var(--svg-color--e8b79d, #E8B79D);
  stop-opacity: 0;
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
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

.wxw4scccx {
  stop-color: var(--svg-color--e29f87, #E29F87);
}

.xh2rvubci {
  d: path("M11.366 20.36a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.469a1.917 1.917 0 0 1-2.712-2.71z");
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.y32gqkb3q {
  stop-color: var(--svg-color--e8bea3, #E8BEA3);
  stop-opacity: 0;
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.y8vzjr5cn {
  stop-color: var(--svg-color--c89b7b, #C89B7B);
}

.yjndchflo {
  fill: var(--svg-color--9e6b41, #9E6B41);
  fill-rule: evenodd;
  d: path("M17.866 6.981a.72.72 0 0 0-.488-.027a.1.1 0 0 1-.066-.19a.92.92 0 0 1 .637.036a.1.1 0 1 1-.083.181");
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zavz50bxt {
  stop-color: var(--svg-color--a4744f, #A4744F);
}

.zg7-mji4k {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.443c.016-.037.07-.049.119-.027s.075.07.059.106c-.017.037-.07.049-.119.027s-.075-.07-.059-.106");
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

.zvi39h0vi {
  stop-color: var(--svg-color--d1a587, #D1A587);
}

</style>
