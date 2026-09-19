<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijbEHXd)"><path fill="url(#iT2jKgb)" class="v75v0bcwr"/></g><g filter="url(#i8QY3Fb)"><path fill="url(#iRkLEbD)" class="m5aq2lbxt"/></g><path fill="url(#i0ZBu6b)" class="m5aq2lbxt"/><g filter="url(#i2AHooh)"><rect class="qu2bd2nkn"/><rect fill="url(#iwvPGNW)" class="ujmt13eto"/></g><g filter="url(#i7KLaib)"><path fill="url(#i4Btl1b)" class="pekyb4upb"/></g><g filter="url(#iM6cMce)"><rect class="t1if7942e"/></g><path fill="url(#i0qlu3d)" class="f7nhe6b0r"/><path fill="url(#idlmcwV)" class="f7nhe6b0r"/><path fill="url(#iuT0uXd)" class="f7nhe6b0r"/><g filter="url(#iMvw3hd)"><path stroke="url(#imxMr1c)" class="erfqgab3i"/></g><g filter="url(#iQnWoFb)"><path class="sdtdks66e"/><path fill="url(#iphDXOe)" class="lhz9dwthl"/></g><path class="rb-07kbbi"/><path fill="url(#iQecl2c)" class="nm9injj3a"/><path fill="url(#iQXrElw)" class="nm9injj3a"/><g filter="url(#i3WjdZb)"><path class="hbnsmby5h"/><path fill="url(#iHZsACX)" class="ssp2ukbkf"/><path fill="url(#iAhpKae)" class="ssp2ukbkf"/></g><path fill="url(#iEhFSDy)" class="ssp2ukbkf"/><path fill="url(#iITxQrd)" class="ssp2ukbkf"/><g filter="url(#itbXVDc)"><path class="qtloaqkuk"/><path fill="url(#iqtc76A)" class="qixmh3bzw"/><path fill="url(#iutpYVc)" class="qixmh3bzw"/><path fill="url(#iYwHZGc)" class="qixmh3bzw"/></g><defs><linearGradient id="iT2jKgb" x1="15.511" x2="15.511" y1="2" y2="24.992" gradientUnits="userSpaceOnUse"><stop class="vn6kyub5a"/><stop offset="1" class="moitchbbr"/></linearGradient><linearGradient id="iRkLEbD" x1="9.027" x2="22.203" y1="5.102" y2="5.102" gradientUnits="userSpaceOnUse"><stop class="wdmtujz2k"/><stop offset="1" class="dntbt6d8j"/></linearGradient><linearGradient id="iwvPGNW" x1="9.604" x2="11.294" y1="13.157" y2="17.702" gradientUnits="userSpaceOnUse"><stop class="a487pcb6l"/><stop offset="1" class="is9y8lrrd"/></linearGradient><linearGradient id="i4Btl1b" x1="12.828" x2="11.797" y1="11.281" y2="16.803" gradientUnits="userSpaceOnUse"><stop class="l9n84vb-x"/><stop offset="1" class="cid4h2byu"/></linearGradient><linearGradient id="i0qlu3d" x1="14.401" x2="17.279" y1="28.391" y2="28.391" gradientUnits="userSpaceOnUse"><stop class="oid8s4bhb"/><stop offset="1" class="v0n19wb6y"/></linearGradient><linearGradient id="idlmcwV" x1="18.644" x2="17.37" y1="24.6" y2="27.203" gradientUnits="userSpaceOnUse"><stop offset=".241" class="mzaqm9brj"/><stop offset="1" class="s1tj1bbsm"/></linearGradient><linearGradient id="iuT0uXd" x1="12.433" x2="14.857" y1="28.3" y2="28.3" gradientUnits="userSpaceOnUse"><stop class="n152rd-1l"/><stop offset="1" class="vyn_8cc9e"/></linearGradient><linearGradient id="imxMr1c" x1="23.308" x2="23.308" y1="3.906" y2="26.016" gradientUnits="userSpaceOnUse"><stop class="fcfqaabhi"/><stop offset="1" class="g2n27dbga"/></linearGradient><linearGradient id="iphDXOe" x1="16.75" x2="16.254" y1="9.044" y2="8.591" gradientUnits="userSpaceOnUse"><stop class="b55w4yemo"/><stop offset="1" class="owis-l83a"/></linearGradient><linearGradient id="iQecl2c" x1="16.953" x2="16.344" y1="15.122" y2="15.357" gradientUnits="userSpaceOnUse"><stop class="mkxms6ihq"/><stop offset="1" class="rvxu53k3o"/></linearGradient><linearGradient id="iQXrElw" x1="15.266" x2="15.266" y1="16.388" y2="14.982" gradientUnits="userSpaceOnUse"><stop class="mz1ecsb5x"/><stop offset="1" class="pwyis6tkg"/></linearGradient><linearGradient id="iHZsACX" x1="18.844" x2="16.656" y1="13.122" y2="12.622" gradientUnits="userSpaceOnUse"><stop offset=".082" class="mlhf9ubek"/><stop offset="1" class="txozt7bxv"/></linearGradient><linearGradient id="iAhpKae" x1="18.109" x2="18.109" y1="16.247" y2="15.247" gradientUnits="userSpaceOnUse"><stop class="o_wjqz78h"/><stop offset="1" class="mzw8oobko"/></linearGradient><linearGradient id="iITxQrd" x1="16.063" x2="16.25" y1="13.625" y2="13.547" gradientUnits="userSpaceOnUse"><stop class="n-lmad5yn"/><stop offset="1" class="k2m3l31sj"/></linearGradient><linearGradient id="iqtc76A" x1="10.734" x2="12.406" y1="11.466" y2="11.903" gradientUnits="userSpaceOnUse"><stop class="xv5_tpbdl"/><stop offset="1" class="iv-_v2b8v"/></linearGradient><linearGradient id="iYwHZGc" x1="15.156" x2="13.797" y1="9.575" y2="10.044" gradientUnits="userSpaceOnUse"><stop class="ha8ulccow"/><stop offset="1" class="rhc3q8nrx"/></linearGradient><filter id="ijbEHXd" width="20.906" height="24.992" x="5.558" y="1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.764706 0 0 0 0 0.196078 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22169"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.972549 0 0 0 0 0.219608 0 0 0 0 0.545098 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22169" result="effect2_innerShadow_18_22169"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.913725 0 0 0 0 0.160784 0 0 0 0 0.368627 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_22169" result="effect3_innerShadow_18_22169"/></filter><filter id="i8QY3Fb" width="13.215" height=".972" x="8.927" y="4.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.109804 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22169"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.109804 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22169" result="effect2_innerShadow_18_22169"/></filter><filter id="i2AHooh" width="13.415" height="8.274" x="8.827" y="13.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy=".2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.109804 0 0 0 0 0.211765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22169"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.0941176 0 0 0 0 0.364706 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_22169" result="effect2_innerShadow_18_22169"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.2"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.811765 0 0 0 0 0.317647 0 0 0 0 0.435294 0 0 0 1 0"/><feBlend in2="effect2_innerShadow_18_22169" result="effect3_innerShadow_18_22169"/></filter><filter id="i7KLaib" width="11.422" height="9.928" x="8.01" y="8.375" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22169" stdDeviation=".75"/></filter><filter id="iM6cMce" width="14.015" height="5.003" x="8.027" y="6.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy="1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.12549 0 0 0 0 0.0627451 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22169"/></filter><filter id="iMvw3hd" width="4.459" height="22.366" x="21.558" y="1.608" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22169" stdDeviation=".625"/></filter><filter id="iQnWoFb" width="6.82" height="4.773" x="12.344" y="6.95" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-1" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.596078 0 0 0 0 0.54902 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22169"/></filter><filter id="i3WjdZb" width="5.284" height="9.397" x="14.98" y="6.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".15"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.741176 0 0 0 0 0.835294 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22169"/></filter><filter id="itbXVDc" width="5.201" height="9.381" x="10.381" y="6.85" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.1"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.709804 0 0 0 0 0.584314 0 0 0 0 0.819608 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22169"/></filter><radialGradient id="i0ZBu6b" cx="0" cy="0" r="1" gradientTransform="matrix(-.36545 .21699 -.19223 -.32376 21.96 4.791)" gradientUnits="userSpaceOnUse"><stop class="r6tf1cb1z"/><stop offset="1" class="g_p1_c10p"/></radialGradient><radialGradient id="iEhFSDy" cx="0" cy="0" r="1" gradientTransform="matrix(4.09375 -5.65345 8.36347 6.05612 16.39 12.778)" gradientUnits="userSpaceOnUse"><stop offset=".837" class="qo524mb2u"/><stop offset="1" class="p197kac2d"/></radialGradient><radialGradient id="iutpYVc" cx="0" cy="0" r="1" gradientTransform="rotate(-140.079 9.032 4.513)scale(.49915 4.87988)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="am6xewbdg"/><stop offset="1" class="g0fcndbkr"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:postbox" /></template>
<style>
.a487pcb6l {
  stop-color: var(--svg-color--93224a, #93224A);
}

.am6xewbdg {
  stop-color: var(--svg-color--e2d7ee, #E2D7EE);
}

.b55w4yemo {
  stop-color: var(--svg-color--cac5cd, #CAC5CD);
}

.cid4h2byu {
  stop-color: var(--svg-color--971c4a, #971C4A);
}

.dntbt6d8j {
  stop-color: var(--svg-color--bd3961, #BD3961);
}

.erfqgab3i {
  stroke-linecap: round;
  d: path("M23.309 3.358c.32.076.959.475.959 1.462v17.404");
}

.f7nhe6b0r {
  d: path("M12.433 24.992h6.211v4.883h-6.211z");
}

.fcfqaabhi {
  stop-color: var(--svg-color--ff6a9f, #FF6A9F);
}

.ft5dv1b6b {
  fill: none;
}

.g_p1_c10p {
  stop-color: var(--svg-color--c8506d, #C8506D);
  stop-opacity: 0;
}

.g0fcndbkr {
  stop-color: var(--svg-color--e2d7ee, #E2D7EE);
  stop-opacity: 0;
}

.g2n27dbga {
  stop-color: var(--svg-color--ff5769, #FF5769);
}

.ha8ulccow {
  stop-color: var(--svg-color--dcd5de, #DCD5DE);
}

.hbnsmby5h {
  fill: var(--svg-color--dad3e1, #DAD3E1);
  d: path("M15.063 10.728c.962-1.157 3.265-3.496 3.75-3.778h1.351l-2.02 8.679a.8.8 0 0 1-.78.618h-.208c-.414-1.321-1.644-4.104-2.175-5.27z");
}

.is9y8lrrd {
  stop-color: var(--svg-color--93224a, #93224A);
  stop-opacity: 0;
}

.iv-_v2b8v {
  stop-color: var(--svg-color--bdb5c3, #BDB5C3);
  stop-opacity: 0;
}

.k2m3l31sj {
  stop-color: var(--svg-color--ac9cbc, #AC9CBC);
  stop-opacity: 0;
}

.l9n84vb-x {
  stop-color: var(--svg-color--bf2657, #BF2657);
}

.lhz9dwthl {
  d: path("M13.344 6.95h5.82l-1.492 4.524h-4.328z");
}

.m5aq2lbxt {
  d: path("M9.027 5.102c0-.213.173-.386.386-.386h12.243a.386.386 0 0 1 0 .772H9.413a.386.386 0 0 1-.386-.386");
}

.mkxms6ihq {
  stop-color: var(--svg-color--bbaec9, #BBAEC9);
}

.mlhf9ubek {
  stop-color: var(--svg-color--f3eafa, #F3EAFA);
}

.moitchbbr {
  stop-color: var(--svg-color--fe3f5e, #FE3F5E);
}

.mz1ecsb5x {
  stop-color: var(--svg-color--b17fcc, #B17FCC);
}

.mzaqm9brj {
  stop-color: var(--svg-color--9f799f, #9F799F);
}

.mzw8oobko {
  stop-color: var(--svg-color--ddceee, #DDCEEE);
  stop-opacity: 0;
}

.n-lmad5yn {
  stop-color: var(--svg-color--ac9cbc, #AC9CBC);
}

.n152rd-1l {
  stop-color: var(--svg-color--916593, #916593);
}

.nm9injj3a {
  d: path("M17.352 16.232h-6.414c.3-1.287 2.906-4.224 4.171-5.532z");
}

.o_wjqz78h {
  stop-color: var(--svg-color--b587cd, #B587CD);
}

.oid8s4bhb {
  stop-color: var(--svg-color--b399c4, #B399C4);
}

.owis-l83a {
  stop-color: var(--svg-color--cac5cd, #CAC5CD);
  stop-opacity: 0;
}

.p197kac2d {
  stop-color: var(--svg-color--867994, #867994);
}

.pekyb4upb {
  d: path("M11.691 9.875h5.64a.6.6 0 0 1 .58.752l-1.503 5.728a.6.6 0 0 1-.58.448H10.11a.6.6 0 0 1-.578-.76l1.58-5.728a.6.6 0 0 1 .58-.44");
}

.pwyis6tkg {
  stop-color: var(--svg-color--cbb1e5, #CBB1E5);
  stop-opacity: 0;
}

.qixmh3bzw {
  d: path("m10.395 15.617l2.043-8.667h1.32l1.802 3.708a.23.23 0 0 1-.04.255c-.437.447-3.043 3.15-4.337 5.2a.25.25 0 0 1-.213.119h-.088a.5.5 0 0 1-.487-.615");
}

.qo524mb2u {
  stop-color: var(--svg-color--a49ab0, #A49AB0);
  stop-opacity: 0;
}

.qtloaqkuk {
  fill: var(--svg-color--d5cedc, #D5CEDC);
  d: path("m10.395 15.617l2.043-8.667h1.32l1.802 3.708a.23.23 0 0 1-.04.255c-.437.447-3.043 3.15-4.337 5.2a.25.25 0 0 1-.213.119h-.088a.5.5 0 0 1-.487-.615");
}

.qu2bd2nkn {
  width: 13.015px;
  height: 7.874px;
  x: 9.027px;
  y: 13.595px;
  fill: var(--svg-color--c13965, #C13965);
  rx: 1px;
}

.r6tf1cb1z {
  stop-color: var(--svg-color--c8506d, #C8506D);
}

.rb-07kbbi {
  fill: var(--svg-color--d9cfe2, #D9CFE2);
  d: path("M17.352 16.232h-6.414c.3-1.287 2.906-4.224 4.171-5.532z");
}

.rhc3q8nrx {
  stop-color: var(--svg-color--dcd5de, #DCD5DE);
  stop-opacity: 0;
}

.rvxu53k3o {
  stop-color: var(--svg-color--cdc2d8, #CDC2D8);
  stop-opacity: 0;
}

.s1tj1bbsm {
  stop-color: var(--svg-color--c2a5cc, #C2A5CC);
  stop-opacity: 0;
}

.sdtdks66e {
  fill: var(--svg-color--d4ccd8, #D4CCD8);
  d: path("M13.344 6.95h5.82l-1.492 4.524h-4.328z");
}

.ssp2ukbkf {
  d: path("M15.063 10.728c.962-1.157 3.265-3.496 3.75-3.778h1.351l-2.02 8.679a.8.8 0 0 1-.78.618h-.208c-.414-1.321-1.644-4.104-2.175-5.27z");
}

.t1if7942e {
  width: 13.015px;
  height: 4.003px;
  x: 9.027px;
  y: 6.95px;
  fill: var(--svg-color--3b2a4c, #3B2A4C);
  rx: 2.001px;
}

.txozt7bxv {
  stop-color: var(--svg-color--ded7e5, #DED7E5);
  stop-opacity: 0;
}

.ujmt13eto {
  width: 13.015px;
  height: 7.874px;
  x: 9.027px;
  y: 13.595px;
  rx: 1px;
}

.v0n19wb6y {
  stop-color: var(--svg-color--d8c5e7, #D8C5E7);
}

.v75v0bcwr {
  d: path("M5.558 4.8a2.8 2.8 0 0 1 2.8-2.8h14.307a2.8 2.8 0 0 1 2.8 2.8v17.392a2.8 2.8 0 0 1-2.8 2.8H8.358a2.8 2.8 0 0 1-2.8-2.8z");
}

.vn6kyub5a {
  stop-color: var(--svg-color--e93d8f, #E93D8F);
}

.vyn_8cc9e {
  stop-color: var(--svg-color--aa8eba, #AA8EBA);
  stop-opacity: 0;
}

.wdmtujz2k {
  stop-color: var(--svg-color--ba3961, #BA3961);
}

.xv5_tpbdl {
  stop-color: var(--svg-color--a499a6, #A499A6);
}

</style>
