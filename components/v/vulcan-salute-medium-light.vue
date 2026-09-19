<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i8VvYtB)"><path class="smfpysbbt"/><path fill="url(#idzW2YM)" class="zs2tjwkbj"/><path fill="url(#iBGPmCe)" class="zs2tjwkbj"/><path fill="url(#i67Wtgd)" class="zs2tjwkbj"/></g><path fill="url(#iC9nDjz)" class="lod54qbgp"/><path fill="url(#iVurcne)" class="lod54qbgp"/><path fill="url(#ima7snb)" class="lod54qbgp"/><g filter="url(#iA4sLjb)"><rect transform="rotate(-22.578 5.469 9)" class="zgd211bqt"/></g><path fill="url(#iVV6Z3J)" class="yrv334b1j"/><path fill="url(#iWVIkFd)" class="yrv334b1j"/><path fill="url(#ivqNafe)" class="yrv334b1j"/><path fill="url(#iMqribc)" class="yrv334b1j"/><path fill="url(#iy8P8Vb)" class="yrv334b1j"/><path fill="url(#iMnFmnX)" class="yrv334b1j"/><g filter="url(#i7ru1vb)"><rect transform="rotate(-19.107 9.815 5.753)" class="g_uat2ucg"/></g><path fill="url(#iFEWrnb)" class="o6cqoibvx"/><path fill="url(#igShgDc)" class="o6cqoibvx"/><path fill="url(#idWdnoo)" class="o6cqoibvx"/><path fill="url(#iv5EYRc)" class="o6cqoibvx"/><path fill="url(#i9crxcl)" class="o6cqoibvx"/><g filter="url(#ioHisCe)"><rect fill="url(#iPkN1qc)" transform="rotate(16.763 19.543 3.744)" class="ck2uxcccz"/></g><path fill="url(#iNlJxQd)" class="ukfpbt0da"/><path fill="url(#iYOPEzI)" class="ukfpbt0da"/><path fill="url(#inqRBtd)" class="ukfpbt0da"/><path fill="url(#iN1kOCd)" class="ukfpbt0da"/><g filter="url(#iauVgJe)"><rect fill="url(#iKFh2Gd)" transform="rotate(20.79 23.814 5.836)" class="y3ge8uxbf"/></g><g filter="url(#iod64GY)"><path stroke="url(#i9gJajd)" class="cn6_jpbda"/></g><path fill="url(#iTY60by)" class="tgdcydmal"/><path fill="url(#iJgjfwj)" class="tgdcydmal"/><g filter="url(#iqdTxlj)"><path stroke="url(#iZSjO1b)" class="zxa28fquk"/></g><g filter="url(#i1vp3Qb)"><path stroke="url(#iF1Hseb)" class="w9dr1bb1y"/></g><g filter="url(#iWpE2oc)"><path stroke="url(#iIxt8Cc)" class="n6o1lybvk"/></g><g filter="url(#iwIBOEx)"><path stroke="url(#ivz69we)" class="xjortmbgy"/></g><g filter="url(#iSnByBb)"><path stroke="url(#icj6V6b)" class="uaanmdj8v"/></g><path fill="url(#ivE3KBe)" class="w6d_0kb9f"/><path fill="url(#ieSKuIM)" class="w6d_0kb9f"/><path fill="url(#iONKx3d)" class="w6d_0kb9f"/><path fill="url(#iNCmKzc)" class="w6d_0kb9f"/><path fill="url(#i7AHtwb)" class="w6d_0kb9f"/><path fill="url(#is2wnzc)" class="w6d_0kb9f"/><path fill="url(#iAgfGTc)" class="w6d_0kb9f"/><defs><radialGradient id="idzW2YM" cx="0" cy="0" r="1" gradientTransform="matrix(5.57964 -3.27694 6.45506 10.99104 7.615 26.957)" gradientUnits="userSpaceOnUse"><stop class="rjyypub1e"/><stop offset="1" class="oxb09wspc"/></radialGradient><radialGradient id="iBGPmCe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.50706 8.21304 -8.36063 -3.57008 23.029 25.357)" gradientUnits="userSpaceOnUse"><stop class="f8_p_wq3x"/><stop offset="1" class="qcgpa1bfi"/></radialGradient><radialGradient id="i67Wtgd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.59125 8.97762 -5.45827 -4.61537 32.231 19.921)" gradientUnits="userSpaceOnUse"><stop class="nrgcn-bmj"/><stop offset="1" class="qtnyoe6zz"/><stop offset="1" class="necrjmb0z"/></radialGradient><radialGradient id="ima7snb" cx="0" cy="0" r="1" gradientTransform="rotate(68.515 -2.83 7.528)scale(2.99536 5.57619)" gradientUnits="userSpaceOnUse"><stop class="fd9v4ubat"/><stop offset="1" class="dfs1rr2vz"/></radialGradient><radialGradient id="iWVIkFd" cx="0" cy="0" r="1" gradientTransform="matrix(-.88994 .30388 -1.63403 -4.7854 14.007 9.714)" gradientUnits="userSpaceOnUse"><stop class="ry8qfz_dh"/><stop offset="1" class="z3xwwlagu"/></radialGradient><radialGradient id="ivqNafe" cx="0" cy="0" r="1" gradientTransform="matrix(.41951 -.13185 1.49361 4.7524 9.235 12.348)" gradientUnits="userSpaceOnUse"><stop class="jqqhsrbhx"/><stop offset="1" class="b9xgr7szd"/></radialGradient><radialGradient id="iMnFmnX" cx="0" cy="0" r="1" gradientTransform="matrix(.8227 2.71004 -3.53608 1.07347 9.31 4.189)" gradientUnits="userSpaceOnUse"><stop class="l_w5cbbvy"/><stop offset="1" class="zh1z8qbfc"/></radialGradient><radialGradient id="i9crxcl" cx="0" cy="0" r="1" gradientTransform="rotate(103.309 9.215 8.727)scale(3.79934 4.20751)" gradientUnits="userSpaceOnUse"><stop class="g6hc1040k"/><stop offset="1" class="bzthhfbtw"/></radialGradient><radialGradient id="inqRBtd" cx="0" cy="0" r="1" gradientTransform="rotate(-160.567 12.811 6.162)scale(.74532 1.9169)" gradientUnits="userSpaceOnUse"><stop class="uti0ugmbw"/><stop offset="1" class="j4qm-t7hh"/></radialGradient><radialGradient id="iN1kOCd" cx="0" cy="0" r="1" gradientTransform="rotate(101.271 10.364 11.791)scale(3.74953 4.50938)" gradientUnits="userSpaceOnUse"><stop class="ne7nwcctv"/><stop offset="1" class="yie3fibqq"/></radialGradient><radialGradient id="iTY60by" cx="0" cy="0" r="1" gradientTransform="matrix(1.29719 1.10259 -3.33471 3.92326 24.542 13.79)" gradientUnits="userSpaceOnUse"><stop class="i2iiazbhr"/><stop offset="1" class="nmm9rpbaz"/></radialGradient><radialGradient id="iJgjfwj" cx="0" cy="0" r="1" gradientTransform="rotate(113.749 10.384 15.344)scale(4.01662 4.13507)" gradientUnits="userSpaceOnUse"><stop class="lr_3rxbtk"/><stop offset="1" class="qvtd6ccmf"/></radialGradient><radialGradient id="ivE3KBe" cx="0" cy="0" r="1" gradientTransform="rotate(93.244 2.653 13.175)scale(19.7866 19.1478)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="nb6whhbdc"/><stop offset="1" class="xidocdcaj"/></radialGradient><radialGradient id="ieSKuIM" cx="0" cy="0" r="1" gradientTransform="matrix(-.02402 2.56503 -.76778 -.0072 14.376 10.378)" gradientUnits="userSpaceOnUse"><stop offset=".304" class="pw8bpacwl"/><stop offset="1" class="myczoyi5n"/></radialGradient><radialGradient id="iONKx3d" cx="0" cy="0" r="1" gradientTransform="rotate(136.84 12.027 12.694)scale(3.56633 2.41749)" gradientUnits="userSpaceOnUse"><stop class="zw1k0-prr"/><stop offset="1" class="g6mty-b8t"/></radialGradient><radialGradient id="iNCmKzc" cx="0" cy="0" r="1" gradientTransform="rotate(124.344 11.225 9.721)scale(2.30423 2.42474)" gradientUnits="userSpaceOnUse"><stop class="zw1k0-prr"/><stop offset="1" class="g6mty-b8t"/></radialGradient><radialGradient id="i7AHtwb" cx="0" cy="0" r="1" gradientTransform="rotate(124.706 9.645 7.104)scale(3.09549 2.22986)" gradientUnits="userSpaceOnUse"><stop class="zw1k0-prr"/><stop offset="1" class="g6mty-b8t"/></radialGradient><radialGradient id="is2wnzc" cx="0" cy="0" r="1" gradientTransform="matrix(-.90997 2.55112 -1.66421 -.59361 11.458 5.592)" gradientUnits="userSpaceOnUse"><stop class="zw1k0-prr"/><stop offset="1" class="g6mty-b8t"/></radialGradient><radialGradient id="iAgfGTc" cx="0" cy="0" r="1" gradientTransform="rotate(113.794 .088 6.846)scale(1.18141 1.33457)" gradientUnits="userSpaceOnUse"><stop class="zw1k0-prr"/><stop offset="1" class="g6mty-b8t"/></radialGradient><linearGradient id="iC9nDjz" x1="9.694" x2="8.148" y1="11.893" y2="12.438" gradientUnits="userSpaceOnUse"><stop class="seldi1blh"/><stop offset="1" class="y-yz7bcsb"/></linearGradient><linearGradient id="iVurcne" x1="10.42" x2="9.072" y1="14.509" y2="13.23" gradientUnits="userSpaceOnUse"><stop class="d45rozkcj"/><stop offset="1" class="h6q9cs4gl"/></linearGradient><linearGradient id="iVV6Z3J" x1="8.592" x2="11.072" y1="11.739" y2="10.823" gradientUnits="userSpaceOnUse"><stop class="d2m8m4bgi"/><stop offset="1" class="oac1o4olg"/></linearGradient><linearGradient id="iMqribc" x1="14.24" x2="11.698" y1="9.063" y2="9.824" gradientUnits="userSpaceOnUse"><stop class="ertbuvb0r"/><stop offset="1" class="mrx-mta2y"/></linearGradient><linearGradient id="iy8P8Vb" x1="12.802" x2="12.459" y1="14.688" y2="13.594" gradientUnits="userSpaceOnUse"><stop class="d45rozkcj"/><stop offset="1" class="h6q9cs4gl"/></linearGradient><linearGradient id="iFEWrnb" x1="14.596" x2="17.148" y1="8.389" y2="9.169" gradientUnits="userSpaceOnUse"><stop class="n9rh2vbir"/><stop offset="1" class="cz3oprb8q"/></linearGradient><linearGradient id="igShgDc" x1="20.232" x2="18.987" y1="10.522" y2="10.107" gradientUnits="userSpaceOnUse"><stop class="eeg5spbdy"/><stop offset="1" class="gnhh4dbdg"/></linearGradient><linearGradient id="idWdnoo" x1="19.86" x2="19.459" y1="10.556" y2="10.427" gradientUnits="userSpaceOnUse"><stop class="b1jpjobvq"/><stop offset="1" class="ond-4xb_e"/></linearGradient><linearGradient id="iv5EYRc" x1="17.959" x2="16.158" y1="15.177" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="s2m54db3x"/><stop offset="1" class="y8en6kbls"/></linearGradient><linearGradient id="iPkN1qc" x1="20.957" x2="20.888" y1="4.932" y2="15.559" gradientUnits="userSpaceOnUse"><stop class="iax95ggde"/><stop offset="1" class="bprwjcb0l"/></linearGradient><linearGradient id="iNlJxQd" x1="19.14" x2="22.241" y1="10.639" y2="11.633" gradientUnits="userSpaceOnUse"><stop class="grj83qbzi"/><stop offset="1" class="d4cprkn1i"/></linearGradient><linearGradient id="iYOPEzI" x1="20.218" x2="21.16" y1="16.039" y2="14.146" gradientUnits="userSpaceOnUse"><stop class="d45rozkcj"/><stop offset="1" class="h6q9cs4gl"/></linearGradient><linearGradient id="iKFh2Gd" x1="25.319" x2="25.253" y1="7.024" y2="17.65" gradientUnits="userSpaceOnUse"><stop class="iax95ggde"/><stop offset="1" class="bprwjcb0l"/></linearGradient><linearGradient id="i9gJajd" x1="21.631" x2="20.873" y1="17.163" y2="16.637" gradientUnits="userSpaceOnUse"><stop class="w50xjybbe"/><stop offset="1" class="wwqt7bcaw"/></linearGradient><linearGradient id="iZSjO1b" x1="27.742" x2="23.644" y1="14.916" y2="20.062" gradientUnits="userSpaceOnUse"><stop class="hd9h8gb6h"/><stop offset="1" class="clhp8rz4o"/></linearGradient><linearGradient id="iF1Hseb" x1="10.535" x2="8.916" y1="17.615" y2="18.138" gradientUnits="userSpaceOnUse"><stop class="yq1n7wbvk"/><stop offset="1" class="fca6qb6dn"/></linearGradient><linearGradient id="iIxt8Cc" x1="13.528" x2="12.282" y1="15.086" y2="15.036" gradientUnits="userSpaceOnUse"><stop class="yq1n7wbvk"/><stop offset="1" class="fca6qb6dn"/></linearGradient><linearGradient id="ivz69we" x1="18.355" x2="17.103" y1="15.133" y2="16.218" gradientUnits="userSpaceOnUse"><stop class="yq1n7wbvk"/><stop offset="1" class="fca6qb6dn"/></linearGradient><linearGradient id="icj6V6b" x1="22.132" x2="20.879" y1="17.358" y2="18.443" gradientUnits="userSpaceOnUse"><stop class="yq1n7wbvk"/><stop offset="1" class="fca6qb6dn"/></linearGradient><filter id="i8VvYtB" width="27.027" height="28.645" x="3.486" y="1.473" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.75"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.784314 0 0 0 0 0.556863 0 0 0 0 0.490196 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1665"/></filter><filter id="iA4sLjb" width="6.832" height="10.115" x="4.198" y="7.156" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".75"/></filter><filter id="i7ru1vb" width="6.862" height="11.328" x="8.518" y="3.967" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".75"/></filter><filter id="ioHisCe" width="7.078" height="13.072" x="15.212" y="2.428" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".75"/></filter><filter id="iauVgJe" width="7.735" height="12.875" x="18.835" y="4.566" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".75"/></filter><filter id="iod64GY" width="2.968" height="5.692" x="20.486" y="12.372" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".3"/></filter><filter id="iqdTxlj" width="8.372" height="8.6" x="21.37" y="12.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".75"/></filter><filter id="i1vp3Qb" width="4.049" height="3.811" x="7.254" y="14.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".3"/></filter><filter id="iWpE2oc" width="3.874" height="3.076" x="11.109" y="12.007" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".3"/></filter><filter id="iwIBOEx" width="4.556" height="2.719" x="14.536" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".3"/></filter><filter id="iSnByBb" width="4.556" height="2.719" x="18.313" y="15.323" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1665" stdDeviation=".3"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:vulcan-salute-medium-light" /></template>
<style>
.b1jpjobvq {
  stop-color: var(--svg-color--a36643, #A36643);
}

.b9xgr7szd {
  stop-color: var(--svg-color--af6b4a, #AF6B4A);
  stop-opacity: 0;
}

.bprwjcb0l {
  stop-color: var(--svg-color--dfa891, #DFA891);
  stop-opacity: 0;
}

.bzthhfbtw {
  stop-color: var(--svg-color--cfa380, #CFA380);
  stop-opacity: 0;
}

.ck2uxcccz {
  width: 1.494px;
  height: 10.452px;
  x: 19.543px;
  y: 3.744px;
  rx: 0.747px;
}

.clhp8rz4o {
  stop-color: var(--svg-color--fecdaa, #FECDAA);
  stop-opacity: 0;
}

.cn6_jpbda {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("m21.386 17.163l1.167-3.891");
}

.cz3oprb8q {
  stop-color: var(--svg-color--d19979, #D19979);
  stop-opacity: 0;
}

.d2m8m4bgi {
  stop-color: var(--svg-color--c58564, #C58564);
}

.d45rozkcj {
  stop-color: var(--svg-color--ebb297, #EBB297);
}

.d4cprkn1i {
  stop-color: var(--svg-color--bc7d5c, #BC7D5C);
  stop-opacity: 0;
}

.dfs1rr2vz {
  stop-color: var(--svg-color--cca07f, #CCA07F);
  stop-opacity: 0;
}

.eeg5spbdy {
  stop-color: var(--svg-color--bd7e5e, #BD7E5E);
}

.ertbuvb0r {
  stop-color: var(--svg-color--d7a889, #D7A889);
}

.f8_p_wq3x {
  stop-color: var(--svg-color--edb39c, #EDB39C);
}

.fca6qb6dn {
  stop-color: var(--svg-color--f6c3a5, #F6C3A5);
  stop-opacity: 0;
}

.fd9v4ubat {
  stop-color: var(--svg-color--cca07f, #CCA07F);
}

.ft5dv1b6b {
  fill: none;
}

.g_uat2ucg {
  width: 1.494px;
  height: 8.726px;
  x: 9.815px;
  y: 5.753px;
  fill: var(--svg-color--f4c4a4, #F4C4A4);
  rx: 0.747px;
}

.g6hc1040k {
  stop-color: var(--svg-color--cfa380, #CFA380);
}

.g6mty-b8t {
  stop-color: var(--svg-color--fecea7, #FECEA7);
  stop-opacity: 0;
}

.gnhh4dbdg {
  stop-color: var(--svg-color--bd7e5e, #BD7E5E);
  stop-opacity: 0;
}

.grj83qbzi {
  stop-color: var(--svg-color--bc7d5c, #BC7D5C);
}

.h6q9cs4gl {
  stop-color: var(--svg-color--ebb297, #EBB297);
  stop-opacity: 0;
}

.hd9h8gb6h {
  stop-color: var(--svg-color--fecdaa, #FECDAA);
}

.i2iiazbhr {
  stop-color: var(--svg-color--ca9d81, #CA9D81);
}

.iax95ggde {
  stop-color: var(--svg-color--dfa891, #DFA891);
}

.j4qm-t7hh {
  stop-color: var(--svg-color--ce9d7e, #CE9D7E);
  stop-opacity: 0;
}

.jqqhsrbhx {
  stop-color: var(--svg-color--af6b4a, #AF6B4A);
}

.l_w5cbbvy {
  stop-color: var(--svg-color--cea17d, #CEA17D);
}

.lod54qbgp {
  d: path("M5.193 15.951a4.99 4.99 0 0 0 5.086-1.405L7.98 8.73a2.45 2.45 0 0 0-4.35 2.17l.678 1.904l.057.168c.196.571.557 1.623.828 2.978");
}

.lr_3rxbtk {
  stop-color: var(--svg-color--daac87, #DAAC87);
}

.mrx-mta2y {
  stop-color: var(--svg-color--d7a889, #D7A889);
  stop-opacity: 0;
}

.myczoyi5n {
  stop-color: var(--svg-color--c08662, #C08662);
  stop-opacity: 0;
}

.n6o1lybvk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M12.01 14.183c.362-.056 1.513-.346 2.073-1.276");
}

.n9rh2vbir {
  stop-color: var(--svg-color--d19979, #D19979);
}

.nb6whhbdc {
  stop-color: var(--svg-color--b6708f, #B6708F);
  stop-opacity: 0;
}

.ne7nwcctv {
  stop-color: var(--svg-color--cca07d, #CCA07D);
}

.necrjmb0z {
  stop-color: var(--svg-color--ca948c, #CA948C);
  stop-opacity: 0;
}

.nmm9rpbaz {
  stop-color: var(--svg-color--ca9d81, #CA9D81);
  stop-opacity: 0;
}

.nrgcn-bmj {
  stop-color: var(--svg-color--ca948c, #CA948C);
}

.o6cqoibvx {
  d: path("M14.328 11.81c.083 2.688 2.763 3.825 3.94 3.481l2.865-8.797l.342-1.081a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.826 3.9c-.65 2.013-1.61 5.042-2.415 7.812a.15.15 0 0 1-.083.097");
}

.oac1o4olg {
  stop-color: var(--svg-color--c58564, #C58564);
  stop-opacity: 0;
}

.ond-4xb_e {
  stop-color: var(--svg-color--a36643, #A36643);
  stop-opacity: 0;
}

.oxb09wspc {
  stop-color: var(--svg-color--c78d80, #C78D80);
  stop-opacity: 0;
}

.pw8bpacwl {
  stop-color: var(--svg-color--c08662, #C08662);
}

.qcgpa1bfi {
  stop-color: var(--svg-color--edb39c, #EDB39C);
  stop-opacity: 0;
}

.qtnyoe6zz {
  stop-color: var(--svg-color--86575f, #86575F);
  stop-opacity: 0;
}

.qvtd6ccmf {
  stop-color: var(--svg-color--daac87, #DAAC87);
  stop-opacity: 0;
}

.rjyypub1e {
  stop-color: var(--svg-color--c78d80, #C78D80);
}

.ry8qfz_dh {
  stop-color: var(--svg-color--ce9a7a, #CE9A7A);
}

.s2m54db3x {
  stop-color: var(--svg-color--ebb298, #EBB298);
}

.seldi1blh {
  stop-color: var(--svg-color--c38260, #C38260);
}

.smfpysbbt {
  fill: var(--svg-color--ebb297, #EBB297);
  d: path("M21.475 5.413a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.826 3.9c-.65 2.013-1.61 5.042-2.415 7.812c-.041.142-.241.147-.287.006c-.6-1.825-1.558-4.734-1.856-5.613c-.446-1.312-1.887-1.94-3.165-1.485A2.43 2.43 0 0 0 7.63 7.724L8 8.758a2.45 2.45 0 0 0-4.37 2.143l.679 1.904c.235.696.905 2.518 1.148 4.869l.065.645c.244 2.454.519 5.22 1.953 7.523a8.33 8.33 0 0 0 7.28 4.277a8.3 8.3 0 0 0 3.477-.758c1.36-.584 2.62-1.481 3.6-2.802c1.159-1.472 1.545-2.166 2.138-3.23c.102-.184.21-.378.33-.59c.577-1.02 1.763-2.611 2.446-3.496l2.283-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.283 2.457l3.146-8.221a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.tgdcydmal {
  d: path("m22.786 15.929l-.008.011c-.348 1.417-.32 4.26 1.725 6.455c.62-1.007 1.632-2.361 2.242-3.152l2.283-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.283 2.457z");
}

.uaanmdj8v {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M19.213 16.223c.406.297 1.524.897 2.756.919");
}

.ukfpbt0da {
  d: path("m21.043 6.777l-2.85 8.68c.46.614 1.787 1.854 3.8 1.94c0-.037.3-.584.786-1.45l3.146-8.22a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.uti0ugmbw {
  stop-color: var(--svg-color--ce9d7e, #CE9D7E);
}

.w50xjybbe {
  stop-color: var(--svg-color--fac5a5, #FAC5A5);
}

.w6d_0kb9f {
  d: path("M21.514 5.408a2.45 2.45 0 0 0-1.592-3.07a2.436 2.436 0 0 0-3.068 1.558a290 290 0 0 0-2.42 7.814a.15.15 0 0 1-.287.006a1087 1087 0 0 0-1.86-5.614c-.447-1.313-1.892-1.941-3.172-1.486A2.43 2.43 0 0 0 7.639 7.72l.37 1.033a2.46 2.46 0 0 0-2.892-.985a2.447 2.447 0 0 0-1.488 3.128l.68 1.904c.237.697.907 2.518 1.15 4.869q.034.318.066.645c.245 2.454.52 5.22 1.957 7.523a8.35 8.35 0 0 0 7.296 4.277a8.3 8.3 0 0 0 3.484-.758c1.363-.584 2.626-1.481 3.607-2.801c1.162-1.473 1.55-2.167 2.143-3.23l.331-.59c.578-1.02 1.767-2.612 2.451-3.496l2.289-2.58c.955-1.03 1.044-2.55-.105-3.61c-1.031-.952-2.74-.807-3.87.438l-2.288 2.457l3.153-8.222a2.456 2.456 0 0 0-1.465-3.18c-1.266-.458-2.672.182-3.129 1.445l-.426 1.188z");
}

.w9dr1bb1y {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M8.154 17.142c.332-.159 1.523-1.111 2.249-2.01");
}

.wwqt7bcaw {
  stop-color: var(--svg-color--fac5a5, #FAC5A5);
  stop-opacity: 0;
}

.xidocdcaj {
  stop-color: var(--svg-color--b6708f, #B6708F);
}

.xjortmbgy {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-6px, 0.6px);
  d: path("M15.437 13.998c.405.297 1.524.897 2.756.918");
}

.y-yz7bcsb {
  stop-color: var(--svg-color--c38260, #C38260);
  stop-opacity: 0;
}

.y3ge8uxbf {
  width: 1.589px;
  height: 10.452px;
  x: 23.814px;
  y: 5.836px;
  rx: 0.794px;
}

.y8en6kbls {
  stop-color: var(--svg-color--ebb298, #EBB298);
  stop-opacity: 0;
}

.yie3fibqq {
  stop-color: var(--svg-color--cca07d, #CCA07D);
  stop-opacity: 0;
}

.yq1n7wbvk {
  stop-color: var(--svg-color--f6c3a5, #F6C3A5);
}

.yrv334b1j {
  d: path("M14.124 11.72a.15.15 0 0 0 .037.06l.495 1.981c-1.612 1.435-3.434 1.475-4.143 1.387l-.237-.598q0-.003.003-.004L7.98 8.73l.02.028l-.37-1.034a2.43 2.43 0 0 1 1.473-3.103c1.278-.456 2.72.173 3.165 1.485c.298.88 1.256 3.788 1.856 5.613");
}

.z3xwwlagu {
  stop-color: var(--svg-color--ce9a7a, #CE9A7A);
  stop-opacity: 0;
}

.zgd211bqt {
  width: 1.494px;
  height: 7.581px;
  x: 5.469px;
  y: 9px;
  fill: var(--svg-color--f4c4a4, #F4C4A4);
  rx: 0.747px;
}

.zh1z8qbfc {
  stop-color: var(--svg-color--cea17d, #CEA17D);
  stop-opacity: 0;
}

.zs2tjwkbj {
  d: path("M21.475 5.413a2.45 2.45 0 0 0-1.588-3.071A2.43 2.43 0 0 0 16.826 3.9c-.65 2.013-1.61 5.042-2.415 7.812c-.041.142-.241.147-.287.006c-.6-1.825-1.558-4.734-1.856-5.613c-.446-1.312-1.887-1.94-3.165-1.485A2.43 2.43 0 0 0 7.63 7.724L8 8.758a2.45 2.45 0 0 0-4.37 2.143l.679 1.904c.235.696.905 2.518 1.148 4.869l.065.645c.244 2.454.519 5.22 1.953 7.523a8.33 8.33 0 0 0 7.28 4.277a8.3 8.3 0 0 0 3.477-.758c1.36-.584 2.62-1.481 3.6-2.802c1.159-1.472 1.545-2.166 2.138-3.23c.102-.184.21-.378.33-.59c.577-1.02 1.763-2.611 2.446-3.496l2.283-2.58c.953-1.03 1.042-2.549-.104-3.61c-1.03-.952-2.735-.806-3.862.438l-2.283 2.457l3.146-8.221a2.457 2.457 0 0 0-1.462-3.181c-1.263-.458-2.666.182-3.122 1.446l-.425 1.187z");
}

.zw1k0-prr {
  stop-color: var(--svg-color--fecea7, #FECEA7);
}

.zxa28fquk {
  stroke-linecap: round;
  d: path("m23.37 19.288l4.372-4.6");
}

</style>
