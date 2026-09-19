<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#ik5lLqe)" class="hrdr5zbwd"/><path fill="url(#i1Fixub)" class="hrdr5zbwd"/><path fill="url(#ilzLjSb)" class="hrdr5zbwd"/><path fill="url(#ieTIIyx)" class="hrdr5zbwd"/><path fill="url(#iSUCMSC)" class="hrdr5zbwd"/><path fill="url(#iU56gHe)" class="hrdr5zbwd"/><path fill="url(#iO6MArd)" class="vpa3-5bis"/><g filter="url(#iny7jJN)"><path class="wyfxh4o3p"/></g><g filter="url(#iqkd1Fb)"><ellipse fill="url(#iKvYkvd)" transform="rotate(-44.19 18.666 16.535)" class="j90cu8b4u"/></g><g filter="url(#ibV7B4d)"><ellipse fill="url(#ipwiO2b)" transform="rotate(-128.955 9.907 16.914)" class="xvqwc2b3y"/></g><path fill="url(#iGwJ5Ed)" class="ha7z-8b-c"/><path fill="url(#ihEWpse)" class="ha7z-8b-c"/><path fill="url(#i6fCDuc)" class="ha7z-8b-c"/><path fill="url(#iXwKM2d)" class="ha7z-8b-c"/><path fill="url(#iQ8gEle)" class="ha7z-8b-c"/><path fill="url(#iFyXZZi)" class="ha7z-8b-c"/><path fill="url(#i58Kv7Z)" class="xn_z20g_g"/><g filter="url(#iJk9AFd)"><path class="br6ynnbne"/></g><g filter="url(#itg2qre)"><ellipse fill="url(#ipVh8wr)" transform="rotate(-44.19 27.736 4.793)" class="xxsb2liok"/></g><g filter="url(#iO34Jod)"><ellipse fill="url(#iY7KMxe)" transform="rotate(-128.955 21.974 5.042)" class="u7tol448f"/></g><path fill="url(#irqXgQc)" clip-rule="evenodd" class="jn81m953t"/><path fill="url(#i0OvQhb)" clip-rule="evenodd" class="jn81m953t"/><path fill="url(#iKg1RWc)" clip-rule="evenodd" class="jn81m953t"/><path fill="url(#ijuWfxd)" clip-rule="evenodd" class="b04u83bab"/><path fill="url(#iOC9wqH)" clip-rule="evenodd" class="b04u83bab"/><path fill="url(#iCwmpCx)" class="r3xhfwbmj"/><g filter="url(#izpSMUb)"><path stroke="url(#iEms19b)" class="o71wbhikl"/></g><g filter="url(#iIz35me)"><path stroke="url(#i802k2c)" class="ls2cvrbbo"/></g></g><defs><radialGradient id="ik5lLqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -23.9627 40.7367 0 14.317 29.605)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="i1Fixub" cx="0" cy="0" r="1" gradientTransform="rotate(142.986 5.875 11.223)scale(19.29 36.132)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="ilzLjSb" cx="0" cy="0" r="1" gradientTransform="rotate(-158.663 9.561 9.265)scale(16.7324 23.6536)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="ieTIIyx" cx="0" cy="0" r="1" gradientTransform="rotate(90 -3.31 15.142)scale(14.5627)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="iKvYkvd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.52034 -.2547 .17199 -3.05234 21.747 17.183)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="ipwiO2b" cx="0" cy="0" r="1" gradientTransform="matrix(-8.30787 -.19332 .10239 -4.40002 12.212 17.483)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="iGwJ5Ed" cx="0" cy="0" r="1" gradientTransform="matrix(0 -15.7644 26.7994 0 24.875 13.392)" gradientUnits="userSpaceOnUse"><stop class="ejc52zb_a"/><stop offset=".596" class="xg2pw8btp"/><stop offset="1" class="r-3kexbeb"/></radialGradient><radialGradient id="ihEWpse" cx="0" cy="0" r="1" gradientTransform="rotate(142.986 12.612 6.928)scale(12.6903 23.7702)" gradientUnits="userSpaceOnUse"><stop offset=".483" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="i6fCDuc" cx="0" cy="0" r="1" gradientTransform="matrix(-10.25329 -4.00522 5.66191 -14.4944 25.387 7.977)" gradientUnits="userSpaceOnUse"><stop offset=".41" class="fdfp5-b0w"/><stop offset=".834" class="lj35z3s3o"/></radialGradient><radialGradient id="iXwKM2d" cx="0" cy="0" r="1" gradientTransform="rotate(90 8.593 14.647)scale(9.58038)" gradientUnits="userSpaceOnUse"><stop offset=".671" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></radialGradient><radialGradient id="ipVh8wr" cx="0" cy="0" r="1" gradientTransform="rotate(-176.775 14.955 2.19)scale(2.97851 2.01123)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="iY7KMxe" cx="0" cy="0" r="1" gradientTransform="rotate(-178.667 11.777 2.572)scale(5.46698 2.89543)" gradientUnits="userSpaceOnUse"><stop class="pl211ybaw"/><stop offset="1" class="qnbh2pn9v"/></radialGradient><radialGradient id="iCwmpCx" cx="0" cy="0" r="1" gradientTransform="matrix(1.36955 .01857 -.10531 7.76518 27.99 13.975)" gradientUnits="userSpaceOnUse"><stop offset=".108" class="um5epfuly"/><stop offset="1" class="l6w9fiiic"/></radialGradient><linearGradient id="iSUCMSC" x1="13.44" x2="19.333" y1="20.156" y2="27.17" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iU56gHe" x1="12.71" x2="5.793" y1="20.449" y2="28.241" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iO6MArd" x1="14.97" x2="12.903" y1="15.164" y2="12.894" gradientUnits="userSpaceOnUse"><stop offset=".41" class="k0jhnr2iw"/><stop offset=".834" class="yxx9jebfv"/></linearGradient><linearGradient id="iQ8gEle" x1="24.298" x2="28.175" y1="7.175" y2="11.79" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="iFyXZZi" x1="23.817" x2="19.267" y1="7.368" y2="12.494" gradientUnits="userSpaceOnUse"><stop offset=".694" class="qudiit10p"/><stop offset=".934" class="yw57-9naf"/></linearGradient><linearGradient id="i58Kv7Z" x1="25.305" x2="23.945" y1="3.891" y2="2.397" gradientUnits="userSpaceOnUse"><stop offset=".41" class="k0jhnr2iw"/><stop offset=".834" class="yxx9jebfv"/></linearGradient><linearGradient id="irqXgQc" x1="4.731" x2="12.436" y1="11.968" y2="8.174" gradientUnits="userSpaceOnUse"><stop offset=".047" class="pgcy-ekrs"/><stop offset="1" class="p3pp_8bno"/></linearGradient><linearGradient id="i0OvQhb" x1="2.352" x2="6.699" y1="15.175" y2="10.433" gradientUnits="userSpaceOnUse"><stop offset=".108" class="um5epfuly"/><stop offset="1" class="l6w9fiiic"/></linearGradient><linearGradient id="iKg1RWc" x1="17.557" x2="13.561" y1="7.303" y2="7.187" gradientUnits="userSpaceOnUse"><stop offset=".108" class="um5epfuly"/><stop offset="1" class="l6w9fiiic"/></linearGradient><linearGradient id="ijuWfxd" x1="24.164" x2="28.868" y1="20.984" y2="20.187" gradientUnits="userSpaceOnUse"><stop offset=".047" class="pgcy-ekrs"/><stop offset="1" class="p3pp_8bno"/></linearGradient><linearGradient id="iOC9wqH" x1="23.302" x2="27.582" y1="25.022" y2="23.431" gradientUnits="userSpaceOnUse"><stop offset=".108" class="c85n-e9fg"/><stop offset="1" class="bj-9kibqz"/></linearGradient><linearGradient id="iEms19b" x1="18.225" x2="4.675" y1="4.184" y2="10.583" gradientUnits="userSpaceOnUse"><stop class="dhj3xbbcu"/><stop offset="1" class="pl211ybaw"/></linearGradient><linearGradient id="i802k2c" x1="32.502" x2="26.951" y1="13.245" y2="17.645" gradientUnits="userSpaceOnUse"><stop class="dhj3xbbcu"/><stop offset="1" class="pl211ybaw"/></linearGradient><filter id="iny7jJN" width="7.323" height="10.359" x="10.671" y="13.629" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5009" stdDeviation="1"/></filter><filter id="iqkd1Fb" width="8.283" height="8.229" x="14.525" y="12.421" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5009" stdDeviation=".75"/></filter><filter id="ibV7B4d" width="8.903" height="9.627" x="5.455" y="12.1" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5009" stdDeviation=".75"/></filter><filter id="iJk9AFd" width="6.182" height="7.302" x="21.792" y="2.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5009" stdDeviation="1"/></filter><filter id="itg2qre" width="6.475" height="6.44" x="24.498" y="1.573" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5009" stdDeviation=".75"/></filter><filter id="iO34Jod" width="6.884" height="7.36" x="18.532" y="1.362" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5009" stdDeviation=".75"/></filter><filter id="izpSMUb" width="12.719" height="6.451" x="2.787" y="5.226" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5009" stdDeviation=".125"/></filter><filter id="iIz35me" width="6.954" height="7.539" x="23.228" y="13.067" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7000_5009" stdDeviation=".125"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:revolving-hearts" /></template>
<style>
.b04u83bab {
  fill-rule: evenodd;
  d: path("M28.233 10.64a.55.55 0 0 1 .759.172c.585.928 1.814 3.2.354 6.088c-.657 1.298-1.758 2.228-2.834 2.87a11.2 11.2 0 0 1-2.866 1.197a.55.55 0 0 1-.27-1.067a10 10 0 0 0 2.573-1.075c.971-.58 1.886-1.374 2.415-2.42c1.194-2.362.216-4.184-.303-5.006a.55.55 0 0 1 .172-.759");
}

