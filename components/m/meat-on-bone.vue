<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="xdoi7pygt"/><path fill="url(#iqHLhxe)" class="o2drhvbbz"/><path fill="url(#iNpWoRn)" class="o2drhvbbz"/><path fill="url(#iEUcOGe)" class="bbce-6a0o"/><path fill="url(#i1DrPab)" class="bbce-6a0o"/><path fill="url(#i3ItMac)" class="fawnvcc6u"/><g filter="url(#iP9JSlL)"><path fill="url(#irt8u1N)" class="mhino9psf"/><path fill="url(#iIGWQFc)" class="mhino9psf"/></g><path fill="url(#iFH4Oum)" class="w4f60g2aq"/><path fill="url(#i46XSXc)" class="w4f60g2aq"/><path class="kbop2ubcg"/><path fill="url(#i6fONdc)" class="b1-7o4kji"/><g filter="url(#idTxpoc)"><rect transform="rotate(44.395 20.446 18.408)" class="iidy3s01e"/></g><path clip-rule="evenodd" class="uvwcx6bix"/><path fill="url(#iREtMBd)" clip-rule="evenodd" class="w_-zykbbb"/><path fill="url(#i7CGMtb)" clip-rule="evenodd" class="w_-zykbbb"/><g filter="url(#iPh8jpc)"><path stroke="url(#i1G4IIb)" class="y3bgd5bcr"/></g><g filter="url(#iGZHvFd)"><path stroke="url(#iZx2a1b)" class="qtchasitq"/></g><g filter="url(#itVpw5c)"><path stroke="url(#iwvrGXd)" class="ekmn5qbwd"/></g><defs><radialGradient id="iqHLhxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 4.4375 -4.437 1.18736 4.125 7.375)" gradientUnits="userSpaceOnUse"><stop class="l05gnktcn"/><stop offset=".92" class="exlrp35oh"/></radialGradient><radialGradient id="iNpWoRn" cx="0" cy="0" r="1" gradientTransform="matrix(-.8171 4.75 -4.74945 -.817 8.875 3.875)" gradientUnits="userSpaceOnUse"><stop offset=".152" class="cw4om937z"/><stop offset=".853" class="ofpsxfd7h"/></radialGradient><radialGradient id="i1DrPab" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 3.18799 -2.33834 2.33798 8.063 5.25)" gradientUnits="userSpaceOnUse"><stop class="h17to2bce"/><stop offset="1" class="mb8jiebgo"/></radialGradient><radialGradient id="iIGWQFc" cx="0" cy="0" r="1" gradientTransform="matrix(4.125 .96507 -.97392 4.16285 16.563 27.285)" gradientUnits="userSpaceOnUse"><stop class="eyec28f9u"/><stop offset="1" class="jqb--v0sg"/></radialGradient><radialGradient id="i46XSXc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.3125 3.9375 -1.86767 -1.57122 18.75 22.375)" gradientUnits="userSpaceOnUse"><stop class="v2ltuhzpf"/><stop offset="1" class="en8c5ptsi"/></radialGradient><radialGradient id="i6fONdc" cx="0" cy="0" r="1" gradientTransform="rotate(132.44 6.69 17.576)scale(4.14982 2.14476)" gradientUnits="userSpaceOnUse"><stop class="q4-b1sbse"/><stop offset="1" class="k05n1gbkm"/></radialGradient><radialGradient id="iREtMBd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.31248 3.8125 -3.80564 -2.30832 28.875 22.813)" gradientUnits="userSpaceOnUse"><stop offset=".133" class="t64xrsb7t"/><stop offset="1" class="kwhv5ltmq"/></radialGradient><radialGradient id="i7CGMtb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 2.625 -2.62026 -2.4955 25 26.375)" gradientUnits="userSpaceOnUse"><stop offset=".227" class="f9r60idgb"/><stop offset="1" class="e9ngu8lse"/></radialGradient><radialGradient id="i1G4IIb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18751 2.87499 -8.91927 -9.88884 23.25 13.813)" gradientUnits="userSpaceOnUse"><stop class="df38_ubqb"/><stop offset="1" class="oeo36w46h"/></radialGradient><radialGradient id="iZx2a1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.42527 5.3125 -2.84831 .76416 12.576 22.406)" gradientUnits="userSpaceOnUse"><stop class="bu3f3xb-t"/><stop offset="1" class="qpk2s4bux"/></radialGradient><linearGradient id="iEUcOGe" x1="6.813" x2="10.125" y1="9.683" y2="5.938" gradientUnits="userSpaceOnUse"><stop offset=".42" class="rt3wl5fil"/><stop offset="1" class="lxrbuflao"/></linearGradient><linearGradient id="i3ItMac" x1="10.435" x2="24.653" y1="22.812" y2="10.111" gradientUnits="userSpaceOnUse"><stop class="dkuoubc5u"/><stop offset=".613" class="i4o4w3fqt"/><stop offset="1" class="y0hpskbnq"/></linearGradient><linearGradient id="irt8u1N" x1="14.133" x2="26.702" y1="25.956" y2="15.253" gradientUnits="userSpaceOnUse"><stop class="lc6w3sbjr"/><stop offset="1" class="y0qxddbcl"/></linearGradient><linearGradient id="iFH4Oum" x1="17.68" x2="23.902" y1="17.369" y2="23.093" gradientUnits="userSpaceOnUse"><stop class="kqtzasnqb"/><stop offset="1" class="ocs8mi9ey"/></linearGradient><linearGradient id="iwvrGXd" x1="5.031" x2="8.274" y1="8.156" y2="8.011" gradientUnits="userSpaceOnUse"><stop class="cuxm4pbhg"/><stop offset=".442" class="yb1bvvd_d"/><stop offset="1" class="q-t-otz6z"/></linearGradient><filter id="iP9JSlL" width="15.88" height="15.749" x="12.078" y="12.285" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29741" stdDeviation=".375"/></filter><filter id="idTxpoc" width="9.554" height="9.479" x="17.501" y="17.516" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29741" stdDeviation=".75"/></filter><filter id="iPh8jpc" width="10.531" height="4.372" x="17.015" y="12.353" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29741" stdDeviation=".25"/></filter><filter id="iGZHvFd" width="3.691" height="10.625" x="12.184" y="16.406" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29741" stdDeviation=".25"/></filter><filter id="itVpw5c" width="5.564" height="5.658" x="4.451" y="4.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29741" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:meat-on-bone" /></template>
<style>
.b1-7o4kji {
  d: path("M29.032 21.758c-1.067-.926-2.667-.886-3.733.04a.453.453 0 0 1-.624-.02L21.756 18.9c-1.835-1.856-4.587 1.022-2.857 2.858l2.877 2.919a.453.453 0 0 1 .02.624c-.926 1.066-.966 2.667-.04 3.733a2.805 2.805 0 0 0 4.106.141a2.8 2.8 0 0 0 .825-1.952c0-.292.242-.534.544-.544a2.8 2.8 0 0 0 1.952-.825c1.137-1.127 1.087-3.01-.15-4.096");
}

