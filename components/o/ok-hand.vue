<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iR3FhAe)"><path class="aj_l2-d9a"/><path fill="url(#iMOP2wD)" class="c-0-ffbgp"/><path fill="url(#iFmhsce)" class="c-0-ffbgp"/><path fill="url(#i7bz3ct)" class="c-0-ffbgp"/><path fill="url(#ioy19Ic)" class="c-0-ffbgp"/></g><path fill="url(#iDObOQe)" class="t0j3w4byy"/><path fill="url(#i4XEL4c)" class="t0j3w4byy"/><path fill="url(#iKauLKe)" class="t0j3w4byy"/><path fill="url(#iloj7Ad)" class="t0j3w4byy"/><path fill="url(#iwaPZMe)" class="t0j3w4byy"/><path fill="url(#imwftPp)" class="cwlxsm45w"/><path fill="url(#iWW1Fth)" class="cwlxsm45w"/><path fill="url(#iZDodip)" class="cwlxsm45w"/><path fill="url(#iWWXgzc)" class="cwlxsm45w"/><path fill="url(#iHedMKj)" class="j27cnyeuj"/><path fill="url(#iL1W3fb)" class="j27cnyeuj"/><path fill="url(#ivbcExR)" class="j27cnyeuj"/><path fill="url(#iv2ubLe)" class="j27cnyeuj"/><g filter="url(#iNMFtoA)"><path stroke="url(#ivelgmV)" class="f03fg5wyx"/></g><g filter="url(#iensLhb)"><path stroke="url(#i8ZsnXd)" class="ym4f1ac5d"/></g><g filter="url(#i29f7rb)"><path stroke="url(#ib30o1l)" class="hmkfq0btk"/></g><g filter="url(#iN4kjlb)"><path stroke="url(#i9zYQgp)" class="gr1lr6juf"/></g><g filter="url(#iIcJiGc)"><path stroke="url(#i3Pm7ye)" class="ie4mjlf7u"/></g><defs><linearGradient id="iDObOQe" x1="20.385" x2="23.397" y1="9.41" y2="9.41" gradientUnits="userSpaceOnUse"><stop class="hlms2gmxk"/><stop offset="1" class="f7qf7lbzz"/></linearGradient><linearGradient id="i4XEL4c" x1="20.869" x2="21.828" y1="9.786" y2="9.535" gradientUnits="userSpaceOnUse"><stop class="zs3ut5bwi"/><stop offset="1" class="d9d80bbly"/></linearGradient><linearGradient id="iloj7Ad" x1="25.813" x2="23.926" y1="10.327" y2="10.327" gradientUnits="userSpaceOnUse"><stop class="kxfq-cbin"/><stop offset="1" class="f-vhpzbvw"/></linearGradient><linearGradient id="iwaPZMe" x1="25.471" x2="24.733" y1="10.928" y2="10.928" gradientUnits="userSpaceOnUse"><stop class="kumifl3lh"/><stop offset="1" class="t4goseb1a"/></linearGradient><linearGradient id="imwftPp" x1="15.669" x2="18.505" y1="9.625" y2="8.719" gradientUnits="userSpaceOnUse"><stop class="k52y4cbzh"/><stop offset="1" class="ht2qmkbba"/></linearGradient><linearGradient id="iWW1Fth" x1="16.35" x2="17.251" y1="9.284" y2="8.904" gradientUnits="userSpaceOnUse"><stop class="zs3ut5bwi"/><stop offset="1" class="d9d80bbly"/></linearGradient><linearGradient id="iWWXgzc" x1="21.419" x2="19.482" y1="8.312" y2="9.062" gradientUnits="userSpaceOnUse"><stop class="kviru670g"/><stop offset="1" class="s039vx_iw"/></linearGradient><linearGradient id="iHedMKj" x1="10.982" x2="14.308" y1="10.449" y2="8.521" gradientUnits="userSpaceOnUse"><stop class="hfe9wac-f"/><stop offset="1" class="ldxlrmups"/></linearGradient><linearGradient id="iL1W3fb" x1="16.325" x2="14.794" y1="7.5" y2="8.598" gradientUnits="userSpaceOnUse"><stop class="q_lk1gbal"/><stop offset="1" class="rvf_s0b7o"/></linearGradient><linearGradient id="ivbcExR" x1="19.138" x2="17.208" y1="12.148" y2="11.547" gradientUnits="userSpaceOnUse"><stop offset=".612" class="s14ll-bma"/><stop offset="1" class="rprdsmbxe"/></linearGradient><linearGradient id="ivelgmV" x1="10.178" x2="17.012" y1="22.488" y2="27.143" gradientUnits="userSpaceOnUse"><stop class="r7tg2k_jb"/><stop offset="1" class="g4o8hli5p"/></linearGradient><linearGradient id="ib30o1l" x1="14.071" x2="20.118" y1="6.54" y2="15.351" gradientUnits="userSpaceOnUse"><stop class="s05ajackq"/><stop offset="1" class="pp8v3-b-z"/></linearGradient><linearGradient id="i9zYQgp" x1="20.217" x2="26.264" y1="6.54" y2="15.351" gradientUnits="userSpaceOnUse"><stop class="s05ajackq"/><stop offset="1" class="pp8v3-b-z"/></linearGradient><linearGradient id="i3Pm7ye" x1="23.668" x2="24.325" y1="6.256" y2="15.998" gradientUnits="userSpaceOnUse"><stop class="rhhh3kv2j"/><stop offset="1" class="l_iu3xbdk"/></linearGradient><radialGradient id="iMOP2wD" cx="0" cy="0" r="1" gradientTransform="matrix(0 .53295 -1.14361 0 9.26 20.772)" gradientUnits="userSpaceOnUse"><stop class="vzeokccph"/><stop offset=".792" class="pgyrhdbcl"/></radialGradient><radialGradient id="iFmhsce" cx="0" cy="0" r="1" gradientTransform="matrix(2.09172 2.73585 -3.3536 2.56402 16.506 22.358)" gradientUnits="userSpaceOnUse"><stop offset=".416" class="aidw8sbwg"/><stop offset=".882" class="frxb4db8d"/></radialGradient><radialGradient id="i7bz3ct" cx="0" cy="0" r="1" gradientTransform="rotate(-38.12 36.751 -14.309)scale(5.88904 5.60323)" gradientUnits="userSpaceOnUse"><stop class="g95nuxc8g"/><stop offset="1" class="amnxpabse"/></radialGradient><radialGradient id="ioy19Ic" cx="0" cy="0" r="1" gradientTransform="rotate(147.419 11.94 10.458)scale(11.9012 24.4655)" gradientUnits="userSpaceOnUse"><stop class="koglvbiqy"/><stop offset="1" class="j8_pncc_x"/></radialGradient><radialGradient id="iKauLKe" cx="0" cy="0" r="1" gradientTransform="matrix(-.7531 -3.10204 2.28202 -.55402 21.819 12.297)" gradientUnits="userSpaceOnUse"><stop class="nb5dhbc6o"/><stop offset="1" class="yen5rgb-x"/></radialGradient><radialGradient id="iZDodip" cx="0" cy="0" r="1" gradientTransform="rotate(41.186 3.744 20.89)scale(3.04972 5.90543)" gradientUnits="userSpaceOnUse"><stop class="p-daluboa"/><stop offset="1" class="kxkp8yb8j"/></radialGradient><radialGradient id="iv2ubLe" cx="0" cy="0" r="1" gradientTransform="rotate(54.462 1.93 10.506)scale(3.54768 4.64569)" gradientUnits="userSpaceOnUse"><stop class="p-daluboa"/><stop offset="1" class="kxkp8yb8j"/></radialGradient><radialGradient id="i8ZsnXd" cx="0" cy="0" r="1" gradientTransform="rotate(153.789 9.477 10.57)scale(4.29914 20.7123)" gradientUnits="userSpaceOnUse"><stop class="ujz7r0kgp"/><stop offset="1" class="as-a-_bsh"/></radialGradient><filter id="iR3FhAe" width="19.214" height="28.317" x="6.693" y="1.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.909804 0 0 0 0 0.494118 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1735"/></filter><filter id="iNMFtoA" width="9.69" height="8.342" x="7.632" y="20.238" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1735" stdDeviation=".75"/></filter><filter id="iensLhb" width="12.193" height="16.62" x="14.107" y="9.455" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1735" stdDeviation="1"/></filter><filter id="i29f7rb" width="10.646" height="14.381" x="9.174" y="1.359" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1735" stdDeviation=".75"/></filter><filter id="iN4kjlb" width="7.431" height="15.185" x="15.887" y="1.69" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1735" stdDeviation=".75"/></filter><filter id="iIcJiGc" width="3" height="13.543" x="21.885" y="5.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1735" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ok-hand" /></template>
<style>
.aidw8sbwg {
  stop-color: var(--svg-color--d08c3b, #D08C3B);
}

.aj_l2-d9a {
  fill: var(--svg-color--ffc03a, #FFC03A);
  d: path("M15.156 5.106a2.343 2.343 0 1 1 4.52-1.241l.975 3.547v-1.01a2.328 2.328 0 0 1 4.656 0v9.536q0 .1-.008.197v1.934c0 6.218-2.54 8.953-5.04 10.547c-1.999 1.274-5.857 1.882-8.904.274c-1.974-.98-3.556-2.642-4.424-4.512a2.55 2.55 0 0 1 4.625-2.149c.662 1.425 2.2 2.485 3.669 2.485a3.891 3.891 0 0 0 0-7.783c-1.69 0-3.032.937-3.593 2.264a2.55 2.55 0 1 1-4.697-1.987c1.043-2.465 3.122-4.25 5.63-4.994l-3.674-5.97a2.54 2.54 0 0 1 4.324-2.662l2.75 4.469z");
}

.amnxpabse {
  stop-color: var(--svg-color--e17c51, #E17C51);
  stop-opacity: 0;
}

.as-a-_bsh {
  stop-color: var(--svg-color--ffe94a, #FFE94A);
  stop-opacity: 0;
}

.c-0-ffbgp {
  d: path("M15.156 5.106a2.343 2.343 0 1 1 4.52-1.241l.975 3.547v-1.01a2.328 2.328 0 0 1 4.656 0v9.536q0 .1-.008.197v1.934c0 6.218-2.54 8.953-5.04 10.547c-1.999 1.274-5.857 1.882-8.904.274c-1.974-.98-3.556-2.642-4.424-4.512a2.55 2.55 0 0 1 4.625-2.149c.662 1.425 2.2 2.485 3.669 2.485a3.891 3.891 0 0 0 0-7.783c-1.69 0-3.032.937-3.593 2.264a2.55 2.55 0 1 1-4.697-1.987c1.043-2.465 3.122-4.25 5.63-4.994l-3.674-5.97a2.54 2.54 0 0 1 4.324-2.662l2.75 4.469z");
}

.cwlxsm45w {
  d: path("M15.156 5.106a2.343 2.343 0 0 1 4.52-1.241l2.212 8.174h-3.645c-.06-.269-.113-.472-.266-.72l-2.012-3.268z");
}

.d9d80bbly {
  stop-color: var(--svg-color--e37917, #E37917);
  stop-opacity: 0;
}

.f-vhpzbvw {
  stop-color: var(--svg-color--ffde3f, #FFDE3F);
  stop-opacity: 0;
}

.f03fg5wyx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.882 22.488c.794 1.478 2.604 3.546 5.19 3.842");
}

.f7qf7lbzz {
  stop-color: var(--svg-color--db8e1e, #DB8E1E);
  stop-opacity: 0;
}

.frxb4db8d {
  stop-color: var(--svg-color--d08c3b, #D08C3B);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4o8hli5p {
  stop-color: var(--svg-color--ffd535, #FFD535);
  stop-opacity: 0;
}

.g95nuxc8g {
  stop-color: var(--svg-color--e17c51, #E17C51);
}

.gr1lr6juf {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m18.137 3.94l2.931 10.684");
}

.hfe9wac-f {
  stop-color: var(--svg-color--d58441, #D58441);
}

.hlms2gmxk {
  stop-color: var(--svg-color--db8e1e, #DB8E1E);
}

.hmkfq0btk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m11.424 3.609l6.146 9.88");
}

.ht2qmkbba {
  stop-color: var(--svg-color--d58430, #D58430);
  stop-opacity: 0;
}

.ie4mjlf7u {
  stroke-linecap: round;
  d: path("M23.385 6.871v10.542");
}

.j27cnyeuj {
  d: path("M9.722 2.74a2.54 2.54 0 0 0-.831 3.494l3.674 5.97c.846-.25 2.138-.161 3.057-.161h3.516c-1.125-.574-1.329-1.048-1.535-1.383l-4.388-7.088a2.54 2.54 0 0 0-3.493-.831");
}

.j8_pncc_x {
  stop-color: var(--svg-color--ffe452, #FFE452);
  stop-opacity: 0;
}

.k52y4cbzh {
  stop-color: var(--svg-color--d58430, #D58430);
}

.koglvbiqy {
  stop-color: var(--svg-color--ffe452, #FFE452);
}

.kumifl3lh {
  stop-color: var(--svg-color--fac54c, #FAC54C);
}

.kviru670g {
  stop-color: var(--svg-color--ffe54d, #FFE54D);
}

.kxfq-cbin {
  stop-color: var(--svg-color--ffde3f, #FFDE3F);
}

.kxkp8yb8j {
  stop-color: var(--svg-color--dea23e, #DEA23E);
  stop-opacity: 0;
}

.l_iu3xbdk {
  stop-color: var(--svg-color--ffe949, #FFE949);
  stop-opacity: 0;
}

.ldxlrmups {
  stop-color: var(--svg-color--efa230, #EFA230);
  stop-opacity: 0;
}

.nb5dhbc6o {
  stop-color: var(--svg-color--ffdd4b, #FFDD4B);
}

.p-daluboa {
  stop-color: var(--svg-color--dea23e, #DEA23E);
}

.pgyrhdbcl {
  stop-color: var(--svg-color--be6e00, #BE6E00);
  stop-opacity: 0;
}

.pp8v3-b-z {
  stop-color: var(--svg-color--ffe746, #FFE746);
  stop-opacity: 0;
}

.q_lk1gbal {
  stop-color: var(--svg-color--ffe946, #FFE946);
}

.r7tg2k_jb {
  stop-color: var(--svg-color--ffd535, #FFD535);
}

.rhhh3kv2j {
  stop-color: var(--svg-color--ffe949, #FFE949);
}

.rprdsmbxe {
  stop-color: var(--svg-color--ffd747, #FFD747);
  stop-opacity: 0;
}

.rvf_s0b7o {
  stop-color: var(--svg-color--ffe946, #FFE946);
  stop-opacity: 0;
}

.s039vx_iw {
  stop-color: var(--svg-color--ffe54d, #FFE54D);
  stop-opacity: 0;
}

.s05ajackq {
  stop-color: var(--svg-color--ffe746, #FFE746);
}

.s14ll-bma {
  stop-color: var(--svg-color--ffd747, #FFD747);
}

.t0j3w4byy {
  d: path("M21.937 12.04h3.37V6.348a2.328 2.328 0 1 0-4.656 0v1.01z");
}

.t4goseb1a {
  stop-color: var(--svg-color--fac54c, #FAC54C);
  stop-opacity: 0;
}

.ujz7r0kgp {
  stop-color: var(--svg-color--ffeb5c, #FFEB5C);
}

.vzeokccph {
  stop-color: var(--svg-color--be6e00, #BE6E00);
}

.yen5rgb-x {
  stop-color: var(--svg-color--ffdd4b, #FFDD4B);
  stop-opacity: 0;
}

.ym4f1ac5d {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.108 12.455c2.547.54 7.304 3.42 5.957 10.62");
}

.zs3ut5bwi {
  stop-color: var(--svg-color--e37917, #E37917);
}

</style>
