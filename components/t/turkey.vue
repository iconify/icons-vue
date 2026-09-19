<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="odl3_chmv"/><path fill="url(#i9A65ze)" class="sw5t8obgx"/><path fill="url(#iysmZge)" class="sw5t8obgx"/><path fill="url(#i6vOBCe)" class="sw5t8obgx"/><path class="d349wtbqb"/><path fill="url(#iKLDDXB)" class="vyz8zj0vc"/><path fill="url(#isq16ce)" class="vyz8zj0vc"/><path fill="url(#igqz7zb)" class="vyz8zj0vc"/><path fill="url(#iETFecb)" class="qlgj9mbxt"/><path fill="url(#ivPj3Ec)" class="qlgj9mbxt"/><path fill="url(#i1nl7JT)" class="qlgj9mbxt"/><path fill="url(#iIVQQne)" class="pbvselb1a"/><path fill="url(#i7p2s1b)" class="pbvselb1a"/><path fill="url(#il5Q1Oe)" class="tlkisu1jf"/><path fill="url(#ii4Jmhb)" class="tlkisu1jf"/><path fill="url(#iKhIsVd)" class="v96g48b_b"/><path fill="url(#ioogvvb)" class="v96g48b_b"/><path fill="url(#irbTdFb)" class="lgzjv11sb"/><path fill="url(#i1HMdpb)" class="lgzjv11sb"/><path fill="url(#ib5wuPe)" class="eec65cbsr"/><path fill="url(#iL8f3fc)" class="eec65cbsr"/><path fill="url(#it0HtHd)" class="bcq4odbyv"/><path fill="url(#iPLEXfc)" class="bcq4odbyv"/><path fill="url(#iCpeqvd)" class="wgemjbc-y"/><path fill="url(#iey2GAd)" class="wgemjbc-y"/><path fill="url(#iRXyRSc)" class="fcd7kc9-u"/><path fill="url(#iAzNmte)" class="fcd7kc9-u"/><path fill="url(#iKlbKIe)" class="fcd7kc9-u"/><path class="uqn0he-oh"/><path fill="url(#ib8oEmd)" class="xm5a4hb_m"/><path fill="url(#inbNLUd)" class="xm5a4hb_m"/><path class="l7oebmbar"/><path fill="url(#izHNnFb)" class="derelpwjr"/><path fill="url(#iW1bwMb)" class="derelpwjr"/><path fill="url(#igVDX2b)" class="derelpwjr"/><path fill="url(#irqMR9c)" class="derelpwjr"/><path fill="url(#iQZzect)" class="derelpwjr"/><path class="gs6nzbcwo"/><path fill="url(#iDgEMUb)" class="okluc6v9l"/><path fill="url(#ixhbM4c)" class="okluc6v9l"/><path fill="url(#iRuotQc)" class="okluc6v9l"/><g filter="url(#igoImbb)"><ellipse fill="url(#igdz5xd)" transform="rotate(-35 20.238 13.89)" class="kqvjecchm"/></g><path fill="url(#iucaPAe)" class="evwk91m1l"/><path fill="url(#iGywhae)" class="evwk91m1l"/><path class="jcin7-lmi"/><path fill="url(#i8SSe5b)" class="m-aqfdvrz"/><path fill="url(#iXm1ZIw)" class="m-aqfdvrz"/><path fill="url(#i1mn5te)" class="exgttbbry"/><rect fill="url(#inZMrVd)" class="q27gc5b6o"/><circle fill="url(#iXBOiCd)" class="twwsfzbtn"/><circle fill="url(#i8BgdRb)" class="twwsfzbtn"/><circle fill="url(#iEVcDpd)" class="twwsfzbtn"/><g filter="url(#ioSuTCZ)"><path fill="url(#iKB4y5b)" class="br2zzo91n"/></g><g filter="url(#iCFpSmd)"><ellipse class="i2up3qfoc"/></g><g filter="url(#ilQ42Ld)"><path fill="url(#iv6cjtb)" class="rgjn5cbxy"/></g><defs><radialGradient id="i6vOBCe" cx="0" cy="0" r="1" gradientTransform="matrix(.25543 3.60065 -1.6591 .1177 14.266 24.562)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="j2775johd"/><stop offset="1" class="q8wpksbws"/></radialGradient><radialGradient id="igqz7zb" cx="0" cy="0" r="1" gradientTransform="matrix(.25543 3.60065 -1.6591 .1177 18.25 24.562)" gradientUnits="userSpaceOnUse"><stop offset=".122" class="j2775johd"/><stop offset="1" class="q8wpksbws"/></radialGradient><radialGradient id="ii4Jmhb" cx="0" cy="0" r="1" gradientTransform="rotate(148.655 14.707 5.855)scale(1.26237 1.49797)" gradientUnits="userSpaceOnUse"><stop class="b5-p3qb9c"/><stop offset="1" class="fd7whqb6j"/></radialGradient><radialGradient id="ioogvvb" cx="0" cy="0" r="1" gradientTransform="rotate(152.771 14.394 6.887)scale(1.43519 1.55959)" gradientUnits="userSpaceOnUse"><stop class="b5-p3qb9c"/><stop offset="1" class="fd7whqb6j"/></radialGradient><radialGradient id="i1HMdpb" cx="0" cy="0" r="1" gradientTransform="rotate(152.771 13.981 8.59)scale(1.43519 1.55959)" gradientUnits="userSpaceOnUse"><stop class="b5-p3qb9c"/><stop offset="1" class="fd7whqb6j"/></radialGradient><radialGradient id="iL8f3fc" cx="0" cy="0" r="1" gradientTransform="rotate(152.771 13.6 10.16)scale(1.43519 1.55959)" gradientUnits="userSpaceOnUse"><stop class="b5-p3qb9c"/><stop offset="1" class="fd7whqb6j"/></radialGradient><radialGradient id="iPLEXfc" cx="0" cy="0" r="1" gradientTransform="rotate(152.771 13.2 11.816)scale(1.43519 1.55959)" gradientUnits="userSpaceOnUse"><stop class="b5-p3qb9c"/><stop offset="1" class="fd7whqb6j"/></radialGradient><radialGradient id="iey2GAd" cx="0" cy="0" r="1" gradientTransform="rotate(152.771 12.808 13.433)scale(1.43519 1.55959)" gradientUnits="userSpaceOnUse"><stop class="b5-p3qb9c"/><stop offset="1" class="fd7whqb6j"/></radialGradient><radialGradient id="iAzNmte" cx="0" cy="0" r="1" gradientTransform="matrix(-2.71365 .62051 -.36016 -1.57506 30.561 22.858)" gradientUnits="userSpaceOnUse"><stop class="b5-p3qb9c"/><stop offset="1" class="fd7whqb6j"/></radialGradient><radialGradient id="ib8oEmd" cx="0" cy="0" r="1" gradientTransform="rotate(-130.951 14.911 -1.938)scale(7.36342 8.27806)" gradientUnits="userSpaceOnUse"><stop offset=".7" class="naovrub_y"/><stop offset="1" class="pbxzhobpk"/></radialGradient><radialGradient id="izHNnFb" cx="0" cy="0" r="1" gradientTransform="rotate(108.36 2.101 5.255)scale(5.17613 2.6344)" gradientUnits="userSpaceOnUse"><stop class="l0esiybuz"/><stop offset="1" class="dekvgdc_l"/></radialGradient><radialGradient id="iW1bwMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.19507 -3.85938 .99292 .30746 7.984 11.15)" gradientUnits="userSpaceOnUse"><stop class="ghz4lqyrp"/><stop offset=".731" class="mv9zogjid"/></radialGradient><radialGradient id="igVDX2b" cx="0" cy="0" r="1" gradientTransform="matrix(1.38995 0 0 2.90947 5.288 7.732)" gradientUnits="userSpaceOnUse"><stop class="ghz4lqyrp"/><stop offset=".737" class="mv9zogjid"/></radialGradient><radialGradient id="irqMR9c" cx="0" cy="0" r="1" gradientTransform="matrix(-.01123 1.61355 -1.59946 -.01113 6.8 6.512)" gradientUnits="userSpaceOnUse"><stop offset=".208" class="a-o37pt_y"/><stop offset="1" class="v4_wg-bls"/></radialGradient><radialGradient id="iQZzect" cx="0" cy="0" r="1" gradientTransform="matrix(1.75476 1.5921 -1.85432 2.04377 2.852 12.403)" gradientUnits="userSpaceOnUse"><stop class="zkfwggb0z"/><stop offset="1" class="h9h0qtumf"/></radialGradient><radialGradient id="iDgEMUb" cx="0" cy="0" r="1" gradientTransform="rotate(-118.56 11.573 9.123)scale(8.64576 13.9308)" gradientUnits="userSpaceOnUse"><stop class="qjy0-zbea"/><stop offset="1" class="cc-g6acdv"/></radialGradient><radialGradient id="ixhbM4c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.88318 5.86963 -4.49237 -1.4413 9.897 18.518)" gradientUnits="userSpaceOnUse"><stop class="t0_lgd09e"/><stop offset="1" class="j8wf2nbfu"/></radialGradient><radialGradient id="iRuotQc" cx="0" cy="0" r="1" gradientTransform="matrix(-8.9592 6.79794 -9.19154 -12.1138 21.895 15.016)" gradientUnits="userSpaceOnUse"><stop class="nm8szrbdu"/><stop offset="1" class="m8zsnf8bc"/></radialGradient><radialGradient id="igdz5xd" cx="0" cy="0" r="1" gradientTransform="rotate(170.277 12.1 7.563)scale(9.29475 12.3673)" gradientUnits="userSpaceOnUse"><stop class="p1_uitujj"/><stop offset="1" class="is9y73bhd"/></radialGradient><radialGradient id="iucaPAe" cx="0" cy="0" r="1" gradientTransform="matrix(-6.71873 -4.2338 6.53284 -10.36714 25.442 24.24)" gradientUnits="userSpaceOnUse"><stop offset=".098" class="ln4b4mrye"/><stop offset=".863" class="ow8f4d-wg"/></radialGradient><radialGradient id="i8SSe5b" cx="0" cy="0" r="1" gradientTransform="matrix(-6.60037 -6.6794 5.43575 -5.37143 14.835 26.938)" gradientUnits="userSpaceOnUse"><stop offset=".368" class="qjy0-zbea"/><stop offset="1" class="cc-g6acdv"/></radialGradient><radialGradient id="iXm1ZIw" cx="0" cy="0" r="1" gradientTransform="matrix(-12.92524 -3.20634 2.69983 -10.88343 20.479 20.244)" gradientUnits="userSpaceOnUse"><stop offset=".833" class="d39hg2gif"/><stop offset="1" class="m4r5igllj"/></radialGradient><radialGradient id="iXBOiCd" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 .5625 -.5015 -.3622 6.913 6.363)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="i8BgdRb" cx="0" cy="0" r="1" gradientTransform="rotate(137.643 2.237 4.546)scale(.35946 .31624)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="iv6cjtb" cx="0" cy="0" r="1" gradientTransform="matrix(8.1408 3.68912 -2.60203 5.74192 16.756 16.23)" gradientUnits="userSpaceOnUse"><stop class="x05re6a6e"/><stop offset="1" class="iv7-s7bnt"/></radialGradient><linearGradient id="i9A65ze" x1="12.212" x2="13.141" y1="28.012" y2="28.111" gradientUnits="userSpaceOnUse"><stop class="g84i42buk"/><stop offset=".689" class="pfw5_m13q"/></linearGradient><linearGradient id="iysmZge" x1="13.048" x2="13.141" y1="29.237" y2="28.111" gradientUnits="userSpaceOnUse"><stop class="g84i42buk"/><stop offset=".689" class="pfw5_m13q"/></linearGradient><linearGradient id="iKLDDXB" x1="16.196" x2="17.125" y1="28.012" y2="28.111" gradientUnits="userSpaceOnUse"><stop class="g84i42buk"/><stop offset=".689" class="pfw5_m13q"/></linearGradient><linearGradient id="isq16ce" x1="17.033" x2="17.125" y1="29.237" y2="28.111" gradientUnits="userSpaceOnUse"><stop class="g84i42buk"/><stop offset=".689" class="pfw5_m13q"/></linearGradient><linearGradient id="iETFecb" x1="11.782" x2="11.782" y1="29.146" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="j4t5ayz5c"/><stop offset="1" class="wnnoyce8k"/></linearGradient><linearGradient id="ivPj3Ec" x1="11.782" x2="11.782" y1="29.998" y2="29.797" gradientUnits="userSpaceOnUse"><stop class="jed_dd41j"/><stop offset="1" class="rku61abky"/></linearGradient><linearGradient id="i1nl7JT" x1="13.247" x2="11.923" y1="29.966" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="j4t5ayz5c"/><stop offset="1" class="azlhml69r"/></linearGradient><linearGradient id="iIVQQne" x1="16.763" x2="16.763" y1="29.146" y2="29.966" gradientUnits="userSpaceOnUse"><stop class="j4t5ayz5c"/><stop offset="1" class="wnnoyce8k"/></linearGradient><linearGradient id="i7p2s1b" x1="16.763" x2="16.763" y1="29.998" y2="29.797" gradientUnits="userSpaceOnUse"><stop class="jed_dd41j"/><stop offset="1" class="rku61abky"/></linearGradient><linearGradient id="il5Q1Oe" x1="29.001" x2="29.001" y1="2" y2="5.272" gradientUnits="userSpaceOnUse"><stop class="l5xlbus-p"/><stop offset="1" class="kohc9obge"/></linearGradient><linearGradient id="iKhIsVd" x1="28.79" x2="28.79" y1="5.219" y2="8.491" gradientUnits="userSpaceOnUse"><stop class="l5xlbus-p"/><stop offset="1" class="kohc9obge"/></linearGradient><linearGradient id="irbTdFb" x1="28.79" x2="28.79" y1="8.625" y2="11.897" gradientUnits="userSpaceOnUse"><stop class="l5xlbus-p"/><stop offset="1" class="kohc9obge"/></linearGradient><linearGradient id="ib5wuPe" x1="28.79" x2="28.79" y1="11.766" y2="15.038" gradientUnits="userSpaceOnUse"><stop class="l5xlbus-p"/><stop offset="1" class="kohc9obge"/></linearGradient><linearGradient id="it0HtHd" x1="28.79" x2="28.79" y1="15.078" y2="18.351" gradientUnits="userSpaceOnUse"><stop class="l5xlbus-p"/><stop offset="1" class="kohc9obge"/></linearGradient><linearGradient id="iCpeqvd" x1="28.79" x2="28.79" y1="18.313" y2="21.585" gradientUnits="userSpaceOnUse"><stop class="l5xlbus-p"/><stop offset="1" class="kohc9obge"/></linearGradient><linearGradient id="iRXyRSc" x1="27.259" x2="27.259" y1="21.719" y2="24.811" gradientUnits="userSpaceOnUse"><stop class="l5xlbus-p"/><stop offset="1" class="kohc9obge"/></linearGradient><linearGradient id="iKlbKIe" x1="28.092" x2="28.092" y1="26.049" y2="23.517" gradientUnits="userSpaceOnUse"><stop class="bodx_jbsn"/><stop offset="1" class="lvklgbboy"/></linearGradient><linearGradient id="inbNLUd" x1="26.425" x2="26.425" y1="8.069" y2="16.448" gradientUnits="userSpaceOnUse"><stop class="naovrub_y"/><stop offset="1" class="pbxzhobpk"/></linearGradient><linearGradient id="iGywhae" x1="18.06" x2="23.212" y1="26.036" y2="20.585" gradientUnits="userSpaceOnUse"><stop class="ctp2f-ddv"/><stop offset="1" class="gob4z2k0d"/></linearGradient><linearGradient id="i1mn5te" x1="3.789" x2="3.789" y1="6.689" y2="8.766" gradientUnits="userSpaceOnUse"><stop class="jkfjydppz"/><stop offset="1" class="zrbodeqjf"/></linearGradient><linearGradient id="inZMrVd" x1="5.056" x2="5.056" y1="5.578" y2="10" gradientUnits="userSpaceOnUse"><stop class="v4svkvbyq"/><stop offset="1" class="vdipuqb2z"/></linearGradient><linearGradient id="iEVcDpd" x1="6.667" x2="6.324" y1="6.131" y2="5.912" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="iKB4y5b" x1="3.481" x2="4.842" y1="7.144" y2="7.144" gradientUnits="userSpaceOnUse"><stop class="r-8jnbbhh"/><stop offset="1" class="gd4jr8kgh"/></linearGradient><filter id="igoImbb" width="18.223" height="20.318" x="11.127" y="3.731" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4595" stdDeviation="1.25"/></filter><filter id="ioSuTCZ" width="1.607" height="1.292" x="3.035" y="6.273" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4595" stdDeviation=".125"/></filter><filter id="iCFpSmd" width=".73" height="2.611" x="4.881" y="6.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4595" stdDeviation=".125"/></filter><filter id="ilQ42Ld" width="15.882" height="11.707" x="10.82" y="11.469" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_4595" stdDeviation="1"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:turkey" /></template>
<style>
.a-o37pt_y {
  stop-color: var(--svg-color--b19cdd, #B19CDD);
}

.azlhml69r {
  stop-color: var(--svg-color--8a858a, #8A858A);
  stop-opacity: 0;
}

.b5-p3qb9c {
  stop-color: var(--svg-color--f3c092, #F3C092);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.bcq4odbyv {
  d: path("M27.431 15.078h1.016a1.703 1.703 0 0 1 0 3.406H27.43z");
}

.bodx_jbsn {
  stop-color: var(--svg-color--cd7e8e, #CD7E8E);
}

.br2zzo91n {
  d: path("m4.392 6.523l-1.107.792h1.107z");
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.cc-g6acdv {
  stop-color: var(--svg-color--5a2846, #5A2846);
  stop-opacity: 0;
}

.ctp2f-ddv {
  stop-color: var(--svg-color--a35f50, #A35F50);
}

.d349wtbqb {
  fill: var(--svg-color--a99cb7, #A99CB7);
  d: path("m16 29.063l.61-4.375h1.64l-.656 4.375z");
}

.d39hg2gif {
  stop-color: var(--svg-color--665044, #665044);
  stop-opacity: 0;
}

.dekvgdc_l {
  stop-color: var(--svg-color--e85897, #E85897);
  stop-opacity: 0;
}

.derelpwjr {
  d: path("M8.59 9.583c.084-.243.164-.534.227-.848l.252-.942q.109-.326.11-.689a2.189 2.189 0 1 0-3.751 1.532q.093.318.197.583c.453 1.156.484 2.64-.766 2.797c-2.108.263-2.583 1.713-2.593 2.578V18.5H5.53l1.914-5.583l.21.167z");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.eec65cbsr {
  d: path("M27.431 11.766h1.016a1.703 1.703 0 0 1 0 3.406H27.43z");
}

.evwk91m1l {
  d: path("M19.203 14.125c-1.986-1.703-4.015-2.062-4.937-2.062c-4.625 0-6.032 4.343-6.032 5.906c0 6.047 4.594 7 8.125 7h8.844c.438 0 1.39-.36 1.938-1.219c.302-.475.632-1.633-.563-2.828c-1.734-1.672-5.297-5.016-7.375-6.797");
}

.exgttbbry {
  d: path("m3.115 7.145l1.62-1.192v2.813l-1.623-1.22a.25.25 0 0 1 .003-.401");
}

.fcd7kc9-u {
  d: path("M24.369 21.719h4.171a1.61 1.61 0 1 1 0 3.219h-4.17z");
}

.fd7whqb6j {
  stop-color: var(--svg-color--f3c092, #F3C092);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g84i42buk {
  stop-color: var(--svg-color--8b8390, #8B8390);
}

.gd4jr8kgh {
  stop-color: var(--svg-color--ffd765, #FFD765);
  stop-opacity: 0;
}

.ghz4lqyrp {
  stop-color: var(--svg-color--9a0a37, #9A0A37);
}

.gob4z2k0d {
  stop-color: var(--svg-color--a35f50, #A35F50);
  stop-opacity: 0;
}

.gs6nzbcwo {
  fill: var(--svg-color--5b3a2a, #5B3A2A);
  d: path("M8.328 24.969c-2.042-.146-6.062-1.422-6.062-6.89c0-3.06 2.343-4.72 4.64-5.907c.69-.357.864-.562 1.016-.985c.857-2.381 3.969-6.124 9.312-6.124c6.97 0 10.907 7.718 10.907 12v.004h.009v4.402a3.5 3.5 0 0 1-3.5 3.5z");
}

.h9h0qtumf {
  stop-color: var(--svg-color--ca5677, #CA5677);
  stop-opacity: 0;
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.i2up3qfoc {
  cx: 5.246px;
  cy: 7.404px;
  fill: var(--svg-color--eb5592, #EB5592);
  rx: 0.115px;
  ry: 1.056px;
}

.is9y73bhd {
  stop-color: var(--svg-color--8d6d5d, #8D6D5D);
  stop-opacity: 0;
}

.iv7-s7bnt {
  stop-color: var(--svg-color--816558, #816558);
  stop-opacity: 0;
}

.j2775johd {
  stop-color: var(--svg-color--735e82, #735E82);
}

.j4t5ayz5c {
  stop-color: var(--svg-color--8a858a, #8A858A);
}

.j8wf2nbfu {
  stop-color: var(--svg-color--4f332c, #4F332C);
  stop-opacity: 0;
}

.jcin7-lmi {
  fill: var(--svg-color--674430, #674430);
  d: path("M19.203 14.125c-1.986-1.703-4.015-2.062-4.937-2.062c-4.625 0-6.032 4.343-6.032 5.906c0 6.864 5.766 7 7.344 7c3.906 0 6.656-2.39 6.656-8.125a132 132 0 0 0-3.03-2.719");
}

.jed_dd41j {
  stop-color: var(--svg-color--9f79c0, #9F79C0);
}

.jkfjydppz {
  stop-color: var(--svg-color--f1c35b, #F1C35B);
}

.kohc9obge {
  stop-color: var(--svg-color--e09f6c, #E09F6C);
}

.kqvjecchm {
  cx: 20.238px;
  cy: 13.89px;
  rx: 5.419px;
  ry: 8.543px;
}

.l0esiybuz {
  stop-color: var(--svg-color--e85897, #E85897);
}

.l5xlbus-p {
  stop-color: var(--svg-color--e9af84, #E9AF84);
}

.l7oebmbar {
  fill: var(--svg-color--c21b6b, #C21B6B);
  d: path("M8.59 9.583c.084-.243.164-.534.227-.848l.252-.942q.109-.326.11-.689a2.189 2.189 0 1 0-3.751 1.532q.093.318.197.583c.453 1.156.484 2.64-.766 2.797c-2.108.263-2.583 1.713-2.593 2.578V18.5H5.53l1.914-5.583l.21.167z");
}

.lgzjv11sb {
  d: path("M27.431 8.625h1.016a1.703 1.703 0 0 1 0 3.406H27.43z");
}

.ln4b4mrye {
  stop-color: var(--svg-color--694638, #694638);
}

.lvklgbboy {
  stop-color: var(--svg-color--cd7e8e, #CD7E8E);
  stop-opacity: 0;
}

.m-aqfdvrz {
  d: path("M19.203 14.125c-1.986-1.703-4.015-2.062-4.937-2.062c-4.625 0-6.032 4.343-6.032 5.906c0 6.864 5.766 7 7.344 7c3.906 0 6.656-2.39 6.656-8.125a132 132 0 0 0-3.03-2.719");
}

.m4r5igllj {
  stop-color: var(--svg-color--665044, #665044);
}

.m8zsnf8bc {
  stop-color: var(--svg-color--7b5946, #7B5946);
  stop-opacity: 0;
}

.mv9zogjid {
  stop-color: var(--svg-color--9a0a37, #9A0A37);
  stop-opacity: 0;
}

.naovrub_y {
  stop-color: var(--svg-color--4e3324, #4E3324);
  stop-opacity: 0;
}

.nm8szrbdu {
  stop-color: var(--svg-color--7b5946, #7B5946);
}

.odl3_chmv {
  fill: var(--svg-color--a99cb7, #A99CB7);
  d: path("m12.016 29.063l.609-4.375h1.64l-.656 4.375z");
}

.okluc6v9l {
  d: path("M8.328 24.969c-2.042-.146-6.062-1.422-6.062-6.89c0-3.06 2.343-4.72 4.64-5.907c.69-.357.864-.562 1.016-.985c.857-2.381 3.969-6.124 9.312-6.124c6.97 0 10.907 7.718 10.907 12v.004h.009v4.402a3.5 3.5 0 0 1-3.5 3.5z");
}

.ow8f4d-wg {
  stop-color: var(--svg-color--c6975d, #C6975D);
}

.p1_uitujj {
  stop-color: var(--svg-color--8d6d5d, #8D6D5D);
}

.pbvselb1a {
  d: path("M19.14 28.973h-4.833c-.65 0-.934.33-1.01.744c-.025.136.09.249.228.249H20c.138 0 .254-.114.22-.248c-.134-.526-.691-.745-1.08-.745");
}

.pbxzhobpk {
  stop-color: var(--svg-color--4e3324, #4E3324);
}

.pfw5_m13q {
  stop-color: var(--svg-color--8b8390, #8B8390);
  stop-opacity: 0;
}

.q27gc5b6o {
  width: 1.049px;
  height: 4.422px;
  x: 4.531px;
  y: 5.578px;
  rx: 0.524px;
}

.q8wpksbws {
  stop-color: var(--svg-color--735e82, #735E82);
  stop-opacity: 0;
}

.qjy0-zbea {
  stop-color: var(--svg-color--612c4c, #612C4C);
}

.qlgj9mbxt {
  d: path("M14.16 28.973H9.326c-.65 0-.934.33-1.01.744c-.025.136.09.249.228.249h6.475c.138 0 .254-.114.22-.248c-.134-.526-.691-.745-1.08-.745");
}

.r-8jnbbhh {
  stop-color: var(--svg-color--ffd765, #FFD765);
}

.rgjn5cbxy {
  d: path("m18.426 14.71l6.276 5.767c-1.515.528-5.349 1.266-8.567 0c-4.021-1.582-3.917-5.302-2.149-6.555c1.517-1.075 3.598 0 4.44.787");
}

.rku61abky {
  stop-color: var(--svg-color--9f79c0, #9F79C0);
  stop-opacity: 0;
}

.sw5t8obgx {
  d: path("m12.016 29.063l.609-4.375h1.64l-.656 4.375z");
}

.t0_lgd09e {
  stop-color: var(--svg-color--412720, #412720);
}

.tlkisu1jf {
  d: path("M27.853 2h.594a1.703 1.703 0 0 1 0 3.406h-.594z");
}

.twwsfzbtn {
  cx: 6.766px;
  cy: 6.523px;
  r: 0.5px;
}

.uqn0he-oh {
  fill: var(--svg-color--68473c, #68473C);
  d: path("M19.536 8a6 6 0 0 1 6-6h2.614v17.969a5 5 0 0 1-5 5h-3.614z");
}

.v4_wg-bls {
  stop-color: var(--svg-color--b19cdd, #B19CDD);
  stop-opacity: 0;
}

.v4svkvbyq {
  stop-color: var(--svg-color--e54f8e, #E54F8E);
}

.v96g48b_b {
  d: path("M27.431 5.219h1.016a1.703 1.703 0 0 1 0 3.406H27.43z");
}

.vdipuqb2z {
  stop-color: var(--svg-color--bc0c44, #BC0C44);
}

.vyz8zj0vc {
  d: path("m16 29.063l.61-4.375h1.64l-.656 4.375z");
}

.wgemjbc-y {
  d: path("M27.431 18.313h1.016a1.703 1.703 0 0 1 0 3.406H27.43z");
}

.wnnoyce8k {
  stop-color: var(--svg-color--b6abc1, #B6ABC1);
}

.x05re6a6e {
  stop-color: var(--svg-color--816558, #816558);
}

.xm5a4hb_m {
  d: path("M19.536 8a6 6 0 0 1 6-6h2.614v17.969a5 5 0 0 1-5 5h-3.614z");
}

.zkfwggb0z {
  stop-color: var(--svg-color--ca5677, #CA5677);
}

.zrbodeqjf {
  stop-color: var(--svg-color--ce8b36, #CE8B36);
}

</style>
