<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path stroke="url(#ihESi8b)" class="bj7wzbohv"/><path fill="url(#iqyq0yd)" class="akc2r_bli"/><path fill="url(#i8a4hwd)" class="akc2r_bli"/><path fill="url(#iXRh49b)" class="akc2r_bli"/><path stroke="url(#iwLgBkb)" class="ejq4g8uqj"/><path fill="url(#ik7xH6X)" class="r_pm-_wcb"/><path stroke="url(#iTIftCd)" class="e8q1vqb_d"/><path fill="url(#irJ6M7P)" class="jf5aeac0r"/><path fill="url(#iyPeyVc)" class="jf5aeac0r"/><path fill="url(#ifZ2rlZ)" class="jf5aeac0r"/><path fill="url(#i1G7QYR)" class="jf5aeac0r"/><path fill="url(#iwYCDmc)" class="qyln-_i-o"/><path fill="url(#i1MufOb)" class="qyln-_i-o"/><path stroke="url(#i2n055d)" class="ylz13cckx"/><path fill="url(#ijq2qWB)" class="mze0qaclu"/><path fill="url(#iXU1ree)" class="mze0qaclu"/><path fill="url(#iCNrB2b)" class="mze0qaclu"/><path fill="url(#iZUMEce)" class="mze0qaclu"/><path fill="url(#iuDC4De)" class="mze0qaclu"/><path fill="url(#i684dmb)" class="mze0qaclu"/><path fill="url(#ixwd5wc)" class="mze0qaclu"/><path fill="url(#i4VqW2d)" class="mze0qaclu"/><path fill="url(#iyLgScd)" class="mze0qaclu"/><path fill="url(#i1t2Tfe)" class="lpqrx8dec"/><path fill="url(#iAsXDve)" class="lpqrx8dec"/><path fill="url(#iF1MqBi)" class="lpqrx8dec"/><path fill="url(#ihShVCd)" class="hpl6habja"/><path fill="url(#itvATMc)" class="hpl6habja"/><path fill="url(#iD0rsyb)" class="hpl6habja"/><path fill="url(#idbfgOd)" class="hpl6habja"/><rect class="nrmgy1z2p"/><rect fill="url(#iWZElVc)" class="qz3s_ibbr"/><rect fill="url(#itQ6ZzM)" class="qz3s_ibbr"/><rect class="lf0vi3ftf"/><rect fill="url(#iGvn9pc)" class="quty4wb_t"/><rect fill="url(#iysghKs)" class="quty4wb_t"/><g filter="url(#i9aBsHd)"><ellipse class="tvx_33p0v"/></g><g filter="url(#i57MKbc)"><ellipse class="iiujksbic"/></g><g filter="url(#iINFBfb)"><path fill="url(#iRwiwce)" class="c3jxrmbmo"/></g><defs><linearGradient id="ihESi8b" x1="25.45" x2="22.545" y1="10.069" y2="10.069" gradientUnits="userSpaceOnUse"><stop class="malcizgcg"/><stop offset="1" class="vetkbgbwl"/></linearGradient><linearGradient id="iwLgBkb" x1="6.188" x2="13.28" y1="18.47" y2="18.47" gradientUnits="userSpaceOnUse"><stop class="malcizgcg"/><stop offset="1" class="vetkbgbwl"/></linearGradient><linearGradient id="iTIftCd" x1="24.554" x2="25.511" y1="14.948" y2="14.948" gradientUnits="userSpaceOnUse"><stop class="a8du1nbdc"/><stop offset="1" class="v-2miyn2t"/></linearGradient><linearGradient id="irJ6M7P" x1="24.99" x2="24.99" y1="17" y2="18.96" gradientUnits="userSpaceOnUse"><stop offset=".399" class="ku7au_eyw"/><stop offset="1" class="dw1dk_sdf"/></linearGradient><linearGradient id="iyPeyVc" x1="21.09" x2="22.392" y1="18.96" y2="18.96" gradientUnits="userSpaceOnUse"><stop class="uew8-27kn"/><stop offset="1" class="cc91z6bes"/></linearGradient><linearGradient id="ifZ2rlZ" x1="23.709" x2="23.709" y1="16.506" y2="17.344" gradientUnits="userSpaceOnUse"><stop class="uew8-27kn"/><stop offset="1" class="cc91z6bes"/></linearGradient><linearGradient id="iwYCDmc" x1="21.599" x2="28.006" y1="21.493" y2="21.493" gradientUnits="userSpaceOnUse"><stop class="o22-5b5fg"/><stop offset="1" class="lyvo23rlp"/></linearGradient><linearGradient id="i1MufOb" x1="28.006" x2="27.229" y1="22.167" y2="22.167" gradientUnits="userSpaceOnUse"><stop class="qty7i9yub"/><stop offset="1" class="najh2hcrb"/></linearGradient><linearGradient id="i2n055d" x1="6.494" x2="7.451" y1="22.348" y2="22.348" gradientUnits="userSpaceOnUse"><stop class="a8du1nbdc"/><stop offset="1" class="v-2miyn2t"/></linearGradient><linearGradient id="ijq2qWB" x1="18.562" x2="12.395" y1="23.26" y2="22.489" gradientUnits="userSpaceOnUse"><stop class="faxntnbnm"/><stop offset="1" class="vby7iubti"/></linearGradient><linearGradient id="iXU1ree" x1="18.664" x2="19.555" y1="30.861" y2="21.327" gradientUnits="userSpaceOnUse"><stop class="w995oiyii"/><stop offset="1" class="mpq7-abyy"/></linearGradient><linearGradient id="iZUMEce" x1="15.1" x2="15.1" y1="30.46" y2="29.48" gradientUnits="userSpaceOnUse"><stop class="eblrn9bol"/><stop offset="1" class="lnm0twm4i"/></linearGradient><linearGradient id="i684dmb" x1="21.768" x2="19.809" y1="17.665" y2="17.345" gradientUnits="userSpaceOnUse"><stop class="n_4zlgbml"/><stop offset="1" class="gcnm8wbtw"/></linearGradient><linearGradient id="i1t2Tfe" x1="3.539" x2="9.946" y1="25.493" y2="25.493" gradientUnits="userSpaceOnUse"><stop class="pa6zkt6zb"/><stop offset="1" class="n2-kn-bvp"/></linearGradient><linearGradient id="iAsXDve" x1="4.034" x2="4.654" y1="26.167" y2="26.167" gradientUnits="userSpaceOnUse"><stop class="nh36-ub0g"/><stop offset="1" class="w_jfx-p1u"/></linearGradient><linearGradient id="ihShVCd" x1="6.99" x2="6.99" y1="21" y2="22.96" gradientUnits="userSpaceOnUse"><stop offset=".399" class="zka1ixbor"/><stop offset="1" class="ei50bm_ey"/></linearGradient><linearGradient id="itvATMc" x1="3.09" x2="4.392" y1="22.96" y2="22.96" gradientUnits="userSpaceOnUse"><stop class="vbkfdn0_p"/><stop offset="1" class="ufkpq1b2l"/></linearGradient><linearGradient id="iD0rsyb" x1="5.709" x2="5.709" y1="20.506" y2="21.344" gradientUnits="userSpaceOnUse"><stop class="vbkfdn0_p"/><stop offset="1" class="ufkpq1b2l"/></linearGradient><linearGradient id="idbfgOd" x1="10.89" x2="9.869" y1="21.98" y2="21.98" gradientUnits="userSpaceOnUse"><stop class="o5jgpg3hf"/><stop offset="1" class="vtz21rb8b"/></linearGradient><linearGradient id="iWZElVc" x1="15.526" x2="15.526" y1="27.073" y2="25.62" gradientUnits="userSpaceOnUse"><stop class="g3ex_5z4o"/><stop offset="1" class="m-hoy19io"/></linearGradient><linearGradient id="itQ6ZzM" x1="13.137" x2="11.275" y1="25.023" y2="25.023" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mnym9vbhw"/><stop offset="1" class="els-r4bce"/></linearGradient><linearGradient id="iGvn9pc" x1="17.659" x2="17.659" y1="15.53" y2="14.077" gradientUnits="userSpaceOnUse"><stop class="g3ex_5z4o"/><stop offset="1" class="m-hoy19io"/></linearGradient><linearGradient id="iysghKs" x1="15.27" x2="13.409" y1="13.481" y2="13.481" gradientUnits="userSpaceOnUse"><stop offset=".006" class="mnym9vbhw"/><stop offset="1" class="els-r4bce"/></linearGradient><linearGradient id="iRwiwce" x1="4.313" x2="4.313" y1="10.25" y2="17.469" gradientUnits="userSpaceOnUse"><stop class="gvrclxb-w"/><stop offset="1" class="wd7frwbvj"/></linearGradient><radialGradient id="iqyq0yd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86827 7.44683 -6.47407 -2.4936 29.99 2.408)" gradientUnits="userSpaceOnUse"><stop class="x71cc0g_n"/><stop offset="1" class="j8976wbsw"/></radialGradient><radialGradient id="i8a4hwd" cx="0" cy="0" r="1" gradientTransform="rotate(108.825 15.682 12.026)scale(8.71623 3.91108)" gradientUnits="userSpaceOnUse"><stop class="u9pyy2bwu"/><stop offset="1" class="ft4d5hyca"/></radialGradient><radialGradient id="iXRh49b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.36496 3.37501 -.306 -.12376 29.99 1.469)" gradientUnits="userSpaceOnUse"><stop class="blx06kkwy"/><stop offset="1" class="aaoln0bok"/></radialGradient><radialGradient id="ik7xH6X" cx="0" cy="0" r="1" gradientTransform="matrix(.5625 7.72 -6.74731 .49163 5.625 10.75)" gradientUnits="userSpaceOnUse"><stop class="es73t3b6g"/><stop offset="1" class="ycir1tblk"/></radialGradient><radialGradient id="i1G7QYR" cx="0" cy="0" r="1" gradientTransform="rotate(170.148 13.684 10.076)scale(1.39926 1.33637)" gradientUnits="userSpaceOnUse"><stop class="gn67s1beu"/><stop offset="1" class="o38c5rykb"/></radialGradient><radialGradient id="iCNrB2b" cx="0" cy="0" r="1" gradientTransform="rotate(-84.36 24.121 10.003)scale(13.9437 7.15092)" gradientUnits="userSpaceOnUse"><stop class="q662xm1tq"/><stop offset="1" class="fv_awl7bn"/></radialGradient><radialGradient id="iuDC4De" cx="0" cy="0" r="1" gradientTransform="rotate(163.78 5.745 14.062)scale(5.10381 2.34551)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="z9fw1_jvx"/><stop offset="1" class="iuib-vizb"/></radialGradient><radialGradient id="ixwd5wc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4148 12.66502 -4.87505 -.54458 20.136 4.68)" gradientUnits="userSpaceOnUse"><stop class="efl4ex63r"/><stop offset="1" class="wjh9nh3-k"/></radialGradient><radialGradient id="i4VqW2d" cx="0" cy="0" r="1" gradientTransform="matrix(-5.54697 0 0 -.61633 22.635 5.068)" gradientUnits="userSpaceOnUse"><stop class="ww9264biq"/><stop offset="1" class="nirsmkb6i"/></radialGradient><radialGradient id="iyLgScd" cx="0" cy="0" r="1" gradientTransform="rotate(173.136 8.165 7.672)scale(6.79872 2.63008)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="jqeax-okh"/><stop offset="1" class="cw3fdmorm"/></radialGradient><radialGradient id="iF1MqBi" cx="0" cy="0" r="1" gradientTransform="matrix(-2.43961 0 0 -2.63095 10.777 26.452)" gradientUnits="userSpaceOnUse"><stop class="nh36-ub0g"/><stop offset="1" class="w_jfx-p1u"/></radialGradient><filter id="i9aBsHd" width="7.086" height="2.607" x="15.519" y="11.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_682" stdDeviation=".5"/></filter><filter id="i57MKbc" width="7.086" height="2.607" x="13.272" y="23.417" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_682" stdDeviation=".5"/></filter><filter id="iINFBfb" width="4.563" height="9.219" x="2.031" y="9.25" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_682" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tanabata-tree" /></template>
<style>
.a8du1nbdc {
  stop-color: var(--svg-color--4e4878, #4E4878);
}

.aaoln0bok {
  stop-color: var(--svg-color--9ad966, #9AD966);
  stop-opacity: 0;
}

.akc2r_bli {
  d: path("M29.99 6.54V2.25a.24.24 0 0 0-.25-.243a4.465 4.465 0 0 0-4.21 4.453V11c2.46 0 4.46-2 4.46-4.46");
}

.bj7wzbohv {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M20.88 10.49h4.57");
}

.blx06kkwy {
  stop-color: var(--svg-color--9ad966, #9AD966);
}

.c3jxrmbmo {
  d: path("M5.594 13.094c0-1.825-1.709-2.656-2.563-2.844c1.406 1.125 1.344 2.656 1.344 4.563c0 1.524.813 2.406 1.219 2.656z");
}

.cc91z6bes {
  stop-color: var(--svg-color--ceb03a, #CEB03A);
  stop-opacity: 0;
}

.cw3fdmorm {
  stop-color: var(--svg-color--598445, #598445);
  stop-opacity: 0;
}

.dw1dk_sdf {
  stop-color: var(--svg-color--ffaa52, #FFAA52);
}

.e8q1vqb_d {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M24.99 18.37V9.9");
}

.eblrn9bol {
  stop-color: var(--svg-color--58629a, #58629A);
}

.efl4ex63r {
  stop-color: var(--svg-color--9fdb56, #9FDB56);
}

.ei50bm_ey {
  stop-color: var(--svg-color--f3a563, #F3A563);
}

.ejq4g8uqj {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M13.28 17.97H6.53");
}

.els-r4bce {
  stop-color: var(--svg-color--759c47, #759C47);
}

.es73t3b6g {
  stop-color: var(--svg-color--7ebf41, #7EBF41);
}

.faxntnbnm {
  stop-color: var(--svg-color--89c460, #89C460);
}

.ft4d5hyca {
  stop-color: var(--svg-color--8cce57, #8CCE57);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv_awl7bn {
  stop-color: var(--svg-color--326a70, #326A70);
  stop-opacity: 0;
}

.g3ex_5z4o {
  stop-color: var(--svg-color--879c47, #879C47);
}

.gcnm8wbtw {
  stop-color: var(--svg-color--527c42, #527C42);
  stop-opacity: 0;
}

.gn67s1beu {
  stop-color: var(--svg-color--ffef65, #FFEF65);
}

.gvrclxb-w {
  stop-color: var(--svg-color--8fcb6d, #8FCB6D);
}

.hpl6habja {
  d: path("M9.91 22.96H4.07c-.54 0-.98-.44-.98-.98s.44-.98.98-.98h5.84c.54 0 .98.44.98.98s-.44.98-.98.98");
}

.iiujksbic {
  cx: 16.815px;
  cy: 24.72px;
  fill: var(--svg-color--b8f063, #B8F063);
  rx: 2.543px;
  ry: 0.303px;
}

.iuib-vizb {
  stop-color: var(--svg-color--4c726a, #4C726A);
  stop-opacity: 0;
}

.j8976wbsw {
  stop-color: var(--svg-color--417d65, #417D65);
}

.jf5aeac0r {
  d: path("M27.91 18.96h-5.84c-.54 0-.98-.44-.98-.98s.44-.98.98-.98h5.84c.54 0 .98.44.98.98s-.44.98-.98.98");
}

.jqeax-okh {
  stop-color: var(--svg-color--598445, #598445);
}

.ku7au_eyw {
  stop-color: var(--svg-color--ffd140, #FFD140);
}

.lf0vi3ftf {
  width: 9.063px;
  height: 2.984px;
  x: 13.128px;
  y: 11.989px;
  fill: var(--svg-color--92c52a, #92C52A);
  rx: 1.492px;
}

.lnm0twm4i {
  stop-color: var(--svg-color--58629a, #58629A);
  stop-opacity: 0;
}

.lpqrx8dec {
  d: path("m9.054 30.13l-1.72-1.32a.58.58 0 0 0-.688 0l-1.72 1.32c-.355.27-.892.04-.892-.39v-6.78h5.912v6.78c0 .42-.537.66-.892.39");
}

.lyvo23rlp {
  stop-color: var(--svg-color--ff40a0, #FF40A0);
}

.m-hoy19io {
  stop-color: var(--svg-color--879c47, #879C47);
  stop-opacity: 0;
}

.malcizgcg {
  stop-color: var(--svg-color--408066, #408066);
}

.mnym9vbhw {
  stop-color: var(--svg-color--759c47, #759C47);
  stop-opacity: 0;
}

.mpq7-abyy {
  stop-color: var(--svg-color--64a77d, #64A77D);
  stop-opacity: 0;
}

.mze0qaclu {
  d: path("M22.22 4.68h-6.56c-.2 0-.38.15-.41.35L11 29.52c-.04.26.15.49.41.49h6.56c.2 0 .38-.15.41-.35l4.25-24.49a.417.417 0 0 0-.41-.49");
}

.n_4zlgbml {
  stop-color: var(--svg-color--527c42, #527C42);
}

.n2-kn-bvp {
  stop-color: var(--svg-color--5ab8ff, #5AB8FF);
}

.najh2hcrb {
  stop-color: var(--svg-color--ff75c5, #FF75C5);
  stop-opacity: 0;
}

.nh36-ub0g {
  stop-color: var(--svg-color--4483ff, #4483FF);
}

.nirsmkb6i {
  stop-color: var(--svg-color--a7e55c, #A7E55C);
  stop-opacity: 0;
}

.nrmgy1z2p {
  width: 9.063px;
  height: 2.984px;
  x: 10.995px;
  y: 23.531px;
  fill: var(--svg-color--92c52a, #92C52A);
  rx: 1.492px;
}

.o22-5b5fg {
  stop-color: var(--svg-color--e73467, #E73467);
}

.o38c5rykb {
  stop-color: var(--svg-color--ffef65, #FFEF65);
  stop-opacity: 0;
}

.o5jgpg3hf {
  stop-color: var(--svg-color--ffda5c, #FFDA5C);
}

.pa6zkt6zb {
  stop-color: var(--svg-color--4baaff, #4BAAFF);
}

.q662xm1tq {
  stop-color: var(--svg-color--326a70, #326A70);
}

.qty7i9yub {
  stop-color: var(--svg-color--ff75c5, #FF75C5);
}

.quty4wb_t {
  width: 9.063px;
  height: 2.984px;
  x: 13.128px;
  y: 11.989px;
  rx: 1.492px;
}

.qyln-_i-o {
  d: path("m27.114 26.13l-1.72-1.32a.58.58 0 0 0-.688 0l-1.72 1.32c-.355.27-.892.04-.892-.39v-6.78h5.912v6.78c0 .42-.537.66-.892.39");
}

.qz3s_ibbr {
  width: 9.063px;
  height: 2.984px;
  x: 10.995px;
  y: 23.531px;
  rx: 1.492px;
}

.r_pm-_wcb {
  d: path("M2 14.01V9.47c2.46 0 4.46 2 4.46 4.46v4.54C3.99 18.47 2 16.48 2 14.01");
}

.tvx_33p0v {
  cx: 19.062px;
  cy: 13.178px;
  fill: var(--svg-color--b8f063, #B8F063);
  rx: 2.543px;
  ry: 0.303px;
}

.u9pyy2bwu {
  stop-color: var(--svg-color--8cce57, #8CCE57);
}

.uew8-27kn {
  stop-color: var(--svg-color--ceb03a, #CEB03A);
}

.ufkpq1b2l {
  stop-color: var(--svg-color--cd9a38, #CD9A38);
  stop-opacity: 0;
}

.v-2miyn2t {
  stop-color: var(--svg-color--7c6da1, #7C6DA1);
}

.vbkfdn0_p {
  stop-color: var(--svg-color--cd9a38, #CD9A38);
}

.vby7iubti {
  stop-color: var(--svg-color--538249, #538249);
}

.vetkbgbwl {
  stop-color: var(--svg-color--5c8939, #5C8939);
}

.vtz21rb8b {
  stop-color: var(--svg-color--ffda5c, #FFDA5C);
  stop-opacity: 0;
}

.w_jfx-p1u {
  stop-color: var(--svg-color--4483ff, #4483FF);
  stop-opacity: 0;
}

.w995oiyii {
  stop-color: var(--svg-color--64a77d, #64A77D);
}

.wd7frwbvj {
  stop-color: var(--svg-color--8fcb6d, #8FCB6D);
  stop-opacity: 0;
}

.wjh9nh3-k {
  stop-color: var(--svg-color--9fdb56, #9FDB56);
  stop-opacity: 0;
}

.ww9264biq {
  stop-color: var(--svg-color--a7e55c, #A7E55C);
}

.x71cc0g_n {
  stop-color: var(--svg-color--73ba35, #73BA35);
}

.ycir1tblk {
  stop-color: var(--svg-color--3f7876, #3F7876);
}

.ylz13cckx {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("M6.93 25.77V17.3");
}

.z9fw1_jvx {
  stop-color: var(--svg-color--4c726a, #4C726A);
}

.zka1ixbor {
  stop-color: var(--svg-color--f4c739, #F4C739);
}

</style>
