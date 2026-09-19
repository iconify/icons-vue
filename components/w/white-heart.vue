<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iYamrgc)" class="fi-r-8b5d"/><path fill="url(#iTb0UZa)" class="fi-r-8b5d"/><path fill="url(#i82tCqc)" class="fi-r-8b5d"/><path fill="url(#iPdtsCe)" class="fi-r-8b5d"/><path fill="url(#iYifmIc)" class="fi-r-8b5d"/><path fill="url(#ife8RfW)" class="fgfdpshau"/><path fill="url(#imT3Rrd)" class="bx2w7wsuv"/><path fill="url(#ivYIGFc)" class="bx2w7wsuv"/><path fill="url(#i6w8a2b)" class="bx2w7wsuv"/><path fill="url(#iu0dYVc)" class="jqjgsf81p"/><g filter="url(#iSbhVPb)"><path fill="url(#iXopabb)" class="xl4zk2xes"/></g><g filter="url(#ikonRqe)"><path fill="url(#i8IICeI)" class="h7sijcb_i"/></g><g filter="url(#iUh2Hue)"><path stroke="url(#iUhM1Ie)" class="ylqec66vg"/></g><g filter="url(#iE7YdPd)"><path fill="url(#iQbiQCd)" class="j3mzvpbty"/></g><g filter="url(#izD4yZd)"><path stroke="url(#ig53FSc)" class="d54wskbka"/></g><g filter="url(#igwHE7b)"><path fill="url(#ilSq5LT)" class="fg83bzbli"/></g></g><defs><radialGradient id="iYamrgc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.94862 24.04125 -29.72566 -3.6458 17.924 5.9)" gradientUnits="userSpaceOnUse"><stop offset=".063" class="dwv20bwpp"/><stop offset=".463" class="r-vg0k7ei"/><stop offset="1" class="du8kaw22e"/></radialGradient><radialGradient id="iTb0UZa" cx="0" cy="0" r="1" gradientTransform="matrix(-24.3124 -6.87514 4.15616 -14.69735 23.648 15.37)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="onbsaylqo"/><stop offset="1" class="e-kppb9rh"/></radialGradient><radialGradient id="i82tCqc" cx="0" cy="0" r="1" gradientTransform="matrix(-17.1875 -13.18749 11.85052 -15.44502 19.71 18.37)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mw4dabcry"/><stop offset="1" class="t-rxjcbca"/></radialGradient><radialGradient id="iPdtsCe" cx="0" cy="0" r="1" gradientTransform="matrix(-17.1875 -13.18749 11.85052 -15.44502 19.71 18.37)" gradientUnits="userSpaceOnUse"><stop offset=".821" class="mw4dabcry"/><stop offset="1" class="oyem64b6r"/></radialGradient><radialGradient id="iYifmIc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.25005 11.12495 -15.55588 -19.92567 18.71 11.183)" gradientUnits="userSpaceOnUse"><stop offset=".8" class="mw4dabcry"/><stop offset="1" class="t-rxjcbca"/></radialGradient><radialGradient id="ife8RfW" cx="0" cy="0" r="1" gradientTransform="matrix(-1.73372 -12.19397 16.83648 -2.39379 21.913 15.61)" gradientUnits="userSpaceOnUse"><stop offset=".565" class="mw4dabcry"/><stop offset="1" class="t-rxjcbca"/></radialGradient><radialGradient id="imT3Rrd" cx="0" cy="0" r="1" gradientTransform="scale(15.7131 15.8728)rotate(90 .06 .954)" gradientUnits="userSpaceOnUse"><stop offset=".751" class="m0vu0kq3p"/><stop offset="1" class="otqf3m3qo"/></radialGradient><radialGradient id="iXopabb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.06251 9.43753 -3.93674 -2.5289 26.106 7.178)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="iQbiQCd" cx="0" cy="0" r="1" gradientTransform="matrix(-7.12673 -5.5468 5.67683 -7.2938 14.587 15.917)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><linearGradient id="ivYIGFc" x1="16.273" x2="5.773" y1="17.246" y2="28.121" gradientUnits="userSpaceOnUse"><stop offset=".632" class="m0vu0kq3p"/><stop offset="1" class="otqf3m3qo"/></linearGradient><linearGradient id="i6w8a2b" x1="16.273" x2="25.773" y1="17.246" y2="27.464" gradientUnits="userSpaceOnUse"><stop offset=".622" class="m0vu0kq3p"/><stop offset="1" class="otqf3m3qo"/></linearGradient><linearGradient id="iu0dYVc" x1="18.908" x2="15.316" y1="11.853" y2="7.149" gradientUnits="userSpaceOnUse"><stop offset=".6" class="mw4dabcry"/><stop offset=".89" class="oyem64b6r"/></linearGradient><linearGradient id="i8IICeI" x1="20.71" x2="26.085" y1="2.871" y2="4.652" gradientUnits="userSpaceOnUse"><stop class="l7v-5hb1e"/><stop offset="1" class="k2ceuu2kb"/></linearGradient><linearGradient id="iUhM1Ie" x1="27.803" x2="24.771" y1="8.146" y2="6.396" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ig53FSc" x1="27.806" x2="17.693" y1="13.645" y2="26.474" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></linearGradient><linearGradient id="ilSq5LT" x1="15.96" x2="9.648" y1="30.496" y2="23.152" gradientUnits="userSpaceOnUse"><stop class="y5m7h3bxi"/><stop offset="1" class="v47sxv0xz"/></linearGradient><filter id="iSbhVPb" width="13.569" height="16.002" x="16.617" y="4.082" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6140" stdDeviation=".75"/></filter><filter id="ikonRqe" width="10.972" height="19.871" x="14.708" y="3.917" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6140" stdDeviation="1"/></filter><filter id="iUh2Hue" width="7.531" height="5.959" x="21.646" y="4.969" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6140" stdDeviation=".5"/></filter><filter id="iE7YdPd" width="12.852" height="21.845" x="5.214" y="3.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6140" stdDeviation="1.5"/></filter><filter id="izD4yZd" width="20.576" height="25.546" x="12.23" y="5.928" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6140" stdDeviation="2"/></filter><filter id="igwHE7b" width="14.688" height="16.938" x="3.898" y="14.683" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_7320_6140" stdDeviation="1.5"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:white-heart" /></template>
<style>
.bx2w7wsuv {
  d: path("M3.35 17.558c1.926 4.163 8.059 9.57 11.775 11.644a1.73 1.73 0 0 0 1.71-.022c3.333-1.905 8.953-6.116 11.69-11.622z");
}

.d54wskbka {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M27.807 10.929c-.636 4.507-5.78 12.02-10.576 15.545");
}

.du8kaw22e {
  stop-color: var(--svg-color--e3ccfb, #E3CCFB);
}

.dwv20bwpp {
  stop-color: var(--svg-color--f5f3f8, #F5F3F8);
}

.e-kppb9rh {
  stop-color: var(--svg-color--dcc2f7, #DCC2F7);
}

.fg83bzbli {
  d: path("M6.898 20.308c2 2.85 6.625 6.73 8.687 8.313l-2.812-10.938z");
}

.fgfdpshau {
  d: path("M24.349 23.313c1.939-2.012 3.69-4.385 4.741-7.018c3.59-7.972-4.838-14.336-10.662-9.76c-.15.12-.311.242-.475.368c-.497.38-1.027.785-1.422 1.174a.68.68 0 0 1-.454.19l-.002.003z");
}

.fi-r-8b5d {
  d: path("M15.125 29.202a1.73 1.73 0 0 0 1.71-.023c3.584-2.047 9.81-6.761 12.256-12.884c3.589-7.973-4.839-14.337-10.663-9.76c-.607.478-1.371 1.025-1.897 1.542c-.238.234-.657.258-.903.034c-.691-.63-1.772-1.436-2.465-1.905c-4.966-3.36-14 1.069-10.147 10.52c1.412 4.242 8.14 10.26 12.11 12.476");
}

.ft5dv1b6b {
  fill: none;
}

.h7sijcb_i {
  d: path("M16.708 9.32v12.468c3.002-5.667 8.852-12.573 6.377-15.48c-.835-.98-3.295-.077-6.038 2.267a.98.98 0 0 0-.339.744");
}

.j3mzvpbty {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("m14.861 9.18l.205 13.407C8.191 15.9 6.96 8.734 9.298 7.127c1.67-1.147 4.813.491 5.563 2.054");
}

.jqjgsf81p {
  d: path("M15.628 8.11c.946.861 2.456.65 3.31-.302c.915-1.018 2.146-2.075 3.639-2.806c-1.404.03-2.842.507-4.149 1.534c-.15.118-.311.241-.475.366c-.497.38-1.027.786-1.422 1.175c-.238.234-.657.258-.903.034");
}

.k2ceuu2kb {
  stop-color: var(--svg-color--cfc7d9, #CFC7D9);
  stop-opacity: 0;
}

.l7v-5hb1e {
  stop-color: var(--svg-color--cfc7d9, #CFC7D9);
}

.m0vu0kq3p {
  stop-color: var(--svg-color--dbaeff, #DBAEFF);
  stop-opacity: 0;
}

.mw4dabcry {
  stop-color: var(--svg-color--b6b6b6, #B6B6B6);
  stop-opacity: 0;
}

.onbsaylqo {
  stop-color: var(--svg-color--dcc2f7, #DCC2F7);
  stop-opacity: 0;
}

.otqf3m3qo {
  stop-color: var(--svg-color--dbaeff, #DBAEFF);
}

.oyem64b6r {
  stop-color: var(--svg-color--919191, #919191);
}

.r-vg0k7ei {
  stop-color: var(--svg-color--e4d9f1, #E4D9F1);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.t-rxjcbca {
  stop-color: var(--svg-color--b6b6b6, #B6B6B6);
}

.v47sxv0xz {
  stop-color: var(--svg-color--dcbff9, #DCBFF9);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.xl4zk2xes {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M25.638 5.973c2.598 1.07 3.975 3.488 2.343 7.455c-2.875 5.437-5.963 5.533-7.563 4.875c-1.875-1.125-3.195-4.409-1.562-8.375s4.184-5.024 6.782-3.955");
}

.y5m7h3bxi {
  stop-color: var(--svg-color--dcbff9, #DCBFF9);
}

.ylqec66vg {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M22.771 6.115c1.087-.135 4.063.281 5.281 3.688");
}

</style>
