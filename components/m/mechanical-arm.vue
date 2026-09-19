<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iSNJV6d)"><path class="m-fo3w3jr"/><path fill="url(#ieLXzyc)" class="i8fd66ptk"/><path fill="url(#iFy4Czb)" class="i8fd66ptk"/><path fill="url(#i4MRWbd)" class="i8fd66ptk"/><path fill="url(#in3gQ5c)" class="i8fd66ptk"/></g><path fill="url(#iDx3ife)" class="vd1ylccwz"/><path fill="url(#iZZQnJb)" class="vd1ylccwz"/><path fill="url(#iaDLYGb)" class="vd1ylccwz"/><path fill="url(#iWfrgXy)" class="vd1ylccwz"/><g filter="url(#iaOYpsc)"><circle stroke="url(#ifcP6Qd)" class="cskuu8j6x"/></g><g filter="url(#iErj5ke)"><circle stroke="url(#i6YA2Ib)" class="tor4gcbpa"/></g><g filter="url(#i7vdGhb)"><circle class="ou8ht6hut"/></g><circle fill="url(#iN2J6ne)" class="p913mb25a"/><g filter="url(#iorTDRV)"><circle stroke="url(#ikdTEFd)" class="r3cc8cbgl"/></g><g filter="url(#iGJ6Mue)"><circle fill="url(#ijpDGnz)" class="z7jw17ejy"/></g><circle fill="url(#iIvDFAd)" class="z7jw17ejy"/><circle fill="url(#ixGB1Sc)" class="z7jw17ejy"/><g filter="url(#i2EDS7d)"><circle stroke="url(#iIfi5pd)" class="aleyy5bqt"/></g><circle fill="url(#iQpk8kb)" class="uogkkkbir"/><circle fill="url(#i1nRqpb)" class="uogkkkbir"/><g filter="url(#ivSl5bb)"><circle stroke="url(#iMhOcuH)" class="xo2w5wbsq"/></g><g filter="url(#ivXmnAL)"><circle fill="url(#in6bfte)" class="jpsbt4hwi"/></g><path fill="url(#iQisQmb)" class="wye7g4g7v"/><g filter="url(#iNhtKXi)"><path stroke="url(#idZV1Cc)" class="kf3xrgb1t"/></g><rect fill="url(#iCTW6Pb)" class="afu3b-cmp"/><rect fill="url(#iUzGlob)" class="afu3b-cmp"/><rect fill="url(#isowuSd)" class="afu3b-cmp"/><rect fill="url(#iYFRIbb)" class="afu3b-cmp"/><g filter="url(#isKtx3d)"><circle stroke="url(#i7LCtud)" class="t08hqzb4a"/></g><g filter="url(#iQK5e6c)"><circle class="adzcqibhg"/></g><g filter="url(#izt11OI)"><circle fill="url(#iW6q5id)" class="grap1vbaw"/></g><g filter="url(#idLeKle)"><path fill="url(#i0py6qc)" class="qo2dc2bhb"/></g><defs><radialGradient id="iFy4Czb" cx="0" cy="0" r="1" gradientTransform="matrix(1.09376 2.71875 -2.97195 1.19562 10.117 10.718)" gradientUnits="userSpaceOnUse"><stop offset=".157" class="qnxd2wb4e"/><stop offset="1" class="d6772sbzg"/></radialGradient><radialGradient id="i4MRWbd" cx="0" cy="0" r="1" gradientTransform="rotate(77.574 -5.4 15.18)scale(5.66393 2.61627)" gradientUnits="userSpaceOnUse"><stop class="my4o4gmyo"/><stop offset="1" class="vg7klur1n"/></radialGradient><radialGradient id="in3gQ5c" cx="0" cy="0" r="1" gradientTransform="matrix(-5.4788 3.56246 -3.90368 -6.00356 16.253 5.937)" gradientUnits="userSpaceOnUse"><stop class="zidmtyn5i"/><stop offset="1" class="zvvhlzqhb"/></radialGradient><radialGradient id="iDx3ife" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.79386 -8.09335 0 9.3 19.75)" gradientUnits="userSpaceOnUse"><stop class="hw3nizz_v"/><stop offset="1" class="ylqs9b_hr"/></radialGradient><radialGradient id="iaDLYGb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.65249 1.88156 -3.65707 -7.09911 15.757 24.305)" gradientUnits="userSpaceOnUse"><stop class="kbaazmb3o"/><stop offset="1" class="pcxbs-bai"/></radialGradient><radialGradient id="iWfrgXy" cx="0" cy="0" r="1" gradientTransform="rotate(-132.632 11.876 10.906)scale(11.8059 10.2499)" gradientUnits="userSpaceOnUse"><stop offset=".942" class="bfgxzgb-n"/><stop offset="1" class="afjlfybqu"/></radialGradient><radialGradient id="iN2J6ne" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5.236 6.59375 0 9.211 28.469)" gradientUnits="userSpaceOnUse"><stop class="leby--1fh"/><stop offset="1" class="d2noh_w7q"/></radialGradient><radialGradient id="ijpDGnz" cx="0" cy="0" r="1" gradientTransform="rotate(152.865 10.365 13.216)scale(11.2368)" gradientUnits="userSpaceOnUse"><stop class="nsmntj3ul"/><stop offset="1" class="s_ehm9b4e"/></radialGradient><radialGradient id="iIvDFAd" cx="0" cy="0" r="1" gradientTransform="rotate(100.607 3.305 18.888)scale(14.1885 16.7623)" gradientUnits="userSpaceOnUse"><stop offset=".495" class="ueea7c_yz"/><stop offset=".912" class="ngrhtw27e"/></radialGradient><radialGradient id="ixGB1Sc" cx="0" cy="0" r="1" gradientTransform="rotate(102.067 3.44 18.11)scale(11.6594 11.3693)" gradientUnits="userSpaceOnUse"><stop offset=".907" class="w07tpwb2f"/><stop offset="1" class="j7j1oi9as"/></radialGradient><radialGradient id="iIfi5pd" cx="0" cy="0" r="1" gradientTransform="matrix(4.07815 -5.74998 7.70564 5.4652 19.258 24.218)" gradientUnits="userSpaceOnUse"><stop class="q-ln-vbkt"/><stop offset="1" class="r8hd1cbzx"/></radialGradient><radialGradient id="iQpk8kb" cx="0" cy="0" r="1" gradientTransform="rotate(138.325 8.555 14.454)scale(7.23793 8.72495)" gradientUnits="userSpaceOnUse"><stop class="vro8t3wmz"/><stop offset="1" class="bxxk5fxwn"/></radialGradient><radialGradient id="i1nRqpb" cx="0" cy="0" r="1" gradientTransform="rotate(-60.709 32.382 -2.703)scale(4.73017)" gradientUnits="userSpaceOnUse"><stop class="rp0_o4b6g"/><stop offset="1" class="p6o33jont"/></radialGradient><radialGradient id="iQisQmb" cx="0" cy="0" r="1" gradientTransform="matrix(.17188 -.64844 1.30013 .34461 11.07 7.875)" gradientUnits="userSpaceOnUse"><stop class="ianidmbft"/><stop offset="1" class="ercpjgb1d"/></radialGradient><radialGradient id="iUzGlob" cx="0" cy="0" r="1" gradientTransform="matrix(9.69943 0 0 7.55237 6.713 9.598)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="p_197nrym"/><stop offset="1" class="yi5996bix"/></radialGradient><radialGradient id="isowuSd" cx="0" cy="0" r="1" gradientTransform="rotate(159.344 7.133 5.15)scale(9.26397 7.21331)" gradientUnits="userSpaceOnUse"><stop offset=".926" class="wyiduzb-b"/><stop offset="1" class="dx9vagbwe"/></radialGradient><radialGradient id="iYFRIbb" cx="0" cy="0" r="1" gradientTransform="rotate(-102.875 11.683 .79)scale(1.27282 4.36126)" gradientUnits="userSpaceOnUse"><stop class="uw77loaqg"/><stop offset="1" class="o3icv6bfr"/></radialGradient><radialGradient id="iW6q5id" cx="0" cy="0" r="1" gradientTransform="rotate(-32.152 23.859 -18.762)scale(2.33578)" gradientUnits="userSpaceOnUse"><stop class="rqtbz4fac"/><stop offset="1" class="p2p5klb-a"/></radialGradient><filter id="iSNJV6d" width="15.541" height="18.621" x="2.211" y="3.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0.25 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4391"/></filter><filter id="iaOYpsc" width="7.103" height="7.103" x="5.484" y="19.681" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".075"/></filter><filter id="iErj5ke" width="7.09" height="7.09" x="5.49" y="19.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".2"/></filter><filter id="i7vdGhb" width="5.719" height="5.719" x="6.176" y="20.373" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.364706 0 0 0 0 0.345098 0 0 0 0 0.388235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4391"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.301961 0 0 0 0 0.282353 0 0 0 0 0.32549 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_20020_4391" result="effect2_innerShadow_20020_4391"/></filter><filter id="iorTDRV" width="4.847" height="4.847" x="6.612" y="20.809" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".15"/></filter><filter id="iGJ6Mue" width="17.849" height="16.849" x="13.151" y="13.084" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.501961 0 0 0 0 0.509804 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4391"/></filter><filter id="i2EDS7d" width="8.303" height="8.303" x="17.424" y="17.357" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".125"/></filter><filter id="ivSl5bb" width="8.784" height="8.784" x="17.183" y="17.116" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".075"/></filter><filter id="ivXmnAL" width="6.445" height="6.445" x="18.353" y="18.286" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".25"/></filter><filter id="iNhtKXi" width="3.892" height="5.39" x="12.532" y="4.312" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".375"/></filter><filter id="isKtx3d" width="2.412" height="2.412" x="8.107" y="8.505" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".075"/></filter><filter id="iQK5e6c" width="2.038" height="2.038" x="8.344" y="8.642" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.501961 0 0 0 0 0.54902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_4391"/></filter><filter id="izt11OI" width="3.624" height="3.624" x="12.455" y="7.742" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".5"/></filter><filter id="idLeKle" width="1.157" height="1.375" x="9.134" y="8.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_4391" stdDeviation=".075"/></filter><linearGradient id="ieLXzyc" x1="-.257" x2="10.243" y1="18.312" y2="15.75" gradientUnits="userSpaceOnUse"><stop class="cd1ygacis"/><stop offset="1" class="sp3l5tbhd"/></linearGradient><linearGradient id="iZZQnJb" x1="12.215" x2="12.215" y1="29.933" y2="25.891" gradientUnits="userSpaceOnUse"><stop class="rtnz3_bmj"/><stop offset="1" class="hfqomtbpn"/></linearGradient><linearGradient id="ifcP6Qd" x1="6.723" x2="9.035" y1="26.24" y2="23.536" gradientUnits="userSpaceOnUse"><stop class="kfm28os3g"/><stop offset="1" class="k1dh_kbvt"/></linearGradient><linearGradient id="i6YA2Ib" x1="7.54" x2="11.089" y1="20.588" y2="25.878" gradientUnits="userSpaceOnUse"><stop class="oro0uwl6w"/><stop offset="1" class="olhrobbtj"/></linearGradient><linearGradient id="ikdTEFd" x1="11.33" x2="9.365" y1="21.359" y2="23.233" gradientUnits="userSpaceOnUse"><stop class="oyqh_gbss"/><stop offset="1" class="o4f04z4no"/></linearGradient><linearGradient id="iMhOcuH" x1="18.679" x2="21.576" y1="25.276" y2="21.889" gradientUnits="userSpaceOnUse"><stop class="kfm28os3g"/><stop offset="1" class="k1dh_kbvt"/></linearGradient><linearGradient id="in6bfte" x1="23.175" x2="20.325" y1="18.786" y2="24.703" gradientUnits="userSpaceOnUse"><stop class="smxbn79hw"/><stop offset="1" class="n75uffspr"/></linearGradient><linearGradient id="idZV1Cc" x1="15.174" x2="14.238" y1="6.375" y2="6.731" gradientUnits="userSpaceOnUse"><stop class="uk0oujenw"/><stop offset="1" class="ut1klz98a"/></linearGradient><linearGradient id="iCTW6Pb" x1="12.586" x2="11.461" y1="8.5" y2="12.531" gradientUnits="userSpaceOnUse"><stop class="fjvlpbcfk"/><stop offset="1" class="jqi3v0b1o"/></linearGradient><linearGradient id="i7LCtud" x1="10.22" x2="8.634" y1="10.551" y2="8.593" gradientUnits="userSpaceOnUse"><stop class="gpkl63bjc"/><stop offset="1" class="m68yzwb1q"/></linearGradient><linearGradient id="i0py6qc" x1="10.055" x2="9.638" y1="9.03" y2="9.514" gradientUnits="userSpaceOnUse"><stop class="nixu09bdr"/><stop offset="1" class="evx15l9tx"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mechanical-arm" /></template>
<style>
.adzcqibhg {
  cx: 9.314px;
  cy: 9.711px;
  r: 0.969px;
  fill: var(--svg-color--b7b6b9, #B7B6B9);
}

.afjlfybqu {
  stop-color: var(--svg-color--959595, #959595);
}

.afu3b-cmp {
  width: 8.357px;
  height: 4.03px;
  x: 6.956px;
  y: 7.759px;
  rx: 2.015px;
}

.aleyy5bqt {
  cx: 21.576px;
  cy: 21.508px;
  r: 3.652px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.bfgxzgb-n {
  stop-color: var(--svg-color--959595, #959595);
  stop-opacity: 0;
}

.bxxk5fxwn {
  stop-color: var(--svg-color--8e8796, #8E8796);
}

.cd1ygacis {
  stop-color: var(--svg-color--777678, #777678);
}

.cskuu8j6x {
  cx: 9.035px;
  cy: 23.233px;
  r: 3.326px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.d2noh_w7q {
  stop-color: var(--svg-color--746582, #746582);
  stop-opacity: 0;
}

.d6772sbzg {
  stop-color: var(--svg-color--58565b, #58565B);
  stop-opacity: 0;
}

.dx9vagbwe {
  stop-color: var(--svg-color--818082, #818082);
}

.ercpjgb1d {
  stop-color: var(--svg-color--454545, #454545);
}

.evx15l9tx {
  stop-color: var(--svg-color--d2d2d3, #D2D2D3);
  stop-opacity: 0;
}

.fjvlpbcfk {
  stop-color: var(--svg-color--9f9f9f, #9F9F9F);
}

.ft5dv1b6b {
  fill: none;
}

.gpkl63bjc {
  stop-color: var(--svg-color--6c6a6d, #6C6A6D);
}

.grap1vbaw {
  cx: 14.267px;
  cy: 9.554px;
  r: 0.812px;
}

.hfqomtbpn {
  stop-color: var(--svg-color--886aa4, #886AA4);
  stop-opacity: 0;
}

.hw3nizz_v {
  stop-color: var(--svg-color--a8a8a9, #A8A8A9);
}

.i8fd66ptk {
  d: path("M3.211 18.156c-.675 2.05-.979 3.604-1 4.031l11.313-2.875l-4.438-8.562h5.25c2.532-1.063 1.91-3.696 1.676-4.277c-.465-1.157-1.574-1.989-3.793-2.676c-2.218-.688-3.703.281-4.312 1.36c-.625.866-.828 2.257-1.352 3.413c-.781 1.5-2.5 7.024-3.344 9.586");
}

.ianidmbft {
  stop-color: var(--svg-color--555554, #555554);
}

.j7j1oi9as {
  stop-color: var(--svg-color--9677b2, #9677B2);
}

.jpsbt4hwi {
  cx: 21.576px;
  cy: 21.508px;
  r: 2.722px;
}

.jqi3v0b1o {
  stop-color: var(--svg-color--6e6972, #6E6972);
}

.k1dh_kbvt {
  stop-color: var(--svg-color--96919b, #96919B);
  stop-opacity: 0;
}

.kbaazmb3o {
  stop-color: var(--svg-color--676668, #676668);
}

.kf3xrgb1t {
  stroke-linecap: round;
  d: path("M13.782 5.563c.617.247 1.737 1.171 1.289 2.89");
}

.kfm28os3g {
  stop-color: var(--svg-color--96919b, #96919B);
}

.leby--1fh {
  stop-color: var(--svg-color--746582, #746582);
}

.m-fo3w3jr {
  fill: var(--svg-color--aaa9aa, #AAA9AA);
  d: path("M3.211 18.156c-.675 2.05-.979 3.604-1 4.031l11.313-2.875l-4.438-8.562h5.25c2.532-1.063 1.91-3.696 1.676-4.277c-.465-1.157-1.574-1.989-3.793-2.676c-2.218-.688-3.703.281-4.312 1.36c-.625.866-.828 2.257-1.352 3.413c-.781 1.5-2.5 7.024-3.344 9.586");
}

.m68yzwb1q {
  stop-color: var(--svg-color--6b686f, #6B686F);
  stop-opacity: 0;
}

.my4o4gmyo {
  stop-color: var(--svg-color--c5c4c6, #C5C4C6);
}

.n75uffspr {
  stop-color: var(--svg-color--b9b3bf, #B9B3BF);
}

.ngrhtw27e {
  stop-color: var(--svg-color--83659e, #83659E);
}

.nixu09bdr {
  stop-color: var(--svg-color--d2d2d3, #D2D2D3);
}

.nsmntj3ul {
  stop-color: var(--svg-color--d2d1d3, #D2D1D3);
}

.o3icv6bfr {
  stop-color: var(--svg-color--877798, #877798);
  stop-opacity: 0;
}

.o4f04z4no {
  stop-color: var(--svg-color--918e93, #918E93);
  stop-opacity: 0;
}

.olhrobbtj {
  stop-color: var(--svg-color--706c74, #706C74);
}

.oro0uwl6w {
  stop-color: var(--svg-color--8d8b90, #8D8B90);
}

.ou8ht6hut {
  cx: 9.035px;
  cy: 23.233px;
  r: 2.86px;
  fill: var(--svg-color--85818a, #85818A);
}

.oyqh_gbss {
  stop-color: var(--svg-color--99979b, #99979B);
}

.p_197nrym {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
  stop-opacity: 0;
}

.p2p5klb-a {
  stop-color: var(--svg-color--c8c8c9, #C8C8C9);
  stop-opacity: 0;
}

.p6o33jont {
  stop-color: var(--svg-color--89739f, #89739F);
  stop-opacity: 0;
}

.p913mb25a {
  cx: 9.035px;
  cy: 23.233px;
  r: 2.86px;
}

.pcxbs-bai {
  stop-color: var(--svg-color--676668, #676668);
  stop-opacity: 0;
}

.q-ln-vbkt {
  stop-color: var(--svg-color--696073, #696073);
}

.qnxd2wb4e {
  stop-color: var(--svg-color--58565b, #58565B);
}

.qo2dc2bhb {
  d: path("M9.84 9.795a.15.15 0 1 0 .299.021zm-.556-.615c.114 0 .265.041.38.138c.107.09.193.237.176.477l.299.021c.023-.334-.1-.575-.283-.728a.9.9 0 0 0-.572-.208z");
}

.r3cc8cbgl {
  cx: 9.035px;
  cy: 23.233px;
  r: 1.873px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.r8hd1cbzx {
  stop-color: var(--svg-color--a5a4a6, #A5A4A6);
}

.rp0_o4b6g {
  stop-color: var(--svg-color--89739f, #89739F);
}

.rqtbz4fac {
  stop-color: var(--svg-color--c8c8c9, #C8C8C9);
}

.rtnz3_bmj {
  stop-color: var(--svg-color--886aa4, #886AA4);
}

.s_ehm9b4e {
  stop-color: var(--svg-color--7f7886, #7F7886);
}

.smxbn79hw {
  stop-color: var(--svg-color--bfbbc4, #BFBBC4);
}

.sp3l5tbhd {
  stop-color: var(--svg-color--777678, #777678);
  stop-opacity: 0;
}

.t08hqzb4a {
  cx: 9.314px;
  cy: 9.711px;
  r: 0.981px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.tor4gcbpa {
  cx: 9.035px;
  cy: 23.233px;
  r: 2.895px;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
}

.ueea7c_yz {
  stop-color: var(--svg-color--83659e, #83659E);
  stop-opacity: 0;
}

.uk0oujenw {
  stop-color: var(--svg-color--cfcfcf, #CFCFCF);
}

.uogkkkbir {
  cx: 21.576px;
  cy: 21.509px;
  r: 3.607px;
}

.ut1klz98a {
  stop-color: var(--svg-color--cfcfcf, #CFCFCF);
  stop-opacity: 0;
}

.uw77loaqg {
  stop-color: var(--svg-color--877798, #877798);
}

.vd1ylccwz {
  d: path("M15.53 23.233a6.7 6.7 0 1 0-6.852 6.698v.002H21.66v-6.7z");
}

.vg7klur1n {
  stop-color: var(--svg-color--c5c4c6, #C5C4C6);
  stop-opacity: 0;
}

.vro8t3wmz {
  stop-color: var(--svg-color--e8e7e9, #E8E7E9);
}

.w07tpwb2f {
  stop-color: var(--svg-color--9677b2, #9677B2);
  stop-opacity: 0;
}

.wye7g4g7v {
  d: path("M11.737 8.011a.748.748 0 1 1-.377-1.022l2.43 1.022z");
}

.wyiduzb-b {
  stop-color: var(--svg-color--818082, #818082);
  stop-opacity: 0;
}

.xo2w5wbsq {
  cx: 21.576px;
  cy: 21.508px;
  r: 4.167px;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
}

.yi5996bix {
  stop-color: var(--svg-color--c1c1c2, #C1C1C2);
}

.ylqs9b_hr {
  stop-color: var(--svg-color--7c7780, #7C7780);
}

.z7jw17ejy {
  cx: 21.576px;
  cy: 21.508px;
  r: 8.425px;
}

.zidmtyn5i {
  stop-color: var(--svg-color--bcbcbc, #BCBCBC);
}

.zvvhlzqhb {
  stop-color: var(--svg-color--bcbcbc, #BCBCBC);
  stop-opacity: 0;
}

</style>
