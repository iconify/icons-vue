<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iVFbIee)"><path fill="url(#irXFtld)" class="wp1cdeorw"/><path fill="url(#iH4ADPc)" class="wp1cdeorw"/><path fill="url(#ipShgLc)" class="wp1cdeorw"/><path fill="url(#i7AUeGe)" class="wp1cdeorw"/><path fill="url(#i4NgPFW)" class="wp1cdeorw"/><path fill="url(#i9hoIgb)" class="wp1cdeorw"/><path fill="url(#iUpUMyb)" class="wp1cdeorw"/><path fill="url(#iT4PCzP)" class="wp1cdeorw"/><path fill="url(#iBtOBCb)" class="wp1cdeorw"/></g><path fill="url(#idDpMue)" class="wp1cdeorw"/><path fill="url(#iUQDiUl)" class="wp1cdeorw"/><rect fill="url(#iYVXb8d)" class="qdgvbqb6v"/><rect fill="url(#ix4r3yb)" class="qdgvbqb6v"/><rect fill="url(#i9Ea23d)" class="qdgvbqb6v"/><rect fill="url(#ilw9yjd)" class="qdgvbqb6v"/><rect fill="url(#inRMKOW)" class="qdgvbqb6v"/><g filter="url(#ib7AOuc)"><path stroke="url(#i9MnDUb)" class="tmqhfbceo"/></g><g filter="url(#iCAjcye)"><path stroke="url(#i02TQTl)" class="f8wdq_33a"/></g><g filter="url(#ihQ237b)"><path stroke="url(#iqBLhTk)" class="pjn9lrbag"/></g><g filter="url(#iVaoABz)"><path stroke="url(#iFioQLb)" class="dox196kfo"/></g><defs><radialGradient id="irXFtld" cx="0" cy="0" r="1" gradientTransform="rotate(130.4 8.806 12.704)scale(19.2866 13.5561)" gradientUnits="userSpaceOnUse"><stop class="lcth72b9z"/><stop offset="1" class="bsl0wmbeb"/></radialGradient><radialGradient id="iH4ADPc" cx="0" cy="0" r="1" gradientTransform="matrix(1.21984 2.8015 -2.42064 1.054 8.749 13.46)" gradientUnits="userSpaceOnUse"><stop class="r6tsfnx-o"/><stop offset="1" class="e8b1pzv7o"/></radialGradient><radialGradient id="ipShgLc" cx="0" cy="0" r="1" gradientTransform="matrix(.2806 2.65005 -2.93551 .31082 7.512 15.167)" gradientUnits="userSpaceOnUse"><stop class="pc5ickb1s"/><stop offset="1" class="y7m35izbd"/></radialGradient><radialGradient id="i7AUeGe" cx="0" cy="0" r="1" gradientTransform="rotate(-56.31 20.129 -10.9)scale(1.88757 1.05297)" gradientUnits="userSpaceOnUse"><stop class="jrorz2brg"/><stop offset="1" class="k42pcrb3z"/></radialGradient><radialGradient id="i4NgPFW" cx="0" cy="0" r="1" gradientTransform="rotate(133.299 9.01 10.904)scale(2.23279 1.21415)" gradientUnits="userSpaceOnUse"><stop class="e78toubnb"/><stop offset="1" class="multbabgb"/></radialGradient><radialGradient id="i9hoIgb" cx="0" cy="0" r="1" gradientTransform="rotate(130.957 9.912 12.476)scale(2.93794 3.62296)" gradientUnits="userSpaceOnUse"><stop class="kbo191odp"/><stop offset="1" class="o2e2yg2hs"/></radialGradient><radialGradient id="iUpUMyb" cx="0" cy="0" r="1" gradientTransform="matrix(-.95712 2.1193 -1.60697 -.72574 20.544 12.548)" gradientUnits="userSpaceOnUse"><stop class="x60c6xe9b"/><stop offset="1" class="dd8zj1bmv"/></radialGradient><radialGradient id="iT4PCzP" cx="0" cy="0" r="1" gradientTransform="rotate(46.202 -13.83 17.72)scale(1.58029 .60823)" gradientUnits="userSpaceOnUse"><stop class="e2ry-wb8u"/><stop offset="1" class="mb1uuzf2o"/></radialGradient><radialGradient id="iBtOBCb" cx="0" cy="0" r="1" gradientTransform="matrix(.85937 2.34375 -1.4916 .54692 12.39 11.75)" gradientUnits="userSpaceOnUse"><stop class="ky4gkvdcl"/><stop offset="1" class="ktfil916y"/></radialGradient><radialGradient id="idDpMue" cx="0" cy="0" r="1" gradientTransform="matrix(-18.56652 4.0743 -6.61005 -30.12186 25.541 19.046)" gradientUnits="userSpaceOnUse"><stop offset=".866" class="a4ub-dbws"/><stop offset="1" class="dl4ua154c"/></radialGradient><radialGradient id="iUQDiUl" cx="0" cy="0" r="1" gradientTransform="matrix(-18.34738 4.08297 -6.6241 -29.76625 25.541 19.046)" gradientUnits="userSpaceOnUse"><stop offset=".976" class="g0v90brwv"/><stop offset="1" class="ic9qs4bvm"/></radialGradient><radialGradient id="inRMKOW" cx="0" cy="0" r="1" gradientTransform="matrix(.87792 2.66303 -4.99485 1.64666 13.84 1.586)" gradientUnits="userSpaceOnUse"><stop class="pq4lllb0k"/><stop offset="1" class="rhpvu1b3z"/></radialGradient><linearGradient id="iYVXb8d" x1="13.092" x2="15.793" y1="9.749" y2="9.749" gradientUnits="userSpaceOnUse"><stop class="um_hu_bgx"/><stop offset="1" class="z20z7hb0c"/></linearGradient><linearGradient id="ix4r3yb" x1="18.889" x2="15.27" y1="10.752" y2="11.319" gradientUnits="userSpaceOnUse"><stop class="s_dd3uu0h"/><stop offset="1" class="rzhcoccay"/></linearGradient><linearGradient id="i9Ea23d" x1="14.733" x2="13.759" y1="14.257" y2="15.59" gradientUnits="userSpaceOnUse"><stop class="svfkjdxef"/><stop offset="1" class="qk70xkspj"/></linearGradient><linearGradient id="ilw9yjd" x1="15.314" x2="17.057" y1="14.564" y2="15.829" gradientUnits="userSpaceOnUse"><stop class="c0lm2obrz"/><stop offset="1" class="phzimb_8u"/></linearGradient><linearGradient id="i9MnDUb" x1="24.565" x2="20.575" y1="14.233" y2="30.023" gradientUnits="userSpaceOnUse"><stop class="icjbfbcsz"/><stop offset="1" class="l9j77zbpn"/></linearGradient><linearGradient id="i02TQTl" x1="17.212" x2="9.854" y1="3.263" y2="15.365" gradientUnits="userSpaceOnUse"><stop class="p2z6wx8lk"/><stop offset="1" class="jgmao3b6b"/></linearGradient><linearGradient id="iqBLhTk" x1="17.974" x2="17.68" y1="13.216" y2="17.424" gradientUnits="userSpaceOnUse"><stop class="r3nsh4-st"/><stop offset="1" class="p8puokbgn"/></linearGradient><linearGradient id="iFioQLb" x1="11.656" x2="11.966" y1="12.844" y2="16.588" gradientUnits="userSpaceOnUse"><stop class="u84w_k1bo"/><stop offset="1" class="l2joofb_x"/></linearGradient><filter id="iVFbIee" width="19.914" height="28.977" x="6.168" y=".981" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-1"/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.717647 0 0 0 0 0.443137 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5380"/></filter><filter id="ib7AOuc" width="8.938" height="16.887" x="18.359" y="11.656" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5380" stdDeviation="1.25"/></filter><filter id="iCAjcye" width="3.75" height="13.8" x="14.125" y="2.252" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5380" stdDeviation=".625"/></filter><filter id="ihQ237b" width="4.222" height="4.735" x="14.28" y="12.265" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5380" stdDeviation=".375"/></filter><filter id="iVaoABz" width="4.722" height="5.235" x="11.398" y="12.015" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5380" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:middle-finger-medium-light" /></template>
<style>
.a4ub-dbws {
  stop-color: var(--svg-color--cd917e, #CD917E);
  stop-opacity: 0;
}

.bsl0wmbeb {
  stop-color: var(--svg-color--dea492, #DEA492);
}

.c0lm2obrz {
  stop-color: var(--svg-color--e9b197, #E9B197);
  stop-opacity: 0;
}

.dd8zj1bmv {
  stop-color: var(--svg-color--fecca5, #FECCA5);
  stop-opacity: 0;
}

.dl4ua154c {
  stop-color: var(--svg-color--cd917e, #CD917E);
}

.dox196kfo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m14.87 16l-2.222-2.735");
}

.e2ry-wb8u {
  stop-color: var(--svg-color--be8562, #BE8562);
}

.e78toubnb {
  stop-color: var(--svg-color--d6a37c, #D6A37C);
}

.e8b1pzv7o {
  stop-color: var(--svg-color--ca9977, #CA9977);
  stop-opacity: 0;
}

.f8wdq_33a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M16 4.127v10.05");
}

.ft5dv1b6b {
  fill: none;
}

.g0v90brwv {
  stop-color: var(--svg-color--dc9f89, #DC9F89);
  stop-opacity: 0;
}

.ic9qs4bvm {
  stop-color: var(--svg-color--dc9f89, #DC9F89);
}

.icjbfbcsz {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
}

.jgmao3b6b {
  stop-color: var(--svg-color--fecda8, #FECDA8);
  stop-opacity: 0;
}

.jrorz2brg {
  stop-color: var(--svg-color--cf966c, #CF966C);
}

.k42pcrb3z {
  stop-color: var(--svg-color--cf966c, #CF966C);
  stop-opacity: 0;
}

.kbo191odp {
  stop-color: var(--svg-color--f4c69d, #F4C69D);
}

.ktfil916y {
  stop-color: var(--svg-color--b37c5b, #B37C5B);
  stop-opacity: 0;
}

.ky4gkvdcl {
  stop-color: var(--svg-color--b37c5b, #B37C5B);
}

.l2joofb_x {
  stop-color: var(--svg-color--ba815e, #BA815E);
  stop-opacity: 0;
}

.l9j77zbpn {
  stop-color: var(--svg-color--ffd0aa, #FFD0AA);
  stop-opacity: 0;
}

.lcth72b9z {
  stop-color: var(--svg-color--f1ba9a, #F1BA9A);
}

.mb1uuzf2o {
  stop-color: var(--svg-color--be8562, #BE8562);
  stop-opacity: 0;
}

.multbabgb {
  stop-color: var(--svg-color--d6a37c, #D6A37C);
  stop-opacity: 0;
}

.o2e2yg2hs {
  stop-color: var(--svg-color--f4c69d, #F4C69D);
  stop-opacity: 0;
}

.p2z6wx8lk {
  stop-color: var(--svg-color--fecda8, #FECDA8);
}

.p8puokbgn {
  stop-color: var(--svg-color--ffceaa, #FFCEAA);
  stop-opacity: 0;
}

.pc5ickb1s {
  stop-color: var(--svg-color--bf8867, #BF8867);
}

.phzimb_8u {
  stop-color: var(--svg-color--e9b197, #E9B197);
}

.pjn9lrbag {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m15.28 16l2.222-2.735");
}

.pq4lllb0k {
  stop-color: var(--svg-color--c79a79, #C79A79);
}

.qdgvbqb6v {
  width: 4.781px;
  height: 14.813px;
  x: 12.648px;
  y: 1.981px;
  rx: 2.391px;
}

.qk70xkspj {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
}

.r3nsh4-st {
  stop-color: var(--svg-color--ffceaa, #FFCEAA);
}

.r6tsfnx-o {
  stop-color: var(--svg-color--ca9977, #CA9977);
}

.rhpvu1b3z {
  stop-color: var(--svg-color--c79a79, #C79A79);
  stop-opacity: 0;
}

.rzhcoccay {
  stop-color: var(--svg-color--f2c29c, #F2C29C);
  stop-opacity: 0;
}

.s_dd3uu0h {
  stop-color: var(--svg-color--f2c29c, #F2C29C);
}

.svfkjdxef {
  stop-color: var(--svg-color--e4ab95, #E4AB95);
  stop-opacity: 0;
}

.tmqhfbceo {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M24.048 14.906c-.046 1.015-.215 3.149-.695 5.676c-.48 2.529-1.362 4.194-1.744 4.711");
}

.u84w_k1bo {
  stop-color: var(--svg-color--ba815e, #BA815E);
}

.um_hu_bgx {
  stop-color: var(--svg-color--cf967c, #CF967C);
}

.wp1cdeorw {
  d: path("M12.645 4.371a2.39 2.39 0 0 1 4.78 0v7.588a2.391 2.391 0 0 1 4.242 1.146a2.39 2.39 0 0 1 4.119 2.07l-.29 2.853c-.117 1.242-.84 6.047-2.527 7.937c-1.825 2.456-4.576 3.992-7.645 3.992A8.353 8.353 0 0 1 7.03 22.59l-.784-4.458a2.28 2.28 0 0 1 2.6-2.835a2.602 2.602 0 0 1 3.798-3.11z");
}

.x60c6xe9b {
  stop-color: var(--svg-color--fecca5, #FECCA5);
}

.y7m35izbd {
  stop-color: var(--svg-color--bf8867, #BF8867);
  stop-opacity: 0;
}

.z20z7hb0c {
  stop-color: var(--svg-color--cf967c, #CF967C);
  stop-opacity: 0;
}

</style>
