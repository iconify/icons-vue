<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iFrKkSd)" class="en25hjbrc"/><path fill="url(#itVgTXd)" class="en25hjbrc"/><path fill="url(#iO477Cd)" class="en25hjbrc"/><path fill="url(#iDq30Ke)" class="en25hjbrc"/><path fill="url(#igxYMKb)" class="en25hjbrc"/><path fill="url(#imSg4Xe)" class="aigpknpit"/><g filter="url(#iAg2vme)"><path fill="url(#iGj5uXb)" class="rop537kzt"/><path fill="url(#i0Hxodd)" class="rop537kzt"/><path fill="url(#ixdf01V)" class="rop537kzt"/></g><path fill="url(#ihyRmjd)" class="rop537kzt"/><path fill="url(#iRPTPxd)" class="rop537kzt"/><path fill="url(#i9o0Xab)" class="rop537kzt"/><path fill="url(#iGLaVnc)" class="difyqgbuv"/><path fill="url(#iOl9XAd)" class="difyqgbuv"/><path fill="url(#iPMC47c)" class="difyqgbuv"/><path fill="url(#iLlks1s)" class="til7gubcp"/><path fill="url(#ivPD58R)" class="til7gubcp"/><path fill="url(#iBnP8Ac)" class="til7gubcp"/><path fill="url(#i8d5Lid)" class="til7gubcp"/><path fill="url(#igZyIDc)" class="zpkmjvfhd"/><path fill="url(#iFgHXrO)" class="zpkmjvfhd"/><path fill="url(#iKkbJJK)" class="zpkmjvfhd"/><defs><radialGradient id="iO477Cd" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 .57812 -1.38272 2.84017 25.496 28.074)" gradientUnits="userSpaceOnUse"><stop class="gs6ddsb3t"/><stop offset=".912" class="xcir0qpos"/></radialGradient><radialGradient id="iDq30Ke" cx="0" cy="0" r="1" gradientTransform="matrix(.82422 -.80078 3.94038 4.0557 26.219 29.203)" gradientUnits="userSpaceOnUse"><stop class="tsyjrux_b"/><stop offset=".253" class="e8b31zjef"/></radialGradient><radialGradient id="igxYMKb" cx="0" cy="0" r="1" gradientTransform="matrix(6.625 .3125 -.4838 10.2567 23.906 22.063)" gradientUnits="userSpaceOnUse"><stop offset=".84" class="e_pj9h8gv"/><stop offset="1" class="dt8y6h7qs"/></radialGradient><radialGradient id="imSg4Xe" cx="0" cy="0" r="1" gradientTransform="matrix(5.25 -.125 .14443 6.06606 21.719 22.562)" gradientUnits="userSpaceOnUse"><stop class="lg-vp7lln"/><stop offset="1" class="wgwbd9baq"/></radialGradient><radialGradient id="i0Hxodd" cx="0" cy="0" r="1" gradientTransform="rotate(-144.697 15.111 12.88)scale(17.5202 11.1848)" gradientUnits="userSpaceOnUse"><stop class="x4k8v9xpz"/><stop offset="1" class="cx4qxtdtr"/></radialGradient><radialGradient id="ixdf01V" cx="0" cy="0" r="1" gradientTransform="matrix(-11 -5.37504 2.28671 -4.67975 22 31.5)" gradientUnits="userSpaceOnUse"><stop class="cqiux43cy"/><stop offset="1" class="uvhrxmbwz"/></radialGradient><radialGradient id="iRPTPxd" cx="0" cy="0" r="1" gradientTransform="rotate(156.448 10.455 9.288)scale(10.636 8.08629)" gradientUnits="userSpaceOnUse"><stop class="v95bo0bfg"/><stop offset="1" class="k-5g0ntzq"/></radialGradient><radialGradient id="i9o0Xab" cx="0" cy="0" r="1" gradientTransform="matrix(12.78249 1.5 -1.39247 11.86618 3.5 21.375)" gradientUnits="userSpaceOnUse"><stop class="q53x8e4dr"/><stop offset="1" class="jy2jovegb"/></radialGradient><radialGradient id="iGLaVnc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.75 .0625 -.06242 -2.7463 5.688 4.875)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="gxho33edf"/><stop offset="1" class="q2zj-kojh"/></radialGradient><radialGradient id="iPMC47c" cx="0" cy="0" r="1" gradientTransform="matrix(-1.794 -1.95 2.60712 -2.39854 4.653 5.684)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="og7-6ibpw"/><stop offset=".954" class="ngs5mxf9h"/></radialGradient><radialGradient id="ivPD58R" cx="0" cy="0" r="1" gradientTransform="rotate(138.434 3.912 4.059)scale(4.42737 1.75627)" gradientUnits="userSpaceOnUse"><stop class="p6ab92bed"/><stop offset="1" class="psyaaqb3u"/></radialGradient><radialGradient id="iBnP8Ac" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 -5.6875 5.7764 3.49123 5.563 12)" gradientUnits="userSpaceOnUse"><stop class="ew1uzxvzb"/><stop offset="1" class="l_a452sqg"/></radialGradient><radialGradient id="iFgHXrO" cx="0" cy="0" r="1" gradientTransform="matrix(-4.25 4.125 -2.8921 -2.97973 15.125 7.75)" gradientUnits="userSpaceOnUse"><stop class="p6ab92bed"/><stop offset="1" class="psyaaqb3u"/></radialGradient><radialGradient id="iKkbJJK" cx="0" cy="0" r="1" gradientTransform="rotate(-45 23.73 -.954)scale(10.34139 10.5041)" gradientUnits="userSpaceOnUse"><stop class="ew1uzxvzb"/><stop offset="1" class="l_a452sqg"/></radialGradient><linearGradient id="iFrKkSd" x1="27.105" x2="28.105" y1="19.043" y2="29.895" gradientUnits="userSpaceOnUse"><stop offset=".006" class="kcfcp96ga"/><stop offset="1" class="c-bqjfbdl"/></linearGradient><linearGradient id="itVgTXd" x1="26.012" x2="29.23" y1="14.887" y2="17.168" gradientUnits="userSpaceOnUse"><stop class="kcfcp96ga"/><stop offset="1" class="wa3v7bbbb"/></linearGradient><linearGradient id="iGj5uXb" x1="12.75" x2="29.5" y1="18.063" y2="34.875" gradientUnits="userSpaceOnUse"><stop class="n9h322bub"/><stop offset="1" class="h0alakj3x"/></linearGradient><linearGradient id="ihyRmjd" x1="10.25" x2="13.063" y1="13" y2="15.813" gradientUnits="userSpaceOnUse"><stop class="z6cmhd-2e"/><stop offset="1" class="fb89tvk4t"/></linearGradient><linearGradient id="iOl9XAd" x1="5.234" x2="4.531" y1="5.898" y2="5.109" gradientUnits="userSpaceOnUse"><stop class="xgjvkhp9a"/><stop offset="1" class="to8ww8bkv"/></linearGradient><linearGradient id="iLlks1s" x1="7.122" x2="4.952" y1="7.92" y2="5.721" gradientUnits="userSpaceOnUse"><stop class="j5nonfd8k"/><stop offset="1" class="oeg0whb-d"/></linearGradient><linearGradient id="i8d5Lid" x1="7.5" x2="6.563" y1="9.156" y2="8.188" gradientUnits="userSpaceOnUse"><stop class="wv0i_1biq"/><stop offset="1" class="po71jw9ry"/></linearGradient><linearGradient id="igZyIDc" x1="10.545" x2="7.36" y1="11.58" y2="8.394" gradientUnits="userSpaceOnUse"><stop class="j5nonfd8k"/><stop offset="1" class="oeg0whb-d"/></linearGradient><filter id="iAg2vme" width="21.162" height="23.046" x="5.702" y="7.119" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".25"/><feGaussianBlur stdDeviation=".125"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.780392 0 0 0 0 0.760784 0 0 0 0 0.831373 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_6169"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:spiral-shell" /></template>
<style>
.aigpknpit {
  d: path("m22.933 14.174l-5.79 5.51l8.3 8.71c3.2-3.05 3.32-8.11.27-11.3z");
}

.c-bqjfbdl {
  stop-color: var(--svg-color--bdb3cf, #BDB3CF);
}

.cqiux43cy {
  stop-color: var(--svg-color--9d7bc2, #9D7BC2);
}

.cx4qxtdtr {
  stop-color: var(--svg-color--a382c8, #A382C8);
  stop-opacity: 0;
}

.difyqgbuv {
  d: path("M4.653 8.124a2.44 2.44 0 1 0 0-4.88a2.44 2.44 0 0 0 0 4.88");
}

.dt8y6h7qs {
  stop-color: var(--svg-color--cac4d9, #CAC4D9);
}

.e_pj9h8gv {
  stop-color: var(--svg-color--cac4d9, #CAC4D9);
  stop-opacity: 0;
}

.e8b31zjef {
  stop-color: var(--svg-color--c3bed0, #C3BED0);
  stop-opacity: 0;
}

.en25hjbrc {
  d: path("m23.744 12.255l-7.17 6.84l10.29 10.8c3.96-3.77 4.11-10.05.34-14.01z");
}

.ew1uzxvzb {
  stop-color: var(--svg-color--b4a8c7, #B4A8C7);
}

.fb89tvk4t {
  stop-color: var(--svg-color--b6b1c2, #B6B1C2);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.gs6ddsb3t {
  stop-color: var(--svg-color--a29faf, #A29FAF);
}

.gxho33edf {
  stop-color: var(--svg-color--e2e0ea, #E2E0EA);
}

.h0alakj3x {
  stop-color: var(--svg-color--b196d3, #B196D3);
}

.j5nonfd8k {
  stop-color: var(--svg-color--c7c7ce, #C7C7CE);
}

.jy2jovegb {
  stop-color: var(--svg-color--aca7b8, #ACA7B8);
  stop-opacity: 0;
}

.k-5g0ntzq {
  stop-color: var(--svg-color--e3e1eb, #E3E1EB);
  stop-opacity: 0;
}

.kcfcp96ga {
  stop-color: var(--svg-color--c8c8ce, #C8C8CE);
}

.l_a452sqg {
  stop-color: var(--svg-color--b4a8c7, #B4A8C7);
  stop-opacity: 0;
}

.lg-vp7lln {
  stop-color: var(--svg-color--3e3763, #3E3763);
}

.n9h322bub {
  stop-color: var(--svg-color--c2c2c9, #C2C2C9);
}

.ngs5mxf9h {
  stop-color: var(--svg-color--95959a, #95959A);
}

.oeg0whb-d {
  stop-color: var(--svg-color--a6a5af, #A6A5AF);
}

.og7-6ibpw {
  stop-color: var(--svg-color--a3a3a8, #A3A3A8);
  stop-opacity: 0;
}

.p6ab92bed {
  stop-color: var(--svg-color--e2e1e9, #E2E1E9);
}

.po71jw9ry {
  stop-color: var(--svg-color--b1adbc, #B1ADBC);
  stop-opacity: 0;
}

.psyaaqb3u {
  stop-color: var(--svg-color--e2e1e9, #E2E1E9);
  stop-opacity: 0;
}

.q2zj-kojh {
  stop-color: var(--svg-color--acaab4, #ACAAB4);
}

.q53x8e4dr {
  stop-color: var(--svg-color--aca7b8, #ACA7B8);
}

.rop537kzt {
  d: path("m12.743 9.194l-4 3.81c-3.92 3.74-4.07 9.95-.34 13.87a9.8 9.8 0 0 0 7.12 3.04l11.34-.02l-3.9-4.09c-1.55-1.62-1.48-4.19.14-5.74c3.01-2.86 3.12-7.62.26-10.63c-2.85-2.99-7.61-3.1-10.62-.24");
}

.til7gubcp {
  d: path("m6.773 3.614l-4.08 3.88c-.89.85-.93 2.26-.08 3.15l1.763 1.823l7.3-6.96l-1.763-1.823c-.84-.88-2.25-.92-3.14-.07");
}

.to8ww8bkv {
  stop-color: var(--svg-color--b2b2b9, #B2B2B9);
  stop-opacity: 0;
}

.tsyjrux_b {
  stop-color: var(--svg-color--c3bed0, #C3BED0);
}

.uvhrxmbwz {
  stop-color: var(--svg-color--9d7bc2, #9D7BC2);
  stop-opacity: 0;
}

.v95bo0bfg {
  stop-color: var(--svg-color--e3e1eb, #E3E1EB);
}

.wa3v7bbbb {
  stop-color: var(--svg-color--c8c8ce, #C8C8CE);
  stop-opacity: 0;
}

.wgwbd9baq {
  stop-color: var(--svg-color--271f4b, #271F4B);
}

.wv0i_1biq {
  stop-color: var(--svg-color--b1adbc, #B1ADBC);
}

.x4k8v9xpz {
  stop-color: var(--svg-color--a382c8, #A382C8);
}

.xcir0qpos {
  stop-color: var(--svg-color--a29faf, #A29FAF);
  stop-opacity: 0;
}

.xgjvkhp9a {
  stop-color: var(--svg-color--b2b2b9, #B2B2B9);
}

.z6cmhd-2e {
  stop-color: var(--svg-color--b6b1c2, #B6B1C2);
}

.zpkmjvfhd {
  d: path("m10.613 5.324l-6.4 6.1a3.505 3.505 0 0 0-.12 4.95l1.79 1.88L17.141 7.172l-1.588-1.718a3.475 3.475 0 0 0-4.94-.13");
}

</style>
