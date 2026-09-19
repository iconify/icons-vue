<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="peqaprb8y"/><path fill="url(#irVWBae)" class="pdc-k7s3x"/><path fill="url(#i7ZR4ye)" class="pdc-k7s3x"/><g filter="url(#isQXj2I)"><path fill="url(#iaavO6b)" class="eo99rc62c"/></g><path fill="url(#iDNoIDo)" class="eo99rc62c"/><path fill="url(#ii4kRnd)" class="eo99rc62c"/><path fill="url(#iEdezKb)" class="eo99rc62c"/><g filter="url(#iaKE0Fc)"><path fill="url(#ily1Mwc)" class="fyb_eob5e"/></g><circle fill="url(#i4CftHe)" class="zoy61etgz"/><circle fill="url(#i6Inhhb)" class="zoy61etgz"/><circle fill="url(#iuP8tbb)" class="p8sr3iqfd"/><circle fill="url(#iYioxqW)" class="p8sr3iqfd"/><g filter="url(#iPXZ1gd)"><circle fill="url(#ikBrXuj)" class="t9nr9nbcu"/></g><circle fill="url(#ifz7Veb)" class="szlf0eu1x"/><g clip-rule="evenodd" filter="url(#iA2s5ie)" class="d2kvgvbvc"><path class="f4rcqbqtc"/><path fill="url(#i3X03td)" class="lohm02bdo"/><path fill="url(#iM1KPXp)" class="lohm02bdo"/><path fill="url(#ikiBu7c)" class="lohm02bdo"/><path fill="url(#iIwEUPd)" class="lohm02bdo"/><path fill="url(#iO9GJzc)" class="lohm02bdo"/><path fill="url(#iHZydjH)" class="lohm02bdo"/></g><path fill="url(#iFgN1ce)" clip-rule="evenodd" class="osvde6bjs"/><circle fill="url(#i3LdhQb)" class="xf05d5bux"/><defs><radialGradient id="irVWBae" cx="0" cy="0" r="1" gradientTransform="matrix(5.48453 -5.2234 11.62845 12.2098 11.578 24.092)" gradientUnits="userSpaceOnUse"><stop class="ayt6dccwr"/><stop offset="1" class="ccnzvxb7s"/></radialGradient><radialGradient id="i7ZR4ye" cx="0" cy="0" r="1" gradientTransform="rotate(125.538 3.98 11.792)scale(8.42498 8.82776)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="pwlgssxdt"/><stop offset="1" class="ohxc-iq0g"/></radialGradient><radialGradient id="iEdezKb" cx="0" cy="0" r="1" gradientTransform="matrix(3.80997 4.04984 -5.45541 5.1323 13.687 12.286)" gradientUnits="userSpaceOnUse"><stop offset=".33" class="gz37z7bui"/><stop offset="1" class="ulrbekbdb"/></radialGradient><radialGradient id="i4CftHe" cx="0" cy="0" r="1" gradientTransform="rotate(143.207 12.568 8.935)scale(1.64856)" gradientUnits="userSpaceOnUse"><stop class="tb2ioabxj"/><stop offset="1" class="nrgm4qbhn"/></radialGradient><radialGradient id="i6Inhhb" cx="0" cy="0" r="1" gradientTransform="rotate(90 9.374 18.029)scale(1.44012)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="vecdcjb7u"/><stop offset="1" class="yjld-tbgb"/></radialGradient><radialGradient id="iuP8tbb" cx="0" cy="0" r="1" gradientTransform="rotate(135.89 11.1 12.736)scale(1.77167)" gradientUnits="userSpaceOnUse"><stop class="g--rod_is"/><stop offset="1" class="d3yt-qwbu"/></radialGradient><radialGradient id="iYioxqW" cx="0" cy="0" r="1" gradientTransform="rotate(124.958 10.245 14.39)scale(1.93867)" gradientUnits="userSpaceOnUse"><stop offset=".738" class="vecdcjb7u"/><stop offset="1" class="yjld-tbgb"/></radialGradient><radialGradient id="ikBrXuj" cx="0" cy="0" r="1" gradientTransform="matrix(-1.29127 .9337 -1.16175 -1.60666 18.054 13.76)" gradientUnits="userSpaceOnUse"><stop class="wzbamzb-m"/><stop offset="1" class="pyo71lcgb"/></radialGradient><radialGradient id="ifz7Veb" cx="0" cy="0" r="1" gradientTransform="rotate(137.626 9.437 6.724)scale(1.53118 1.5088)" gradientUnits="userSpaceOnUse"><stop class="kvi85lc-m"/><stop offset="1" class="fs3_7qboj"/></radialGradient><radialGradient id="i3X03td" cx="0" cy="0" r="1" gradientTransform="matrix(-11.7407 0 0 -8.34033 22.722 9.36)" gradientUnits="userSpaceOnUse"><stop offset=".719" class="uc-1znbld"/><stop offset="1" class="dv-x5rb_s"/></radialGradient><radialGradient id="iM1KPXp" cx="0" cy="0" r="1" gradientTransform="rotate(-101.877 15.473 .536)scale(8.04728 3.78154)" gradientUnits="userSpaceOnUse"><stop class="dv-x5rb_s"/><stop offset=".991" class="uc-1znbld"/></radialGradient><radialGradient id="ikiBu7c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.46873 -6.34375 2.98102 -1.1601 23.634 14.35)" gradientUnits="userSpaceOnUse"><stop class="dv-x5rb_s"/><stop offset=".991" class="uc-1znbld"/></radialGradient><radialGradient id="iIwEUPd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.24458 1.25697 -1.24245 -2.21865 15.089 8.497)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="bxn-gedrv"/><stop offset="1" class="tf6i1cb7f"/></radialGradient><radialGradient id="iO9GJzc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.1997 .7723 -.76338 -2.17427 19.533 8.587)" gradientUnits="userSpaceOnUse"><stop offset=".194" class="bxn-gedrv"/><stop offset="1" class="tf6i1cb7f"/></radialGradient><radialGradient id="iHZydjH" cx="0" cy="0" r="1" gradientTransform="matrix(-2.6935 1.42325 -1.43833 -2.72204 24.471 7.936)" gradientUnits="userSpaceOnUse"><stop class="bxn-gedrv"/><stop offset="1" class="tf6i1cb7f"/></radialGradient><radialGradient id="iFgN1ce" cx="0" cy="0" r="1" gradientTransform="rotate(140.845 11.482 8.065)scale(3.62695 3.90833)" gradientUnits="userSpaceOnUse"><stop class="ibamqhhem"/><stop offset="1" class="jizh8sbcc"/></radialGradient><radialGradient id="i3LdhQb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4204 1.57934 -1.8827 -1.69322 25.196 11.287)" gradientUnits="userSpaceOnUse"><stop offset=".143" class="yxcptf_fe"/><stop offset="1" class="e_uwy4dkf"/></radialGradient><linearGradient id="iaavO6b" x1="15.999" x2="15.999" y1="2.678" y2="29.992" gradientUnits="userSpaceOnUse"><stop class="g5qhfdcue"/><stop offset="1" class="n0w5hg0ek"/></linearGradient><linearGradient id="iDNoIDo" x1="15.999" x2="15.999" y1="1.821" y2="15.116" gradientUnits="userSpaceOnUse"><stop class="ty1rfjbwv"/><stop offset="1" class="hy4f-2bdg"/></linearGradient><linearGradient id="ii4kRnd" x1="17.259" x2="17.259" y1="29.992" y2="29.087" gradientUnits="userSpaceOnUse"><stop class="x437yvb-a"/><stop offset="1" class="w66nfi12r"/></linearGradient><linearGradient id="ily1Mwc" x1="21.3" x2="5.199" y1="7.873" y2="1.763" gradientUnits="userSpaceOnUse"><stop class="j571w6boz"/><stop offset="1" class="jlexblbtf"/></linearGradient><filter id="isQXj2I" width="28.74" height="27.814" x="1.754" y="2.678" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.25" dy=".5"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.309804 0 0 0 0 0.611765 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15842"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy=".25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.180392 0 0 0 0 0.501961 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_15842" result="effect2_innerShadow_18_15842"/></filter><filter id="iaKE0Fc" width="15.623" height="7.734" x="8.187" y="2.019" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_15842" stdDeviation=".625"/></filter><filter id="iPXZ1gd" width="2.375" height="2.375" x="16.388" y="12.72" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy="-.1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.505882 0 0 0 0 0.745098 0 0 0 0 0.972549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15842"/></filter><filter id="iA2s5ie" width="13.747" height="5.62" x="11.731" y="6.4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.3"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.498039 0 0 0 0 0.741176 0 0 0 0 0.956863 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_15842"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:water-wave" /></template>
<style>
.ayt6dccwr {
  stop-color: var(--svg-color--52c2ff, #52C2FF);
}

.bxn-gedrv {
  stop-color: var(--svg-color--bbf4ff, #BBF4FF);
}

.ccnzvxb7s {
  stop-color: var(--svg-color--52c2ff, #52C2FF);
  stop-opacity: 0;
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d3yt-qwbu {
  stop-color: var(--svg-color--90d0f8, #90D0F8);
}

.dv-x5rb_s {
  stop-color: var(--svg-color--86ccee, #86CCEE);
}

.e_uwy4dkf {
  stop-color: var(--svg-color--83c5f7, #83C5F7);
}

.eo99rc62c {
  d: path("M2.004 15.154v14.838h27.99V17.844c-2.488.92-4.011 2.663-5.881 4.185c-1.773 1.442-3.962 2.69-7.11 2.69c-4.249 0-9.196-3.822-9.196-8.833c0-6.019 5.182-8.585 8.035-8.585c1.148 0 1.638.245 1.834.367l1.21 1.65h4.183v-.953c-.672-1.896-3.544-5.687-9.649-5.687c-5.613 0-11.416 5.687-11.416 12.476");
}

.f4rcqbqtc {
  fill: var(--svg-color--a1e5ff, #A1E5FF);
  d: path("M16.404 11.098a2.66 2.66 0 1 1 0-3.477a2.657 2.657 0 0 1 4.214.244a2.66 2.66 0 1 1 0 2.99a2.657 2.657 0 0 1-4.214.243");
}

.fs3_7qboj {
  stop-color: var(--svg-color--85defb, #85DEFB);
}

.ft5dv1b6b {
  fill: none;
}

.fyb_eob5e {
  d: path("M9.437 4.262c6.923-2.888 11.634 1.204 13.124 3.61l-2.637.631c-2.108-5.135-7.87-4.967-10.487-4.24");
}

.g--rod_is {
  stop-color: var(--svg-color--bff4ff, #BFF4FF);
}

.g5qhfdcue {
  stop-color: var(--svg-color--52c3fb, #52C3FB);
}

.gz37z7bui {
  stop-color: var(--svg-color--40a3ee, #40A3EE);
}

.hy4f-2bdg {
  stop-color: var(--svg-color--53c2f9, #53C2F9);
  stop-opacity: 0;
}

.ibamqhhem {
  stop-color: var(--svg-color--c3fdff, #C3FDFF);
}

.j571w6boz {
  stop-color: var(--svg-color--74deff, #74DEFF);
}

.jizh8sbcc {
  stop-color: var(--svg-color--c3fdff, #C3FDFF);
  stop-opacity: 0;
}

.jlexblbtf {
  stop-color: var(--svg-color--74deff, #74DEFF);
  stop-opacity: 0;
}

.kvi85lc-m {
  stop-color: var(--svg-color--bbf7ff, #BBF7FF);
}

.lohm02bdo {
  d: path("M16.404 11.098a2.66 2.66 0 1 1 0-3.477a2.657 2.657 0 0 1 4.214.244a2.66 2.66 0 1 1 0 2.99a2.657 2.657 0 0 1-4.214.243");
}

.n0w5hg0ek {
  stop-color: var(--svg-color--3e7ff0, #3E7FF0);
}

.nrgm4qbhn {
  stop-color: var(--svg-color--8fd9fe, #8FD9FE);
}

.ohxc-iq0g {
  stop-color: var(--svg-color--5dc8ff, #5DC8FF);
}

.osvde6bjs {
  fill-rule: evenodd;
  d: path("M16.404 11.098a2.66 2.66 0 1 1 0-3.477a2.657 2.657 0 0 1 4.214.244a2.66 2.66 0 1 1 0 2.99a2.657 2.657 0 0 1-4.214.243");
}

.p8sr3iqfd {
  cx: 27.403px;
  cy: 14.796px;
  r: 1.138px;
}

.pdc-k7s3x {
  d: path("M18.208 8.429V5.886H6.509v20.899h18.98l.715-6.545c-2.726 2.513-5.208 2.775-7.917 2.775c-3.963 0-7.294-3.448-7.294-7.41a7.176 7.176 0 0 1 7.215-7.176");
}

.peqaprb8y {
  fill: var(--svg-color--4ab9ff, #4AB9FF);
  d: path("M18.208 8.429V5.886H6.509v20.899h18.98l.715-6.545c-2.726 2.513-5.208 2.775-7.917 2.775c-3.963 0-7.294-3.448-7.294-7.41a7.176 7.176 0 0 1 7.215-7.176");
}

.pwlgssxdt {
  stop-color: var(--svg-color--5dc8ff, #5DC8FF);
  stop-opacity: 0;
}

.pyo71lcgb {
  stop-color: var(--svg-color--8ac7fb, #8AC7FB);
}

.szlf0eu1x {
  cx: 20.534px;
  cy: 5.682px;
  r: 1.138px;
}

.t9nr9nbcu {
  cx: 17.525px;
  cy: 13.957px;
  r: 1.138px;
}

.tb2ioabxj {
  stop-color: var(--svg-color--bff7ff, #BFF7FF);
}

.tf6i1cb7f {
  stop-color: var(--svg-color--bbf4ff, #BBF4FF);
  stop-opacity: 0;
}

.ty1rfjbwv {
  stop-color: var(--svg-color--53c2f9, #53C2F9);
}

.uc-1znbld {
  stop-color: var(--svg-color--86ccee, #86CCEE);
  stop-opacity: 0;
}

.ulrbekbdb {
  stop-color: var(--svg-color--40a3ee, #40A3EE);
  stop-opacity: 0;
}

.vecdcjb7u {
  stop-color: var(--svg-color--85ccf6, #85CCF6);
  stop-opacity: 0;
}

.w66nfi12r {
  stop-color: var(--svg-color--2e6dea, #2E6DEA);
  stop-opacity: 0;
}

.wzbamzb-m {
  stop-color: var(--svg-color--a8ddff, #A8DDFF);
}

.x437yvb-a {
  stop-color: var(--svg-color--2e6dea, #2E6DEA);
}

.xf05d5bux {
  cx: 24.5px;
  cy: 11.877px;
  r: 1.138px;
}

.yjld-tbgb {
  stop-color: var(--svg-color--85ccf6, #85CCF6);
}

.yxcptf_fe {
  stop-color: var(--svg-color--bdf3ff, #BDF3FF);
}

.zoy61etgz {
  cx: 27.403px;
  cy: 8.958px;
  r: 1.138px;
}

</style>
