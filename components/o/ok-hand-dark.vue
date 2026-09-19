<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-rule="evenodd" filter="url(#i1pypQc)" class="d2kvgvbvc"><path class="sw0nv4a8r"/><path fill="url(#iujgUle)" class="cq9prsi4g"/><path fill="url(#ijAHk1b)" class="cq9prsi4g"/></g><path fill="url(#iJxZmyd)" clip-rule="evenodd" class="uv4z_dt-s"/><path fill="url(#igACIad)" clip-rule="evenodd" class="uv4z_dt-s"/><path fill="url(#iLdmhHd)" clip-rule="evenodd" class="uv4z_dt-s"/><path fill="url(#inddUqq)" clip-rule="evenodd" class="uv4z_dt-s"/><path fill="url(#iJpCczb)" clip-rule="evenodd" class="uv4z_dt-s"/><path fill="url(#ianJcDd)" class="r4n0bhb9j"/><path fill="url(#i2qGAcd)" class="r4n0bhb9j"/><path fill="url(#imq64rb)" class="r4n0bhb9j"/><path fill="url(#i01DpIb)" class="r4n0bhb9j"/><path fill="url(#i7MEvic)" class="kasfw-b4p"/><path fill="url(#ixdTMNd)" class="kasfw-b4p"/><path fill="url(#iSgQFHc)" class="kasfw-b4p"/><path fill="url(#iXDycGc)" class="kasfw-b4p"/><g filter="url(#iDVFi8U)"><path stroke="url(#iCURVge)" class="bu5meojdd"/></g><g filter="url(#i6WNDLe)"><path stroke="url(#ipBcEkd)" class="bkawxhb2a"/></g><g filter="url(#ixu1lAc)"><path stroke="url(#iP6soId)" class="kz2xabbma"/></g><g filter="url(#iB1DaEe)"><path stroke="url(#iQBulKb)" class="tdy7-m_fn"/></g><g filter="url(#iV1oqNb)"><path stroke="url(#iFckTle)" class="ojt9yacts"/></g><g filter="url(#iGvhvUd)"><path fill="url(#iPq6Vue)" class="l6as6xbzq"/></g><path fill="url(#ib3wUmd)" clip-rule="evenodd" class="t9ok82b3y"/><g filter="url(#iCjGhqc)"><path stroke="url(#isMLzLd)" class="dd7t-y1vp"/></g><path fill="url(#iUkasmb)" clip-rule="evenodd" class="d7jdbebsr"/><path fill="url(#iEkUz1d)" clip-rule="evenodd" class="d7jdbebsr"/><defs><linearGradient id="iJxZmyd" x1="14.915" x2="16.619" y1="8.438" y2="7.11" gradientUnits="userSpaceOnUse"><stop class="c9uxd3kco"/><stop offset="1" class="zpmvtok6s"/></linearGradient><linearGradient id="inddUqq" x1="21.9" x2="19.462" y1="6.985" y2="9.485" gradientUnits="userSpaceOnUse"><stop class="wg2c0ccoc"/><stop offset="1" class="qgyopejus"/></linearGradient><linearGradient id="iJpCczb" x1="22.337" x2="21.025" y1="10.985" y2="9.235" gradientUnits="userSpaceOnUse"><stop class="l-3q2ti-u"/><stop offset="1" class="ffwwokb9r"/></linearGradient><linearGradient id="ianJcDd" x1="20.369" x2="23.096" y1="9.704" y2="9.473" gradientUnits="userSpaceOnUse"><stop class="c9uxd3kco"/><stop offset="1" class="zpmvtok6s"/></linearGradient><linearGradient id="i2qGAcd" x1="26.9" x2="24.066" y1="9.454" y2="9.385" gradientUnits="userSpaceOnUse"><stop class="wg2c0ccoc"/><stop offset="1" class="qgyopejus"/></linearGradient><linearGradient id="imq64rb" x1="25.65" x2="24.892" y1="12.329" y2="11.389" gradientUnits="userSpaceOnUse"><stop class="l-3q2ti-u"/><stop offset="1" class="ffwwokb9r"/></linearGradient><linearGradient id="i7MEvic" x1="9.681" x2="10.039" y1="11.985" y2="9.716" gradientUnits="userSpaceOnUse"><stop class="c9uxd3kco"/><stop offset="1" class="zpmvtok6s"/></linearGradient><linearGradient id="iCURVge" x1="22.747" x2="27.634" y1="5.273" y2="7.796" gradientUnits="userSpaceOnUse"><stop class="su_vj-bxv"/><stop offset="1" class="qet12wbke"/></linearGradient><linearGradient id="ipBcEkd" x1="17.056" x2="24.337" y1="4.922" y2="14.547" gradientUnits="userSpaceOnUse"><stop class="su_vj-bxv"/><stop offset="1" class="qet12wbke"/></linearGradient><linearGradient id="iP6soId" x1="8.306" x2="16.994" y1="8.883" y2="10.274" gradientUnits="userSpaceOnUse"><stop class="su_vj-bxv"/><stop offset="1" class="qet12wbke"/></linearGradient><linearGradient id="iQBulKb" x1="10.586" x2="18.055" y1="17.274" y2="11.748" gradientUnits="userSpaceOnUse"><stop class="ahf7vlbjr"/><stop offset="1" class="a86cg4b2m"/></linearGradient><linearGradient id="iFckTle" x1="11.444" x2="18.854" y1="22.654" y2="23.12" gradientUnits="userSpaceOnUse"><stop class="vy3a6n4ty"/><stop offset="1" class="vscc-5lzn"/></linearGradient><linearGradient id="iPq6Vue" x1="26.998" x2="22.025" y1="20.364" y2="11.641" gradientUnits="userSpaceOnUse"><stop class="vyjcl94hi"/><stop offset="1" class="lok06bc5k"/></linearGradient><radialGradient id="iujgUle" cx="0" cy="0" r="1" gradientTransform="matrix(4.5 -4.09375 4.21928 4.63798 16.4 20.641)" gradientUnits="userSpaceOnUse"><stop class="r9o7snbfp"/><stop offset="1" class="jfefw3bda"/></radialGradient><radialGradient id="ijAHk1b" cx="0" cy="0" r="1" gradientTransform="matrix(-.00781 .49219 -1.27635 -.02026 10.525 20.212)" gradientUnits="userSpaceOnUse"><stop class="z_ba_pb-a"/><stop offset="1" class="nj796tspr"/></radialGradient><radialGradient id="igACIad" cx="0" cy="0" r="1" gradientTransform="matrix(-7.83697 -.62504 .61777 -7.74578 20.712 5.204)" gradientUnits="userSpaceOnUse"><stop offset=".767" class="zpmvtok6s"/><stop offset="1" class="c9uxd3kco"/></radialGradient><radialGradient id="iLdmhHd" cx="0" cy="0" r="1" gradientTransform="rotate(-154.517 11.642 2.015)scale(9.9117 7.62008)" gradientUnits="userSpaceOnUse"><stop offset=".843" class="vscc-5lzn"/><stop offset="1" class="xvgffxbks"/></radialGradient><radialGradient id="i01DpIb" cx="0" cy="0" r="1" gradientTransform="matrix(1.49666 -1.00685 2.09997 3.12156 21.8 11.109)" gradientUnits="userSpaceOnUse"><stop offset=".261" class="ozdm7-b2s"/><stop offset="1" class="du8lvqbwy"/></radialGradient><radialGradient id="ixdTMNd" cx="0" cy="0" r="1" gradientTransform="matrix(-.68751 -1.9375 2.0372 -.72289 13.306 11.954)" gradientUnits="userSpaceOnUse"><stop class="c9uxd3kco"/><stop offset="1" class="zpmvtok6s"/></radialGradient><radialGradient id="iSgQFHc" cx="0" cy="0" r="1" gradientTransform="matrix(-12.72015 -2.73997 2.13394 -9.90668 18.338 10.888)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="vscc-5lzn"/><stop offset="1" class="xvgffxbks"/></radialGradient><radialGradient id="iXDycGc" cx="0" cy="0" r="1" gradientTransform="rotate(119.455 6.198 9.903)scale(1.52522 3.27464)" gradientUnits="userSpaceOnUse"><stop class="ko5xwnb5m"/><stop offset="1" class="e-bfalbzl"/></radialGradient><radialGradient id="ib3wUmd" cx="0" cy="0" r="1" gradientTransform="matrix(18.68754 -2.875 4.1034 26.6721 8.775 18.266)" gradientUnits="userSpaceOnUse"><stop offset=".786" class="i6sr0pbno"/><stop offset="1" class="b_e13acxs"/></radialGradient><radialGradient id="isMLzLd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.01673 2.30124 -3.6321 -6.3397 24.612 14.691)" gradientUnits="userSpaceOnUse"><stop class="b7rfw9bck"/><stop offset="1" class="rc8x4nbrs"/></radialGradient><radialGradient id="iUkasmb" cx="0" cy="0" r="1" gradientTransform="matrix(3.1567 -19.21168 17.64953 2.90003 15.678 29.912)" gradientUnits="userSpaceOnUse"><stop offset=".856" class="b6_y3jxfc"/><stop offset="1" class="nanaxrbqi"/></radialGradient><radialGradient id="iEkUz1d" cx="0" cy="0" r="1" gradientTransform="matrix(4.45936 3.04775 -3.06138 4.47929 16.852 20.47)" gradientUnits="userSpaceOnUse"><stop class="dnrnmmbrl"/><stop offset="1" class="tdwmw7_4a"/></radialGradient><filter id="i1pypQc" width="21.365" height="26.791" x="5.617" y="2.305" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".6" dy="-.6"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.308333 0 0 0 0 0.165729 0 0 0 0 0.293054 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1745"/></filter><filter id="iDVFi8U" width="6.375" height="10.781" x="20.181" y="2.98" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1745" stdDeviation=".625"/></filter><filter id="i6WNDLe" width="9.391" height="9.797" x="13.697" y="2.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1745" stdDeviation=".625"/></filter><filter id="ixu1lAc" width="11.703" height="5.477" x="5.9" y="6.672" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1745" stdDeviation=".625"/></filter><filter id="iB1DaEe" width="11.469" height="8.74" x="8.586" y="11.329" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1745" stdDeviation=".625"/></filter><filter id="iV1oqNb" width="10.391" height="7.415" x="9.125" y="20.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1745" stdDeviation=".625"/></filter><filter id="iGvhvUd" width="10.483" height="12.356" x="16.369" y="9.415" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1745" stdDeviation=".5"/></filter><filter id="iCjGhqc" width="8.873" height="11.495" x="17.77" y="10.997" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1745" stdDeviation=".625"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ok-hand-dark" /></template>
<style>
.a86cg4b2m {
  stop-color: var(--svg-color--5e4346, #5E4346);
  stop-opacity: 0;
}

.ahf7vlbjr {
  stop-color: var(--svg-color--5e4346, #5E4346);
}

.b_e13acxs {
  stop-color: var(--svg-color--685452, #685452);
}

.b6_y3jxfc {
  stop-color: var(--svg-color--58423e, #58423E);
  stop-opacity: 0;
}

.b7rfw9bck {
  stop-color: var(--svg-color--7a6967, #7A6967);
}

.bkawxhb2a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M15.572 4.563c1.062.672 3.609 2.984 5.64 6.047");
}

.bu5meojdd {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M22.056 4.855c.625.823 2.156 4.38 2.625 7.031");
}

.c9uxd3kco {
  stop-color: var(--svg-color--2d1a19, #2D1A19);
}

.cq9prsi4g {
  d: path("M13.358 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.176-1.39c1.49 2.53 2.62 6.233 2.907 9.933l.011-.001l.015.278c.034.597.104 1.816.067 4.111c-.037 2.313-.674 4.143-1.606 5.678c-1.613 2.756-4.67 4.575-8.089 4.575c-3.786 0-6.906-2.332-8.36-5.315a2.5 2.5 0 0 1 1.734-3.542a2.504 2.504 0 0 1-2.06-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.946-.754-3.947-.805a2.5 2.5 0 1 1 .253-4.993c1.543.078 3.914.49 6.336 1.438q-.43-.467-.85-.863c-.98-.764-1.136-2.31-.372-3.29m3.32 12.419c-1.893 0-3.443.973-4.032 2.475a2.5 2.5 0 0 1-1.815 1.534a2.5 2.5 0 0 1 1.982 1.39c.714 1.467 2.205 2.272 3.864 2.272c1.901-.15 3.542-1.663 3.542-3.802c0-2.138-1.499-3.87-3.542-3.87");
}

.d2kvgvbvc {
  fill-rule: evenodd;
}

.d7jdbebsr {
  fill-rule: evenodd;
  d: path("M23.635 26.053a9.43 9.43 0 0 1-6.958 3.042c-3.786 0-6.906-2.332-8.36-5.315a2.5 2.5 0 0 1 1.734-3.543a2.5 2.5 0 0 1-2.06-3.4a9.12 9.12 0 0 1 3.947-4.552l-.024-.008c1.437-.818 3.08-1.292 4.775-1.292c5.079 0 9.196 4.075 9.196 9.102a9 9 0 0 1-2.25 5.966m-10.989-7.389c.59-1.501 2.139-2.475 4.031-2.475c2.043 0 3.542 1.732 3.542 3.87s-1.64 3.651-3.542 3.802c-1.658 0-3.15-.805-3.864-2.271a2.5 2.5 0 0 0-1.982-1.392a2.5 2.5 0 0 0 1.815-1.533");
}

.dd7t-y1vp {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.02 13.248c1.488.511 4.445 2.626 4.37 6.994");
}

.dnrnmmbrl {
  stop-color: var(--svg-color--413330, #413330);
}

.du8lvqbwy {
  stop-color: var(--svg-color--5a4643, #5A4643);
  stop-opacity: 0;
}

.e-bfalbzl {
  stop-color: var(--svg-color--59413c, #59413C);
  stop-opacity: 0;
}

.ffwwokb9r {
  stop-color: var(--svg-color--48302f, #48302F);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.i6sr0pbno {
  stop-color: var(--svg-color--685452, #685452);
  stop-opacity: 0;
}

.jfefw3bda {
  stop-color: var(--svg-color--351f27, #351F27);
  stop-opacity: 0;
}

.kasfw-b4p {
  d: path("M8.244 6.487a2.5 2.5 0 0 0-.253 4.993c.99.05 2.414.299 3.896.788a9.5 9.5 0 0 1 4.926-1.363c1.217 0 2.381.227 3.452.641a2.5 2.5 0 0 0-.288-.322C16.362 7.822 10.99 6.626 8.244 6.487");
}

.ko5xwnb5m {
  stop-color: var(--svg-color--59413c, #59413C);
}

.kz2xabbma {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M7.775 8.547c2.093.25 6.187 1.22 7.953 1.727");
}

.l-3q2ti-u {
  stop-color: var(--svg-color--48302f, #48302F);
}

.l6as6xbzq {
  d: path("M25.717 20.77c-1.317-8.847-6.973-9.15-8.348-9.504c2.875-1.844 7.155-.352 7.625 1.25c.906 3.094.994 6.713.723 8.255");
}

.lok06bc5k {
  stop-color: var(--svg-color--6e5e5b, #6E5E5B);
  stop-opacity: 0;
}

.nanaxrbqi {
  stop-color: var(--svg-color--58423e, #58423E);
}

.nj796tspr {
  stop-color: var(--svg-color--210e0e, #210E0E);
  stop-opacity: 0;
}

.ojt9yacts {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M11 21.94c.542 1.378 2.629 4.031 6.641 3.623");
}

.ozdm7-b2s {
  stop-color: var(--svg-color--5a4643, #5A4643);
}

.qet12wbke {
  stop-color: var(--svg-color--604c49, #604C49);
  stop-opacity: 0;
}

.qgyopejus {
  stop-color: var(--svg-color--5f4743, #5F4743);
  stop-opacity: 0;
}

.r4n0bhb9j {
  d: path("M26.166 13.329c-.407-3.314-1.456-6.535-2.794-8.807a2.25 2.25 0 0 0-4.176 1.39c1.889 2.112 3.544 4.722 4.57 7.417z");
}

.r9o7snbfp {
  stop-color: var(--svg-color--351f27, #351F27);
}

.rc8x4nbrs {
  stop-color: var(--svg-color--7c6967, #7C6967);
  stop-opacity: 0;
}

.su_vj-bxv {
  stop-color: var(--svg-color--604c49, #604C49);
}

.sw0nv4a8r {
  fill: var(--svg-color--472f2d, #472F2D);
  d: path("M13.358 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.176-1.39c1.49 2.53 2.62 6.233 2.907 9.933l.011-.001l.015.278c.034.597.104 1.816.067 4.111c-.037 2.313-.674 4.143-1.606 5.678c-1.613 2.756-4.67 4.575-8.089 4.575c-3.786 0-6.906-2.332-8.36-5.315a2.5 2.5 0 0 1 1.734-3.542a2.504 2.504 0 0 1-2.06-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.946-.754-3.947-.805a2.5 2.5 0 1 1 .253-4.993c1.543.078 3.914.49 6.336 1.438q-.43-.467-.85-.863c-.98-.764-1.136-2.31-.372-3.29m3.32 12.419c-1.893 0-3.443.973-4.032 2.475a2.5 2.5 0 0 1-1.815 1.534a2.5 2.5 0 0 1 1.982 1.39c.714 1.467 2.205 2.272 3.864 2.272c1.901-.15 3.542-1.663 3.542-3.802c0-2.138-1.499-3.87-3.542-3.87");
}

.t9ok82b3y {
  fill-rule: evenodd;
  d: path("M13.358 3.771a2.25 2.25 0 0 1 3.158-.39a21 21 0 0 1 2.68 2.53a2.25 2.25 0 0 1 4.176-1.39c1.49 2.53 2.62 6.233 2.907 9.933l.011-.001l.015.278c.034.597.104 1.816.067 4.111c-.037 2.313-.674 4.143-1.606 5.678c-1.613 2.756-4.67 4.575-8.089 4.575c-3.786 0-6.906-2.332-8.36-5.315a2.5 2.5 0 0 1 1.734-3.542a2.504 2.504 0 0 1-2.06-3.4a9.12 9.12 0 0 1 3.947-4.553c-1.501-.5-2.946-.754-3.947-.805a2.5 2.5 0 1 1 .253-4.993c1.543.078 3.914.49 6.336 1.438q-.43-.467-.85-.863c-.98-.764-1.136-2.31-.372-3.29m3.32 12.419c-1.893 0-3.443.973-4.032 2.475a2.5 2.5 0 0 1-1.815 1.534a2.5 2.5 0 0 1 1.982 1.39c.714 1.467 2.205 2.272 3.864 2.272c1.901-.15 3.542-1.663 3.542-3.802c0-2.138-1.499-3.87-3.542-3.87");
}

.tdwmw7_4a {
  stop-color: var(--svg-color--413330, #413330);
  stop-opacity: 0;
}

.tdy7-m_fn {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.586 18.068c1.188-3.406 5.094-5.062 7.469-4.687");
}

.uv4z_dt-s {
  fill-rule: evenodd;
  d: path("M13.358 3.771a2.25 2.25 0 0 1 3.158-.39c2.27 1.77 4.471 4.407 6.043 7.323h-3.168c-1.46-1.223-3.148-2.128-4.81-2.779q-.432-.466-.85-.863c-.98-.764-1.137-2.31-.373-3.29");
}

.vscc-5lzn {
  stop-color: var(--svg-color--614d4c, #614D4C);
  stop-opacity: 0;
}

.vy3a6n4ty {
  stop-color: var(--svg-color--614d4c, #614D4C);
}

.vyjcl94hi {
  stop-color: var(--svg-color--6e5e5b, #6E5E5B);
}

.wg2c0ccoc {
  stop-color: var(--svg-color--5f4743, #5F4743);
}

.xvgffxbks {
  stop-color: var(--svg-color--53433f, #53433F);
}

.z_ba_pb-a {
  stop-color: var(--svg-color--210e0e, #210E0E);
}

.zpmvtok6s {
  stop-color: var(--svg-color--2d1a19, #2D1A19);
  stop-opacity: 0;
}

</style>