.bbce-6a0o {
  d: path("m8.607 5.705l4.919 4.965c.786.787.786 2.07 0 2.857a2.025 2.025 0 0 1-2.857 0l-4.92-4.964c-.75-.713-.797-2.171.001-2.858c.754-.649 2.32-.565 2.857 0");
}

.bu3f3xb-t {
  stop-color: var(--svg-color--74574d, #74574D);
}

.cuxm4pbhg {
  stop-color: var(--svg-color--9f999c, #9F999C);
}

.cw4om937z {
  stop-color: var(--svg-color--f2f0ee, #F2F0EE);
}

.df38_ubqb {
  stop-color: var(--svg-color--aa7461, #AA7461);
}

.dkuoubc5u {
  stop-color: var(--svg-color--4f3b2e, #4F3B2E);
}

.e9ngu8lse {
  stop-color: var(--svg-color--e1dedd, #E1DEDD);
  stop-opacity: 0;
}

.ekmn5qbwd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M6.531 9.375C5.313 8.5 4.712 7.2 5.687 5.875c.563-.615 1.979-1.34 3.579.61");
}

.en8c5ptsi {
  stop-color: var(--svg-color--ab1f4f, #AB1F4F);
  stop-opacity: 0;
}

.exlrp35oh {
  stop-color: var(--svg-color--b1aeaa, #B1AEAA);
  stop-opacity: 0;
}

.eyec28f9u {
  stop-color: var(--svg-color--5d3743, #5D3743);
}

.f9r60idgb {
  stop-color: var(--svg-color--e1dfdd, #E1DFDD);
}

.fawnvcc6u {
  d: path("M18.58 6.399a6.92 6.92 0 0 0-8.21 1.163l-2.801 2.81a6.89 6.89 0 0 0-1.163 8.21a20.5 20.5 0 0 0 8.068 8.068a6.92 6.92 0 0 0 8.21-1.162l2.81-2.811a6.89 6.89 0 0 0 1.163-8.21A20.46 20.46 0 0 0 18.58 6.4");
}

.ft5dv1b6b {
  fill: none;
}

.h17to2bce {
  stop-color: var(--svg-color--cccac7, #CCCAC7);
}

.i4o4w3fqt {
  stop-color: var(--svg-color--67432f, #67432F);
}

.iidy3s01e {
  width: 8px;
  height: 2.935px;
  x: 20.446px;
  y: 18.408px;
  fill: var(--svg-color--b7b2af, #B7B2AF);
  rx: 1.468px;
}

.jqb--v0sg {
  stop-color: var(--svg-color--5f3843, #5F3843);
  stop-opacity: 0;
}

.k05n1gbkm {
  stop-opacity: 0;
}

.kbop2ubcg {
  fill: var(--svg-color--d7d4d3, #D7D4D3);
  d: path("M29.032 21.758c-1.067-.926-2.667-.886-3.733.04a.453.453 0 0 1-.624-.02L21.756 18.9c-1.835-1.856-4.587 1.022-2.857 2.858l2.877 2.919a.453.453 0 0 1 .02.624c-.926 1.066-.966 2.667-.04 3.733a2.805 2.805 0 0 0 4.106.141a2.8 2.8 0 0 0 .825-1.952c0-.292.242-.534.544-.544a2.8 2.8 0 0 0 1.952-.825c1.137-1.127 1.087-3.01-.15-4.096");
}

.kqtzasnqb {
  stop-color: var(--svg-color--d8303c, #D8303C);
}

.kwhv5ltmq {
  stop-color: var(--svg-color--f8f6f4, #F8F6F4);
  stop-opacity: 0;
}

.l05gnktcn {
  stop-color: var(--svg-color--cac8c5, #CAC8C5);
}

.lc6w3sbjr {
  stop-color: var(--svg-color--5e3a40, #5E3A40);
}

.lxrbuflao {
  stop-color: var(--svg-color--d0cecc, #D0CECC);
}

.mb8jiebgo {
  stop-color: var(--svg-color--cecbc8, #CECBC8);
  stop-opacity: 0;
}

.mhino9psf {
  d: path("M14.625 26.438c1.804 1.38 5.64 1.099 7.781-1.032l2.768-2.767c2.14-2.14 2.742-6.361 1.076-7.951c-2.601-2.483-5.796-2.288-10.032 1.405c-4.327 3.772-4.113 8.416-1.593 10.345");
}

.o2drhvbbz {
  d: path("M10.141 2.945a2.796 2.796 0 0 1 .01 3.653c-.19.21-.17.518.02.717l3.355 3.355c.786.787.786 2.07 0 2.857a2.025 2.025 0 0 1-2.857 0l-3.355-3.355a.524.524 0 0 0-.717-.02a2.795 2.795 0 0 1-3.654-.01a2.78 2.78 0 0 1-.13-4.051a2.74 2.74 0 0 1 1.922-.817a.55.55 0 0 0 .538-.537a2.78 2.78 0 0 1 .816-1.932a2.79 2.79 0 0 1 4.052.14");
}

.ocs8mi9ey {
  stop-color: var(--svg-color--cd2e7c, #CD2E7C);
}

.oeo36w46h {
  stop-color: var(--svg-color--aa7461, #AA7461);
  stop-opacity: 0;
}

.ofpsxfd7h {
  stop-color: var(--svg-color--f5f3f1, #F5F3F1);
  stop-opacity: 0;
}

.q-t-otz6z {
  stop-color: var(--svg-color--dedcd9, #DEDCD9);
}

.q4-b1sbse {
  stop-color: var(--svg-color--a8a1a0, #A8A1A0);
}

.qpk2s4bux {
  stop-color: var(--svg-color--684d44, #684D44);
  stop-opacity: 0;
}

.qtchasitq {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M14.719 26.281c-1.906-1.187-2.969-4.25.406-9.125");
}

.rt3wl5fil {
  stop-color: var(--svg-color--9d9997, #9D9997);
}

.t64xrsb7t {
  stop-color: var(--svg-color--f8f6f4, #F8F6F4);
}

.uvwcx6bix {
  fill: var(--svg-color--b8b3b6, #B8B3B6);
  fill-rule: evenodd;
  d: path("M27.2 26.656a2.8 2.8 0 1 0-2.8-2.787a.546.546 0 0 1-.529.532a2.8 2.8 0 1 0 2.8 2.8v-.014a.546.546 0 0 1 .529-.532");
}

.v2ltuhzpf {
  stop-color: var(--svg-color--ab1f4f, #AB1F4F);
}

.w_-zykbbb {
  fill-rule: evenodd;
  d: path("M27.2 26.656a2.8 2.8 0 1 0-2.8-2.787a.546.546 0 0 1-.529.532a2.8 2.8 0 1 0 2.8 2.8v-.014a.546.546 0 0 1 .529-.532");
}

.w4f60g2aq {
  d: path("M22.068 14.812c-.986 0-1.902.378-2.599 1.075l-3.584 3.584a3.64 3.64 0 0 0-1.075 2.598a3.64 3.64 0 0 0 1.075 2.599a3.64 3.64 0 0 0 2.599 1.075c.985 0 1.901-.378 2.598-1.075l3.584-3.584a3.64 3.64 0 0 0 1.075-2.599c0-.985-.378-1.901-1.075-2.598a3.7 3.7 0 0 0-2.598-1.075");
}

.xdoi7pygt {
  fill: var(--svg-color--9a9397, #9A9397);
  d: path("M10.141 2.945a2.796 2.796 0 0 1 .01 3.653c-.19.21-.17.518.02.717l3.355 3.355c.786.787.786 2.07 0 2.857a2.025 2.025 0 0 1-2.857 0l-3.355-3.355a.524.524 0 0 0-.717-.02a2.795 2.795 0 0 1-3.654-.01a2.78 2.78 0 0 1-.13-4.051a2.74 2.74 0 0 1 1.922-.817a.55.55 0 0 0 .538-.537a2.78 2.78 0 0 1 .816-1.932a2.79 2.79 0 0 1 4.052.14");
}

.y0hpskbnq {
  stop-color: var(--svg-color--915b42, #915B42);
}

.y0qxddbcl {
  stop-color: var(--svg-color--995c4b, #995C4B);
}

.y3bgd5bcr {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.797 16.203c-.031-.354-.372-1.61-1.422-2.36c-1.312-.937-4.781-1.437-7.687 1.345");
}

.yb1bvvd_d {
  stop-color: var(--svg-color--b4b1ad, #B4B1AD);
}

</style>
