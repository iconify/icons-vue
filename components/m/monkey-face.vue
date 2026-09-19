<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iA8aGze)" class="r1_szvbbw"/><path fill="url(#i77LwoW)" class="r1_szvbbw"/><path fill="url(#ipju3td)" class="lulizn0um"/><path fill="url(#iGDyyld)" class="pk_jp2bwt"/><g filter="url(#iFirPIz)"><path stroke="url(#iKePTWI)" class="mfk7-_3sv"/></g><path fill="url(#iQq3tSd)" class="e1qaz5b8v"/><path fill="url(#isE43Wb)" class="e1qaz5b8v"/><path fill="url(#iT85ukc)" class="e1qaz5b8v"/><path fill="url(#igNgqEd)" class="e1qaz5b8v"/><g filter="url(#iDTJOmc)"><ellipse transform="rotate(-23.4 23.418 12.94)" class="xnbxhopvn"/></g><g filter="url(#iHQbP5d)"><ellipse transform="rotate(-90 15.773 6.97)" class="eo0mbemcd"/></g><g filter="url(#iCjdzRn)"><path class="hfquubb5o"/></g><path fill="url(#infPzTc)" class="gj5gvmb8m"/><path fill="url(#iYU1YFN)" class="gj5gvmb8m"/><path fill="url(#igsoRce)" class="gj5gvmb8m"/><g filter="url(#iNDyC7J)"><path stroke="url(#iDDJLVd)" class="iyxk9y5xv"/></g><g filter="url(#iZOHcep)"><path stroke="url(#irO5UPc)" class="ffl8wpbok"/></g><g filter="url(#iSoqQwd)"><path stroke="url(#iTQ4dMd)" class="b7fmzm90x"/></g><g filter="url(#iV1RJdd)"><path stroke="url(#i9Q2gzZ)" class="pmnhf4apd"/></g><path fill="url(#iu2tcYd)" class="zbe-frb9m"/><g filter="url(#iWVKarc)"><rect class="p4to4qwoz"/></g><g filter="url(#i7A3wdd)"><rect class="tuntximzk"/></g><rect fill="url(#iacVnQe)" class="qc6f6xbnc"/><rect fill="url(#i4YI1Sb)" class="qc6f6xbnc"/><rect fill="url(#irqbu3B)" class="jvun_3unq"/><rect fill="url(#ievSTjb)" class="jvun_3unq"/><g filter="url(#iqSJWhd)"><rect class="oqb3ddb4k"/></g><rect fill="url(#iBsDqvd)" class="cdmtufb8e"/><rect fill="url(#iBO2bKe)" class="cdmtufb8e"/><circle fill="url(#iRRFGco)" class="f8zr0eo3i"/><circle fill="url(#ird5VYd)" class="nufwklshi"/><g filter="url(#iHooEpZ)"><path stroke="url(#iLgMece)" class="imelqgbol"/></g><g filter="url(#imKD1QA)"><circle class="al4hvcbas"/></g><g filter="url(#iAzfuEl)"><circle class="em4hdktwd"/></g><defs><linearGradient id="iA8aGze" x1="6.516" x2="6.516" y1="13.205" y2="24.143" gradientUnits="userSpaceOnUse"><stop class="ck7f4woko"/><stop offset="1" class="eiejd2bux"/></linearGradient><linearGradient id="i77LwoW" x1="6.516" x2="6.516" y1="16.455" y2="24.643" gradientUnits="userSpaceOnUse"><stop class="ua19fnf6s"/><stop offset="1" class="qb49ptbxt"/></linearGradient><linearGradient id="iGDyyld" x1="25.433" x2="25.433" y1="14.393" y2="24.643" gradientUnits="userSpaceOnUse"><stop offset=".094" class="i3zfssahs"/><stop offset="1" class="tklvtbcin"/></linearGradient><linearGradient id="isE43Wb" x1="16" x2="16" y1="17.425" y2="34.282" gradientUnits="userSpaceOnUse"><stop class="m4eoz0qca"/><stop offset="1" class="qt5w41b2y"/></linearGradient><linearGradient id="infPzTc" x1="16" x2="16" y1="8.901" y2="26.948" gradientUnits="userSpaceOnUse"><stop class="yrar24m3w"/><stop offset=".188" class="i3zfssahs"/><stop offset=".895" class="ppkfmqblg"/></linearGradient><linearGradient id="iDDJLVd" x1="6.647" x2="4.184" y1="23.584" y2="10.914" gradientUnits="userSpaceOnUse"><stop class="p9uo3pblo"/><stop offset=".503" class="qf38a13vx"/><stop offset="1" class="p9uo3pblo"/></linearGradient><linearGradient id="irO5UPc" x1="24.978" x2="28.269" y1="22.955" y2="15.014" gradientUnits="userSpaceOnUse"><stop class="v3_xnsbbc"/><stop offset=".296" class="oi7ddwbfc"/><stop offset=".808" class="v3_xnsbbc"/></linearGradient><linearGradient id="iTQ4dMd" x1="24.528" x2="20.916" y1="14.832" y2="9.414" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".557" class="mebto9quo"/><stop offset="1" class="g-3jcm1lb"/></linearGradient><linearGradient id="i9Q2gzZ" x1="22.767" x2="22.087" y1="22.709" y2="18.635" gradientUnits="userSpaceOnUse"><stop offset=".026" class="g-3jcm1lb"/><stop offset="1" class="mebto9quo"/></linearGradient><linearGradient id="iacVnQe" x1="15.851" x2="11.505" y1="14.479" y2="14.479" gradientUnits="userSpaceOnUse"><stop class="dcdi0_bfz"/><stop offset=".568" class="ixqsitb8q"/><stop offset=".766" class="whjaerb5v"/></linearGradient><linearGradient id="i4YI1Sb" x1="13.344" x2="13.344" y1="14.319" y2="16.675" gradientUnits="userSpaceOnUse"><stop offset=".327" class="n7wvbnb3x"/><stop offset="1" class="whjaerb5v"/></linearGradient><linearGradient id="irqbu3B" x1="21.845" x2="17.499" y1="14.479" y2="14.479" gradientUnits="userSpaceOnUse"><stop class="dcdi0_bfz"/><stop offset=".568" class="ixqsitb8q"/><stop offset=".766" class="whjaerb5v"/></linearGradient><linearGradient id="ievSTjb" x1="19.337" x2="19.337" y1="14.319" y2="16.675" gradientUnits="userSpaceOnUse"><stop offset=".327" class="n7wvbnb3x"/><stop offset="1" class="whjaerb5v"/></linearGradient><linearGradient id="iBsDqvd" x1="16" x2="16" y1="16.387" y2="18.526" gradientUnits="userSpaceOnUse"><stop class="sq6bhdbbn"/><stop offset="1" class="p6w626lsj"/></linearGradient><linearGradient id="iBO2bKe" x1="15.493" x2="14.753" y1="21.323" y2="17.707" gradientUnits="userSpaceOnUse"><stop offset=".07" class="xh0ps3bnm"/><stop offset="1" class="oiv2fhbci"/></linearGradient><linearGradient id="iLgMece" x1="17.68" x2="17.68" y1="16.991" y2="17.713" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".349" class="vpk0l0bon"/></linearGradient><filter id="iFirPIz" width="4.75" height="9.763" x="26.187" y="11.748" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".2"/></filter><filter id="iDTJOmc" width="11.833" height="15.089" x="17.501" y="5.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation="1.75"/></filter><filter id="iHQbP5d" width="13.127" height="7.772" x="9.21" y="3.085" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation="1.75"/></filter><filter id="iCjdzRn" width="21.122" height="21.129" x="5.118" y="7.148" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation="1"/></filter><filter id="iNDyC7J" width="3.023" height="13.73" x="3.818" y="10.025" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".2"/></filter><filter id="iZOHcep" width="2.477" height="11.2" x="25.57" y="12.355" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".2"/></filter><filter id="iSoqQwd" width="4.02" height="7.085" x="20.82" y="8.916" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".2"/></filter><filter id="iV1RJdd" width="2.619" height="6.931" x="20.97" y="16.81" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".2"/></filter><filter id="iWVKarc" width="3.625" height="5.25" x="10.681" y="12.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".5"/></filter><filter id="i7A3wdd" width="3.625" height="5.25" x="16.857" y="12.541" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".5"/></filter><filter id="iqSJWhd" width="7.344" height="4.418" x="12.102" y="15.791" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".5"/></filter><filter id="iHooEpZ" width="1.305" height="1.15" x="17.038" y="16.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".1"/></filter><filter id="imKD1QA" width="2.567" height="2.567" x="17.915" y="12.73" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".5"/></filter><filter id="iAzfuEl" width="2.567" height="2.567" x="11.987" y="12.874" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1406" stdDeviation=".5"/></filter><radialGradient id="ipju3td" cx="0" cy="0" r="1" gradientTransform="matrix(-11.25001 -11.12504 13.27885 -13.42801 10.385 23.08)" gradientUnits="userSpaceOnUse"><stop offset=".632" class="tbqmcsbon"/><stop offset="1" class="d91dz_s7m"/></radialGradient><radialGradient id="iKePTWI" cx="0" cy="0" r="1" gradientTransform="matrix(-5.49997 -6.31252 13.2979 -11.5862 29.02 20.549)" gradientUnits="userSpaceOnUse"><stop class="g-3jcm1lb"/><stop offset=".448" class="mebto9quo"/><stop offset="1" class="g-3jcm1lb"/></radialGradient><radialGradient id="iQq3tSd" cx="0" cy="0" r="1" gradientTransform="matrix(-10.93739 18.417 -32.63847 -19.38316 24.26 10.955)" gradientUnits="userSpaceOnUse"><stop class="lyklk88ly"/><stop offset="1" class="j823ctb-q"/></radialGradient><radialGradient id="iT85ukc" cx="0" cy="0" r="1" gradientTransform="matrix(0 20.6725 -18.4611 0 16 14.439)" gradientUnits="userSpaceOnUse"><stop offset=".688" class="qudiit10p"/><stop offset="1" class="yw57-9naf"/></radialGradient><radialGradient id="igNgqEd" cx="0" cy="0" r="1" gradientTransform="rotate(123.75 9.128 11.177)scale(19.0483)" gradientUnits="userSpaceOnUse"><stop class="zbcxugb8k"/><stop offset="1" class="rtp-u7bcg"/></radialGradient><radialGradient id="iYU1YFN" cx="0" cy="0" r="1" gradientTransform="rotate(159.382 11.532 8.463)scale(20.2335 27.146)" gradientUnits="userSpaceOnUse"><stop offset=".818" class="ovqobxb3d"/><stop offset="1" class="kt15-irns"/></radialGradient><radialGradient id="igsoRce" cx="0" cy="0" r="1" gradientTransform="matrix(-.00069 12.7039 -10.8463 -.00059 16 15.396)" gradientUnits="userSpaceOnUse"><stop offset=".813" class="t9ynm6bcv"/><stop offset="1" class="iedbks3oi"/></radialGradient><radialGradient id="iu2tcYd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -9.07087 17.6698 0 16.653 25.203)" gradientUnits="userSpaceOnUse"><stop class="oitppsb9f"/><stop offset=".548" class="di9ro-btr"/></radialGradient><radialGradient id="iRRFGco" cx="0" cy="0" r="1" gradientTransform="rotate(133.174 3.654 11.999)scale(1.90311 1.14415)" gradientUnits="userSpaceOnUse"><stop class="sf_wn9jlw"/><stop offset="1" class="ixqsitb8q"/></radialGradient><radialGradient id="ird5VYd" cx="0" cy="0" r="1" gradientTransform="matrix(-.774 .94202 -1.47397 -1.21107 17.608 17.544)" gradientUnits="userSpaceOnUse"><stop class="go-58hbeq"/><stop offset="1" class="ixqsitb8q"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:monkey-face" /></template>
<style>
.al4hvcbas {
  cx: 19.199px;
  cy: 14.014px;
  r: 0.284px;
  fill: var(--svg-color--795d72, #795D72);
}

.b7fmzm90x {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M21.42 9.516c1.296.509 3.69 2.495 2.495 5.884");
}

.cdmtufb8e {
  width: 4.891px;
  height: 2.232px;
  x: 13.555px;
  y: 16.387px;
  rx: 1.116px;
}

.ck7f4woko {
  stop-color: var(--svg-color--a67874, #A67874);
}

.d91dz_s7m {
  stop-color: var(--svg-color--f39585, #F39585);
}

.dcdi0_bfz {
  stop-color: var(--svg-color--432a3d, #432A3D);
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.e1qaz5b8v {
  d: path("M16 29.372c7.966 0 11.947-5.349 11.947-11.947S23.967 5.478 16 5.478S4.053 10.827 4.053 17.425S8.033 29.372 16 29.372");
}

.eiejd2bux {
  stop-color: var(--svg-color--8f5872, #8F5872);
}

.em4hdktwd {
  cx: 13.271px;
  cy: 14.158px;
  r: 0.284px;
  fill: var(--svg-color--795d72, #795D72);
}

.eo0mbemcd {
  cx: 15.773px;
  cy: 6.971px;
  fill: var(--svg-color--c58e7d, #C58E7D);
  rx: 0.386px;
  ry: 3.064px;
}

.f8zr0eo3i {
  cx: 14.549px;
  cy: 17.904px;
  r: 0.512px;
}

.ffl8wpbok {
  stroke-linecap: round;
  stroke-opacity: 0.5;
  stroke-width: var(--svg-stroke-width--0-4px, 0.4px);
  d: path("M26.92 12.955c.83 3.28.75 7.563-.75 10");
}

.ft5dv1b6b {
  fill: none;
}

.g-3jcm1lb {
  stop-color: var(--svg-color--ffdacc, #FFDACC);
  stop-opacity: 0;
}

.gj5gvmb8m {
  d: path("M12.156 8.9a4.813 4.813 0 0 0-3.692 7.9a.55.55 0 0 1 .122.458a7.547 7.547 0 1 0 14.828 0a.55.55 0 0 1 .122-.458a4.812 4.812 0 0 0-3.692-7.9z");
}

.go-58hbeq {
  stop-color: var(--svg-color--3c2737, #3C2737);
}

.hfquubb5o {
  fill: var(--svg-color--561e25, #561E25);
  d: path("M11.877 9.148a4.76 4.76 0 0 0-3.653 7.81a.56.56 0 0 1 .122.459q-.13.68-.131 1.397a7.464 7.464 0 1 0 14.797-1.398a.55.55 0 0 1 .121-.457a4.76 4.76 0 0 0-3.653-7.81z");
}

.i3zfssahs {
  stop-color: var(--svg-color--fab8a9, #FAB8A9);
}

.iedbks3oi {
  stop-color: var(--svg-color--ff63c4, #FF63C4);
}

.imelqgbol {
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("M17.243 17.002c.344-.07.82.188.875.711");
}

.ixqsitb8q {
  stop-color: var(--svg-color--684e61, #684E61);
}

.iyxk9y5xv {
  stroke-linecap: round;
  stroke-opacity: 0.4;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M5.71 10.825c-1.593 3.93-1.411 9.682.33 12.13");
}

.j823ctb-q {
  stop-color: var(--svg-color--5b3838, #5B3838);
}

.jvun_3unq {
  width: 1.508px;
  height: 3.016px;
  x: 18.243px;
  y: 13.386px;
  rx: 0.754px;
}

.kt15-irns {
  stop-color: var(--svg-color--a55f89, #A55F89);
}

.lulizn0um {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M6.516 22.424c3.029 0 5.484-2.417 5.484-5.399c0-2.981-2.455-5.398-5.484-5.398S1.03 14.044 1.03 17.025c0 2.982 2.456 5.399 5.485 5.399");
}

.lyklk88ly {
  stop-color: var(--svg-color--a06857, #A06857);
}

.m4eoz0qca {
  stop-color: var(--svg-color--682b5b, #682B5B);
  stop-opacity: 0;
}

.mebto9quo {
  stop-color: var(--svg-color--ffdacc, #FFDACC);
}

.mfk7-_3sv {
  stroke-linecap: round;
  stroke-opacity: 0.8;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M26.837 12.398c.98.148 2.874 1.438 3.293 3.51c.484 1.781-.172 4.063-1.672 4.953");
}

.n7wvbnb3x {
  stop-color: var(--svg-color--43253d, #43253D);
  stop-opacity: 0;
}

.nufwklshi {
  cx: 17.346px;
  cy: 17.904px;
  r: 0.512px;
}

.oi7ddwbfc {
  stop-color: var(--svg-color--be8b89, #BE8B89);
  stop-opacity: 0.6;
}

.oitppsb9f {
  stop-color: var(--svg-color--ef0084, #EF0084);
}

.oiv2fhbci {
  stop-color: var(--svg-color--dc90cc, #DC90CC);
  stop-opacity: 0;
}

.oqb3ddb4k {
  width: 5.344px;
  height: 2.418px;
  x: 13.102px;
  y: 16.791px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  rx: 1.116px;
}

.ovqobxb3d {
  stop-color: var(--svg-color--a55f89, #A55F89);
  stop-opacity: 0;
}

.p4to4qwoz {
  width: 1.625px;
  height: 3.25px;
  x: 11.681px;
  y: 13.541px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.813px;
}

.p6w626lsj {
  stop-color: var(--svg-color--dc89a8, #DC89A8);
}

.p9uo3pblo {
  stop-color: var(--svg-color--7c6160, #7C6160);
  stop-opacity: 0;
}

.pk_jp2bwt {
  d: path("M25.433 22.424c3.029 0 5.484-2.417 5.484-5.399c0-2.981-2.455-5.398-5.484-5.398s-5.485 2.417-5.485 5.398c0 2.982 2.456 5.399 5.485 5.399");
}

.pmnhf4apd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M23.013 17.26c.5 2.938-.593 5.125-1.593 6.031");
}

.ppkfmqblg {
  stop-color: var(--svg-color--ac628e, #AC628E);
}

.qb49ptbxt {
  stop-color: var(--svg-color--ca6fa6, #CA6FA6);
}

.qc6f6xbnc {
  width: 1.508px;
  height: 3.016px;
  x: 12.249px;
  y: 13.386px;
  rx: 0.754px;
}

.qf38a13vx {
  stop-color: var(--svg-color--7c6160, #7C6160);
}

.qt5w41b2y {
  stop-color: var(--svg-color--682b5b, #682B5B);
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r1_szvbbw {
  d: path("M6.516 22.424c3.029 0 5.484-2.417 5.484-5.399c0-2.981-2.455-5.398-5.484-5.398S1.03 14.044 1.03 17.025c0 2.982 2.456 5.399 5.485 5.399");
}

.rtp-u7bcg {
  stop-color: var(--svg-color--a9705e, #A9705E);
  stop-opacity: 0;
}

.sf_wn9jlw {
  stop-color: var(--svg-color--3e2739, #3E2739);
}

.sq6bhdbbn {
  stop-color: var(--svg-color--e9a4a2, #E9A4A2);
}

.t9ynm6bcv {
  stop-color: var(--svg-color--ef5cf2, #EF5CF2);
  stop-opacity: 0;
}

.tbqmcsbon {
  stop-color: var(--svg-color--f39585, #F39585);
  stop-opacity: 0;
}

.tklvtbcin {
  stop-color: var(--svg-color--b56595, #B56595);
}

.tuntximzk {
  width: 1.625px;
  height: 3.25px;
  x: 17.857px;
  y: 13.541px;
  fill: var(--svg-color--bb6f89, #BB6F89);
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 0.813px;
}

.ua19fnf6s {
  stop-color: var(--svg-color--b56595, #B56595);
  stop-opacity: 0;
}

.v3_xnsbbc {
  stop-color: var(--svg-color--be8b89, #BE8B89);
  stop-opacity: 0;
}

.vpk0l0bon {
  stop-color: var(--svg-color--ffebe3, #FFEBE3);
}

.whjaerb5v {
  stop-color: var(--svg-color--43253d, #43253D);
}

.xh0ps3bnm {
  stop-color: var(--svg-color--c971b6, #C971B6);
}

.xnbxhopvn {
  cx: 23.418px;
  cy: 12.94px;
  fill: var(--svg-color--c58e7d, #C58E7D);
  rx: 1.849px;
  ry: 4.333px;
}

.yrar24m3w {
  stop-color: var(--svg-color--ffc8bc, #FFC8BC);
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.zbcxugb8k {
  stop-color: var(--svg-color--a9705e, #A9705E);
}

.zbe-frb9m {
  d: path("M12.006 20.406c0 2.296 1.649 4.005 3.994 4.005c2.523 0 3.994-1.782 3.994-4.005z");
}

</style>
