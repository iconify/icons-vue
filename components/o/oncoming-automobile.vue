<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWFnwEc)" class="xpw3pnkto"/><g filter="url(#i7fWDlb)"><path fill="url(#iL6l4Hc)" class="pug7uijyt"/></g><g filter="url(#iZyjxPe)"><path fill="url(#iDzO29c)" class="gmusieboo"/></g><path fill="url(#i4L2DGd)" class="g4pskspiu"/><path fill="url(#i8lQnxn)" class="pmnk1j68a"/><path fill="url(#iFnJdjc)" class="pmnk1j68a"/><path fill="url(#ioLYDsb)" class="aa3pdackz"/><path fill="url(#ijdYm7c)" class="aa3pdackz"/><path fill="url(#imXhIze)" class="aa3pdackz"/><g filter="url(#iwCqg9z)"><path stroke="url(#i0lHw8d)" class="hjzv0dbrp"/></g><path fill="url(#iAFwwkk)" class="oeb5m_14x"/><g filter="url(#iKT1sLe)"><path stroke="url(#i8YGxXd)" class="k698cxb5a"/></g><path fill="url(#iIWO7Ea)" class="xcm26crry"/><path fill="url(#iyMVEAc)" class="xcm26crry"/><g filter="url(#iyxrxwb)"><path stroke="url(#i9pBtOd)" class="vp7yhcbdb"/></g><g filter="url(#iAemtcz)"><path fill="url(#iyXmCGe)" class="imei5h12v"/><path fill="url(#iWdfuKb)" class="imei5h12v"/></g><g filter="url(#iCcxqdd)"><path fill="url(#ijwCUff)" class="i7nwspsvj"/><path fill="url(#i7aYA6X)" class="i7nwspsvj"/></g><g filter="url(#icwlGJd)"><path stroke="url(#iw3Uwjd)" class="v_9sdtb2z"/></g><path fill="url(#iHKlzuU)" class="fbgbc_xre"/><g filter="url(#i3oW6fc)"><path stroke="url(#i3I7NWc)" class="ugzlsrbbx"/></g><path fill="url(#iItG2Qd)" class="rt7h5jcdu"/><path fill="url(#izzjJ5d)" class="prgoirbos"/><path fill="url(#iaQLTgd)" class="prgoirbos"/><path fill="url(#i96Bgce)" class="prgoirbos"/><path fill="url(#icj0KWt)" class="prgoirbos"/><g clip-rule="evenodd" filter="url(#i44jKnr)" class="d2kvgvbvc"><path fill="url(#ijFPn2l)" class="k2h3m4b0d"/><path fill="url(#iX5lzcc)" class="k2h3m4b0d"/></g><defs><linearGradient id="iL6l4Hc" x1="5.594" x2="8.235" y1="26.506" y2="26.506" gradientUnits="userSpaceOnUse"><stop class="dwjy1_hjr"/><stop offset="1" class="dxjef_7ed"/></linearGradient><linearGradient id="iDzO29c" x1="23.594" x2="26.235" y1="26.506" y2="26.506" gradientUnits="userSpaceOnUse"><stop class="dwjy1_hjr"/><stop offset="1" class="dxjef_7ed"/></linearGradient><linearGradient id="i8lQnxn" x1="15.365" x2="15.365" y1="24.813" y2="18.875" gradientUnits="userSpaceOnUse"><stop class="vz876ib1u"/><stop offset="1" class="bo0zhkyrq"/></linearGradient><linearGradient id="iFnJdjc" x1="15.99" x2="15.99" y1="17.737" y2="19.631" gradientUnits="userSpaceOnUse"><stop class="o_dzv-bhn"/><stop offset="1" class="glyen-1ht"/></linearGradient><linearGradient id="ioLYDsb" x1="14.892" x2="27.7" y1="25.49" y2="25.49" gradientUnits="userSpaceOnUse"><stop class="smg795j2d"/><stop offset="1" class="dw7g7vhjo"/></linearGradient><linearGradient id="ijdYm7c" x1="15.99" x2="15.99" y1="26" y2="25.25" gradientUnits="userSpaceOnUse"><stop class="wi7exgb2z"/><stop offset="1" class="p9b-ccbss"/></linearGradient><linearGradient id="i0lHw8d" x1="24.576" x2="26.38" y1="22.891" y2="21.637" gradientUnits="userSpaceOnUse"><stop class="bx___2bho"/><stop offset="1" class="v-xhqylqp"/></linearGradient><linearGradient id="iAFwwkk" x1="23.834" x2="26.49" y1="20.375" y2="23" gradientUnits="userSpaceOnUse"><stop class="delrb2b8d"/><stop offset="1" class="ei_w2ev7q"/></linearGradient><linearGradient id="i8YGxXd" x1="5.751" x2="7.558" y1="22.891" y2="21.627" gradientUnits="userSpaceOnUse"><stop class="zba1hbbwq"/><stop offset="1" class="nepzn3bxa"/></linearGradient><linearGradient id="iIWO7Ea" x1="5.271" x2="7.052" y1="20" y2="22.813" gradientUnits="userSpaceOnUse"><stop class="lk9l3xk9f"/><stop offset="1" class="cw0mlsimd"/></linearGradient><linearGradient id="iyMVEAc" x1="8.302" x2="7.24" y1="22.313" y2="22.313" gradientUnits="userSpaceOnUse"><stop class="dbugmxbgr"/><stop offset="1" class="zh7_9ob1a"/></linearGradient><linearGradient id="i9pBtOd" x1="13.506" x2="18.49" y1="20.141" y2="23" gradientUnits="userSpaceOnUse"><stop class="b44nmioev"/><stop offset="1" class="oipk5yrep"/></linearGradient><linearGradient id="iyXmCGe" x1="12.99" x2="18.99" y1="21.5" y2="21.5" gradientUnits="userSpaceOnUse"><stop class="qt_rb4l4v"/><stop offset="1" class="z8do9ebsv"/></linearGradient><linearGradient id="iWdfuKb" x1="12.99" x2="14.365" y1="21.844" y2="21.844" gradientUnits="userSpaceOnUse"><stop class="x7sbwkb1z"/><stop offset="1" class="ycy-ddc7h"/></linearGradient><linearGradient id="ijwCUff" x1="15.998" x2="15.998" y1="25" y2="27.01" gradientUnits="userSpaceOnUse"><stop class="uf8mf0flb"/><stop offset="1" class="tvcowqbsi"/></linearGradient><linearGradient id="i7aYA6X" x1="15.995" x2="15.995" y1="27.297" y2="26.797" gradientUnits="userSpaceOnUse"><stop class="a8ol_9brs"/><stop offset="1" class="kw-6libnu"/></linearGradient><linearGradient id="iw3Uwjd" x1="9.615" x2="10.594" y1="22.891" y2="20.444" gradientUnits="userSpaceOnUse"><stop class="oaw93jvaw"/><stop offset="1" class="lwlacl1mn"/></linearGradient><linearGradient id="i3I7NWc" x1="20.615" x2="21.594" y1="22.891" y2="20.444" gradientUnits="userSpaceOnUse"><stop class="oaw93jvaw"/><stop offset="1" class="lwlacl1mn"/></linearGradient><linearGradient id="izzjJ5d" x1="14.835" x2="14.835" y1="12.051" y2="17.313" gradientUnits="userSpaceOnUse"><stop class="g_lcfnb3y"/><stop offset="1" class="u4yanwdgl"/></linearGradient><linearGradient id="iaQLTgd" x1="15.96" x2="15.96" y1="11.875" y2="13.563" gradientUnits="userSpaceOnUse"><stop offset=".259" class="ind0xq1wk"/><stop offset="1" class="k_0o0ab4h"/></linearGradient><linearGradient id="icj0KWt" x1="24.429" x2="24.155" y1="15.531" y2="15.594" gradientUnits="userSpaceOnUse"><stop offset=".313" class="ajietmbyg"/><stop offset="1" class="ka1fgb3yy"/></linearGradient><linearGradient id="ijFPn2l" x1="9.646" x2="22.666" y1="11" y2="11.002" gradientUnits="userSpaceOnUse"><stop class="vot6geb4t"/><stop offset="1" class="q8p87wbcb"/></linearGradient><linearGradient id="iX5lzcc" x1="22.664" x2="20.865" y1="12.188" y2="11.594" gradientUnits="userSpaceOnUse"><stop class="ceoo-ac7h"/><stop offset="1" class="b42ppno_e"/></linearGradient><filter id="i7fWDlb" width="4" height="5" x="4.99" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.329412 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10575"/></filter><filter id="iZyjxPe" width="4" height="5" x="22.99" y="24" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.396078 0 0 0 0 0.329412 0 0 0 0 0.466667 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10575"/></filter><filter id="iwCqg9z" width="3.212" height="3.4" x="23.79" y="19.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10575" stdDeviation=".05"/></filter><filter id="iKT1sLe" width="3.228" height="3.4" x="4.962" y="19.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10575" stdDeviation=".05"/></filter><filter id="iyxrxwb" width="6.4" height="3.4" x="12.79" y="19.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10575" stdDeviation=".05"/></filter><filter id="iAemtcz" width="6.5" height="3.1" x="12.49" y="19.9" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy="-.1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.117647 0 0 0 0 0.0352941 0 0 0 0 0.156863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10575"/></filter><filter id="iCcxqdd" width="4.01" height="2.11" x="13.99" y="25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".1"/><feGaussianBlur stdDeviation=".1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.490196 0 0 0 0 0.458824 0 0 0 0 0.52549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10575"/></filter><filter id="icwlGJd" width="3.4" height="3.4" x="8.79" y="19.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10575" stdDeviation=".05"/></filter><filter id="i3oW6fc" width="3.4" height="3.4" x="19.79" y="19.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_10575" stdDeviation=".05"/></filter><filter id="i44jKnr" width="13.659" height="2" x="9.255" y="10" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.686275 0 0 0 0 0.278431 0 0 0 0 0.298039 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_10575"/></filter><radialGradient id="iWFnwEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.8358 1.26362 -1.19203 -.78845 10.239 16.327)" gradientUnits="userSpaceOnUse"><stop class="komay93pn"/><stop offset="1" class="a4l6zu7ai"/></radialGradient><radialGradient id="i4L2DGd" cx="0" cy="0" r="1" gradientTransform="rotate(123.319 8.477 15.11)scale(1.51217 1.42301)" gradientUnits="userSpaceOnUse"><stop class="komay93pn"/><stop offset="1" class="a4l6zu7ai"/></radialGradient><radialGradient id="imXhIze" cx="0" cy="0" r="1" gradientTransform="matrix(-.61719 .92187 -.5005 -.33509 14.177 25.946)" gradientUnits="userSpaceOnUse"><stop offset=".31" class="dq6zbd7zv"/><stop offset="1" class="ai1uiubsi"/></radialGradient><radialGradient id="iHKlzuU" cx="0" cy="0" r="1" gradientTransform="matrix(1.76563 -1.90625 1.93154 1.78906 9.63 22.422)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="n9demilqz"/></radialGradient><radialGradient id="iItG2Qd" cx="0" cy="0" r="1" gradientTransform="matrix(1.76563 -1.90625 1.93154 1.78906 20.63 22.422)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="n9demilqz"/></radialGradient><radialGradient id="i96Bgce" cx="0" cy="0" r="1" gradientTransform="rotate(131.448 9.191 11.121)scale(3.21025 1.15153)" gradientUnits="userSpaceOnUse"><stop offset=".373" class="c0ep7g8ih"/><stop offset="1" class="w1qgb0b_g"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-automobile" /></template>
<style>
.a4l6zu7ai {
  stop-color: var(--svg-color--36284c, #36284C);
}

.a8ol_9brs {
  stop-color: var(--svg-color--8f77ae, #8F77AE);
}

.aa3pdackz {
  d: path("M24.99 26h-18c-1.1 0-2-.9-2-2h22a2 2 0 0 1-2 2");
}

.ai1uiubsi {
  stop-color: var(--svg-color--694a84, #694A84);
  stop-opacity: 0;
}

.ajietmbyg {
  stop-color: var(--svg-color--76eaff, #76EAFF);
}

.b42ppno_e {
  stop-color: var(--svg-color--ff4e5b, #FF4E5B);
  stop-opacity: 0;
}

.b44nmioev {
  stop-color: var(--svg-color--f83a70, #F83A70);
}

.bo0zhkyrq {
  stop-color: var(--svg-color--f53759, #F53759);
}

.bx___2bho {
  stop-color: var(--svg-color--d13459, #D13459);
  stop-opacity: 0;
}

.c0ep7g8ih {
  stop-color: var(--svg-color--23aaf5, #23AAF5);
}

.ceoo-ac7h {
  stop-color: var(--svg-color--ff4e5b, #FF4E5B);
}

.cw0mlsimd {
  stop-color: var(--svg-color--ffe666, #FFE666);
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.dbugmxbgr {
  stop-color: var(--svg-color--ffe96a, #FFE96A);
}

.delrb2b8d {
  stop-color: var(--svg-color--efcd4b, #EFCD4B);
}

.dq6zbd7zv {
  stop-color: var(--svg-color--694a84, #694A84);
}

.dw7g7vhjo {
  stop-color: var(--svg-color--a99eb7, #A99EB7);
}

.dwjy1_hjr {
  stop-color: var(--svg-color--361752, #361752);
}

.dxjef_7ed {
  stop-color: var(--svg-color--2d1e3b, #2D1E3B);
}

.ei_w2ev7q {
  stop-color: var(--svg-color--fff371, #FFF371);
}

.fbgbc_xre {
  d: path("M10.49 23a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.ft5dv1b6b {
  fill: none;
}

.g_lcfnb3y {
  stop-color: var(--svg-color--289bfd, #289BFD);
}

.g4pskspiu {
  d: path("M24.797 19h-2.931a.33.33 0 0 1-.328-.33A2.66 2.66 0 0 1 24.191 16h.616c.656 0 1.183.53 1.183 1.19v.62c-.01.66-.537 1.19-1.193 1.19");
}

.glyen-1ht {
  stop-color: var(--svg-color--cb545a, #CB545A);
  stop-opacity: 0;
}

.gmusieboo {
  d: path("M25.99 29h-2c-.55 0-1-.45-1-1v-4h4v4c0 .55-.45 1-1 1");
}

.hjzv0dbrp {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M24.928 20c-.516 0-.938.45-.938 1v1c0 .55.422 1 .938 1h1.874v-1.73c0-.44-.071-.87-.212-1.27z");
}

.i7nwspsvj {
  d: path("M17.33 25h-.67zh-2.67c-.37 0-.67.3-.67.67v.67c0 .37.3.67.67.67h2.67h-.67h.67c.37 0 .67-.3.67-.67v-.67c0-.37-.3-.67-.67-.67");
}

.imei5h12v {
  d: path("M17.99 20h-1zh-4c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1h4h-1h1c.55 0 1-.45 1-1v-1c0-.55-.45-1-1-1");
}

.ind0xq1wk {
  stop-color: var(--svg-color--1285eb, #1285EB);
}

.k_0o0ab4h {
  stop-color: var(--svg-color--1285eb, #1285EB);
  stop-opacity: 0;
}

.k2h3m4b0d {
  d: path("M9.255 12c.643-1.22 1.812-2 3.235-2h7c1.423 0 2.538.78 3.174 2z");
}

.k698cxb5a {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M7.99 22v-1c0-.55-.424-1-.943-1l-1.683.015a3.7 3.7 0 0 0-.202 1.255V23h1.885c.519 0 .943-.45.943-1Z");
}

.ka1fgb3yy {
  stop-color: var(--svg-color--76eaff, #76EAFF);
  stop-opacity: 0;
}

.komay93pn {
  stop-color: var(--svg-color--3e355c, #3E355C);
}

.kw-6libnu {
  stop-color: var(--svg-color--8f77ae, #8F77AE);
  stop-opacity: 0;
}

.lk9l3xk9f {
  stop-color: var(--svg-color--fdd86d, #FDD86D);
}

.lwlacl1mn {
  stop-color: var(--svg-color--c21d62, #C21D62);
}

.n9demilqz {
  stop-color: var(--svg-color--e7c9f4, #E7C9F4);
}

.nepzn3bxa {
  stop-color: var(--svg-color--fd4070, #FD4070);
}

.o_dzv-bhn {
  stop-color: var(--svg-color--cb545a, #CB545A);
}

.oaw93jvaw {
  stop-color: var(--svg-color--f84c91, #F84C91);
}

.oeb5m_14x {
  d: path("M24.99 20c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1h2v-1.73c0-.44-.077-.87-.227-1.27z");
}

.oipk5yrep {
  stop-color: var(--svg-color--c51f66, #C51F66);
}

.p9b-ccbss {
  stop-color: var(--svg-color--7b539e, #7B539E);
  stop-opacity: 0;
}

.pmnk1j68a {
  d: path("M24.95 18H7.03a3.64 3.64 0 0 0-2.04 3.27V24h22v-2.73c0-1.39-.79-2.66-2.04-3.27");
}

.prgoirbos {
  d: path("M19.49 10h-7c-1.62 0-2.91 1.01-3.47 2.53L6.99 18h17.94l-2.03-5.47c-.57-1.52-1.79-2.53-3.41-2.53");
}

.pug7uijyt {
  d: path("M7.99 29h-2c-.55 0-1-.45-1-1v-4h4v4c0 .55-.45 1-1 1");
}

.q8p87wbcb {
  stop-color: var(--svg-color--f83444, #F83444);
}

.qt_rb4l4v {
  stop-color: var(--svg-color--362a59, #362A59);
}

.rt7h5jcdu {
  d: path("M21.49 23a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3");
}

.smg795j2d {
  stop-color: var(--svg-color--9076a8, #9076A8);
}

.tvcowqbsi {
  stop-color: var(--svg-color--9988b1, #9988B1);
}

.u4yanwdgl {
  stop-color: var(--svg-color--50e2ff, #50E2FF);
}

.uf8mf0flb {
  stop-color: var(--svg-color--998cad, #998CAD);
}

.ugzlsrbbx {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M21.49 23a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z");
}

.v_9sdtb2z {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M10.49 23a1.5 1.5 0 1 0 0-3a1.5 1.5 0 0 0 0 3Z");
}

.v-xhqylqp {
  stop-color: var(--svg-color--d13459, #D13459);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vot6geb4t {
  stop-color: var(--svg-color--fa3344, #FA3344);
}

.vp7yhcbdb {
  stroke-width: var(--svg-stroke-width--0-2px, 0.2px);
  d: path("M17.99 20h-1zm0 0h-4c-.55 0-1 .45-1 1v1c0 .55.45 1 1 1h4h-1h1c.55 0 1-.45 1-1v-1c0-.55-.45-1-1-1Z");
}

.vz876ib1u {
  stop-color: var(--svg-color--e53a94, #E53A94);
}

.w1qgb0b_g {
  stop-color: var(--svg-color--23aaf5, #23AAF5);
  stop-opacity: 0;
}

.wi7exgb2z {
  stop-color: var(--svg-color--7b539e, #7B539E);
}

.x7sbwkb1z {
  stop-color: var(--svg-color--3d3861, #3D3861);
}

.xcm26crry {
  d: path("M7.99 22v-1c0-.55-.45-1-1-1l-1.785.015c-.15.4-.215.815-.215 1.255V23h2c.55 0 1-.45 1-1");
}

.xpw3pnkto {
  d: path("M7.19 19h2.95c.18 0 .33-.15.33-.33A2.67 2.67 0 0 0 7.8 16h-.62c-.66 0-1.19.53-1.19 1.19v.62c.01.66.54 1.19 1.2 1.19");
}

.ycy-ddc7h {
  stop-color: var(--svg-color--3a355f, #3A355F);
  stop-opacity: 0;
}

.z8do9ebsv {
  stop-color: var(--svg-color--381f4e, #381F4E);
}

.zba1hbbwq {
  stop-color: var(--svg-color--fd4070, #FD4070);
  stop-opacity: 0;
}

.zh7_9ob1a {
  stop-color: var(--svg-color--ffe96a, #FFE96A);
  stop-opacity: 0;
}

</style>
