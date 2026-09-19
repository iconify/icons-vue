<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iBQv33b)" class="e6_ukzb7k"/><path fill="url(#i4KXRMb)" class="e6_ukzb7k"/><path fill="url(#ik2CGXc)" class="e6_ukzb7k"/><g filter="url(#iAsp68c)"><path fill="url(#igTFzKb)" class="zpbfv-xzl"/></g><g filter="url(#inV6z1d)"><path class="zyw285hsx"/><path stroke="url(#iQKgJSc)" class="mguaqs60p"/></g><g filter="url(#itMozlz)"><path fill="url(#ishPBxe)" class="pooknlb3u"/></g><g filter="url(#ijeN17c)"><path class="vfhhjsb2w"/></g><path fill="url(#igIVEQc)" class="scns2qb_j"/><path fill="url(#i6dm45l)" class="scns2qb_j"/><path fill="url(#i0s0PyS)" class="scns2qb_j"/><g filter="url(#isMOQGc)"><rect class="qks2c9_ck"/></g><g filter="url(#iK60jvc)"><ellipse class="rhbibe5ax"/></g><circle fill="url(#i7Lk0Ae)" class="tn3175bug"/><circle fill="url(#iwOfOQM)" class="tn3175bug"/><circle fill="url(#iE1UUvc)" class="tn3175bug"/><g filter="url(#iAGd6Qy)"><path fill="url(#iEcrGDd)" class="i3sel2l0g"/></g><path fill="url(#iLGwzwe)" class="cyqyxcc9a"/><defs><linearGradient id="iBQv33b" x1="16.822" x2="13.186" y1="28.879" y2="28.879" gradientUnits="userSpaceOnUse"><stop class="q2664bbii"/><stop offset=".42" class="v3rncsbye"/><stop offset=".774" class="gxbwcacfp"/></linearGradient><linearGradient id="i4KXRMb" x1="18.103" x2="17.353" y1="28.879" y2="28.879" gradientUnits="userSpaceOnUse"><stop class="w8uut-baw"/><stop offset="1" class="zrqwy0bgb"/></linearGradient><linearGradient id="igTFzKb" x1="20.525" x2="20.525" y1="23.923" y2="10.242" gradientUnits="userSpaceOnUse"><stop offset=".743" class="h9ndio2-g"/><stop offset="1" class="h-91q2h_g"/></linearGradient><linearGradient id="iQKgJSc" x1="17.262" x2="9.296" y1="18.63" y2="18.63" gradientUnits="userSpaceOnUse"><stop offset=".222" class="gch7t-91q"/><stop offset="1" class="ltx6labhr"/></linearGradient><linearGradient id="ishPBxe" x1="28.688" x2="27" y1="16.828" y2="16.828" gradientUnits="userSpaceOnUse"><stop class="s2drkiaqw"/><stop offset="1" class="d16_zibtw"/></linearGradient><linearGradient id="igIVEQc" x1="25.438" x2="25.438" y1="14.527" y2="12.93" gradientUnits="userSpaceOnUse"><stop class="a09hyhb6c"/><stop offset="1" class="hnae3ccbj"/></linearGradient><linearGradient id="i6dm45l" x1="29.769" x2="28.625" y1="13.378" y2="13.378" gradientUnits="userSpaceOnUse"><stop class="msa_14b8b"/><stop offset="1" class="do0vnv4yn"/></linearGradient><linearGradient id="iEcrGDd" x1="9.538" x2="9.538" y1="9.48" y2="22.48" gradientUnits="userSpaceOnUse"><stop offset=".191" class="yqciwabyz"/><stop offset="1" class="uyqzj06di"/></linearGradient><linearGradient id="iLGwzwe" x1="9.926" x2="9.926" y1="9.484" y2="21.438" gradientUnits="userSpaceOnUse"><stop class="gvmd_3pyp"/><stop offset="1" class="lcf2gumwh"/></linearGradient><filter id="iAsp68c" width="23.913" height="16.283" x="4.044" y="7.64" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.356863 0 0 0 0 1 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22120"/></filter><filter id="inV6z1d" width="12.909" height="16.398" x="3.634" y="7.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22120" stdDeviation=".25"/></filter><filter id="itMozlz" width="4.49" height="6.43" x="24.598" y="13.488" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.25"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.858824 0 0 0 0 0.203922 0 0 0 0 0.2 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_22120"/></filter><filter id="ijeN17c" width="10.09" height="12.18" x="16.75" y="10.738" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22120" stdDeviation="1.5"/></filter><filter id="isMOQGc" width="9.516" height="1.319" x="19.25" y="12.641" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22120" stdDeviation=".25"/></filter><filter id="iK60jvc" width="5.645" height="7.313" x="15.024" y="10.253" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22120" stdDeviation=".625"/></filter><filter id="iAGd6Qy" width="10.016" height="13.5" x="4.53" y="9.23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_22120" stdDeviation=".125"/></filter><radialGradient id="ik2CGXc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.95639 5.62268 0 15.511 28.88)" gradientUnits="userSpaceOnUse"><stop offset=".772" class="r2t4_lbss"/><stop offset="1" class="kgtji58_q"/></radialGradient><radialGradient id="i0s0PyS" cx="0" cy="0" r="1" gradientTransform="matrix(.9375 0 0 .50781 29.625 13.024)" gradientUnits="userSpaceOnUse"><stop class="rbz9yubut"/><stop offset="1" class="hm0grp_yj"/></radialGradient><radialGradient id="i7Lk0Ae" cx="0" cy="0" r="1" gradientTransform="rotate(-70.371 20.492 -5.296)scale(3.62801 4.37707)" gradientUnits="userSpaceOnUse"><stop class="uuf7d16qw"/><stop offset="1" class="zoc1v6h3d"/></radialGradient><radialGradient id="iwOfOQM" cx="0" cy="0" r="1" gradientTransform="rotate(180 10.251 6.69)scale(3.58221)" gradientUnits="userSpaceOnUse"><stop offset=".646" class="wsxh4l0ai"/><stop offset="1" class="usuc0321h"/></radialGradient><radialGradient id="iE1UUvc" cx="0" cy="0" r="1" gradientTransform="matrix(2.04688 -.875 .6589 1.54133 20.58 12.461)" gradientUnits="userSpaceOnUse"><stop offset=".247" class="b7qhyuaga"/><stop offset="1" class="wzxqf6jtq"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:open-mailbox-with-lowered-flag" /></template>
<style>
.a09hyhb6c {
  stop-color: var(--svg-color--926bc9, #926BC9);
}

.b7qhyuaga {
  stop-color: var(--svg-color--d0ccda, #D0CCDA);
}

.cyqyxcc9a {
  d: path("M5.169 14.242a4.758 4.758 0 1 1 9.515 0v7.992a.25.25 0 0 1-.25.25H5.42a.25.25 0 0 1-.25-.25z");
}

.d16_zibtw {
  stop-color: var(--svg-color--f96941, #F96941);
}

.do0vnv4yn {
  stop-color: var(--svg-color--bab9bf, #BAB9BF);
  stop-opacity: 0;
}

.e6_ukzb7k {
  d: path("M13.186 23.923h4.65v4.956h-4.65z");
}

.ft5dv1b6b {
  fill: none;
}

.gch7t-91q {
  stop-color: var(--svg-color--3b7bde, #3B7BDE);
}

.gvmd_3pyp {
  stop-color: var(--svg-color--4b1776, #4B1776);
}

.gxbwcacfp {
  stop-color: var(--svg-color--5e3a43, #5E3A43);
}

.h-91q2h_g {
  stop-color: var(--svg-color--5d98da, #5D98DA);
}

.h9ndio2-g {
  stop-color: var(--svg-color--5097da, #5097DA);
}

.hm0grp_yj {
  stop-color: var(--svg-color--cfcbd8, #CFCBD8);
  stop-opacity: 0;
}

.hnae3ccbj {
  stop-color: var(--svg-color--a6a4af, #A6A4AF);
}

.i3sel2l0g {
  d: path("M4.78 14.238a4.758 4.758 0 1 1 9.516 0v7.993a.25.25 0 0 1-.25.25H5.03a.25.25 0 0 1-.25-.25z");
}

.kgtji58_q {
  stop-color: var(--svg-color--5a3a46, #5A3A46);
}

.lcf2gumwh {
  stop-color: var(--svg-color--240b46, #240B46);
}

.ltx6labhr {
  stop-color: var(--svg-color--3c84d5, #3C84D5);
  stop-opacity: 0;
}

.mguaqs60p {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M5.49 23.555h9.198c.66 0 1.23-.458 1.23-1.063V13.69c0-2.82-2.49-5.273-5.826-5.275C6.94 8.25 4.259 10.38 4.259 13.69v8.802c0 .605.57 1.063 1.23 1.063Z");
}

.msa_14b8b {
  stop-color: var(--svg-color--bab9bf, #BAB9BF);
}

.pooknlb3u {
  d: path("M28.688 13.738v5.38c0 .441-.31.8-.694.8h-2.703c-.383 0-.694-.359-.694-.8v-5.38z");
}

.q2664bbii {
  stop-color: var(--svg-color--8f616c, #8F616C);
}

.qks2c9_ck {
  width: 8.516px;
  height: 0.319px;
  x: 19.75px;
  y: 13.141px;
  fill: var(--svg-color--aea4bf, #AEA4BF);
  rx: 0.159px;
}

.r2t4_lbss {
  stop-color: var(--svg-color--632f53, #632F53);
  stop-opacity: 0;
}

.rbz9yubut {
  stop-color: var(--svg-color--cfcbd8, #CFCBD8);
}

.rhbibe5ax {
  cx: 17.847px;
  cy: 13.909px;
  fill: var(--svg-color--264fc5, #264FC5);
  rx: 1.572px;
  ry: 2.406px;
}

.s2drkiaqw {
  stop-color: var(--svg-color--ff8e4e, #FF8E4E);
}

.scns2qb_j {
  d: path("M28.62 12.23a1.149 1.149 0 0 1 0 2.297h-9.616V12.23z");
}

.tn3175bug {
  cx: 19.327px;
  cy: 13.378px;
  r: 2.406px;
}

.usuc0321h {
  stop-color: var(--svg-color--636697, #636697);
}

.uuf7d16qw {
  stop-color: var(--svg-color--9571c7, #9571C7);
}

.uyqzj06di {
  stop-color: var(--svg-color--3255bf, #3255BF);
  stop-opacity: 0;
}

.v3rncsbye {
  stop-color: var(--svg-color--7d4261, #7D4261);
}

.vfhhjsb2w {
  fill: var(--svg-color--4b81d5, #4B81D5);
  d: path("M23.84 13.738v5.38c0 .441-.31.8-.693.8h-2.704c-.383 0-.693-.359-.693-.8v-5.38z");
}

.w8uut-baw {
  stop-color: var(--svg-color--855a5d, #855A5D);
}

.wsxh4l0ai {
  stop-color: var(--svg-color--948da4, #948DA4);
  stop-opacity: 0;
}

.wzxqf6jtq {
  stop-color: var(--svg-color--b6b6bd, #B6B6BD);
  stop-opacity: 0;
}

.yqciwabyz {
  stop-color: var(--svg-color--3255bf, #3255BF);
}

.zoc1v6h3d {
  stop-color: var(--svg-color--b0b0b7, #B0B0B7);
}

.zpbfv-xzl {
  d: path("M4.044 13.54a5.5 5.5 0 0 1 5.5-5.5h12.912a5.5 5.5 0 0 1 5.5 5.5v9.383a1 1 0 0 1-1 1H5.044a1 1 0 0 1-1-1z");
}

.zrqwy0bgb {
  stop-color: var(--svg-color--855a5d, #855A5D);
  stop-opacity: 0;
}

.zyw285hsx {
  fill: var(--svg-color--4473c1, #4473C1);
  d: path("M5.49 23.43h9.198c.61 0 1.105-.42 1.105-.938V13.69c0-2.743-2.428-5.15-5.704-5.15c-3.093-.163-5.705 1.92-5.705 5.15v8.802c0 .518.495.938 1.105.938");
}

</style>
