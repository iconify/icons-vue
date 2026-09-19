<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iMZ6dBH)" class="r5xw9bb4t"/><path fill="url(#i3BnrAe)" class="r5xw9bb4t"/><path fill="url(#is8dtbd)" class="r5xw9bb4t"/><path fill="url(#iClorQe)" class="r5xw9bb4t"/><path fill="url(#ibxrkrc)" class="r5xw9bb4t"/><g filter="url(#iDCHA8B)"><path fill="url(#iCaBvte)" class="tr_qaib-r"/></g><path fill="url(#iYoKyOe)" class="veri86b0r"/><path fill="url(#iEbxYJb)" class="veri86b0r"/><path fill="url(#i6MFXJd)" class="veri86b0r"/><path fill="url(#igGwFGd)" class="veri86b0r"/><g filter="url(#iBOuJSq)"><path fill="url(#iTMMe8c)" class="ydvw7w2vb"/></g><g filter="url(#iw0a0hd)"><path fill="url(#iYwwcdg)" class="koo8w42-j"/></g><g filter="url(#iqCzdzY)"><path fill="url(#iUrjDjd)" class="t0u33nk1d"/></g><g filter="url(#ifJsM6b)"><path fill="url(#ioKf9xb)" class="m1r4adbzk"/><path fill="url(#iXnWBve)" class="m1r4adbzk"/><path fill="url(#iCtX1Rb)" class="m1r4adbzk"/><path fill="url(#iYz9BAb)" class="m1r4adbzk"/></g><g filter="url(#iTRmpfe)"><path stroke="url(#ixHKOYd)" class="ud1ytjbcu"/></g><defs><linearGradient id="iMZ6dBH" x1="15.484" x2="15.484" y1="7.684" y2="19.238" gradientUnits="userSpaceOnUse"><stop class="q14vtsg7s"/><stop offset="1" class="jp48jvrnx"/></linearGradient><linearGradient id="i3BnrAe" x1="15.484" x2="15.484" y1="7.684" y2="19.238" gradientUnits="userSpaceOnUse"><stop class="q14vtsg7s"/><stop offset="1" class="iv85m5bqf"/></linearGradient><linearGradient id="is8dtbd" x1="13.712" x2="14.961" y1="18.378" y2="18.378" gradientUnits="userSpaceOnUse"><stop class="r-lmltjbo"/><stop offset="1" class="ko7j7zp0h"/></linearGradient><linearGradient id="iClorQe" x1="14.679" x2="15.042" y1="8.438" y2="9.631" gradientUnits="userSpaceOnUse"><stop class="r-lmltjbo"/><stop offset="1" class="ko7j7zp0h"/></linearGradient><linearGradient id="ibxrkrc" x1="17.259" x2="16.312" y1="13.561" y2="13.622" gradientUnits="userSpaceOnUse"><stop class="r-lmltjbo"/><stop offset="1" class="ko7j7zp0h"/></linearGradient><linearGradient id="iCaBvte" x1="15.767" x2="15.767" y1="8.938" y2="21.482" gradientUnits="userSpaceOnUse"><stop class="qbvum36ni"/><stop offset="1" class="o1k2huwbo"/></linearGradient><linearGradient id="iYoKyOe" x1="19.92" x2="29.03" y1="14" y2="6.325" gradientUnits="userSpaceOnUse"><stop class="b7xr0zn5n"/><stop offset="1" class="h-p4xeboi"/></linearGradient><linearGradient id="iEbxYJb" x1="22.016" x2="22.016" y1="14.186" y2="13.339" gradientUnits="userSpaceOnUse"><stop class="jn-rhzq6l"/><stop offset="1" class="ccm_cjbxm"/></linearGradient><linearGradient id="i6MFXJd" x1="17.257" x2="18.882" y1="7.906" y2="9.813" gradientUnits="userSpaceOnUse"><stop class="x7jdx7vka"/><stop offset="1" class="xm1h4ubai"/></linearGradient><linearGradient id="iTMMe8c" x1="20.443" x2="27.529" y1="13.219" y2="7.095" gradientUnits="userSpaceOnUse"><stop class="arz153tka"/><stop offset="1" class="i07-gccqz"/></linearGradient><linearGradient id="iYwwcdg" x1="17.945" x2="3.007" y1="8.438" y2="1.375" gradientUnits="userSpaceOnUse"><stop class="bwmw7y8xa"/><stop offset="1" class="qae1eziro"/></linearGradient><linearGradient id="iUrjDjd" x1="16.9" x2="6.184" y1="7.515" y2="1.751" gradientUnits="userSpaceOnUse"><stop class="brdpmjbvk"/><stop offset="1" class="vq349yb_v"/></linearGradient><linearGradient id="iXnWBve" x1="15.52" x2="15.52" y1="30.114" y2="29.539" gradientUnits="userSpaceOnUse"><stop class="c5ic9gbti"/><stop offset="1" class="tycm1xhtr"/></linearGradient><linearGradient id="ixHKOYd" x1="15.445" x2="14.051" y1="6.875" y2="2.222" gradientUnits="userSpaceOnUse"><stop class="m1u61i9tg"/><stop offset="1" class="y6w32lb_u"/></linearGradient><filter id="iDCHA8B" width="2.565" height="14.545" x="14.484" y="7.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7560" stdDeviation=".5"/></filter><filter id="iBOuJSq" width="17.067" height="9.375" x="13.945" y="5.844" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7560" stdDeviation="1"/></filter><filter id="iw0a0hd" width="15.188" height="7.188" x="2" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.507148 0 0 0 0 0.6625 0 0 0 0 0.339531 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7560"/></filter><filter id="iqCzdzY" width="16.605" height="8.781" x="1.445" y="1.078" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7560" stdDeviation="1"/></filter><filter id="ifJsM6b" width="19.092" height="9.202" x="6.049" y="20.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy=".15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.556863 0 0 0 0 0.490196 0 0 0 0 0.486275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_7560"/></filter><filter id="iTRmpfe" width="6.844" height="6.656" x="10.414" y="2.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_7560" stdDeviation=".5"/></filter><radialGradient id="igGwFGd" cx="0" cy="0" r="1" gradientTransform="rotate(145.134 14.004 8.277)scale(4.64659 .54368)" gradientUnits="userSpaceOnUse"><stop class="pqbczpsck"/><stop offset="1" class="hte_6b1lw"/></radialGradient><radialGradient id="ioKf9xb" cx="0" cy="0" r="1" gradientTransform="matrix(-8.01691 -7.84882 7.49547 -7.65599 19.934 30.744)" gradientUnits="userSpaceOnUse"><stop class="h_dr_5bcr"/><stop offset="1" class="twhqp6bhx"/></radialGradient><radialGradient id="iCtX1Rb" cx="0" cy="0" r="1" gradientTransform="rotate(-75.259 26.272 8.012)scale(6.91894 5.0108)" gradientUnits="userSpaceOnUse"><stop class="w19gininy"/><stop offset="1" class="n_2_mabya"/></radialGradient><radialGradient id="iYz9BAb" cx="0" cy="0" r="1" gradientTransform="rotate(134.291 8.278 15.817)scale(6.32327 11.5294)" gradientUnits="userSpaceOnUse"><stop class="h_dr_5bcr"/><stop offset="1" class="ryyf4cbfs"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:seedling" /></template>
<style>
.arz153tka {
  stop-color: var(--svg-color--a0cc4c, #A0CC4C);
}

.b7xr0zn5n {
  stop-color: var(--svg-color--8db746, #8DB746);
}

.brdpmjbvk {
  stop-color: var(--svg-color--b6eb53, #B6EB53);
}

.bwmw7y8xa {
  stop-color: var(--svg-color--97da22, #97DA22);
}

.c5ic9gbti {
  stop-color: var(--svg-color--964972, #964972);
}

.ccm_cjbxm {
  stop-color: var(--svg-color--97b86e, #97B86E);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.h_dr_5bcr {
  stop-color: var(--svg-color--bf8b88, #BF8B88);
}

.h-p4xeboi {
  stop-color: var(--svg-color--abee48, #ABEE48);
}

.hte_6b1lw {
  stop-color: var(--svg-color--cbff78, #CBFF78);
  stop-opacity: 0;
}

.i07-gccqz {
  stop-color: var(--svg-color--c2fd65, #C2FD65);
}

.iv85m5bqf {
  stop-color: var(--svg-color--97d630, #97D630);
}

.jn-rhzq6l {
  stop-color: var(--svg-color--97b86e, #97B86E);
}

.jp48jvrnx {
  stop-color: var(--svg-color--94d22f, #94D22F);
}

.ko7j7zp0h {
  stop-color: var(--svg-color--86b95c, #86B95C);
  stop-opacity: 0;
}

.koo8w42-j {
  d: path("M16.938 8.53c0-3.607-3.329-6.296-7.891-6.53H2.408A.41.41 0 0 0 2 2.408c.408 3.873 2.563 6.217 7.656 6.53h6.873a.41.41 0 0 0 .409-.409");
}

.m1r4adbzk {
  d: path("M15.515 20.938c-5.06 0-9.193 3.785-9.465 8.552c-.016.276.21.5.486.5h17.968a.48.48 0 0 0 .486-.5c-.272-4.767-4.406-8.552-9.475-8.552");
}

.m1u61i9tg {
  stop-color: var(--svg-color--d1ff77, #D1FF77);
}

.n_2_mabya {
  stop-color: var(--svg-color--a3646d, #A3646D);
  stop-opacity: 0;
}

.o1k2huwbo {
  stop-color: var(--svg-color--bcf461, #BCF461);
}

.pqbczpsck {
  stop-color: var(--svg-color--cbff78, #CBFF78);
}

.q14vtsg7s {
  stop-color: var(--svg-color--82bb30, #82BB30);
}

.qae1eziro {
  stop-color: var(--svg-color--90cd2f, #90CD2F);
}

.qbvum36ni {
  stop-color: var(--svg-color--9ed75b, #9ED75B);
}

.r-lmltjbo {
  stop-color: var(--svg-color--86b95c, #86B95C);
}

.r5xw9bb4t {
  d: path("M14.031 8.438h2.906v14.016h-2.906z");
}

.ryyf4cbfs {
  stop-color: var(--svg-color--bf8b88, #BF8B88);
  stop-opacity: 0;
}

.t0u33nk1d {
  d: path("M16.05 7.578c0-2.485-2.809-4.338-6.659-4.5H3.79c-.19 0-.344.126-.344.281c.344 2.67 2.162 4.285 6.46 4.5h5.8c.19 0 .345-.126.345-.28");
}

.tr_qaib-r {
  d: path("M15.484 8.938h.565v12.545h-.565z");
}

.twhqp6bhx {
  stop-color: var(--svg-color--835146, #835146);
}

.tycm1xhtr {
  stop-color: var(--svg-color--964972, #964972);
  stop-opacity: 0;
}

.ud1ytjbcu {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M11.664 3.281c1.156.219 3.643 1.357 4.343 4.156");
}

.veri86b0r {
  d: path("M15 13.592c0-3.606 3.328-6.295 7.89-6.53h6.64c.225 0 .407.183.407.409c-.408 3.873-2.562 6.217-7.656 6.529h-6.873a.41.41 0 0 1-.408-.408");
}

.vq349yb_v {
  stop-color: var(--svg-color--a0d930, #A0D930);
}

.w19gininy {
  stop-color: var(--svg-color--a3646d, #A3646D);
}

.x7jdx7vka {
  stop-color: var(--svg-color--6caf09, #6CAF09);
}

.xm1h4ubai {
  stop-color: var(--svg-color--6caf09, #6CAF09);
  stop-opacity: 0;
}

.y6w32lb_u {
  stop-color: var(--svg-color--d1ff77, #D1FF77);
  stop-opacity: 0;
}

.ydvw7w2vb {
  d: path("M15.945 12.903c0-2.794 3.233-4.877 6.859-5.059h5.883a.32.32 0 0 1 .325.316c-.325 3-2.644 4.817-6.692 5.059h-6.05a.32.32 0 0 1-.325-.316");
}

</style>