.bj-9kibqz {
  stop-color: var(--svg-color--cb1949, #CB1949);
  stop-opacity: 0;
}

.br6ynnbne {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M25.81 5.346a1.75 1.75 0 0 0-.689-.946c-.719-.487-1.329.347-1.329 1.215c0 2.192 2.344 2.737 2.173.552a3.8 3.8 0 0 0-.154-.821");
}

.c85n-e9fg {
  stop-color: var(--svg-color--cb1949, #CB1949);
}

.dhj3xbbcu {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
  stop-opacity: 0;
}

.ejc52zb_a {
  stop-color: var(--svg-color--f12e52, #F12E52);
}

.fdfp5-b0w {
  stop-color: var(--svg-color--b91d43, #B91D43);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.ha7z-8b-c {
  d: path("M22.645 13.243a1.58 1.58 0 0 0 1.688-.012c1.765-1.096 4.409-3.247 5.499-5.977c1.737-3.858-2.341-6.937-5.16-4.723c-.205.162-.447.34-.66.517c-.257.213-.698.233-.956.02a14 14 0 0 0-.931-.696c-2.403-1.626-6.774.517-4.91 5.09c.635 1.906 3.487 4.554 5.43 5.78");
}

.hrdr5zbwd {
  d: path("M11.356 29.64c.529.31 1.177.294 1.705-.017c2.663-1.569 7.042-4.968 8.791-9.348c2.64-5.864-3.558-10.544-7.842-7.178c-.4.314-.892.669-1.268 1.013c-.246.225-.673.248-.924.028a20 20 0 0 0-1.681-1.283c-3.652-2.471-10.298.786-7.463 7.737c1.012 3.042 5.74 7.325 8.682 9.048");
}

.j90cu8b4u {
  cx: 18.666px;
  cy: 16.535px;
  rx: 3.062px;
  ry: 2.107px;
}

.jn81m953t {
  fill-rule: evenodd;
  d: path("M15.774 5.983c-6.745-.228-10.51 2.63-12.403 5.722a.55.55 0 0 1-.938-.574C4.539 7.69 8.68 4.643 15.81 4.884a.55.55 0 0 1-.037 1.1");
}

.k0jhnr2iw {
  stop-color: var(--svg-color--c12372, #C12372);
  stop-opacity: 0;
}

.l6w9fiiic {
  stop-color: var(--svg-color--ce2654, #CE2654);
  stop-opacity: 0;
}

.lj35z3s3o {
  stop-color: var(--svg-color--b91d43, #B91D43);
}

.ls2cvrbbo {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M29.755 13.467c.297 2.042-1.82 5.663-6.127 6.74");
}

.o71wbhikl {
  stroke-linecap: round;
  stroke-opacity: 0.75;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M3.187 11.277c.297-.386 3.305-5.867 11.92-5.644");
}

.p3pp_8bno {
  stop-color: var(--svg-color--ff4781, #FF4781);
}

.pgcy-ekrs {
  stop-color: var(--svg-color--ff1a44, #FF1A44);
}

.pl211ybaw {
  stop-color: var(--svg-color--ff93ba, #FF93BA);
}

.qnbh2pn9v {
  stop-color: var(--svg-color--ff73a6, #FF73A6);
  stop-opacity: 0;
}

.qudiit10p {
  stop-color: var(--svg-color--ff7af2, #FF7AF2);
  stop-opacity: 0;
}

.r-3kexbeb {
  stop-color: var(--svg-color--ff4ec6, #FF4EC6);
}

.r3xhfwbmj {
  d: path("M29.184 11.131a9 9 0 0 0-.192-.32a.55.55 0 1 0-.93.588c.443.703 1.222 2.137.692 4.015c.97-1.542.828-3.152.43-4.283");
}

.u7tol448f {
  cx: 21.974px;
  cy: 5.042px;
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 2.569px;
  ry: 1.386px;
}

.um5epfuly {
  stop-color: var(--svg-color--9c1036, #9C1036);
}

.vpa3-5bis {
  d: path("M11.84 14.157c.84.852 2.223.573 3.027-.313c.81-.891 1.882-1.7 3.24-1.786c-1.343-.259-2.807.025-4.097 1.04l-.35.269c-.357.273-.737.564-1.025.844c-.187.18-.514.2-.707.025z");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.wyfxh4o3p {
  fill: var(--svg-color--fa1c56, #FA1C56);
  d: path("M12.671 17.39v2.11c0 2.714 2.839 3.52 3.233.834c.15-1.017.124-2.029-.164-2.959a2.64 2.64 0 0 0-1.391-1.633c-.971-.462-1.678.572-1.678 1.648");
}

.xg2pw8btp {
  stop-color: var(--svg-color--ff3b79, #FF3B79);
}

.xn_z20g_g {
  d: path("M23.245 3.228c.552.56 1.463.377 1.992-.205c.532-.587 1.238-1.119 2.132-1.176c-.884-.17-1.848.017-2.696.684q-.11.087-.23.178c-.235.18-.345.28-.567.42c-.123.119-.612.114-.739 0c.133.125.07.1.108.1");
}

.xvqwc2b3y {
  cx: 9.907px;
  cy: 16.914px;
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  rx: 3.905px;
  ry: 2.107px;
}

.xxsb2liok {
  cx: 27.736px;
  cy: 4.793px;
  rx: 2.014px;
  ry: 1.386px;
}

.yw57-9naf {
  stop-color: var(--svg-color--ffbce6, #FFBCE6);
}

.yxx9jebfv {
  stop-color: var(--svg-color--b5286e, #B5286E);
}

</style>
