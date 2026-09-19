<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iohaLAc)"><path fill="url(#iVJRsqc)" class="z5gkcf-av"/></g><g filter="url(#ioH2hyb)"><rect fill="url(#iB3iLjx)" class="kgq1yxb-w"/></g><g filter="url(#iKvL6Eb)"><path class="pkaa1lbdu"/></g><rect fill="url(#i2kWPab)" class="yqrsv_hxq"/><rect fill="url(#icdR7Eb)" class="yqrsv_hxq"/><rect fill="url(#iPIdKNd)" class="yqrsv_hxq"/><rect fill="url(#iE02NEd)" class="yqrsv_hxq"/><path fill="url(#ifnFJMb)" class="oz9fqcisu"/><path fill="url(#i2dikbe)" class="oz9fqcisu"/><path fill="url(#iDh8WVd)" class="oz9fqcisu"/><path fill="url(#ivEmL5d)" class="oz9fqcisu"/><rect class="q1vclbzpe"/><rect fill="url(#i9pNIle)" class="tcvr7tulc"/><rect fill="url(#iN7ElHc)" class="tcvr7tulc"/><rect fill="url(#iLPtIpd)" class="tcvr7tulc"/><rect fill="url(#iMpQfuc)" class="tcvr7tulc"/><path fill="url(#iVBVk5d)" class="kb4_9888a"/><path fill="url(#ijMITLe)" class="kb4_9888a"/><path fill="url(#iUmN1Qd)" class="kb4_9888a"/><path fill="url(#iCwHIOb)" class="kb4_9888a"/><path fill="url(#il7evKb)" class="ysk0fqb5c"/><path fill="url(#i6zvlnc)" class="ysk0fqb5c"/><path fill="url(#igdIIne)" class="ysk0fqb5c"/><path fill="url(#iNkpYve)" class="ysk0fqb5c"/><g filter="url(#iBZjRWc)"><path stroke="url(#ikPKpfc)" class="zxgv6ex7l"/></g><defs><radialGradient id="iVJRsqc" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3034 -15.1439 0 16 17.516)" gradientUnits="userSpaceOnUse"><stop class="zcbugyahe"/><stop offset="1" class="a526xpbcv"/></radialGradient><radialGradient id="i2kWPab" cx="0" cy="0" r="1" gradientTransform="matrix(-4.65948 0 0 -9.31895 8.15 8.762)" gradientUnits="userSpaceOnUse"><stop class="ni_pyug7k"/><stop offset="1" class="u8ydjeb6l"/></radialGradient><radialGradient id="icdR7Eb" cx="0" cy="0" r="1" gradientTransform="rotate(107.103 1.074 7.072)scale(7.31258 6.34489)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="yvy8u4bmp"/><stop offset="1" class="onovj9tlm"/></radialGradient><radialGradient id="iPIdKNd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67954 0 0 -10.0187 9.663 10.126)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="oaf885blu"/><stop offset="1" class="ds9neh70o"/></radialGradient><radialGradient id="iE02NEd" cx="0" cy="0" r="1" gradientTransform="matrix(1.22807 1.63545 -3.19277 2.39747 4.202 5.531)" gradientUnits="userSpaceOnUse"><stop class="ugveaibxh"/><stop offset="1" class="oci122bqy"/></radialGradient><radialGradient id="ifnFJMb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.39944 0 0 -14.5141 13.406 7.833)" gradientUnits="userSpaceOnUse"><stop class="ywjq2tb2d"/><stop offset="1" class="u8ydjeb6l"/></radialGradient><radialGradient id="i2dikbe" cx="0" cy="0" r="1" gradientTransform="rotate(98.073 3.477 8.943)scale(8.90071 6.88498)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="yvy8u4bmp"/><stop offset="1" class="onovj9tlm"/></radialGradient><radialGradient id="iDh8WVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 0 0 -12.5748 15.194 9.394)" gradientUnits="userSpaceOnUse"><stop offset=".343" class="oaf885blu"/><stop offset="1" class="ds9neh70o"/></radialGradient><radialGradient id="ivEmL5d" cx="0" cy="0" r="1" gradientTransform="rotate(56.736 .901 10.826)scale(2.23897 4.17494)" gradientUnits="userSpaceOnUse"><stop class="ugveaibxh"/><stop offset="1" class="oci122bqy"/></radialGradient><radialGradient id="i9pNIle" cx="0" cy="0" r="1" gradientTransform="matrix(-3.80251 0 0 -9.85624 25.692 6.921)" gradientUnits="userSpaceOnUse"><stop class="fmipzb3ra"/><stop offset="1" class="k54_qrbzb"/></radialGradient><radialGradient id="iN7ElHc" cx="0" cy="0" r="1" gradientTransform="rotate(97.753 10.02 13.86)scale(9.26599 6.89033)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="yvy8u4bmp"/><stop offset="1" class="onovj9tlm"/></radialGradient><radialGradient id="iLPtIpd" cx="0" cy="0" r="1" gradientTransform="matrix(1.76987 0 0 21.1996 20.228 8.548)" gradientUnits="userSpaceOnUse"><stop offset=".379" class="oaf885blu"/><stop offset="1" class="ds9neh70o"/></radialGradient><radialGradient id="iMpQfuc" cx="0" cy="0" r="1" gradientTransform="rotate(57.804 8.094 21.228)scale(2.30488 4.22527)" gradientUnits="userSpaceOnUse"><stop class="ugveaibxh"/><stop offset="1" class="oci122bqy"/></radialGradient><radialGradient id="iVBVk5d" cx="0" cy="0" r="1" gradientTransform="rotate(179.148 9.659 3.667)scale(4.59167 13.079)" gradientUnits="userSpaceOnUse"><stop class="fmipzb3ra"/><stop offset="1" class="mmp653uqm"/></radialGradient><radialGradient id="ijMITLe" cx="0" cy="0" r="1" gradientTransform="rotate(97.062 6.756 11.292)scale(10.0179 6.79995)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="yvy8u4bmp"/><stop offset="1" class="onovj9tlm"/></radialGradient><radialGradient id="iUmN1Qd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.15579 -5.27349 5.20313 -1.14037 16.363 14.88)" gradientUnits="userSpaceOnUse"><stop class="c2pgqdb-n"/><stop offset="1" class="p6rkbzg6q"/></radialGradient><radialGradient id="iCwHIOb" cx="0" cy="0" r="1" gradientTransform="rotate(60.19 5.138 14.865)scale(2.43413 4.26884)" gradientUnits="userSpaceOnUse"><stop class="ugveaibxh"/><stop offset="1" class="oci122bqy"/></radialGradient><radialGradient id="il7evKb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2179 6.93823 -12.8582 -2.25707 25.116 11.355)" gradientUnits="userSpaceOnUse"><stop class="r245klenb"/><stop offset="1" class="qmwldzbip"/></radialGradient><radialGradient id="i6zvlnc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.77179 -6.0673 0 20.517 17.887)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="b8a6egzhv"/><stop offset="1" class="jasf8r66e"/></radialGradient><radialGradient id="igdIIne" cx="0" cy="0" r="1" gradientTransform="matrix(1.95599 -2.8705 3.17752 2.1652 23.602 21.864)" gradientUnits="userSpaceOnUse"><stop class="qino82ood"/><stop offset="1" class="gcbtadcsl"/></radialGradient><radialGradient id="iNkpYve" cx="0" cy="0" r="1" gradientTransform="matrix(3.54293 0 0 5.4251 15.225 13.605)" gradientUnits="userSpaceOnUse"><stop class="llju146vm"/><stop offset="1" class="lxn6wyb0z"/></radialGradient><filter id="iohaLAc" width="25.02" height="20.828" x="3.49" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.968627 0 0 0 0 0.584314 0 0 0 0 0.305882 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3118"/></filter><filter id="ioH2hyb" width="18.678" height="12.194" x="7.28" y="9.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3118" stdDeviation="1.5"/></filter><filter id="iKvL6Eb" width="24.653" height="14.935" x="3.21" y="3.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3118" stdDeviation="1"/></filter><filter id="iBZjRWc" width="13.395" height="8.553" x="17.128" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3118" stdDeviation=".85"/></filter><linearGradient id="iB3iLjx" x1="20.393" x2="8.571" y1="17.241" y2="21.196" gradientUnits="userSpaceOnUse"><stop class="f3-rvgbrj"/><stop offset="1" class="gelr02bmb"/></linearGradient><linearGradient id="ikPKpfc" x1="19.828" x2="31.896" y1="12.402" y2="16.683" gradientUnits="userSpaceOnUse"><stop class="wvtwdjyyh"/><stop offset="1" class="ni0jqbjqt"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-fist" /></template>
<style>
.a526xpbcv {
  stop-color: var(--svg-color--ffbd33, #FFBD33);
}

.b8a6egzhv {
  stop-color: var(--svg-color--ec7e4b, #EC7E4B);
}

.c2pgqdb-n {
  stop-color: var(--svg-color--da7621, #DA7621);
}

.ds9neh70o {
  stop-color: var(--svg-color--bd7209, #BD7209);
  stop-opacity: 0;
}

.f3-rvgbrj {
  stop-color: var(--svg-color--cc6e17, #CC6E17);
}

.fmipzb3ra {
  stop-color: var(--svg-color--ffe744, #FFE744);
}

.ft5dv1b6b {
  fill: none;
}

.gcbtadcsl {
  stop-color: var(--svg-color--ffb735, #FFB735);
  stop-opacity: 0;
}

.gelr02bmb {
  stop-color: var(--svg-color--cc6e17, #CC6E17);
  stop-opacity: 0;
}

.jasf8r66e {
  stop-color: var(--svg-color--ee8350, #EE8350);
  stop-opacity: 0;
}

.k54_qrbzb {
  stop-color: var(--svg-color--e7af1d, #E7AF1D);
}

.kb4_9888a {
  d: path("M14.78 5.676c0-1.848 1.498-3.167 3.345-3.167a3.345 3.345 0 0 1 3.346 3.346v6.192a3.345 3.345 0 1 1-6.69 0z");
}

.kgq1yxb-w {
  width: 12.678px;
  height: 6.195px;
  x: 10.28px;
  y: 12.903px;
  rx: 3.097px;
}

.llju146vm {
  stop-color: var(--svg-color--f0a92e, #F0A92E);
}

.lxn6wyb0z {
  stop-color: var(--svg-color--f0a92e, #F0A92E);
  stop-opacity: 0;
}

.mmp653uqm {
  stop-color: var(--svg-color--e19614, #E19614);
}

.ni_pyug7k {
  stop-color: var(--svg-color--ffc734, #FFC734);
}

.ni0jqbjqt {
  stop-color: var(--svg-color--ffde43, #FFDE43);
  stop-opacity: 0;
}

.oaf885blu {
  stop-color: var(--svg-color--bd7209, #BD7209);
}

.oci122bqy {
  stop-color: var(--svg-color--cea142, #CEA142);
  stop-opacity: 0;
}

.onovj9tlm {
  stop-color: var(--svg-color--e7803a, #E7803A);
}

.oz9fqcisu {
  d: path("M8.747 7.08c0-2.35 1.52-3.396 3.395-3.396a3.395 3.395 0 0 1 3.395 3.395v4.509c0 1.875-1.52 3.516-3.395 3.516s-3.395-1.085-3.395-3.516z");
}

.p6rkbzg6q {
  stop-color: var(--svg-color--da7621, #DA7621);
  stop-opacity: 0;
}

.pkaa1lbdu {
  fill: var(--svg-color--b45a11, #B45A11);
  d: path("M15.024 14.283c-.504.868-1.422 1.472-2.47 1.472c-.93 0-1.757-.314-2.283-.987a2.882 2.882 0 0 1-5.06-1.886v-2.704a2.882 2.882 0 0 1 4.61-2.306c.383-1.244 1.462-1.81 2.733-1.81c.936 0 1.768.447 2.294 1.138c.26-1.272 1.408-2.135 2.785-2.135a2.84 2.84 0 0 1 2.674 1.884a2.882 2.882 0 0 1 5.556 1.074v4.335a2.882 2.882 0 0 1-5.44 1.328a2.84 2.84 0 0 1-5.4.597");
}

.q1vclbzpe {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  fill: var(--svg-color--7dde5b, #7DDE5B);
  fill-opacity: var(--svg-fill-opacity--0-55, 0.55);
  rx: 3.395px;
}

.qino82ood {
  stop-color: var(--svg-color--ffb735, #FFB735);
}

.qmwldzbip {
  stop-color: var(--svg-color--f2b02c, #F2B02C);
}

.r245klenb {
  stop-color: var(--svg-color--ffdf40, #FFDF40);
}

.tcvr7tulc {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  rx: 3.395px;
}

.u8ydjeb6l {
  stop-color: var(--svg-color--ef9c2e, #EF9C2E);
}

.ugveaibxh {
  stop-color: var(--svg-color--cea142, #CEA142);
}

.wvtwdjyyh {
  stop-color: var(--svg-color--ffde43, #FFDE43);
}

.yqrsv_hxq {
  width: 6.79px;
  height: 9.976px;
  x: 3.49px;
  y: 5.138px;
  rx: 3.395px;
}

.ysk0fqb5c {
  d: path("M19.101 10.136a3.365 3.365 0 1 0 0 6.73h2.46a2 2 0 0 1 2 2v2.998h.189c3.276 0 4.969-3.021 4.969-5.765a5.963 5.963 0 0 0-5.963-5.963z");
}

.yvy8u4bmp {
  stop-color: var(--svg-color--e7803a, #E7803A);
  stop-opacity: 0;
}

.ywjq2tb2d {
  stop-color: var(--svg-color--ffd738, #FFD738);
}

.z5gkcf-av {
  d: path("M27.823 9.479H3.49v9.328c0 6.351 5.149 11.5 11.5 11.5h1.333c2.153 0 4.168-.592 5.89-1.621l.005.018c2.518-1.454 5.089-4.099 5.904-7.358c.83-3.325.134-5.707-.3-6.552z");
}

.zcbugyahe {
  stop-color: var(--svg-color--fdad36, #FDAD36);
}

.zxgv6ex7l {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.828 12.25h2.325c3.462-.131 5.111 1.01 5.67 3.143");
}

</style>
