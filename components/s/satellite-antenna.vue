<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#idf5Tbe)" transform="rotate(38.49 9.672 18.775)" class="gnuk-ypxx"/><path fill="url(#i3SCyxe)" transform="rotate(38.49 9.672 18.775)" class="gnuk-ypxx"/><path fill="url(#iVSAOIb)" class="vlm-rd9pm"/><path fill="url(#iFf0CRd)" class="vlm-rd9pm"/><path fill="url(#iXchfve)" class="vlm-rd9pm"/><path stroke="url(#iCSdWme)" class="zbnkldbpy"/><g filter="url(#irRm4wd)"><path class="w_e9hheiy"/></g><path stroke="url(#itv2khc)" class="x65f0-bmw"/><g filter="url(#i8Q8zld)"><path stroke="url(#ibQ7r2d)" class="wggc91amk"/></g><path stroke="url(#iyPhgsd)" class="dql8cccyb"/><g filter="url(#iIx7uWc)"><path stroke="url(#iNCZXHb)" class="ttsz7aczl"/></g><g filter="url(#i0BixDj)"><path class="gq0m_e_7h"/></g><g filter="url(#iQCToSc)"><path class="ri889jbgx"/></g><circle fill="url(#iM6iXVb)" class="ggx1qnbpu"/><circle fill="url(#igUF3Wb)" class="ggx1qnbpu"/><circle fill="url(#iSMDssb)" class="ggx1qnbpu"/><circle fill="url(#idZ79dd)" class="ggx1qnbpu"/><rect transform="rotate(38.12 10.724 8.474)" class="h-64qwccs"/><rect fill="url(#iA8Tlve)" transform="rotate(38.12 10.724 8.474)" class="uc1ry0zvn"/><rect fill="url(#iZFUjLc)" transform="rotate(38.12 10.724 8.474)" class="uc1ry0zvn"/><rect fill="url(#inabBYc)" transform="rotate(38.12 10.724 8.474)" class="uc1ry0zvn"/><g filter="url(#iQoKHqc)"><path class="l1igjj8eu"/><path fill="url(#ivgwqyb)" class="cb19r6-jp"/></g><circle fill="url(#ipMbhTc)" class="zzbwmqbfv"/><circle fill="url(#iDENl8d)" class="zzbwmqbfv"/><rect fill="url(#ijbqmvc)" class="os57wyyxe"/><rect fill="url(#i4VaAWb)" class="os57wyyxe"/><rect fill="url(#iobeMGA)" class="os57wyyxe"/><rect fill="url(#isWcrJn)" class="os57wyyxe"/><g filter="url(#iKRH5Nc)"><path stroke="url(#i0pI6MW)" class="xedh9wgkm"/></g><defs><linearGradient id="i3SCyxe" x1="9.224" x2="11.859" y1="20.556" y2="20.657" gradientUnits="userSpaceOnUse"><stop class="e4tb6_bli"/><stop offset="1" class="qkql4cbpf"/></linearGradient><linearGradient id="iFf0CRd" x1="18.095" x2="16.381" y1="14.972" y2="17.164" gradientUnits="userSpaceOnUse"><stop class="lnkohpnwe"/><stop offset="1" class="vdwuvuotv"/></linearGradient><linearGradient id="iCSdWme" x1="22.103" x2="21.275" y1="13.722" y2="13.722" gradientUnits="userSpaceOnUse"><stop class="ze79sebpo"/><stop offset="1" class="wphs7sbhb"/></linearGradient><linearGradient id="itv2khc" x1="13.275" x2="20.369" y1="9.991" y2="8.734" gradientUnits="userSpaceOnUse"><stop offset=".716" class="ysoqzis0z"/><stop offset=".943" class="cozf1g8aj"/></linearGradient><linearGradient id="ibQ7r2d" x1="12.494" x2="19.744" y1="9.991" y2="8.593" gradientUnits="userSpaceOnUse"><stop class="a5q1mjb3t"/><stop offset="1" class="xilti08mk"/></linearGradient><linearGradient id="iyPhgsd" x1="17.155" x2="21.288" y1="14.562" y2="14.322" gradientUnits="userSpaceOnUse"><stop offset=".517" class="ysoqzis0z"/><stop offset=".943" class="cozf1g8aj"/></linearGradient><linearGradient id="iNCZXHb" x1="16.804" x2="20.18" y1="14.562" y2="14.472" gradientUnits="userSpaceOnUse"><stop class="a5q1mjb3t"/><stop offset="1" class="xilti08mk"/></linearGradient><linearGradient id="iA8Tlve" x1="18.923" x2="18.952" y1="8.21" y2="10.327" gradientUnits="userSpaceOnUse"><stop class="pglqpib-g"/><stop offset="1" class="k2zwg8bgs"/></linearGradient><linearGradient id="iZFUjLc" x1="20.716" x2="20.578" y1="11.649" y2="9.255" gradientUnits="userSpaceOnUse"><stop offset=".341" class="vdeob5buy"/><stop offset="1" class="kof4fuk6q"/></linearGradient><linearGradient id="ivgwqyb" x1="15.337" x2="14.056" y1="24.64" y2="26.359" gradientUnits="userSpaceOnUse"><stop offset=".284" class="jr0qg39cd"/><stop offset="1" class="o7gnlbv5i"/></linearGradient><linearGradient id="ijbqmvc" x1="12.345" x2="12.345" y1="27.437" y2="29.655" gradientUnits="userSpaceOnUse"><stop class="sw7xfrbqa"/><stop offset="1" class="ijo86h0gf"/></linearGradient><linearGradient id="i4VaAWb" x1="4.259" x2="5.9" y1="28.702" y2="28.702" gradientUnits="userSpaceOnUse"><stop offset=".352" class="ed8_gibkr"/><stop offset="1" class="g_jbiq2hi"/></linearGradient><linearGradient id="iobeMGA" x1="14.306" x2="14.306" y1="29.734" y2="28.827" gradientUnits="userSpaceOnUse"><stop offset=".138" class="jy_1e6b5g"/><stop offset="1" class="p-4221_9v"/></linearGradient><linearGradient id="i0pI6MW" x1="5.697" x2="19.947" y1="28.577" y2="28.577" gradientUnits="userSpaceOnUse"><stop offset=".819" class="feuci0vsd"/><stop offset="1" class="ts4rinbpz"/></linearGradient><radialGradient id="idf5Tbe" cx="0" cy="0" r="1" gradientTransform="rotate(-93.473 16.009 4.645)scale(3.31399 3.46985)" gradientUnits="userSpaceOnUse"><stop class="q0903mb8p"/><stop offset="1" class="jztm27bct"/></radialGradient><radialGradient id="iVSAOIb" cx="0" cy="0" r="1" gradientTransform="rotate(175.001 8.6 9.118)scale(9.32453 10.3714)" gradientUnits="userSpaceOnUse"><stop class="bs0tazb5d"/><stop offset="1" class="newvr32zd"/></radialGradient><radialGradient id="iXchfve" cx="0" cy="0" r="1" gradientTransform="matrix(5.86048 8.57145 -9.19718 6.2883 13.67 13.257)" gradientUnits="userSpaceOnUse"><stop offset=".672" class="mp0zbdcun"/><stop offset="1" class="w0ob-gnxy"/></radialGradient><radialGradient id="iM6iXVb" cx="0" cy="0" r="1" gradientTransform="rotate(142.016 9.843 7.695)scale(2.8943)" gradientUnits="userSpaceOnUse"><stop offset=".181" class="frsmpkb3r"/><stop offset="1" class="j72eenb7n"/></radialGradient><radialGradient id="igUF3Wb" cx="0" cy="0" r="1" gradientTransform="matrix(-.15625 -1.5625 2.53094 -.2531 21.212 10.39)" gradientUnits="userSpaceOnUse"><stop class="mcc45ivaa"/><stop offset="1" class="j9a3_2bpq"/></radialGradient><radialGradient id="iSMDssb" cx="0" cy="0" r="1" gradientTransform="rotate(-34.825 24.277 -28.82)scale(2.62667)" gradientUnits="userSpaceOnUse"><stop offset=".736" class="l7q9j1bvg"/><stop offset="1" class="h96tb5z6w"/></radialGradient><radialGradient id="idZ79dd" cx="0" cy="0" r="1" gradientTransform="rotate(153.166 10.164 6.528)scale(1.4884)" gradientUnits="userSpaceOnUse"><stop class="fyd3sfczx"/><stop offset="1" class="zvrn08edz"/></radialGradient><radialGradient id="inabBYc" cx="0" cy="0" r="1" gradientTransform="rotate(90.974 5.972 14.637)scale(.64424 7.03803)" gradientUnits="userSpaceOnUse"><stop class="r55-5svbp"/><stop offset="1" class="npbo96blx"/></radialGradient><radialGradient id="ipMbhTc" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 -1.28125 1.07375 .78566 8.556 24.297)" gradientUnits="userSpaceOnUse"><stop class="zs18zzr1o"/><stop offset=".784" class="uin5z8f6x"/></radialGradient><radialGradient id="iDENl8d" cx="0" cy="0" r="1" gradientTransform="rotate(-47.793 31.477 2.226)scale(.45353)" gradientUnits="userSpaceOnUse"><stop class="whif3actm"/><stop offset="1" class="qm97xsbbx"/></radialGradient><radialGradient id="isWcrJn" cx="0" cy="0" r="1" gradientTransform="matrix(1.15625 -.5 .26664 .6166 20.134 28.171)" gradientUnits="userSpaceOnUse"><stop class="ts4rinbpz"/><stop offset="1" class="l0rf_ac-o"/></radialGradient><filter id="irRm4wd" width="1.084" height="8.623" x="21.288" y="9.411" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25191" stdDeviation=".1"/></filter><filter id="i8Q8zld" width="9.443" height="2.222" x="11.62" y="8.068" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25191" stdDeviation=".1"/></filter><filter id="iIx7uWc" width="4.606" height="5.818" x="16.23" y="9.004" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25191" stdDeviation=".1"/></filter><filter id="i0BixDj" width="5.644" height="5.348" x="20.281" y="3.879" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.317647 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25191"/></filter><filter id="iQCToSc" width="8.118" height="7.797" x="20.055" y="1.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.317647 0 0 0 0 0.811765 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25191"/></filter><filter id="iQoKHqc" width="14.172" height="8.055" x="6.009" y="20.429" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy=".5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.788235 0 0 0 0 0.756863 0 0 0 0 0.784314 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_25191"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.756863 0 0 0 0 0.717647 0 0 0 0 0.733333 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_25191" result="effect2_innerShadow_18_25191"/></filter><filter id="iKRH5Nc" width="14.675" height="1.2" x="5.125" y="27.821" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_25191" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:satellite-antenna" /></template>
<style>
.a5q1mjb3t {
  stop-color: var(--svg-color--afafaf, #AFAFAF);
}

.bs0tazb5d {
  stop-color: var(--svg-color--d3c4e3, #D3C4E3);
}

.cb19r6-jp {
  d: path("M6.01 22.934v5.05h13.17l-9.148-7.033c-1.644-1.263-4.024-.091-4.024 1.983");
}

.cozf1g8aj {
  stop-color: var(--svg-color--79727c, #79727C);
}

.dql8cccyb {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m20.556 9.265l-4.047 5.297");
}

.e4tb6_bli {
  stop-color: var(--svg-color--aca39f, #ACA39F);
}

.ed8_gibkr {
  stop-color: var(--svg-color--a698a4, #A698A4);
}

.feuci0vsd {
  stop-color: var(--svg-color--bdb4c6, #BDB4C6);
}

.frsmpkb3r {
  stop-color: var(--svg-color--bdbcbf, #BDBCBF);
}

.ft5dv1b6b {
  fill: none;
}

.fyd3sfczx {
  stop-color: var(--svg-color--d7d5da, #D7D5DA);
}

.g_jbiq2hi {
  stop-color: var(--svg-color--a698a4, #A698A4);
  stop-opacity: 0;
}

.ggx1qnbpu {
  cx: 21.392px;
  cy: 8.241px;
  r: 1.766px;
}

.gnuk-ypxx {
  d: path("M9.672 18.775h5.231v4.126H9.672z");
}

.gq0m_e_7h {
  stroke: var(--svg-color--4386ff, #4386FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M20.681 4.726c2.844-.867 5.188 1.25 4.461 4.101");
}

.h-64qwccs {
  width: 16.456px;
  height: 1.853px;
  x: 10.724px;
  y: 8.474px;
  fill: var(--svg-color--a5a0a0, #A5A0A0);
  rx: 0.927px;
}

.h96tb5z6w {
  stop-color: var(--svg-color--a0a2b7, #A0A2B7);
}

.ijo86h0gf {
  stop-color: var(--svg-color--b19ec3, #B19EC3);
}

.j72eenb7n {
  stop-color: var(--svg-color--958f97, #958F97);
}

.j9a3_2bpq {
  stop-color: var(--svg-color--9683a9, #9683A9);
  stop-opacity: 0;
}

.jr0qg39cd {
  stop-color: var(--svg-color--f2ecf8, #F2ECF8);
}

.jy_1e6b5g {
  stop-color: var(--svg-color--a47bc4, #A47BC4);
}

.jztm27bct {
  stop-color: var(--svg-color--b2a7bd, #B2A7BD);
}

.k2zwg8bgs {
  stop-color: var(--svg-color--beb9c3, #BEB9C3);
  stop-opacity: 0;
}

.kof4fuk6q {
  stop-color: var(--svg-color--a082bc, #A082BC);
  stop-opacity: 0;
}

.l0rf_ac-o {
  stop-color: var(--svg-color--d8d2de, #D8D2DE);
  stop-opacity: 0;
}

.l1igjj8eu {
  fill: var(--svg-color--e2daea, #E2DAEA);
  d: path("M6.01 22.934v5.05h13.17l-9.148-7.033c-1.644-1.263-4.024-.091-4.024 1.983");
}

.l7q9j1bvg {
  stop-color: var(--svg-color--b1b3c5, #B1B3C5);
  stop-opacity: 0;
}

.lnkohpnwe {
  stop-color: var(--svg-color--bbb4bb, #BBB4BB);
}

.mcc45ivaa {
  stop-color: var(--svg-color--9683a9, #9683A9);
}

.mp0zbdcun {
  stop-color: var(--svg-color--c6b0dc, #C6B0DC);
  stop-opacity: 0;
}

.newvr32zd {
  stop-color: var(--svg-color--c5b9bd, #C5B9BD);
}

.npbo96blx {
  stop-color: var(--svg-color--d1ccd6, #D1CCD6);
  stop-opacity: 0;
}

.o7gnlbv5i {
  stop-color: var(--svg-color--f2ecf8, #F2ECF8);
  stop-opacity: 0;
}

.os57wyyxe {
  width: 16.172px;
  height: 2.219px;
  x: 4.259px;
  y: 27.437px;
  rx: 1.109px;
}

.p-4221_9v {
  stop-color: var(--svg-color--b19ec3, #B19EC3);
  stop-opacity: 0;
}

.pglqpib-g {
  stop-color: var(--svg-color--beb9c3, #BEB9C3);
}

.q0903mb8p {
  stop-color: var(--svg-color--c3bdc9, #C3BDC9);
}

.qkql4cbpf {
  stop-color: var(--svg-color--aca39f, #ACA39F);
  stop-opacity: 0;
}

.qm97xsbbx {
  stop-color: var(--svg-color--d3cdd8, #D3CDD8);
  stop-opacity: 0;
}

.r55-5svbp {
  stop-color: var(--svg-color--d1ccd6, #D1CCD6);
}

.ri889jbgx {
  stroke: var(--svg-color--4386ff, #4386FF);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M20.455 2.53c4.164-1.351 7.922 1.657 6.898 6.422");
}

.sw7xfrbqa {
  stop-color: var(--svg-color--bbb6bf, #BBB6BF);
}

.ts4rinbpz {
  stop-color: var(--svg-color--d8d2de, #D8D2DE);
}

.ttsz7aczl {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m20.556 9.265l-4.047 5.297");
}

.uc1ry0zvn {
  width: 16.456px;
  height: 1.853px;
  x: 10.724px;
  y: 8.474px;
  rx: 0.927px;
}

.uin5z8f6x {
  stop-color: var(--svg-color--b5abbf, #B5ABBF);
}

.vdeob5buy {
  stop-color: var(--svg-color--a787c5, #A787C5);
}

.vdwuvuotv {
  stop-color: var(--svg-color--bbb4bb, #BBB4BB);
  stop-opacity: 0;
}

.vlm-rd9pm {
  d: path("m11.175 9.641l11.144 8.861a7.24 7.24 0 0 1-6.403 3.857a7.2 7.2 0 0 1-2.159-.327l-4.09-3.253a7.2 7.2 0 0 1-.994-3.662c0-2.187.97-4.148 2.502-5.476");
}

.w_e9hheiy {
  stroke: var(--svg-color--b2afb6, #B2AFB6);
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m21.587 9.616l.485 8.211");
}

.w0ob-gnxy {
  stop-color: var(--svg-color--c6b0dc, #C6B0DC);
}

.wggc91amk {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("m11.837 9.991l9.008-1.625");
}

.whif3actm {
  stop-color: var(--svg-color--d3cdd8, #D3CDD8);
}

.wphs7sbhb {
  stop-color: var(--svg-color--827d87, #827D87);
}

.x65f0-bmw {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m11.837 9.991l9.008-1.625");
}

.xedh9wgkm {
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M5.525 28.421H19.4");
}

.xilti08mk {
  stop-color: var(--svg-color--afafaf, #AFAFAF);
  stop-opacity: 0;
}

.ysoqzis0z {
  stop-color: var(--svg-color--9e9d9d, #9E9D9D);
}

.zbnkldbpy {
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m21.462 9.616l.485 8.211");
}

.ze79sebpo {
  stop-color: var(--svg-color--b3b1b6, #B3B1B6);
}

.zs18zzr1o {
  stop-color: var(--svg-color--c6bfcd, #C6BFCD);
}

.zvrn08edz {
  stop-color: var(--svg-color--aeabb0, #AEABB0);
  stop-opacity: 0;
}

.zzbwmqbfv {
  cx: 8.939px;
  cy: 23.78px;
  r: 0.93px;
}

</style>
