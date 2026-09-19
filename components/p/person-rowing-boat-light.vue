<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iYysSVW)" transform="rotate(39.16 14.713 7.747)" class="gfyld4f1l"/><path fill="url(#iDl9ZTd)" class="u7h-l29hg"/><g filter="url(#iPZCbzc)"><path fill="url(#itLWCsb)" class="mixnxobfm"/><path fill="url(#iFtgSLe)" class="mixnxobfm"/><path fill="url(#iL6C1Jw)" class="mixnxobfm"/></g><path clip-rule="evenodd" class="fncsmqb_p"/><g filter="url(#iV3meje)"><path clip-rule="evenodd" class="hof-w3miu"/></g><g filter="url(#iv1eHWb)"><path fill="url(#iQl5ZHp)" class="jpv3ueb0o"/><path fill="url(#i4Bj0Xb)" class="jpv3ueb0o"/></g><path fill="url(#i9n4UJb)" class="fhzim-uvo"/><g filter="url(#ifrAG6R)"><path class="wef5m0bhm"/><path fill="url(#iCtPLkd)" class="fzzq4hbrq"/></g><path fill="url(#iFldZ8b)" class="lvvvwrb7g"/><path fill="url(#ipxIb7k)" class="xwnu6qbmb"/><path fill="url(#izt8che)" class="xwnu6qbmb"/><path fill="url(#iANrP3W)" class="xwnu6qbmb"/><path fill="url(#iC8Ew9b)" class="xwnu6qbmb"/><g filter="url(#iln1yRd)"><path fill="url(#iS5O4Lw)" class="ckyc6g33c"/><path fill="url(#icVJeYb)" class="ckyc6g33c"/><path fill="url(#ipNWS0C)" class="ckyc6g33c"/></g><g filter="url(#ipuSnId)"><rect fill="url(#iH45lwe)" class="x13ytmb0p"/><rect fill="url(#iVEX5Fe)" class="x13ytmb0p"/><rect fill="url(#iVXqiSb)" class="x13ytmb0p"/><rect fill="url(#iToyIIc)" class="x13ytmb0p"/></g><rect fill="url(#iGxdnxe)" transform="rotate(-21.787 19.331 13.08)" class="d-bivvimq"/><path fill="url(#ivjSLIe)" class="eabxil5ym"/><path fill="url(#ifeaLhv)" class="eabxil5ym"/><path fill="url(#iNrwPfe)" class="eabxil5ym"/><g filter="url(#iqFMDbc)"><path fill="url(#iaf5gGL)" class="toj1uyb4s"/></g><g filter="url(#imYYY2c)"><path fill="url(#if4elwb)" class="ogj7450tq"/><path fill="url(#i7Z2hfd)" class="ogj7450tq"/><path fill="url(#ispBhld)" class="ogj7450tq"/></g><g filter="url(#iexZTRb)"><path class="b2zw1tbmu"/><path fill="url(#iTJYcwc)" class="xy4qksbnn"/></g><g filter="url(#iIM5VqI)"><path stroke="url(#iT98OEW)" class="azyikibrc"/></g><g filter="url(#i1yVYle)"><path fill="url(#iSwhMdb)" class="zwb6vb-og"/></g><path class="sqnqopmqz"/><path fill="url(#iyMwSke)" class="kj3utpbvw"/><path fill="url(#iIJrzob)" class="mh235pe6c"/><path class="r6q_u4bkq"/><g filter="url(#iv8y5ir)"><path class="wrk6-oqgq"/></g><defs><radialGradient id="iYysSVW" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.302 9.677)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="ztkiyibrv"/><stop offset="1" class="bp2cggfyk"/></radialGradient><radialGradient id="iDl9ZTd" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.247 10.543)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="t04vb-hcs"/><stop offset="1" class="kguf3qbxw"/></radialGradient><radialGradient id="itLWCsb" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.17 5.3)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="az2qiyawh"/><stop offset="1" class="t4coan9us"/></radialGradient><radialGradient id="iFtgSLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.1836 .58984 -.6149 -.19139 17.34 7.65)" gradientUnits="userSpaceOnUse"><stop class="q2qi1lbnq"/><stop offset="1" class="kpwscabck"/></radialGradient><radialGradient id="iL6C1Jw" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.142)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="q2qi1lbnq"/><stop offset="1" class="kpwscabck"/></radialGradient><radialGradient id="iQl5ZHp" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 1.21872 -1.51845 -5.21735 18.363 5.724)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="j9b-420yy"/><stop offset="1" class="k5y4d_b1p"/></radialGradient><radialGradient id="i4Bj0Xb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.53125 1.3125 0 14.685 7.079)" gradientUnits="userSpaceOnUse"><stop class="yte4k7nua"/><stop offset="1" class="h846rykft"/></radialGradient><radialGradient id="i9n4UJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 -.1328 .22485 -.63488 15.855 6.974)" gradientUnits="userSpaceOnUse"><stop class="sx736obft"/><stop offset="1" class="sx736obft"/></radialGradient><radialGradient id="iCtPLkd" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.077 15.262)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="cpjrx4bdc"/><stop offset="1" class="gezrebbgs"/></radialGradient><radialGradient id="iFldZ8b" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.284 48.675)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iANrP3W" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.068)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iC8Ew9b" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.974)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iS5O4Lw" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.211 15.112)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="icVJeYb" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.901 10.427)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="ipNWS0C" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.162)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iVEX5Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.193)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="iVXqiSb" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.664)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iToyIIc" cx="0" cy="0" r="1" gradientTransform="rotate(90 .757 17.2)scale(.8125 9.78126)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="iGxdnxe" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 19.826 13.34)" gradientUnits="userSpaceOnUse"><stop class="mwy-f8bpu"/><stop offset="1" class="ejqwb0bqm"/></radialGradient><radialGradient id="ivjSLIe" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.305 10.791)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iaf5gGL" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 21.006)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="i7Z2hfd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.974)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iTJYcwc" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 13.953)" gradientUnits="userSpaceOnUse"><stop class="n4xk4fb0e"/><stop offset="1" class="co6663b7r"/></radialGradient><radialGradient id="iSwhMdb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.193)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="r_erdlb4g"/><stop offset="1" class="w1kjbmbah"/></radialGradient><radialGradient id="iyMwSke" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.802)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="iIJrzob" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.537)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><filter id="iPZCbzc" width="4.364" height="4.439" x="14.22" y="5.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.576471 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="iV3meje" width=".763" height=".367" x="17.253" y="6.511" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0588235 0 0 0 0 0.0352941 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="iv1eHWb" width="5.022" height="4.224" x="13.841" y="4.017" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0588235 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="ifrAG6R" width="6.377" height="6.141" x="9.574" y="8.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.478431 0 0 0 0 0.262745 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.466667 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_3987_23076" result="effect2_innerShadow_3987_23076"/></filter><filter id="iln1yRd" width="27.983" height="6.037" x="2.059" y="20.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="ipuSnId" width="24.059" height="2.191" x="3.886" y="15.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="iqFMDbc" width="6.802" height="6.803" x="8.337" y="19.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="imYYY2c" width="27.983" height="6.037" x="1.959" y="24.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="iexZTRb" width="6.678" height="4.108" x="14.785" y="10.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="iIM5VqI" width="5.181" height="3.008" x="14.85" y="11.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23076" stdDeviation=".2"/></filter><filter id="i1yVYle" width="3.882" height="3.705" x="12.803" y="9.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.870588 0 0 0 0 0.25098 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23076"/></filter><filter id="iv8y5ir" width="3.316" height="1.688" x="15.443" y="5.009" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23076" stdDeviation=".125"/></filter><linearGradient id="ipxIb7k" x1="25.051" x2="7.801" y1="18.912" y2="24.287" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="izt8che" x1="27.145" x2="26.441" y1="20.474" y2="20.474" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="iH45lwe" x1="16.015" x2="16.395" y1="15.318" y2="18.849" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="ifeaLhv" x1="17.168" x2="17.582" y1="16.353" y2="16.748" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="iNrwPfe" x1="19.52" x2="19.184" y1="16.037" y2="15.685" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="if4elwb" x1="18.457" x2="12.738" y1="23.443" y2="33.537" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="ispBhld" x1="18.02" x2="18.02" y1="30.006" y2="29.724" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iT98OEW" x1="15.778" x2="20.06" y1="12.298" y2="14.017" gradientUnits="userSpaceOnUse"><stop class="u_4uylzec"/><stop offset="1" class="yauhuibbl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:person-rowing-boat-light" /></template>
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

.az2qiyawh {
  stop-color: var(--svg-color--fac4b1, #FAC4B1);
}

.azyikibrc {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.403 11.767c.292.349.89.87 1.805 1.164c1.438.46 1.734.515 2.36.726");
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.b2zw1tbmu {
  fill: var(--svg-color--f2c6af, #F2C6AF);
  d: path("M16.504 13.826c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.279 2.684 1.352c.395.094 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.72");
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.bp2cggfyk {
  stop-color: var(--svg-color--e8a28d, #E8A28D);
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.ckyc6g33c {
  d: path("M3.504 20.99c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.co6663b7r {
  stop-color: var(--svg-color--f7cfbd, #F7CFBD);
  stop-opacity: 0;
}

.cpjrx4bdc {
  stop-color: var(--svg-color--e03932, #E03932);
}

.d-bivvimq {
  width: 1.28px;
  height: 0.637px;
  x: 19.331px;
  y: 13.08px;
  rx: 0.318px;
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
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

.eabxil5ym {
  d: path("M21.334 12.32a.59.59 0 1 1 .829.84l-8.439 8.331a.59.59 0 0 1-.829-.84z");
}

.ejqwb0bqm {
  stop-color: var(--svg-color--d9ad92, #D9AD92);
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

.fhzim-uvo {
  d: path("M15.919 6.617a.625.625 0 0 0-.373 1.175z");
}

.fncsmqb_p {
  fill: var(--svg-color--880f4d, #880F4D);
  fill-rule: evenodd;
  d: path("M16.98 8.512a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.184a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.133");
}

.fsljb8bqi {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fzzq4hbrq {
  d: path("M11.168 10.615c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.gezrebbgs {
  stop-color: var(--svg-color--e03932, #E03932);
  stop-opacity: 0;
}

.gfyld4f1l {
  d: path("M14.713 7.747h1.744v2h-1.744z");
}

.h846rykft {
  stop-color: var(--svg-color--48403e, #48403E);
  stop-opacity: 0;
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.hof-w3miu {
  fill: var(--svg-color--323232, #323232);
  fill-rule: evenodd;
  d: path("M17.874 6.868a.72.72 0 0 0-.488-.027a.1.1 0 0 1-.066-.19a.92.92 0 0 1 .637.036a.1.1 0 1 1-.084.181");
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.j9b-420yy {
  stop-color: var(--svg-color--2f2529, #2F2529);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.jpv3ueb0o {
  d: path("M13.872 7.609c.085-.194.296-.227.39-.22c-.39-.765-.085-2.686.65-3.046a1.77 1.77 0 0 1 1.577.023c.243.133.567.446 1.27.41c.645-.032 1 .333 1.004.692c.004.36-.117.844-.637.96c-.52.118-.758-.07-1.394-.148c-.492-.06-.866.278-.989.47c-.183.29-.615.914-.75 1.136c-.168.277-.406.402-.73.34c-.324-.063-.496-.375-.39-.617");
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jv6m1sr_z {
  stop-color: var(--svg-color--99d852, #99D852);
  stop-opacity: 0;
}

.k23k8xbao {
  stop-color: var(--svg-color--6b4841, #6B4841);
}

.k5y4d_b1p {
  stop-color: var(--svg-color--211b1e, #211B1E);
}

.k73oz-bdw {
  stop-color: var(--svg-color--4aadff, #4AADFF);
}

.kguf3qbxw {
  stop-color: var(--svg-color--e7b89f, #E7B89F);
}

.kj3utpbvw {
  d: path("M17.72 7.845c.02-.037.038-.064.051-.113c.048-.178-.02-.355-.169-.394c-.138-.037-.296.079-.343.256a.5.5 0 0 0-.012.124z");
}

.kpwscabck {
  stop-color: var(--svg-color--ffd5be, #FFD5BE);
  stop-opacity: 0;
}

.lvvvwrb7g {
  d: path("M9.598 13.771c-.243.895-.203 1.762-.11 2.024l6.309-.063z");
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.mh235pe6c {
  d: path("M17.641 7.823q.045-.05.061-.11c.027-.099-.019-.206-.097-.227c-.08-.02-.17.04-.198.148a.3.3 0 0 0-.002.126z");
}

.mixnxobfm {
  d: path("M15.931 9.708c-.914-.453-1.535-1.234-1.71-1.617l.662-1.593a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.008.263-.002.372.067c.288.182.576.644.369 1.476c-.229 1.08-.501 1.743-.749 2.226c-.177.344-.533.572-.916.506a3.2 3.2 0 0 1-.718-.217");
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mwy-f8bpu {
  stop-color: var(--svg-color--e2b79d, #E2B79D);
}

.n4xk4fb0e {
  stop-color: var(--svg-color--f7cfbd, #F7CFBD);
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.ogj7450tq {
  d: path("M3.504 24.49c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.156-3.53 1.156c-1.317 0-2.188-1.156-3.548-1.156c-1.117 0-2.242 1.156-3.508 1.156c-.972 0-2.203-1.156-3.39-1.156c-1.258 0-2.262 1.156-3.399 1.156c-.558 0-.836-.101-1.539-.437s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.621l-.007.004c-.57.289-1.031.515-1.656.515s-1.031-.203-2-.734");
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.q2qi1lbnq {
  stop-color: var(--svg-color--ffd5be, #FFD5BE);
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.r_erdlb4g {
  stop-color: var(--svg-color--ff9954, #FF9954);
}

.r6q_u4bkq {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.452c.016-.036.07-.048.119-.026s.075.07.059.106c-.017.037-.07.048-.119.026s-.075-.07-.059-.106");
}

.rltzfib1k {
  stop-color: var(--svg-color--79b34c, #79B34C);
}

.rqyiu8baj {
  stop-color: var(--svg-color--528c3f, #528C3F);
}

.s5cu-8c1s {
  stop-color: var(--svg-color--fecca0, #FECCA0);
}

.sqnqopmqz {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.824c.048.013.099-.026.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.05-.434.031-.5.278l-.003.01c-.015.059.01.118.066.133z");
}

.sx736obft {
  stop-color: var(--svg-color--f6c1ac, #F6C1AC);
}

.t04vb-hcs {
  stop-color: var(--svg-color--f4c8b2, #F4C8B2);
}

.t4coan9us {
  stop-color: var(--svg-color--eea894, #EEA894);
}

.toj1uyb4s {
  d: path("M11.366 20.369a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.47a1.917 1.917 0 0 1-2.712-2.711z");
}

.u_4uylzec {
  stop-color: var(--svg-color--f7c6b6, #F7C6B6);
}

.u7h-l29hg {
  d: path("M18.232 8.103c-.081-.147-.066-.411-.047-.504l-.445 1.02c.14.074.378.14.515-.031c.098-.122.079-.301-.023-.485");
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.w1kjbmbah {
  stop-color: var(--svg-color--f9663c, #F9663C);
}

.wef5m0bhm {
  fill: var(--svg-color--fa623e, #FA623E);
  d: path("M11.168 10.615c-1.006 1.231-1.414 2.668-1.594 3.273l3.992 1.25c.125-1.023.75-2.718 1.172-3.375c.422-.656.489-.87.555-1.347s-.256-1.195-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.wqxg4jbgc {
  stop-color: var(--svg-color--286ec5, #286EC5);
  stop-opacity: 0;
}

.wrk6-oqgq {
  fill: var(--svg-color--3d3d3d, #3D3D3D);
  d: path("M17.068 6.079c-.675-.137-1.198.188-1.375.367c.632-1 1.43-.656 2.054-.68c.5-.018.709-.346.75-.507c.006.172.064.53-.144.715c-.256.227-.442.277-1.285.105");
}

.wvez-gyvu {
  stop-color: var(--svg-color--86bf45, #86BF45);
}

.wwotuurhh {
  stop-color: var(--svg-color--528c3f, #528C3F);
  stop-opacity: 0;
}

.x13ytmb0p {
  width: 23.859px;
  height: 2.191px;
  x: 4.086px;
  y: 15.569px;
  rx: 1.095px;
}

.xqbtmwqoi {
  stop-color: var(--svg-color--7caf55, #7CAF55);
}

.xwnu6qbmb {
  d: path("m5.232 17.027l21.725-.021v6.25l-18.008-.118z");
}

.xy4qksbnn {
  d: path("M16.504 13.826c-.713-.331-1.443-.966-1.719-1.242l1.281-1.192c1.157 1.11 2.375 1.279 2.684 1.352c.395.094 1.538.3 2.168.73c.516.352.379.992.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.72");
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.yauhuibbl {
  stop-color: var(--svg-color--f7c6b6, #F7C6B6);
  stop-opacity: 0;
}

.yte4k7nua {
  stop-color: var(--svg-color--48403e, #48403E);
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.ztkiyibrv {
  stop-color: var(--svg-color--d38e77, #D38E77);
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

.zwb6vb-og {
  d: path("M13.004 11.115c.6.719 1.333 1.555 1.625 1.883l1.656-1.485c-.33-.395-1.117-1.303-1.617-1.765c-.625-.578-1.27-.192-1.469 0c-.172.165-.672.687-.195 1.367");
}

</style>
