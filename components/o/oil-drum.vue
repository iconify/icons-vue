<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iqqf20c)" class="t8c7vbinb"/><path fill="url(#iq24lsd)" class="pl941pbbx"/><path fill="url(#ip2wb8c)" class="pl941pbbx"/><path fill="url(#iHKXAFc)" class="pl941pbbx"/><path fill="url(#idoldFb)" class="pl941pbbx"/><path fill="url(#irERNEd)" class="p8czhccqg"/><path fill="url(#iR5iDhe)" class="inom_xbag"/><g filter="url(#iTZjW9b)"><path class="xpgrbhfes"/></g><g filter="url(#ivtFZsb)"><path class="j92e05bok"/></g><g filter="url(#iwlmFLe)"><path class="y3llub55i"/></g><g filter="url(#i5M7Nke)"><path class="hld1bn9fn"/></g><path fill="url(#i9u1hQc)" class="scvxmrbxp"/><path fill="url(#i7KK7Tb)" class="scvxmrbxp"/><path fill="url(#iUbgzPe)" class="scvxmrbxp"/><path fill="url(#iWwWrAd)" class="jw1y2uxie"/><path fill="url(#ivtFqge)" class="jw1y2uxie"/><path fill="url(#ioqJgYc)" class="jw1y2uxie"/><path fill="url(#iCdq8fb)" class="wbk2cwbda"/><path fill="url(#iCRzAvc)" class="wbk2cwbda"/><path fill="url(#iuTVaKc)" class="wbk2cwbda"/><path fill="url(#iWHusbe)" class="zek8pqbla"/><path fill="url(#iYLL0oc)" class="zek8pqbla"/><path fill="url(#iscA46d)" class="zek8pqbla"/><defs><linearGradient id="iqqf20c" x1="7.002" x2="25" y1="16.956" y2="16.956" gradientUnits="userSpaceOnUse"><stop class="ouj-acids"/><stop offset=".177" class="vzc-habug"/><stop offset="1" class="t-5b9vblb"/></linearGradient><linearGradient id="iq24lsd" x1="19.002" x2="24.563" y1="2.956" y2="2.956" gradientUnits="userSpaceOnUse"><stop class="ngw1erk2m"/><stop offset="1" class="s1_wmdpkc"/></linearGradient><linearGradient id="ip2wb8c" x1="24" x2="23.247" y1="3.956" y2="3.956" gradientUnits="userSpaceOnUse"><stop class="qa4m-nq6i"/><stop offset="1" class="a6cf72yfw"/></linearGradient><linearGradient id="irERNEd" x1="24.406" x2="22.5" y1="16.932" y2="16.932" gradientUnits="userSpaceOnUse"><stop class="squvep3ii"/><stop offset="1" class="fdd72shlv"/></linearGradient><linearGradient id="iR5iDhe" x1="21" x2="21" y1="27.956" y2="5.956" gradientUnits="userSpaceOnUse"><stop class="uib3th7rc"/><stop offset="1" class="gst5h_zxo"/></linearGradient><linearGradient id="i9u1hQc" x1="26.002" x2="6.002" y1="28.956" y2="28.956" gradientUnits="userSpaceOnUse"><stop class="r16hl3_bj"/><stop offset="1" class="tco24_bou"/></linearGradient><linearGradient id="i7KK7Tb" x1="16" x2="16" y1="30.456" y2="29.206" gradientUnits="userSpaceOnUse"><stop class="v6o_1bbty"/><stop offset="1" class="gkfimccdj"/></linearGradient><linearGradient id="iWwWrAd" x1="26.002" x2="6.002" y1="4.956" y2="4.956" gradientUnits="userSpaceOnUse"><stop class="r16hl3_bj"/><stop offset="1" class="tco24_bou"/></linearGradient><linearGradient id="ivtFqge" x1="16" x2="16" y1="6.456" y2="5.206" gradientUnits="userSpaceOnUse"><stop class="v6o_1bbty"/><stop offset="1" class="gkfimccdj"/></linearGradient><linearGradient id="iCdq8fb" x1="26.002" x2="6.002" y1="12.956" y2="12.956" gradientUnits="userSpaceOnUse"><stop class="r16hl3_bj"/><stop offset="1" class="tco24_bou"/></linearGradient><linearGradient id="iCRzAvc" x1="16" x2="16" y1="14.456" y2="13.206" gradientUnits="userSpaceOnUse"><stop class="v6o_1bbty"/><stop offset="1" class="gkfimccdj"/></linearGradient><linearGradient id="iWHusbe" x1="26.002" x2="6.002" y1="20.956" y2="20.956" gradientUnits="userSpaceOnUse"><stop class="r16hl3_bj"/><stop offset="1" class="tco24_bou"/></linearGradient><linearGradient id="iYLL0oc" x1="16" x2="16" y1="22.456" y2="21.206" gradientUnits="userSpaceOnUse"><stop class="v6o_1bbty"/><stop offset="1" class="gkfimccdj"/></linearGradient><radialGradient id="iHKXAFc" cx="0" cy="0" r="1" gradientTransform="rotate(140.194 11.513 5.497)scale(.70274 .80899)" gradientUnits="userSpaceOnUse"><stop class="n3yz20bei"/><stop offset="1" class="huzgt9bpc"/></radialGradient><radialGradient id="idoldFb" cx="0" cy="0" r="1" gradientTransform="matrix(2.81927 0 0 .44025 20.787 2.54)" gradientUnits="userSpaceOnUse"><stop class="vbf8jf20e"/><stop offset=".64" class="w26md4o5y"/></radialGradient><radialGradient id="iUbgzPe" cx="0" cy="0" r="1" gradientTransform="matrix(0 .65625 -10.5757 0 22.75 28.612)" gradientUnits="userSpaceOnUse"><stop class="mg34y-z9v"/><stop offset="1" class="plak7fl-j"/></radialGradient><radialGradient id="ioqJgYc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .65625 -10.5757 0 22.75 4.612)" gradientUnits="userSpaceOnUse"><stop class="mg34y-z9v"/><stop offset="1" class="plak7fl-j"/></radialGradient><radialGradient id="iuTVaKc" cx="0" cy="0" r="1" gradientTransform="matrix(0 .65625 -10.5757 0 22.75 12.612)" gradientUnits="userSpaceOnUse"><stop class="mg34y-z9v"/><stop offset="1" class="plak7fl-j"/></radialGradient><radialGradient id="iscA46d" cx="0" cy="0" r="1" gradientTransform="matrix(0 .65625 -10.5757 0 22.75 20.612)" gradientUnits="userSpaceOnUse"><stop class="mg34y-z9v"/><stop offset="1" class="plak7fl-j"/></radialGradient><filter id="iTZjW9b" width="18.5" height="1.375" x="6.75" y="13.206" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11874" stdDeviation=".25"/></filter><filter id="ivtFZsb" width="18.5" height="1.375" x="6.75" y="5.19" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11874" stdDeviation=".25"/></filter><filter id="iwlmFLe" width="18.5" height="1.375" x="6.75" y="21.182" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11874" stdDeviation=".25"/></filter><filter id="i5M7Nke" width="18.5" height="1.375" x="6.75" y="27.354" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_11874" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oil-drum" /></template>
<style>
.a6cf72yfw {
  stop-color: var(--svg-color--747374, #747374);
  stop-opacity: 0;
}

.fdd72shlv {
  stop-color: var(--svg-color--65e0ff, #65E0FF);
}

.ft5dv1b6b {
  fill: none;
}

.gkfimccdj {
  stop-color: var(--svg-color--373490, #373490);
  stop-opacity: 0;
}

.gst5h_zxo {
  stop-color: var(--svg-color--55c0fa, #55C0FA);
}

.hld1bn9fn {
  fill: var(--svg-color--3c62a7, #3C62A7);
  d: path("M7.25 27.854h17.5v.375H7.25z");
}

.huzgt9bpc {
  stop-color: var(--svg-color--69696a, #69696A);
  stop-opacity: 0;
}

.inom_xbag {
  d: path("M21 5.956h-1v22h1z");
}

.j92e05bok {
  fill: var(--svg-color--3c62a7, #3C62A7);
  d: path("M7.25 5.69h17.5v.375H7.25z");
}

.jw1y2uxie {
  d: path("M25 5.956H7c-.55 0-1-.45-1-1s.45-1 1-1h18c.55 0 1 .45 1 1s-.45 1-1 1");
}

.mg34y-z9v {
  stop-color: var(--svg-color--71a2ee, #71A2EE);
}

.n3yz20bei {
  stop-color: var(--svg-color--69696a, #69696A);
}

.ngw1erk2m {
  stop-color: var(--svg-color--463b5e, #463B5E);
}

.ouj-acids {
  stop-color: var(--svg-color--3974a8, #3974A8);
}

.p8czhccqg {
  d: path("M24 5.956h-2v22h2z");
}

.pl941pbbx {
  d: path("M23.02 1.956h-3.03c-.55 0-.99.44-.99.98v1.02h5v-1.02c0-.54-.44-.98-.98-.98");
}

.plak7fl-j {
  stop-color: var(--svg-color--71a2ee, #71A2EE);
  stop-opacity: 0;
}

.qa4m-nq6i {
  stop-color: var(--svg-color--747374, #747374);
}

.r16hl3_bj {
  stop-color: var(--svg-color--4285d9, #4285D9);
}

.s1_wmdpkc {
  stop-color: var(--svg-color--4e4b54, #4E4B54);
}

.scvxmrbxp {
  d: path("M25 29.956H7c-.55 0-1-.45-1-1s.45-1 1-1h18c.55 0 1 .45 1 1s-.45 1-1 1");
}

.squvep3ii {
  stop-color: var(--svg-color--72fbff, #72FBFF);
}

.t-5b9vblb {
  stop-color: var(--svg-color--5998e8, #5998E8);
}

.t8c7vbinb {
  d: path("M25 5.956H7v22h18z");
}

.tco24_bou {
  stop-color: var(--svg-color--3e409a, #3E409A);
}

.uib3th7rc {
  stop-color: var(--svg-color--53bdfe, #53BDFE);
}

.v6o_1bbty {
  stop-color: var(--svg-color--373490, #373490);
}

.vbf8jf20e {
  stop-color: var(--svg-color--5c4f6b, #5C4F6B);
}

.vzc-habug {
  stop-color: var(--svg-color--448fdd, #448FDD);
}

.w26md4o5y {
  stop-color: var(--svg-color--5c4f6b, #5C4F6B);
  stop-opacity: 0;
}

.wbk2cwbda {
  d: path("M25 13.956H7c-.55 0-1-.45-1-1s.45-1 1-1h18c.55 0 1 .45 1 1s-.45 1-1 1");
}

.xpgrbhfes {
  fill: var(--svg-color--3c62a7, #3C62A7);
  d: path("M7.25 13.706h17.5v.375H7.25z");
}

.y3llub55i {
  fill: var(--svg-color--3c62a7, #3C62A7);
  d: path("M7.25 21.682h17.5v.375H7.25z");
}

.zek8pqbla {
  d: path("M25 21.956H7c-.55 0-1-.45-1-1s.45-1 1-1h18c.55 0 1 .45 1 1s-.45 1-1 1");
}

</style>
