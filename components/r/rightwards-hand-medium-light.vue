<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDgJJeb)"><path class="tbghklb3h"/><path fill="url(#iPEET3b)" class="nydovgb3n"/><path fill="url(#ikUXUGc)" class="nydovgb3n"/></g><path fill="url(#iMwBEsb)" class="ktbkdyb2r"/><g filter="url(#iabkhpe)"><path fill="url(#iIR17jc)" class="ml5zpzp8m"/></g><path fill="url(#ij0KlCe)" class="olyg7gbdo"/><path fill="url(#ibwRMKR)" class="olyg7gbdo"/><path fill="url(#itpNWhT)" class="olyg7gbdo"/><path fill="url(#iDli5ab)" class="olyg7gbdo"/><path fill="url(#iNOEUmd)" class="olyg7gbdo"/><g filter="url(#i8l9D1d)"><path class="dc8-ntdhu"/></g><path fill="url(#iqRLkOe)" class="puoda7b1n"/><path fill="url(#ieeZFHc)" class="puoda7b1n"/><path fill="url(#iNWDiLq)" class="puoda7b1n"/><path fill="url(#icZ2brb)" class="puoda7b1n"/><g filter="url(#icgN1Lb)"><path fill="url(#ioJXTAe)" class="ldzl_vb_b"/></g><path fill="url(#iX37kFe)" class="e_4z8xbvr"/><path fill="url(#i5oFYuG)" class="e_4z8xbvr"/><path fill="url(#iOU2BOb)" class="e_4z8xbvr"/><path fill="url(#iliG7ib)" class="e_4z8xbvr"/><g filter="url(#iRERZWp)"><path fill="url(#i21XpIc)" class="o5oh4imtv"/></g><path fill="url(#iZUOl3u)" class="nydovgb3n"/><path fill="url(#ioc2uzw)" class="nydovgb3n"/><path fill="url(#iRqaUHc)" class="nydovgb3n"/><path fill="url(#iskaQvb)" class="nydovgb3n"/><path fill="url(#iqfcxhj)" class="nydovgb3n"/><path fill="url(#ipHrhie)" class="nydovgb3n"/><g filter="url(#iEZJnUd)"><path fill="url(#iuN1Kfc)" class="pw36wubqc"/></g><path fill="url(#ijKGWtb)" class="yes9llscm"/><path fill="url(#iAulrSd)" class="yes9llscm"/><path fill="url(#idCDW2h)" class="yes9llscm"/><g filter="url(#iCn1TPc)"><path fill="url(#ixKZ6Od)" class="cab3jgbnd"/></g><defs><linearGradient id="iIR17jc" x1="18.414" x2="11.624" y1="6.012" y2="10.321" gradientUnits="userSpaceOnUse"><stop class="h23j5l7wg"/><stop offset="1" class="iqtd7_e4j"/></linearGradient><linearGradient id="ij0KlCe" x1="20.155" x2="20.267" y1="8.639" y2="10.689" gradientUnits="userSpaceOnUse"><stop class="a61ui5bws"/><stop offset="1" class="i7h39qb_i"/></linearGradient><linearGradient id="ibwRMKR" x1="20.939" x2="20.924" y1="13.664" y2="12.679" gradientUnits="userSpaceOnUse"><stop class="ecqussste"/><stop offset="1" class="oi3x9iuvd"/></linearGradient><linearGradient id="iDli5ab" x1="15.221" x2="17.221" y1="11.11" y2="10.492" gradientUnits="userSpaceOnUse"><stop offset=".236" class="qj6gmdbak"/><stop offset="1" class="fqq1wfb3b"/></linearGradient><linearGradient id="iqRLkOe" x1="22.111" x2="22.164" y1="12.335" y2="15.414" gradientUnits="userSpaceOnUse"><stop class="t5m624b_w"/><stop offset="1" class="c38bebani"/></linearGradient><linearGradient id="iNWDiLq" x1="22.485" x2="22.485" y1="18.517" y2="17.31" gradientUnits="userSpaceOnUse"><stop class="xtkuzf2ei"/><stop offset="1" class="eizovsb1f"/></linearGradient><linearGradient id="icZ2brb" x1="14.924" x2="17.855" y1="14.867" y2="15.071" gradientUnits="userSpaceOnUse"><stop class="qj6gmdbak"/><stop offset="1" class="fqq1wfb3b"/></linearGradient><linearGradient id="ioJXTAe" x1="29.845" x2="23.682" y1="17.17" y2="25.801" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></linearGradient><linearGradient id="iX37kFe" x1="21.177" x2="21.229" y1="17.238" y2="20.023" gradientUnits="userSpaceOnUse"><stop class="lf7vr6vni"/><stop offset="1" class="a1pfh5noq"/></linearGradient><linearGradient id="i5oFYuG" x1="21.149" x2="21.139" y1="23.152" y2="21.681" gradientUnits="userSpaceOnUse"><stop class="r8e3pjzpw"/><stop offset="1" class="kpujw3iqu"/></linearGradient><linearGradient id="iOU2BOb" x1="16.111" x2="18.85" y1="19.054" y2="19.583" gradientUnits="userSpaceOnUse"><stop class="qj6gmdbak"/><stop offset="1" class="fqq1wfb3b"/></linearGradient><linearGradient id="i21XpIc" x1="26.549" x2="12.986" y1="21.443" y2="21.443" gradientUnits="userSpaceOnUse"><stop class="chfuwtbnr"/><stop offset="1" class="kr0fi1udo"/></linearGradient><linearGradient id="iZUOl3u" x1="9.401" x2="9.401" y1="26.953" y2="21.599" gradientUnits="userSpaceOnUse"><stop class="lbtd6zbkm"/><stop offset="1" class="ubibb2bhq"/></linearGradient><linearGradient id="iuN1Kfc" x1="15.869" x2="15.975" y1="26.794" y2="23.825" gradientUnits="userSpaceOnUse"><stop class="l_r-rkb0i"/><stop offset="1" class="prsh4r1dj"/></linearGradient><linearGradient id="ijKGWtb" x1="19.391" x2="19.145" y1="21.325" y2="23.651" gradientUnits="userSpaceOnUse"><stop class="oi7g8dknq"/><stop offset="1" class="le_j5cb3p"/></linearGradient><linearGradient id="iAulrSd" x1="15.049" x2="18.542" y1="23.968" y2="24.158" gradientUnits="userSpaceOnUse"><stop class="yvwph9bfk"/><stop offset="1" class="dl3-s1bsu"/></linearGradient><linearGradient id="ixKZ6Od" x1="23.477" x2="9.916" y1="25.624" y2="25.376" gradientUnits="userSpaceOnUse"><stop class="zw1k0-prr"/><stop offset="1" class="g6mty-b8t"/></linearGradient><radialGradient id="iPEET3b" cx="0" cy="0" r="1" gradientTransform="matrix(2.62497 5.12502 -18.39164 9.41998 4.924 9.086)" gradientUnits="userSpaceOnUse"><stop class="h1sgtxtqh"/><stop offset="1" class="uo_inwq3m"/></radialGradient><radialGradient id="ikUXUGc" cx="0" cy="0" r="1" gradientTransform="rotate(169.33 9.706 3.672)scale(2.48176 3.91796)" gradientUnits="userSpaceOnUse"><stop class="aflb6lbgt"/><stop offset="1" class="l02kk_bos"/></radialGradient><radialGradient id="iMwBEsb" cx="0" cy="0" r="1" gradientTransform="matrix(-.7422 -1.1133 3.24362 -2.1624 16.611 9.724)" gradientUnits="userSpaceOnUse"><stop class="h41yutqjs"/><stop offset="1" class="uxe06abat"/></radialGradient><radialGradient id="itpNWhT" cx="0" cy="0" r="1" gradientTransform="rotate(-112.681 17.902 -2.161)scale(1.13462 1.78724)" gradientUnits="userSpaceOnUse"><stop class="z_uwteb1p"/><stop offset="1" class="zaw1ewbji"/></radialGradient><radialGradient id="iNOEUmd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.36578 1.14881 -2.17622 -4.48155 27.964 9.961)" gradientUnits="userSpaceOnUse"><stop class="eenwi56gr"/><stop offset="1" class="xaai3vbav"/></radialGradient><radialGradient id="ieeZFHc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.08638 1.14425 -2.31876 -4.22794 29.983 14.242)" gradientUnits="userSpaceOnUse"><stop class="a94a7rh-y"/><stop offset="1" class="zshydrbec"/></radialGradient><radialGradient id="iliG7ib" cx="0" cy="0" r="1" gradientTransform="matrix(-1.354 .79135 -1.24433 -2.12908 27.75 18.962)" gradientUnits="userSpaceOnUse"><stop class="w14svvb0t"/><stop offset="1" class="qyy62abgt"/></radialGradient><radialGradient id="ioc2uzw" cx="0" cy="0" r="1" gradientTransform="matrix(2.2675 -.1875 .14684 1.77572 16 12.304)" gradientUnits="userSpaceOnUse"><stop class="kw5vl0jtb"/><stop offset="1" class="p0p4x4g6v"/></radialGradient><radialGradient id="iRqaUHc" cx="0" cy="0" r="1" gradientTransform="matrix(2.17374 -.09375 .08645 2.00449 16 17.023)" gradientUnits="userSpaceOnUse"><stop class="kw5vl0jtb"/><stop offset="1" class="p0p4x4g6v"/></radialGradient><radialGradient id="iskaQvb" cx="0" cy="0" r="1" gradientTransform="rotate(-1.909 634.996 -462.71)scale(1.87604)" gradientUnits="userSpaceOnUse"><stop class="kw5vl0jtb"/><stop offset="1" class="p0p4x4g6v"/></radialGradient><radialGradient id="iqfcxhj" cx="0" cy="0" r="1" gradientTransform="matrix(1.06249 -2.12498 2.79983 1.39991 15.518 24.43)" gradientUnits="userSpaceOnUse"><stop class="kw5vl0jtb"/><stop offset="1" class="p0p4x4g6v"/></radialGradient><radialGradient id="ipHrhie" cx="0" cy="0" r="1" gradientTransform="rotate(62.242 -1.93 11.897)scale(3.03562 12.0503)" gradientUnits="userSpaceOnUse"><stop class="dogyjmbix"/><stop offset="1" class="h1t291b3h"/></radialGradient><radialGradient id="idCDW2h" cx="0" cy="0" r="1" gradientTransform="rotate(154.485 10.074 14.383)scale(1.95209 5.21489)" gradientUnits="userSpaceOnUse"><stop class="w-t4tqbjy"/><stop offset="1" class="holmj9bgg"/></radialGradient><filter id="iDgJJeb" width="27.965" height="24.039" x="2.017" y="2.528" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-1"/><feGaussianBlur stdDeviation="1.25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.729412 0 0 0 0 0.454902 0 0 0 0 0.541176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_6505"/></filter><filter id="iabkhpe" width="7.823" height="5.458" x="11.832" y="4.512" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6505" stdDeviation=".375"/></filter><filter id="i8l9D1d" width="12.102" height="3.414" x="15.398" y="10.32" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6505" stdDeviation=".5"/></filter><filter id="icgN1Lb" width="15.808" height="4.064" x="14.438" y="14.453" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6505" stdDeviation=".5"/></filter><filter id="iRERZWp" width="13.094" height="3.555" x="14.455" y="19.233" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6505" stdDeviation=".5"/></filter><filter id="iEZJnUd" width="21.827" height="6.11" x="3.418" y="21.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6505" stdDeviation=".5"/></filter><filter id="iCn1TPc" width="13.092" height="3.521" x="11.391" y="23.389" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_6505" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rightwards-hand-medium-light" /></template>
<style>
.a1pfh5noq {
  stop-color: var(--svg-color--d89671, #D89671);
  stop-opacity: 0;
}

.a61ui5bws {
  stop-color: var(--svg-color--bd8465, #BD8465);
}

.a94a7rh-y {
  stop-color: var(--svg-color--c79a78, #C79A78);
}

.aflb6lbgt {
  stop-color: var(--svg-color--c99f80, #C99F80);
}

.c38bebani {
  stop-color: var(--svg-color--c68869, #C68869);
  stop-opacity: 0;
}

.cab3jgbnd {
  d: path("M23.483 25.248a.673.673 0 0 0-.664-.688c-2.142-.026-7.103-.092-9.627-.17c-.433-.014-.794.282-.8.659c-.007.37.333.677.76.684l9.644.177c.373.007.68-.29.687-.663");
}

.chfuwtbnr {
  stop-color: var(--svg-color--fcc9a8, #FCC9A8);
}

.dc8-ntdhu {
  fill: var(--svg-color--ecb99e, #ECB99E);
  d: path("m25.882 11.32l-9.484.13l.189 1.284l9.316-.194a.61.61 0 0 0-.021-1.22");
}

.dl3-s1bsu {
  stop-color: var(--svg-color--efba9a, #EFBA9A);
  stop-opacity: 0;
}

.dogyjmbix {
  stop-color: var(--svg-color--c88c7e, #C88C7E);
}

.e_4z8xbvr {
  d: path("m26.705 18.042l-12.156-.02v4.188l9.383.197l-.002-.002l1.37.026a2.406 2.406 0 0 0 1.405-4.39");
}

.ecqussste {
  stop-color: var(--svg-color--cc8e6e, #CC8E6E);
}

.eenwi56gr {
  stop-color: var(--svg-color--c89d7c, #C89D7C);
}

.eizovsb1f {
  stop-color: var(--svg-color--db9b77, #DB9B77);
  stop-opacity: 0;
}

.fqq1wfb3b {
  stop-color: var(--svg-color--e7ad97, #E7AD97);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g6mty-b8t {
  stop-color: var(--svg-color--fecea7, #FECEA7);
  stop-opacity: 0;
}

.h1sgtxtqh {
  stop-color: var(--svg-color--c98f80, #C98F80);
}

.h1t291b3h {
  stop-color: var(--svg-color--c88c7e, #C88C7E);
  stop-opacity: 0;
}

.h23j5l7wg {
  stop-color: var(--svg-color--eeb99a, #EEB99A);
}

.h41yutqjs {
  stop-color: var(--svg-color--a9775c, #A9775C);
}

.holmj9bgg {
  stop-color: var(--svg-color--ce9e7b, #CE9E7B);
  stop-opacity: 0;
}

.i7h39qb_i {
  stop-color: var(--svg-color--bd8465, #BD8465);
  stop-opacity: 0;
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.iqtd7_e4j {
  stop-color: var(--svg-color--eeb99a, #EEB99A);
  stop-opacity: 0;
}

.kpujw3iqu {
  stop-color: var(--svg-color--e2aa80, #E2AA80);
  stop-opacity: 0;
}

.kr0fi1udo {
  stop-color: var(--svg-color--fcc9a8, #FCC9A8);
  stop-opacity: 0;
}

.ktbkdyb2r {
  d: path("m19.292 4.471l.06.079a2.536 2.536 0 0 1-.494 3.53l-1.419 1.084l-4.512.162z");
}

.kw5vl0jtb {
  stop-color: var(--svg-color--f0b998, #F0B998);
}

.l_r-rkb0i {
  stop-color: var(--svg-color--fdc8a8, #FDC8A8);
}

.l02kk_bos {
  stop-color: var(--svg-color--c99f80, #C99F80);
  stop-opacity: 0;
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.lbtd6zbkm {
  stop-color: var(--svg-color--efbf9c, #EFBF9C);
}

.ldzl_vb_b {
  d: path("M26.804 15.952c.302 0 .58-.061.81-.187c.38-.209.855-.43 1.244-.24c.311.154.487.51.33.82c-.542 1.065-1.67 1.196-2.384 1.17H16.211a.773.773 0 0 1-.773-.773c0-.434.355-.782.788-.776c3.493.048 9.664-.014 10.578-.014");
}

.le_j5cb3p {
  stop-color: var(--svg-color--db9b79, #DB9B79);
  stop-opacity: 0;
}

.lf7vr6vni {
  stop-color: var(--svg-color--d89671, #D89671);
}

.ml5zpzp8m {
  d: path("M15.683 9.22h-3.1l4.822-3.761a.93.93 0 0 1 1.152 1.457z");
}

.nydovgb3n {
  d: path("M27.51 13.202a2.406 2.406 0 0 1 .135 4.81l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.026a2.406 2.406 0 0 1-1.736 4.16l-8.822-.335c-1.33-.005-3.695-.15-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.016c0-3.715 2.379-6.876 5.701-8.054c2.11-.889 4.284-2.362 5.206-2.987l.06-.04l2.82-2.1a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.089l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
}

.o5oh4imtv {
  d: path("M26.549 21.01c0-.432-.35-.78-.782-.777c-2.195.015-7.039.043-9.523.006a.776.776 0 0 0-.789.776c0 .426.346.772.772.772h9.545a.777.777 0 0 0 .777-.777");
}

.oi3x9iuvd {
  stop-color: var(--svg-color--cc8e6e, #CC8E6E);
  stop-opacity: 0;
}

.oi7g8dknq {
  stop-color: var(--svg-color--db9b79, #DB9B79);
}

.olyg7gbdo {
  d: path("m17.453 9.154l-2.78.119l1.72 4.125l10.377-.178a2.384 2.384 0 0 0-1.383-4.396l-7.953.344z");
}

.p0p4x4g6v {
  stop-color: var(--svg-color--f0b998, #F0B998);
  stop-opacity: 0;
}

.prsh4r1dj {
  stop-color: var(--svg-color--fdc8a8, #FDC8A8);
  stop-opacity: 0;
}

.puoda7b1n {
  d: path("m26.702 18.04l-.002-.002l.945-.026a2.406 2.406 0 0 0 .022-4.81l-.455.009l-.447.012l.008-.005l-12.6.172v4.688z");
}

.pw36wubqc {
  d: path("M11.986 25.787c-3.648-.17-6.402-1.909-7.568-3.711l19.827 1.882c0 2.014-1.511 2.252-2.452 2.226c-1.961-.053-6.16-.228-9.807-.397");
}

.qj6gmdbak {
  stop-color: var(--svg-color--e7ad97, #E7AD97);
}

.qyy62abgt {
  stop-color: var(--svg-color--cf9f7b, #CF9F7B);
  stop-opacity: 0;
}

.r8e3pjzpw {
  stop-color: var(--svg-color--e2aa80, #E2AA80);
}

.t5m624b_w {
  stop-color: var(--svg-color--c68869, #C68869);
}

.tbghklb3h {
  fill: var(--svg-color--e7ad97, #E7AD97);
  d: path("M27.51 13.202a2.406 2.406 0 0 1 .135 4.81l-.945.026a2.406 2.406 0 0 1-1.4 4.393l-1.37-.026a2.406 2.406 0 0 1-1.736 4.16l-8.822-.335c-1.33-.005-3.695-.15-5.76-1.004c-3.267-1.207-5.595-4.34-5.595-8.016c0-3.715 2.379-6.876 5.701-8.054c2.11-.889 4.284-2.362 5.206-2.987l.06-.04l2.82-2.1a2.536 2.536 0 0 1 3.054 4.05l-1.424 1.089l7.953-.344a2.385 2.385 0 0 1 1.378 4.4z");
}

.ubibb2bhq {
  stop-color: var(--svg-color--efbf9c, #EFBF9C);
  stop-opacity: 0;
}

.uo_inwq3m {
  stop-color: var(--svg-color--c98f80, #C98F80);
  stop-opacity: 0;
}

.uxe06abat {
  stop-color: var(--svg-color--a9775c, #A9775C);
  stop-opacity: 0;
}

.w-t4tqbjy {
  stop-color: var(--svg-color--ce9e7b, #CE9E7B);
}

.w14svvb0t {
  stop-color: var(--svg-color--cf9f7b, #CF9F7B);
}

.xaai3vbav {
  stop-color: var(--svg-color--c59878, #C59878);
  stop-opacity: 0;
}

.xtkuzf2ei {
  stop-color: var(--svg-color--db9b77, #DB9B77);
}

.yes9llscm {
  d: path("m23.94 22.415l-8.548-.267l-.343 4.156l7.145.261a2.406 2.406 0 0 0 1.747-4.15");
}

.yvwph9bfk {
  stop-color: var(--svg-color--efba9a, #EFBA9A);
}

.z_uwteb1p {
  stop-color: var(--svg-color--ae7956, #AE7956);
}

.zaw1ewbji {
  stop-color: var(--svg-color--ae7956, #AE7956);
  stop-opacity: 0;
}

.zshydrbec {
  stop-color: var(--svg-color--c79a78, #C79A78);
  stop-opacity: 0;
}

.zw1k0-prr {
  stop-color: var(--svg-color--fecea7, #FECEA7);
}

</style>
