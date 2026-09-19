<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iWxG5gb)" class="zpz3r9byf"/><path fill="url(#iOgR3oe)" class="zpz3r9byf"/><path fill="url(#iHm82xX)" class="zpz3r9byf"/><path fill="url(#i47QLae)" class="zpz3r9byf"/><path fill="url(#iq3nkHc)" class="zpz3r9byf"/><path fill="url(#iXsDrJc)" class="mr36-xw8w"/><path fill="url(#i98SCjb)" class="mr36-xw8w"/><path fill="url(#idnAekc)" class="mr36-xw8w"/><path fill="url(#iu93Cab)" class="mr36-xw8w"/><path fill="url(#iXc8Rwd)" class="w8ko9nkai"/><path fill="url(#ieGzoJb)" class="a5f1lbznu"/><path fill="url(#iEVbvqe)" class="fxcdwnbpd"/><path fill="url(#ijuBZKc)" class="eg57kuk_a"/><path fill="url(#iM1j3Kc)" class="l-w42ub4h"/><path fill="url(#iRm1Mud)" class="ituen3n1v"/><path fill="url(#iAmwqqS)" class="hwll3r-7l"/><path fill="url(#i9MfmBe)" class="j3o4xac8m"/><path fill="url(#i3DPJNL)" class="h1c3w7bzz"/><g filter="url(#iNEN7Kd)"><path class="lairl_pvi"/></g><path fill="url(#iDi407Z)" class="hc5excc9p"/><path class="d182vxblh"/><path class="qxl2kub_h"/><g filter="url(#irZmuEd)"><path stroke="url(#iumVnyb)" class="hc_qjoxoj"/></g><g filter="url(#ihUDczc)"><path stroke="url(#izOUCCP)" class="hdx6nw_zi"/></g><g filter="url(#iSAIhpe)"><path stroke="url(#iexy1ne)" class="fjqj_1g3s"/></g><defs><radialGradient id="iOgR3oe" cx="0" cy="0" r="1" gradientTransform="matrix(-21.87501 12.56244 -1.97698 -3.44253 27.875 23.312)" gradientUnits="userSpaceOnUse"><stop class="oiewj1b9l"/><stop offset=".858" class="sfmksg-ww"/><stop offset="1" class="bfmrf_b0i"/></radialGradient><radialGradient id="iHm82xX" cx="0" cy="0" r="1" gradientTransform="matrix(0 5.0625 -3.47277 0 15.968 29.687)" gradientUnits="userSpaceOnUse"><stop offset=".46" class="m5tm1abix"/><stop offset="1" class="vv5yk2bbm"/></radialGradient><radialGradient id="i47QLae" cx="0" cy="0" r="1" gradientTransform="matrix(14.37496 7.87499 -1.1551 2.10852 6.875 24.5)" gradientUnits="userSpaceOnUse"><stop class="gvlwd8bvv"/><stop offset="1" class="o0kpzrb1x"/></radialGradient><radialGradient id="iq3nkHc" cx="0" cy="0" r="1" gradientTransform="rotate(137.07 11.893 15.176)scale(3.67051 5.2482)" gradientUnits="userSpaceOnUse"><stop class="ucel41bkw"/><stop offset="1" class="qoi3jh2jb"/></radialGradient><radialGradient id="iXsDrJc" cx="0" cy="0" r="1" gradientTransform="rotate(10.766 -90.875 44.03)scale(18.068 28.176)" gradientUnits="userSpaceOnUse"><stop class="rfjmk-kjz"/><stop offset="1" class="sbu53kxow"/></radialGradient><radialGradient id="i98SCjb" cx="0" cy="0" r="1" gradientTransform="matrix(14.49997 4.5 -3.98815 12.85067 9.375 23.563)" gradientUnits="userSpaceOnUse"><stop class="mlnilqhka"/><stop offset="1" class="o3-a-696h"/></radialGradient><radialGradient id="iXc8Rwd" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.6875 -4.4516 0 14.938 21.688)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="vzqa40bie"/><stop offset=".817" class="j28r3bl5j"/></radialGradient><radialGradient id="ieGzoJb" cx="0" cy="0" r="1" gradientTransform="matrix(-.10504 2.0925 -4.18744 -.2102 11.293 19.113)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="d6rcnviyr"/><stop offset=".817" class="j28r3bl5j"/></radialGradient><radialGradient id="iEVbvqe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10504 2.0925 -4.18744 -.2102 7.533 16.942)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="q7khhzn1i"/><stop offset=".817" class="j28r3bl5j"/></radialGradient><radialGradient id="ijuBZKc" cx="0" cy="0" r="1" gradientTransform="matrix(.01 1.7425 -4.59667 .0264 18.688 19.313)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="id029-m4a"/><stop offset=".817" class="j28r3bl5j"/></radialGradient><radialGradient id="iRm1Mud" cx="0" cy="0" r="1" gradientTransform="matrix(-.10504 2.0925 -4.18744 -.2102 11.293 14.623)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="a7hq3ymiw"/><stop offset=".817" class="j28r3bl5j"/></radialGradient><radialGradient id="iAmwqqS" cx="0" cy="0" r="1" gradientTransform="matrix(-.10504 2.09847 -4.1875 -.2096 22.563 16.648)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="a1uwy0iyy"/><stop offset=".817" class="j28r3bl5j"/></radialGradient><radialGradient id="i9MfmBe" cx="0" cy="0" r="1" gradientTransform="matrix(-.10504 2.0925 -4.18744 -.2102 18.803 14.473)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="kqi-sjb8o"/><stop offset=".817" class="j28r3bl5j"/></radialGradient><radialGradient id="i3DPJNL" cx="0" cy="0" r="1" gradientTransform="matrix(-.10504 2.0925 -4.18744 -.2102 15.043 12.303)" gradientUnits="userSpaceOnUse"><stop offset=".583" class="ope-_n7qw"/><stop offset=".817" class="j28r3bl5j"/></radialGradient><radialGradient id="izOUCCP" cx="0" cy="0" r="1" gradientTransform="rotate(145.72 6.768 11.511)scale(4.84088 4.89453)" gradientUnits="userSpaceOnUse"><stop class="asj-gpdqo"/><stop offset="1" class="eruwijb5d"/></radialGradient><radialGradient id="iexy1ne" cx="0" cy="0" r="1" gradientTransform="matrix(4 2.72656 -2.75678 4.04433 13.307 17.287)" gradientUnits="userSpaceOnUse"><stop class="x57jl-toe"/><stop offset="1" class="eruwijb5d"/></radialGradient><linearGradient id="iWxG5gb" x1="28.688" x2="3.688" y1="21.625" y2="21.625" gradientUnits="userSpaceOnUse"><stop class="xo_ctfqjh"/><stop offset=".994" class="s0c1xgboy"/></linearGradient><linearGradient id="idnAekc" x1="7.563" x2="13.5" y1="22.375" y2="14.75" gradientUnits="userSpaceOnUse"><stop offset=".126" class="jlqnc4u3v"/><stop offset=".255" class="q65hg7bxg"/></linearGradient><linearGradient id="iu93Cab" x1="20.375" x2="17.375" y1="22.625" y2="17.813" gradientUnits="userSpaceOnUse"><stop class="xiru_e-jj"/><stop offset=".26" class="eho8fbcyp"/></linearGradient><linearGradient id="iM1j3Kc" x1="17.223" x2="14.708" y1="15.536" y2="18.051" gradientUnits="userSpaceOnUse"><stop class="u-1se5bme"/><stop offset=".385" class="lxsqblbtv"/><stop offset=".755" class="pp7ghrbxn"/><stop offset="1" class="xpg7qbdiy"/></linearGradient><linearGradient id="iDi407Z" x1="11.54" x2="20.531" y1="17.663" y2="17.663" gradientUnits="userSpaceOnUse"><stop class="yqhhz1byj"/><stop offset="1" class="u1dhqdhom"/></linearGradient><linearGradient id="iumVnyb" x1="3.484" x2="17.67" y1="18.5" y2="5.614" gradientUnits="userSpaceOnUse"><stop class="x33tema_b"/><stop offset=".124" class="np_u72rji"/><stop offset=".368" class="eqdi4z1xm"/><stop offset=".969" class="y-j97mbzr"/><stop offset="1" class="qbvy3ebmp"/></linearGradient><filter id="iNEN7Kd" width="10.193" height="7.772" x="10.807" y="14.104" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27385" stdDeviation=".5"/></filter><filter id="irZmuEd" width="26.552" height="9.484" x="2.836" y="16.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27385" stdDeviation=".125"/></filter><filter id="ihUDczc" width="4.613" height="3.191" x="16.131" y="15.616" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27385" stdDeviation=".125"/></filter><filter id="iSAIhpe" width="4.613" height="3.191" x="11.407" y="15.692" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27385" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:waffle" /></template>
<style>
.a1uwy0iyy {
  stop-color: var(--svg-color--a4704e, #A4704E);
}

.a5f1lbznu {
  d: path("m11.73 17.708l-1.46.86c-.41.24-.41.84 0 1.09l1.46.86c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.46-.86a.92.92 0 0 0-.96 0");
}

.a7hq3ymiw {
  stop-color: var(--svg-color--ac7752, #AC7752);
}

.asj-gpdqo {
  stop-color: var(--svg-color--f4d154, #F4D154);
}

.bfmrf_b0i {
  stop-color: var(--svg-color--db7e89, #DB7E89);
  stop-opacity: 0;
}

.d182vxblh {
  fill: var(--svg-color--e7bb2b, #E7BB2B);
  d: path("m17.32 15.358l-.43-.26c-.57-.34-1.28-.34-1.85 0l-.44.26h-3.2v2.04c0 .4.19.79.58 1.02l3.06 1.81c.57.34 1.28.34 1.85 0l3.06-1.81c.39-.23.58-.63.58-1.02v-2.04z");
}

.d6rcnviyr {
  stop-color: var(--svg-color--a76e47, #A76E47);
}

.eg57kuk_a {
  d: path("m19.24 17.558l-1.46.86c-.41.24-.41.84 0 1.09l1.46.86c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.46-.86a.92.92 0 0 0-.96 0");
}

.eho8fbcyp {
  stop-color: var(--svg-color--e8ab6b, #E8AB6B);
  stop-opacity: 0;
}

.eqdi4z1xm {
  stop-color: var(--svg-color--f5b98f, #F5B98F);
}

.eruwijb5d {
  stop-color: var(--svg-color--f4d154, #F4D154);
  stop-opacity: 0;
}

.fjqj_1g3s {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M11.807 16.092c.14.281.248.309.515.5c.35.25 2.152 1.234 3.297 1.89");
}

.ft5dv1b6b {
  fill: none;
}

.fxcdwnbpd {
  d: path("m7.97 15.538l-1.46.86c-.41.24-.41.84 0 1.09l1.46.86c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.46-.86a.92.92 0 0 0-.96 0");
}

.gvlwd8bvv {
  stop-color: var(--svg-color--de887c, #DE887C);
}

.h1c3w7bzz {
  d: path("m15.48 10.898l-1.46.86c-.41.24-.41.84 0 1.09l1.46.86c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.45-.86a.94.94 0 0 0-.97 0");
}

.hc_qjoxoj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M28.688 16.969c.234.531-.032 1.322-1.438 2.093c-1.937 1.063-8.953 5.891-11.344 5.891c-2.14 0-8.328-3.99-11.828-6.344c-.63-.423-.86-1.203-.297-1.89");
}

.hc5excc9p {
  d: path("m17.32 15.358l-.43-.26c-.57-.34-1.28-.34-1.85 0l-.44.26h-3.2v2.04c0 .4.19.79.58 1.02l3.06 1.81c.57.34 1.28.34 1.85 0l3.06-1.81c.39-.23.58-.63.58-1.02v-2.04z");
}

.hdx6nw_zi {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-3px, 0.3px);
  d: path("M20.344 16.016c-.14.28-.248.309-.516.5c-.35.25-2.15 1.234-3.297 1.89");
}

.hwll3r-7l {
  d: path("m23 15.238l-1.46.86c-.41.24-.41.84 0 1.09l1.46.87c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.46-.86a.9.9 0 0 0-.96-.01");
}

.id029-m4a {
  stop-color: var(--svg-color--b2764a, #B2764A);
}

.ituen3n1v {
  d: path("m11.73 13.218l-1.46.86c-.41.24-.41.84 0 1.09l1.46.86c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.46-.86a.92.92 0 0 0-.96 0");
}

.j28r3bl5j {
  stop-color: var(--svg-color--8f5630, #8F5630);
}

.j3o4xac8m {
  d: path("m19.24 13.068l-1.46.86c-.41.24-.41.84 0 1.09l1.46.86c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.46-.86a.92.92 0 0 0-.96 0");
}

.jlqnc4u3v {
  stop-color: var(--svg-color--e29754, #E29754);
}

.kqi-sjb8o {
  stop-color: var(--svg-color--a97451, #A97451);
}

.l-w42ub4h {
  d: path("m15.48 15.387l-1.46.86c-.41.24-.41.84 0 1.09l1.46.86c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.46-.86a.92.92 0 0 0-.96 0");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.lairl_pvi {
  fill: var(--svg-color--7a4423, #7A4423);
  d: path("m17.12 15.642l-.387-.272a1.43 1.43 0 0 0-1.66 0l-.395.272h-2.871v2.133c0 .418.17.969.52 1.21l2.746 1.624a1.425 1.425 0 0 0 1.66 0l2.89-1.625c.35-.24.377-.801.377-1.21v-2.132z");
}

.lxsqblbtv {
  stop-color: var(--svg-color--7f4b3b, #7F4B3B);
}

.m5tm1abix {
  stop-color: var(--svg-color--e2878b, #E2878B);
}

.mlnilqhka {
  stop-color: var(--svg-color--e59b59, #E59B59);
}

.mr36-xw8w {
  d: path("m14.07 9.518l-9.55 5.66c-1.4.83-1.4 2.85 0 3.67l9.55 5.66c1.17.69 2.62.69 3.79 0l9.55-5.66c1.4-.83 1.4-2.85 0-3.67l-9.55-5.66a3.73 3.73 0 0 0-3.79 0");
}

.np_u72rji {
  stop-color: var(--svg-color--f4ae75, #F4AE75);
}

.o0kpzrb1x {
  stop-color: var(--svg-color--e28c7f, #E28C7F);
  stop-opacity: 0;
}

.o3-a-696h {
  stop-color: var(--svg-color--e49b59, #E49B59);
  stop-opacity: 0;
}

.oiewj1b9l {
  stop-color: var(--svg-color--d28890, #D28890);
}

.ope-_n7qw {
  stop-color: var(--svg-color--ad7853, #AD7853);
}

.pp7ghrbxn {
  stop-color: var(--svg-color--6b392f, #6B392F);
}

.q65hg7bxg {
  stop-color: var(--svg-color--e29856, #E29856);
  stop-opacity: 0;
}

.q7khhzn1i {
  stop-color: var(--svg-color--a26f4e, #A26F4E);
}

.qbvy3ebmp {
  stop-color: var(--svg-color--fdcea1, #FDCEA1);
  stop-opacity: 0;
}

.qoi3jh2jb {
  stop-color: var(--svg-color--f9c796, #F9C796);
  stop-opacity: 0;
}

.qxl2kub_h {
  fill: var(--svg-color--ead237, #EAD237);
  d: path("m15.04 12.588l-3.06 1.82a1.19 1.19 0 0 0 0 2.05l3.06 1.81c.57.34 1.28.34 1.85 0l3.06-1.81c.78-.46.78-1.59 0-2.05l-3.06-1.81c-.57-.35-1.28-.35-1.85-.01");
}

.rfjmk-kjz {
  stop-color: var(--svg-color--f3a363, #F3A363);
}

.s0c1xgboy {
  stop-color: var(--svg-color--ee9d67, #EE9D67);
}

.sbu53kxow {
  stop-color: var(--svg-color--eeba87, #EEBA87);
}

.sfmksg-ww {
  stop-color: var(--svg-color--d4868e, #D4868E);
  stop-opacity: 0;
}

.u-1se5bme {
  stop-color: var(--svg-color--9c634d, #9C634D);
}

.u1dhqdhom {
  stop-color: var(--svg-color--e8c12e, #E8C12E);
}

.ucel41bkw {
  stop-color: var(--svg-color--fac796, #FAC796);
}

.vv5yk2bbm {
  stop-color: var(--svg-color--e48c8c, #E48C8C);
  stop-opacity: 0;
}

.vzqa40bie {
  stop-color: var(--svg-color--b1764b, #B1764B);
}

.w8ko9nkai {
  d: path("m15.48 19.878l-1.46.86c-.41.24-.41.84 0 1.09l1.46.86c.3.18.67.18.96 0l1.46-.86c.41-.24.41-.84 0-1.09l-1.46-.86a.92.92 0 0 0-.96 0");
}

.x33tema_b {
  stop-color: var(--svg-color--f0a264, #F0A264);
  stop-opacity: 0;
}

.x57jl-toe {
  stop-color: var(--svg-color--f0cb4b, #F0CB4B);
}

.xiru_e-jj {
  stop-color: var(--svg-color--e6a868, #E6A868);
}

.xo_ctfqjh {
  stop-color: var(--svg-color--f8c199, #F8C199);
}

.xpg7qbdiy {
  stop-color: var(--svg-color--63332a, #63332A);
}

.y-j97mbzr {
  stop-color: var(--svg-color--fdcea1, #FDCEA1);
}

.yqhhz1byj {
  stop-color: var(--svg-color--c7a22b, #C7A22B);
}

.zpz3r9byf {
  d: path("m22.92 14.558l-5.34-4.66c-1-.59-2.24-.59-3.24 0l-5.33 4.66l-1.78-.04a5.14 5.14 0 0 0-4.96 3.41c-.39 1.03-.36 2.18.1 3.18c.32.71.84 1.31 1.5 1.73l8.65 5.21a6.75 6.75 0 0 0 6.89 0l8.65-5.21c.65-.42 1.17-1.02 1.5-1.73c.46-1 .5-2.15.1-3.18a5.14 5.14 0 0 0-4.96-3.42z");
}

</style>
