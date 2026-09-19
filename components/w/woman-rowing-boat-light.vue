<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iTGR66b)" transform="rotate(39.16 14.713 7.747)" class="gfyld4f1l"/><path fill="url(#iDl9ZTd)" class="qgpj16bec"/><g filter="url(#iuNbXNb)"><path fill="url(#itLWCsb)" class="hdaqt0bwx"/><path fill="url(#iFtgSLe)" class="hdaqt0bwx"/><path fill="url(#iL6C1Jw)" class="hdaqt0bwx"/></g><path clip-rule="evenodd" class="cibf3wbnh"/><g filter="url(#i5KIKqc)"><path clip-rule="evenodd" class="goynh311p"/></g><g filter="url(#iFQV3Ke)"><path class="a8k50x03d"/><path fill="url(#ibcDQde)" class="wht0ubbtr"/></g><path fill="url(#iWut3Dc)" class="qn887rbfy"/><path fill="url(#ipxIb7k)" class="a74d7aclo"/><path fill="url(#i9yuIxd)" class="a74d7aclo"/><path fill="url(#iANrP3W)" class="a74d7aclo"/><path fill="url(#iC9moCd)" class="a74d7aclo"/><g filter="url(#iQq253d)"><path fill="url(#iS5O4Lw)" class="i5bb1evpw"/><path fill="url(#ikCGfzp)" class="i5bb1evpw"/><path fill="url(#ipNWS0C)" class="i5bb1evpw"/></g><g filter="url(#i0Zl5Lc)"><rect fill="url(#iq06SVc)" class="x13ytmb0p"/><rect fill="url(#iVEX5Fe)" class="x13ytmb0p"/><rect fill="url(#iVXqiSb)" class="x13ytmb0p"/><rect fill="url(#iToyIIc)" class="x13ytmb0p"/></g><rect fill="url(#ihSjuxd)" transform="rotate(-21.787 19.523 13.105)" class="g7ohc9bre"/><path fill="url(#iopkIke)" class="v6p95_84a"/><path fill="url(#idDFTAb)" class="v6p95_84a"/><path fill="url(#iNrwPfe)" class="v6p95_84a"/><g filter="url(#i5NKbhc)"><path fill="url(#iaf5gGL)" class="h0p0yxwmg"/></g><g filter="url(#ikPjYvd)"><path fill="url(#if4elwb)" class="gk2ia4b1g"/><path fill="url(#iSDWV7U)" class="gk2ia4b1g"/><path fill="url(#iN4CJth)" class="gk2ia4b1g"/></g><g filter="url(#iY03Esd)"><path class="dq5-cvbyp"/><path fill="url(#iFOymjZ)" class="yeadpn21v"/></g><g filter="url(#irLuDne)"><path stroke="url(#iUREDDH)" class="ahgf9db2u"/></g><g filter="url(#irKkVib)"><path fill="url(#ipF34lw)" class="pyyiilrww"/></g><path fill="url(#iaxxxHb)" class="vz3r91b9q"/><path class="nummxxbxx"/><path fill="url(#iyMwSke)" class="zr9po46dd"/><path fill="url(#iIJrzob)" class="sav8j7bhz"/><path class="g4x6peb3r"/><g filter="url(#i9usvOb)"><path fill="url(#i7CmPPd)" class="n06ongbiu"/><path fill="url(#iGZK6XT)" class="n06ongbiu"/></g><defs><radialGradient id="iTGR66b" cx="0" cy="0" r="1" gradientTransform="rotate(112.51 5.302 9.677)scale(1.02069 1.88161)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="jum6cmbcz"/><stop offset="1" class="oadl-1bdu"/></radialGradient><radialGradient id="iDl9ZTd" cx="0" cy="0" r="1" gradientTransform="rotate(109.376 6.247 10.543)scale(.62401 .57809)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="t04vb-hcs"/><stop offset="1" class="kguf3qbxw"/></radialGradient><radialGradient id="itLWCsb" cx="0" cy="0" r="1" gradientTransform="rotate(161.861 8.17 5.3)scale(2.84448 2.94485)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="az2qiyawh"/><stop offset="1" class="t4coan9us"/></radialGradient><radialGradient id="iFtgSLe" cx="0" cy="0" r="1" gradientTransform="matrix(-.1836 .58984 -.6149 -.19139 17.34 7.65)" gradientUnits="userSpaceOnUse"><stop class="q2qi1lbnq"/><stop offset="1" class="kpwscabck"/></radialGradient><radialGradient id="iL6C1Jw" cx="0" cy="0" r="1" gradientTransform="matrix(-.60106 2 -1.01904 -.30625 16.903 6.142)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="q2qi1lbnq"/><stop offset="1" class="kpwscabck"/></radialGradient><radialGradient id="ibcDQde" cx="0" cy="0" r="1" gradientTransform="rotate(72.474 -1.077 15.262)scale(4.35856 2.29046)" gradientUnits="userSpaceOnUse"><stop offset=".08" class="ik1b347lr"/><stop offset="1" class="fyswmcz3l"/></radialGradient><radialGradient id="iWut3Dc" cx="0" cy="0" r="1" gradientTransform="rotate(15.117 -49.285 48.675)scale(4.82315 2.16799)" gradientUnits="userSpaceOnUse"><stop offset=".396" class="espuh9d_f"/><stop offset=".77" class="z7o0euhwd"/></radialGradient><radialGradient id="iANrP3W" cx="0" cy="0" r="1" gradientTransform="matrix(5.5625 -6.21875 2.25745 2.01923 13.145 22.068)" gradientUnits="userSpaceOnUse"><stop class="e21-2rm4b"/><stop offset="1" class="d8-6g_bzt"/></radialGradient><radialGradient id="iC9moCd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.15625 -1.84376 1.36973 -1.60188 11.332 21.975)" gradientUnits="userSpaceOnUse"><stop class="rqyiu8baj"/><stop offset="1" class="wwotuurhh"/></radialGradient><radialGradient id="iS5O4Lw" cx="0" cy="0" r="1" gradientTransform="rotate(133.063 7.211 15.112)scale(9.15342 18.4848)" gradientUnits="userSpaceOnUse"><stop class="b2ub1pmeu"/><stop offset="1" class="bit9nibqa"/></radialGradient><radialGradient id="ikCGfzp" cx="0" cy="0" r="1" gradientTransform="rotate(-133.468 9.901 10.428)scale(4.13363 7.33334)" gradientUnits="userSpaceOnUse"><stop class="hob-w_b7u"/><stop offset="1" class="wqxg4jbgc"/></radialGradient><radialGradient id="ipNWS0C" cx="0" cy="0" r="1" gradientTransform="matrix(-4.875 .37502 -1.76114 -22.89326 31.55 23.162)" gradientUnits="userSpaceOnUse"><stop offset=".288" class="ifzxkw8wi"/><stop offset="1" class="e_s-6on8g"/></radialGradient><radialGradient id="iVEX5Fe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28125 0 0 -1 27.55 16.193)" gradientUnits="userSpaceOnUse"><stop class="akun2bbyl"/><stop offset="1" class="fsljb8bqi"/></radialGradient><radialGradient id="iVXqiSb" cx="0" cy="0" r="1" gradientTransform="matrix(16.1875 0 0 .71644 4.27 16.664)" gradientUnits="userSpaceOnUse"><stop class="xqbtmwqoi"/><stop offset="1" class="y866tkb_w"/></radialGradient><radialGradient id="iToyIIc" cx="0" cy="0" r="1" gradientTransform="rotate(90 .757 17.2)scale(.8125 9.78126)" gradientUnits="userSpaceOnUse"><stop class="bkb526bql"/><stop offset="1" class="mpozi6wus"/></radialGradient><radialGradient id="ihSjuxd" cx="0" cy="0" r="1" gradientTransform="matrix(.6797 -.01657 .00353 .14487 20.018 13.366)" gradientUnits="userSpaceOnUse"><stop class="mwy-f8bpu"/><stop offset="1" class="ejqwb0bqm"/></radialGradient><radialGradient id="iopkIke" cx="0" cy="0" r="1" gradientTransform="rotate(135.21 8.304 10.792)scale(12.0651 1.31103)" gradientUnits="userSpaceOnUse"><stop offset=".236" class="s5cu-8c1s"/><stop offset="1" class="zuv3brbdp"/></radialGradient><radialGradient id="iaf5gGL" cx="0" cy="0" r="1" gradientTransform="matrix(-3.55739 3.43749 -2.0246 -2.09522 14.64 21.006)" gradientUnits="userSpaceOnUse"><stop class="ja67fo1gr"/><stop offset="1" class="lx7f_77ow"/></radialGradient><radialGradient id="iSDWV7U" cx="0" cy="0" r="1" gradientTransform="matrix(-3.09375 0 0 -12.375 30.176 28.975)" gradientUnits="userSpaceOnUse"><stop class="ncdif6bxa"/><stop offset="1" class="qjl30cblz"/></radialGradient><radialGradient id="iFOymjZ" cx="0" cy="0" r="1" gradientTransform="matrix(.60937 -.29687 .16254 .33364 20.747 13.954)" gradientUnits="userSpaceOnUse"><stop class="n4xk4fb0e"/><stop offset="1" class="co6663b7r"/></radialGradient><radialGradient id="ipF34lw" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 2.4375 -1.4473 1.28031 15.176 10.193)" gradientUnits="userSpaceOnUse"><stop offset=".049" class="d8l2uy9_q"/><stop offset="1" class="ml-wi-9ur"/></radialGradient><radialGradient id="iaxxxHb" cx="0" cy="0" r="1" gradientTransform="matrix(-.36061 .26664 -.28066 -.37957 17.457 7.314)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="iyMwSke" cx="0" cy="0" r="1" gradientTransform="matrix(.12683 -.48047 .539 .14228 17.543 7.802)" gradientUnits="userSpaceOnUse"><stop offset=".626" class="k23k8xbao"/><stop offset="1" class="cemcwib4u"/></radialGradient><radialGradient id="iIJrzob" cx="0" cy="0" r="1" gradientTransform="matrix(.07385 .26172 -.25328 .07147 17.49 7.537)" gradientUnits="userSpaceOnUse"><stop class="m8h6tdgkz"/><stop offset="1" class="ju-dj4awd"/></radialGradient><radialGradient id="i7CmPPd" cx="0" cy="0" r="1" gradientTransform="rotate(163.724 8.88 4.335)scale(5.51064 6.88411)" gradientUnits="userSpaceOnUse"><stop offset=".332" class="j9b-420yy"/><stop offset="1" class="k5y4d_b1p"/></radialGradient><radialGradient id="iGZK6XT" cx="0" cy="0" r="1" gradientTransform="matrix(-1.35938 .17969 -.15962 -1.20756 18.854 5.36)" gradientUnits="userSpaceOnUse"><stop class="wqvuuub3k"/><stop offset="1" class="xxkg1ibyo"/></radialGradient><filter id="iuNbXNb" width="4.364" height="4.439" x="14.22" y="5.498" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.572549 0 0 0 0 0.482353 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="i5KIKqc" width=".763" height=".367" x="17.245" y="6.634" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.0470588 0 0 0 0 0.0196078 0 0 0 0 0.0745098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="iFQV3Ke" width="6.377" height="6.141" x="9.574" y="8.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".65"/><feGaussianBlur stdDeviation=".6"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.407843 0 0 0 0 0.321569 0 0 0 0 0.666667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="iQq253d" width="27.983" height="6.037" x="2.059" y="20.568" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.541176 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="i0Zl5Lc" width="24.059" height="2.191" x="3.886" y="15.569" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.278431 0 0 0 0 0.529412 0 0 0 0 0.184314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="i5NKbhc" width="6.802" height="6.803" x="8.337" y="19.307" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.5"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.776471 0 0 0 0 0.556863 0 0 0 0 0.341176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="ikPjYvd" width="27.983" height="6.037" x="1.959" y="24.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.843137 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="iY03Esd" width="6.678" height="4.108" x="14.785" y="10.893" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.5"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.823529 0 0 0 0 0.623529 0 0 0 0 0.596078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="irLuDne" width="5.181" height="3.008" x="14.876" y="11.239" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_23077" stdDeviation=".2"/></filter><filter id="irKkVib" width="3.882" height="3.705" x="12.803" y="9.293" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.15"/><feGaussianBlur stdDeviation=".4"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.337255 0 0 0 0 0.243137 0 0 0 0 0.611765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><filter id="i9usvOb" width="6.317" height="5.313" x="12.906" y="3.885" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.15"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.164706 0 0 0 0 0.0588235 0 0 0 0 0.0784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_23077"/></filter><linearGradient id="ipxIb7k" x1="25.051" x2="7.801" y1="18.912" y2="24.287" gradientUnits="userSpaceOnUse"><stop offset=".353" class="wvez-gyvu"/><stop offset="1" class="a-c1axuni"/></linearGradient><linearGradient id="i9yuIxd" x1="27.145" x2="26.441" y1="20.475" y2="20.475" gradientUnits="userSpaceOnUse"><stop class="v5wfdhbpr"/><stop offset="1" class="jv6m1sr_z"/></linearGradient><linearGradient id="iq06SVc" x1="16.015" x2="16.395" y1="15.318" y2="18.85" gradientUnits="userSpaceOnUse"><stop class="rltzfib1k"/><stop offset="1" class="f6scwccnd"/></linearGradient><linearGradient id="idDFTAb" x1="17.168" x2="17.582" y1="16.354" y2="16.748" gradientUnits="userSpaceOnUse"><stop class="pna-0uy1p"/><stop offset="1" class="v15kcqbep"/></linearGradient><linearGradient id="iNrwPfe" x1="19.52" x2="19.184" y1="16.037" y2="15.685" gradientUnits="userSpaceOnUse"><stop class="f3ogmdbgo"/><stop offset="1" class="a_bfjubwy"/></linearGradient><linearGradient id="if4elwb" x1="18.457" x2="12.738" y1="23.443" y2="33.537" gradientUnits="userSpaceOnUse"><stop class="afnbbr78b"/><stop offset="1" class="k73oz-bdw"/></linearGradient><linearGradient id="iN4CJth" x1="18.02" x2="18.02" y1="30.006" y2="29.725" gradientUnits="userSpaceOnUse"><stop class="pjzjl2c9v"/><stop offset="1" class="dzuixsuao"/></linearGradient><linearGradient id="iUREDDH" x1="15.804" x2="20.086" y1="12.298" y2="14.017" gradientUnits="userSpaceOnUse"><stop class="u_4uylzec"/><stop offset="1" class="yauhuibbl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:woman-rowing-boat-light" /></template>
<style>
.a_bfjubwy {
  stop-color: var(--svg-color--d59c7a, #D59C7A);
  stop-opacity: 0;
}

.a-c1axuni {
  stop-color: var(--svg-color--679951, #679951);
}

.a74d7aclo {
  d: path("m5.232 17.027l21.725-.021v6.25l-18.008-.117z");
}

.a8k50x03d {
  fill: var(--svg-color--7355bd, #7355BD);
  d: path("M11.168 10.615c-1.006 1.232-1.414 2.668-1.594 3.274l3.992 1.25c.125-1.024.75-2.72 1.172-3.375c.422-.657.489-.871.555-1.348s-.256-1.194-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.afnbbr78b {
  stop-color: var(--svg-color--5fcdff, #5FCDFF);
}

.ahgf9db2u {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M15.43 11.767c.291.349.889.87 1.804 1.164c1.438.46 1.734.516 2.36.727");
}

.akun2bbyl {
  stop-color: var(--svg-color--78bb7d, #78BB7D);
}

.az2qiyawh {
  stop-color: var(--svg-color--fac4b1, #FAC4B1);
}

.b2ub1pmeu {
  stop-color: var(--svg-color--379fe9, #379FE9);
}

.bit9nibqa {
  stop-color: var(--svg-color--3691df, #3691DF);
}

.bkb526bql {
  stop-color: var(--svg-color--70a762, #70A762);
}

.cemcwib4u {
  stop-color: var(--svg-color--a38c84, #A38C84);
}

.cibf3wbnh {
  fill: var(--svg-color--86004c, #86004C);
  fill-rule: evenodd;
  d: path("M16.98 8.513a.1.1 0 0 1 .132.05c.032.07.15.243.339.324a.1.1 0 0 1-.079.183a.92.92 0 0 1-.442-.425a.1.1 0 0 1 .05-.132");
}

.co6663b7r {
  stop-color: var(--svg-color--f7cfbd, #F7CFBD);
  stop-opacity: 0;
}

.d8-6g_bzt {
  stop-color: var(--svg-color--79af4c, #79AF4C);
  stop-opacity: 0;
}

.d8l2uy9_q {
  stop-color: var(--svg-color--9178d3, #9178D3);
}

.dq5-cvbyp {
  fill: var(--svg-color--f2c6af, #F2C6AF);
  d: path("M16.504 13.826c-.713-.331-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.109 2.375 1.278 2.684 1.351c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
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

.g4x6peb3r {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.545 7.453c.016-.037.07-.049.119-.027s.075.07.059.106c-.017.037-.07.049-.119.027s-.075-.07-.059-.106");
}

.g7ohc9bre {
  width: 1.28px;
  height: 0.637px;
  x: 19.523px;
  y: 13.105px;
  rx: 0.318px;
}

.gfyld4f1l {
  d: path("M14.713 7.747h1.744v2h-1.744z");
}

.gk2ia4b1g {
  d: path("M3.504 24.49c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.157-3.53 1.157c-1.317 0-2.188-1.157-3.548-1.157c-1.117 0-2.242 1.157-3.508 1.157c-.972 0-2.203-1.157-3.39-1.157c-1.258 0-2.262 1.157-3.399 1.157c-.558 0-.836-.102-1.539-.438s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.622l-.007.003c-.57.289-1.031.516-1.656.516s-1.031-.204-2-.735");
}

.goynh311p {
  fill: var(--svg-color--323232, #323232);
  fill-rule: evenodd;
  d: path("M17.866 6.991a.72.72 0 0 0-.488-.027a.1.1 0 0 1-.066-.19a.92.92 0 0 1 .637.036a.1.1 0 1 1-.083.181");
}

.h0p0yxwmg {
  d: path("M11.366 20.37a1.917 1.917 0 1 1 2.712 2.71l-2.468 2.469a1.917 1.917 0 0 1-2.712-2.71z");
}

.hdaqt0bwx {
  d: path("M15.931 9.708c-.914-.453-1.535-1.234-1.71-1.617l.662-1.592a1.2 1.2 0 0 1 1.034-.738l1.656-.11c.13-.009.263-.003.372.066c.288.183.576.645.369 1.476c-.229 1.08-.501 1.743-.749 2.226c-.177.345-.533.572-.916.506a3.2 3.2 0 0 1-.718-.217");
}

.hob-w_b7u {
  stop-color: var(--svg-color--286ec5, #286EC5);
}

.i5bb1evpw {
  d: path("M3.504 20.99c-.775-.425-1.254-.422-1.445-.422v5.938H29.94v-5.938c-1.562 0-2.214 1.157-3.53 1.157c-1.317 0-2.188-1.157-3.548-1.157c-1.117 0-2.242 1.157-3.508 1.157c-.972 0-2.203-1.157-3.39-1.157c-1.258 0-2.262 1.157-3.399 1.157c-.558 0-.836-.102-1.539-.438s-1.324-.703-1.98-.703c-.654 0-1.311.333-1.88.622l-.007.003c-.57.289-1.031.516-1.656.516s-1.031-.204-2-.735");
}

.ifzxkw8wi {
  stop-color: var(--svg-color--38a7fb, #38A7FB);
}

.ik1b347lr {
  stop-color: var(--svg-color--57399f, #57399F);
}

.j9b-420yy {
  stop-color: var(--svg-color--2f2529, #2F2529);
}

.ja67fo1gr {
  stop-color: var(--svg-color--fbc998, #FBC998);
}

.ju-dj4awd {
  stop-color: var(--svg-color--191919, #191919);
}

.jum6cmbcz {
  stop-color: var(--svg-color--af866a, #AF866A);
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

.kpwscabck {
  stop-color: var(--svg-color--ffd5be, #FFD5BE);
  stop-opacity: 0;
}

.lx7f_77ow {
  stop-color: var(--svg-color--e9b37e, #E9B37E);
}

.m8h6tdgkz {
  stop-color: var(--svg-color--3d3d3d, #3D3D3D);
}

.ml-wi-9ur {
  stop-color: var(--svg-color--7151be, #7151BE);
}

.mpozi6wus {
  stop-color: var(--svg-color--70a762, #70A762);
  stop-opacity: 0;
}

.mwy-f8bpu {
  stop-color: var(--svg-color--e2b79d, #E2B79D);
}

.n06ongbiu {
  d: path("M13.6 6.827c.332-.227.418-.442.515-1.094c.219-1.094.542-1.306.969-1.547c.449-.254 1.195-.187 1.703.196c.558.42.668.34 1.348.363c.722.023.972.496.988.91c.015.414-.207.98-.934 1.031c-.834.058-.875-.687-1.574-.531c-.596.133-.727 1.316-.976 1.797c-.159.305-.3 1.013-1.165 1.21c-.921.212-1.68-.562-1.554-1.327c.1-.613.382-.805.68-1.008");
}

.n4xk4fb0e {
  stop-color: var(--svg-color--f7cfbd, #F7CFBD);
}

.ncdif6bxa {
  stop-color: var(--svg-color--65deff, #65DEFF);
}

.nummxxbxx {
  fill: var(--svg-color--fff, #fff);
  d: path("M17.645 7.825c.048.012.099-.027.124-.083l.003-.01c.066-.246-.096-.437-.295-.49c-.189-.051-.434.03-.5.277l-.003.01c-.015.059.01.118.066.133z");
}

.oadl-1bdu {
  stop-color: var(--svg-color--bc8c78, #BC8C78);
}

.pjzjl2c9v {
  stop-color: var(--svg-color--59a0ff, #59A0FF);
}

.pna-0uy1p {
  stop-color: var(--svg-color--cd9157, #CD9157);
}

.pyyiilrww {
  d: path("M13.004 11.115c.6.719 1.333 1.555 1.625 1.883l1.656-1.484c-.33-.396-1.117-1.303-1.617-1.766c-.625-.578-1.27-.191-1.469 0c-.172.166-.672.688-.195 1.367");
}

.q2qi1lbnq {
  stop-color: var(--svg-color--ffd5be, #FFD5BE);
}

.qgpj16bec {
  d: path("M18.232 8.104c-.081-.147-.066-.412-.047-.504l-.445 1.02c.14.073.378.138.515-.032c.098-.121.079-.3-.023-.484");
}

.qjl30cblz {
  stop-color: var(--svg-color--5dc9ff, #5DC9FF);
  stop-opacity: 0;
}

.qn887rbfy {
  d: path("M9.598 13.772c-.243.894-.203 1.761-.11 2.023l6.309-.063z");
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

.sav8j7bhz {
  d: path("M17.641 7.823q.045-.05.061-.11c.027-.098-.019-.205-.097-.226c-.08-.022-.17.039-.198.147a.3.3 0 0 0-.002.126z");
}

.t04vb-hcs {
  stop-color: var(--svg-color--f4c8b2, #F4C8B2);
}

.t4coan9us {
  stop-color: var(--svg-color--eea894, #EEA894);
}

.u_4uylzec {
  stop-color: var(--svg-color--f7c6b6, #F7C6B6);
}

.v15kcqbep {
  stop-color: var(--svg-color--eeb683, #EEB683);
  stop-opacity: 0;
}

.v5wfdhbpr {
  stop-color: var(--svg-color--99d852, #99D852);
}

.v6p95_84a {
  d: path("M21.334 12.32a.59.59 0 0 1 .829.84l-8.439 8.331a.59.59 0 0 1-.829-.839z");
}

.vz3r91b9q {
  d: path("m16.914 7.522l.116.063l.57-.29c-.28-.16-.543-.126-.722.026c-.068.057-.042.16.036.201");
}

.wht0ubbtr {
  d: path("M11.168 10.615c-1.006 1.232-1.414 2.668-1.594 3.274l3.992 1.25c.125-1.024.75-2.72 1.172-3.375c.422-.657.489-.871.555-1.348s-.256-1.194-1.336-1.395c-.844-.156-1.854.45-2.789 1.594");
}

.wqvuuub3k {
  stop-color: var(--svg-color--4b4748, #4B4748);
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

.xxkg1ibyo {
  stop-color: var(--svg-color--4b4748, #4B4748);
  stop-opacity: 0;
}

.y866tkb_w {
  stop-color: var(--svg-color--7caf55, #7CAF55);
  stop-opacity: 0;
}

.yauhuibbl {
  stop-color: var(--svg-color--f7c6b6, #F7C6B6);
  stop-opacity: 0;
}

.yeadpn21v {
  d: path("M16.504 13.826c-.713-.331-1.443-.966-1.719-1.242l1.281-1.191c1.157 1.109 2.375 1.278 2.684 1.351c.395.094 1.538.3 2.168.73c.516.352.379.993.07 1.266c-.254.225-.675.336-1.011.203s-.559-.27-1.227-.398a10 10 0 0 1-2.246-.719");
}

.z7o0euhwd {
  stop-color: var(--svg-color--697167, #697167);
}

.zr9po46dd {
  d: path("M17.72 7.845c.02-.037.038-.063.051-.113c.048-.177-.02-.354-.169-.394c-.138-.037-.296.08-.343.257a.5.5 0 0 0-.012.123z");
}

.zuv3brbdp {
  stop-color: var(--svg-color--da9c63, #DA9C63);
}

</style>
