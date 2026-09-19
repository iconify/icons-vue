<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iKoaBqb)"><path class="odr9yccgd"/><path fill="url(#iN8jUie)" class="sv6g2qbgh"/></g><path fill="url(#im1V5Ec)" class="sv6g2qbgh"/><path fill="url(#id6ILSd)" class="sv6g2qbgh"/><path fill="url(#iqqN4nd)" class="sv6g2qbgh"/><path fill="url(#iIfvsiM)" class="sv6g2qbgh"/><g filter="url(#iqW9Xtc)" class="av_u01b_m"><path class="dhnd5bffp"/><path class="wf221ebjs"/><path class="dcozvkfld"/></g><path class="h-av7ub2j"/><path fill="url(#ii2YSZd)" class="wusbk-b3u"/><path fill="url(#ihYp6Wd)" class="wusbk-b3u"/><path fill="url(#iBp08nc)" class="wusbk-b3u"/><g filter="url(#icsialc)"><rect class="ob84epbhr"/></g><path class="o248et9xg"/><path fill="url(#if210wb)" class="a1nmgmbmx"/><path fill="url(#iMiwT4d)" class="a1nmgmbmx"/><path fill="url(#iMF35gb)" class="a1nmgmbmx"/><g filter="url(#iGQZ63N)"><rect class="kx9wnxbjo"/></g><path class="gi7_5-o2o"/><path fill="url(#iNiQh7b)" class="hiwhu_bne"/><path fill="url(#ineayge)" class="hiwhu_bne"/><path fill="url(#iCQBnbb)" class="fv07au17g"/><path fill="url(#iy00M7d)" class="fv07au17g"/><path fill="url(#i7AIGHj)" class="fv07au17g"/><defs><radialGradient id="iN8jUie" cx="0" cy="0" r="1" gradientTransform="matrix(-8.51709 12.41796 -9.2504 -6.34456 22.193 16.761)" gradientUnits="userSpaceOnUse"><stop class="u2if-wb1f"/><stop offset="1" class="izsryac0o"/></radialGradient><radialGradient id="im1V5Ec" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56813 -3.0232 2.6919 -2.28669 25.379 11.983)" gradientUnits="userSpaceOnUse"><stop class="uodcjlb2l"/><stop offset="1" class="kq0dvbcgz"/></radialGradient><radialGradient id="id6ILSd" cx="0" cy="0" r="1" gradientTransform="rotate(153.925 12.708 6.704)scale(3.40199 3.98225)" gradientUnits="userSpaceOnUse"><stop class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="iqqN4nd" cx="0" cy="0" r="1" gradientTransform="matrix(1.61753 1.77534 -9.13543 8.3234 18.155 6.325)" gradientUnits="userSpaceOnUse"><stop class="u7snel3zl"/><stop offset="1" class="m309dcyvo"/></radialGradient><radialGradient id="iIfvsiM" cx="0" cy="0" r="1" gradientTransform="matrix(1.14411 0 0 3.35343 17.17 9.403)" gradientUnits="userSpaceOnUse"><stop class="aqt0a_b7y"/><stop offset="1" class="am1cv07aq"/></radialGradient><radialGradient id="ihYp6Wd" cx="0" cy="0" r="1" gradientTransform="rotate(50.042 -9.403 7.899)scale(7.61743 6.61775)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="nddt9cb2v"/><stop offset=".941" class="dlrd3nbvu"/><stop offset=".959" class="dlrd3nbvu"/></radialGradient><radialGradient id="iBp08nc" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.64062 -3.01625 0 6.041 10.281)" gradientUnits="userSpaceOnUse"><stop class="hxm-6izwk"/><stop offset="1" class="uwlfcppjp"/></radialGradient><radialGradient id="iMiwT4d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.99155 -5.23271 0 9.738 9.666)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="nddt9cb2v"/><stop offset="1" class="nz5smemnm"/></radialGradient><radialGradient id="iMF35gb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.8826 0 0 -7.31912 10.745 8.515)" gradientUnits="userSpaceOnUse"><stop class="hxm-6izwk"/><stop offset="1" class="uwlfcppjp"/></radialGradient><radialGradient id="iNiQh7b" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.00555 -5.31537 0 14.674 9.53)" gradientUnits="userSpaceOnUse"><stop offset=".637" class="shw1xemdo"/><stop offset="1" class="yhymhl0la"/></radialGradient><radialGradient id="ineayge" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.25 -4 0 16.9 9.906)" gradientUnits="userSpaceOnUse"><stop class="qp25d62ho"/><stop offset="1" class="pkec2tbkr"/></radialGradient><radialGradient id="iy00M7d" cx="0" cy="0" r="1" gradientTransform="rotate(138.085 11.387 12.835)scale(3.84431 3.58316)" gradientUnits="userSpaceOnUse"><stop class="itt9z7bbf"/><stop offset="1" class="eh2hzabiv"/></radialGradient><radialGradient id="i7AIGHj" cx="0" cy="0" r="1" gradientTransform="matrix(1.46286 .58513 -2.0674 5.16858 21.64 17.28)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="wef8zac8b"/><stop offset="1" class="kp355o60v"/><stop offset="1" class="d7cfdwb-a"/></radialGradient><filter id="iKoaBqb" width="27.675" height="25.549" x="2.095" y="4.388" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.490196 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1963"/></filter><filter id="iqW9Xtc" width="16.091" height="12.26" x="1.467" y="7.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1963" stdDeviation="1"/></filter><filter id="icsialc" width="2.266" height="8.313" x="5.806" y="8.203" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1963" stdDeviation=".375"/></filter><filter id="iGQZ63N" width="2.266" height="8.719" x="10.744" y="7.797" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1963" stdDeviation=".375"/></filter><linearGradient id="ii2YSZd" x1="2.661" x2="5.484" y1="13.427" y2="13.427" gradientUnits="userSpaceOnUse"><stop class="wuxahcc4s"/><stop offset="1" class="ezbtgdqku"/></linearGradient><linearGradient id="if210wb" x1="7.451" x2="10.202" y1="13.199" y2="13.199" gradientUnits="userSpaceOnUse"><stop class="wuxahcc4s"/><stop offset="1" class="ezbtgdqku"/></linearGradient><linearGradient id="iCQBnbb" x1="24.924" x2="23.428" y1="15.461" y2="21.703" gradientUnits="userSpaceOnUse"><stop class="lx5f03b4z"/><stop offset="1" class="xutluyp0z"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinching-hand" /></template>
<style>
.a1nmgmbmx {
  d: path("M9.738 7.078c-1.565 0-2.838 1.23-2.838 2.744v4.568c0 1.513 1.273 2.744 2.838 2.744s2.838-1.23 2.838-2.744V9.811c0-1.512-1.273-2.733-2.838-2.733");
}

.am1cv07aq {
  stop-color: var(--svg-color--d48002, #D48002);
  stop-opacity: 0;
}

.aqt0a_b7y {
  stop-color: var(--svg-color--d48002, #D48002);
}

.av_u01b_m {
  fill: var(--svg-color--bd5717, #BD5717);
}

.d7cfdwb-a {
  stop-color: var(--svg-color--ffdd43, #FFDD43);
  stop-opacity: 0;
}

.dcozvkfld {
  d: path("M5.75 10.464a2.28 2.28 0 0 0-2.283 2.266v2.55a2.28 2.28 0 0 0 2.282 2.267a2.28 2.28 0 0 0 2.283-2.267v-2.55a2.27 2.27 0 0 0-2.283-2.266");
}

.dhnd5bffp {
  d: path("M12.896 9.875c-1.468 0-2.663 1.186-2.663 2.643v2.974c0 1.457 1.195 2.643 2.663 2.643s2.662-1.186 2.662-2.643v-2.974a2.65 2.65 0 0 0-2.662-2.643");
}

.dlrd3nbvu {
  stop-color: var(--svg-color--e17a24, #E17A24);
}

.eh2hzabiv {
  stop-color: var(--svg-color--ffe848, #FFE848);
  stop-opacity: 0;
}

.ezbtgdqku {
  stop-color: var(--svg-color--eda042, #EDA042);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv07au17g {
  d: path("M24.103 14.672c1.547-1.344 3.412-.999 4.375.437c1.525 2.276-.46 4.16-2.356 5.96c-.473.45-.94.894-1.347 1.337c-.884.823-1.6 1.536-2.253 2.187a51 51 0 0 1-1.967 1.893c-.446.4-.886.768-1.328 1.104l3.427-11.924c.252.078.71-.333 1.167-.743z");
}

.gi7_5-o2o {
  fill: var(--svg-color--e9a31e, #E9A31E);
  d: path("M14.674 6.938c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.577 1.293 2.862 2.883 2.862c1.589 0 2.882-1.285 2.882-2.862v-4.35a2.87 2.87 0 0 0-2.882-2.861");
}

.h-av7ub2j {
  fill: var(--svg-color--fbb726, #FBB726);
  d: path("M5.008 7.99c-1.606 0-2.913 1.19-2.913 2.655v3.622c0 1.464 1.307 2.655 2.913 2.655S7.92 15.73 7.92 14.267v-3.622c0-1.465-1.306-2.655-2.912-2.655");
}

.hiwhu_bne {
  d: path("M14.674 6.938c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.577 1.293 2.862 2.883 2.862c1.589 0 2.882-1.285 2.882-2.862v-4.35a2.87 2.87 0 0 0-2.882-2.861");
}

.hxm-6izwk {
  stop-color: var(--svg-color--ffcd30, #FFCD30);
}

.itt9z7bbf {
  stop-color: var(--svg-color--ffe848, #FFE848);
}

.izsryac0o {
  stop-color: var(--svg-color--ffe143, #FFE143);
  stop-opacity: 0;
}

.kp355o60v {
  stop-color: var(--svg-color--ffd543, #FFD543);
  stop-opacity: 0;
}

.kq0dvbcgz {
  stop-color: var(--svg-color--e98a5b, #E98A5B);
  stop-opacity: 0;
}

.kx9wnxbjo {
  width: 0.766px;
  height: 7.219px;
  x: 11.494px;
  y: 8.547px;
  fill: var(--svg-color--bf6f03, #BF6F03);
  rx: 0.383px;
}

.lx5f03b4z {
  stop-color: var(--svg-color--eca60f, #ECA60F);
}

.m309dcyvo {
  stop-color: var(--svg-color--d29a3e, #D29A3E);
  stop-opacity: 0;
}

.nddt9cb2v {
  stop-color: var(--svg-color--f8832e, #F8832E);
  stop-opacity: 0;
}

.nz5smemnm {
  stop-color: var(--svg-color--e6802b, #E6802B);
}

.o248et9xg {
  fill: var(--svg-color--fbb726, #FBB726);
  d: path("M9.738 7.078c-1.565 0-2.838 1.23-2.838 2.744v4.568c0 1.513 1.273 2.744 2.838 2.744s2.838-1.23 2.838-2.744V9.811c0-1.512-1.273-2.733-2.838-2.733");
}

.ob84epbhr {
  width: 0.766px;
  height: 6.813px;
  x: 6.556px;
  y: 8.953px;
  fill: var(--svg-color--bf6f03, #BF6F03);
  rx: 0.383px;
}

.odr9yccgd {
  fill: var(--svg-color--ffb943, #FFB943);
  d: path("M28.478 15.11c-.963-1.437-2.828-1.782-4.375-.438c-.761.661-1.648 1.618-1.648.464v-3.097c.07-1.281.828-1.625 2.062-1.203c1.757.445 3.169-.964 3.43-2.164c.204-.938-.007-2.441-1.61-3.203c-3.296-1.422-7.359-.203-8.899 3.333l-3.302 2.334H2.096v6.583c0 7.718 3.982 12.218 10.455 12.218c3.26 0 5.551-1.251 8.004-3.45c1.31-1.175 2.411-2.398 4.22-4.08c2.031-2.22 5.61-4.454 3.703-7.298");
}

.pkec2tbkr {
  stop-color: var(--svg-color--ffe740, #FFE740);
  stop-opacity: 0;
}

.qp25d62ho {
  stop-color: var(--svg-color--ffe740, #FFE740);
}

.shw1xemdo {
  stop-color: var(--svg-color--ef833b, #EF833B);
  stop-opacity: 0;
}

.sv6g2qbgh {
  d: path("M28.478 15.11c-.963-1.437-2.828-1.782-4.375-.438c-.761.661-1.648 1.618-1.648.464v-3.097c.07-1.281.828-1.625 2.062-1.203c1.757.445 3.169-.964 3.43-2.164c.204-.938-.007-2.441-1.61-3.203c-3.296-1.422-7.359-.203-8.899 3.333l-3.302 2.334H2.096v6.583c0 7.718 3.982 12.218 10.455 12.218c3.26 0 5.551-1.251 8.004-3.45c1.31-1.175 2.411-2.398 4.22-4.08c2.031-2.22 5.61-4.454 3.703-7.298");
}

.u2if-wb1f {
  stop-color: var(--svg-color--ffe143, #FFE143);
}

.u7snel3zl {
  stop-color: var(--svg-color--d29a3e, #D29A3E);
}

.uodcjlb2l {
  stop-color: var(--svg-color--e98a5b, #E98A5B);
}

.uwlfcppjp {
  stop-color: var(--svg-color--ffcd30, #FFCD30);
  stop-opacity: 0;
}

.wef8zac8b {
  stop-color: var(--svg-color--ffdd43, #FFDD43);
}

.wf221ebjs {
  d: path("M9.089 10.279a2.527 2.527 0 0 0-2.533 2.514v2.828a2.527 2.527 0 0 0 2.533 2.514a2.527 2.527 0 0 0 2.532-2.514v-2.828a2.52 2.52 0 0 0-2.532-2.514");
}

.wusbk-b3u {
  d: path("M5.008 7.99c-1.606 0-2.913 1.19-2.913 2.655v3.622c0 1.464 1.307 2.655 2.913 2.655S7.92 15.73 7.92 14.267v-3.622c0-1.465-1.306-2.655-2.912-2.655");
}

.wuxahcc4s {
  stop-color: var(--svg-color--eda042, #EDA042);
}

.xutluyp0z {
  stop-color: var(--svg-color--eca60f, #ECA60F);
  stop-opacity: 0;
}

.yhymhl0la {
  stop-color: var(--svg-color--ef833b, #EF833B);
}

</style>
