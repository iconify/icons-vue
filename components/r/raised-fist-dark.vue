<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iDi1Sxc)"><path fill="url(#iOAKcSY)" class="z5gkcf-av"/></g><g filter="url(#imm3Egd)"><rect fill="url(#iy6lYYL)" class="kgq1yxb-w"/></g><g filter="url(#iYPQWDK)"><path class="f_-18gbax"/></g><rect fill="url(#iHfA9Ea)" class="yqrsv_hxq"/><rect fill="url(#iaq53Be)" class="yqrsv_hxq"/><rect fill="url(#i7KAnVC)" class="yqrsv_hxq"/><rect fill="url(#iurGTuB)" class="yqrsv_hxq"/><path fill="url(#i3CjV3c)" class="oz9fqcisu"/><path fill="url(#iVvhTFb)" class="oz9fqcisu"/><path fill="url(#iiXlOHd)" class="oz9fqcisu"/><path fill="url(#i8JJxCd)" class="oz9fqcisu"/><rect class="q1vclbzpe"/><rect fill="url(#iApnqhc)" class="tcvr7tulc"/><rect fill="url(#iD5ESed)" class="tcvr7tulc"/><rect fill="url(#i9HKrRb)" class="tcvr7tulc"/><rect fill="url(#iUWpkie)" class="tcvr7tulc"/><path fill="url(#i6iRZ9c)" class="e599lnq0o"/><path fill="url(#iZRlaNw)" class="e599lnq0o"/><path fill="url(#iU5Tpel)" class="e599lnq0o"/><path fill="url(#iCPHlPd)" class="e599lnq0o"/><path fill="url(#i4Bm7ve)" class="k0zn1ebow"/><path fill="url(#iQC5Sqe)" class="k0zn1ebow"/><path fill="url(#i41drZO)" class="k0zn1ebow"/><path fill="url(#iZCOwxe)" class="k0zn1ebow"/><g filter="url(#i4WeuCn)"><path stroke="url(#imP5mTd)" class="nq9o5_b-r"/></g><defs><radialGradient id="iOAKcSY" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3034 -15.1439 0 16 17.516)" gradientUnits="userSpaceOnUse"><stop class="z_wfxjr5n"/><stop offset="1" class="k5ghui_bl"/></radialGradient><radialGradient id="iHfA9Ea" cx="0" cy="0" r="1" gradientTransform="matrix(-2.5 0 0 -5.6994 8.031 8.762)" gradientUnits="userSpaceOnUse"><stop class="ku8qdqe8t"/><stop offset="1" class="z1jsyjv2f"/></radialGradient><radialGradient id="iaq53Be" cx="0" cy="0" r="1" gradientTransform="rotate(107.103 1.074 7.072)scale(7.31258 6.34489)" gradientUnits="userSpaceOnUse"><stop offset=".629" class="dii1v3btn"/><stop offset="1" class="g8yemxb4v"/></radialGradient><radialGradient id="i7KAnVC" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67954 0 0 -10.0187 9.663 10.126)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="es6vmmb9b"/><stop offset="1" class="pwmb7xbsq"/></radialGradient><radialGradient id="iurGTuB" cx="0" cy="0" r="1" gradientTransform="matrix(1.22807 1.63545 -3.19277 2.39747 4.202 5.531)" gradientUnits="userSpaceOnUse"><stop class="oz1mwln8e"/><stop offset="1" class="r-xeijbgi"/></radialGradient><radialGradient id="i3CjV3c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68026 0 0 -6.81623 13.288 7.833)" gradientUnits="userSpaceOnUse"><stop class="ku8qdqe8t"/><stop offset="1" class="z1jsyjv2f"/></radialGradient><radialGradient id="iVvhTFb" cx="0" cy="0" r="1" gradientTransform="rotate(99.464 3.695 9.23)scale(7.68967 5.95051)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="dii1v3btn"/><stop offset="1" class="g8yemxb4v"/></radialGradient><radialGradient id="iiXlOHd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.69318 0 0 -11.0191 15.537 9.394)" gradientUnits="userSpaceOnUse"><stop class="ohrh-ib0s"/><stop offset="1" class="v_3957bgx"/></radialGradient><radialGradient id="i8JJxCd" cx="0" cy="0" r="1" gradientTransform="rotate(56.736 .901 10.826)scale(2.23897 4.17494)" gradientUnits="userSpaceOnUse"><stop class="oz1mwln8e"/><stop offset="1" class="r-xeijbgi"/></radialGradient><radialGradient id="iApnqhc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02062 0 0 -8.00328 25.914 6.921)" gradientUnits="userSpaceOnUse"><stop class="a5c9r5b5q"/><stop offset="1" class="wf6fztybg"/></radialGradient><radialGradient id="iD5ESed" cx="0" cy="0" r="1" gradientTransform="matrix(1.22188 0 0 9.17868 21.241 8.548)" gradientUnits="userSpaceOnUse"><stop class="ohrh-ib0s"/><stop offset="1" class="v_3957bgx"/></radialGradient><radialGradient id="i9HKrRb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.26443 7.90242 -5.88203 -.94116 25.692 6.161)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="dii1v3btn"/><stop offset="1" class="g8yemxb4v"/></radialGradient><radialGradient id="iUWpkie" cx="0" cy="0" r="1" gradientTransform="rotate(57.804 8.094 21.228)scale(2.30488 4.22527)" gradientUnits="userSpaceOnUse"><stop class="oz1mwln8e"/><stop offset="1" class="r-xeijbgi"/></radialGradient><radialGradient id="i6iRZ9c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.74005 0 0 -6.46652 19.845 8.177)" gradientUnits="userSpaceOnUse"><stop class="z_ok4qbes"/><stop offset="1" class="wf6fztybg"/></radialGradient><radialGradient id="iZRlaNw" cx="0" cy="0" r="1" gradientTransform="matrix(-1.2549 0 0 -9.3506 22 8.952)" gradientUnits="userSpaceOnUse"><stop class="waud5kbkr"/><stop offset="1" class="okk48gb0v"/></radialGradient><radialGradient id="iU5Tpel" cx="0" cy="0" r="1" gradientTransform="matrix(-1.24589 8.5571 -5.82078 -.84749 19.371 6.367)" gradientUnits="userSpaceOnUse"><stop offset=".613" class="b4qwoqbba"/><stop offset="1" class="mt3j0vb9i"/></radialGradient><radialGradient id="iCPHlPd" cx="0" cy="0" r="1" gradientTransform="rotate(60.19 5.138 14.865)scale(2.43413 4.26884)" gradientUnits="userSpaceOnUse"><stop class="oz1mwln8e"/><stop offset="1" class="r-xeijbgi"/></radialGradient><radialGradient id="i4Bm7ve" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0336 5.97998 -11.68396 -2.0195 24.445 11.974)" gradientUnits="userSpaceOnUse"><stop class="mhcyt_btx"/><stop offset="1" class="jd-z1nwds"/></radialGradient><radialGradient id="iQC5Sqe" cx="0" cy="0" r="1" gradientTransform="matrix(1.77917 -3.58357 4.1073 2.03918 23.818 21.525)" gradientUnits="userSpaceOnUse"><stop class="yhq7pzb7h"/><stop offset="1" class="thc9rbyed"/></radialGradient><radialGradient id="i41drZO" cx="0" cy="0" r="1" gradientTransform="matrix(3.74677 0 0 5.4251 14.24 13.267)" gradientUnits="userSpaceOnUse"><stop class="vgekv3bdy"/><stop offset="1" class="dud306bbg"/></radialGradient><radialGradient id="iZCOwxe" cx="0" cy="0" r="1" gradientTransform="matrix(1.14015 -.98439 1.64762 1.90833 15.307 15.661)" gradientUnits="userSpaceOnUse"><stop class="dzz3qsbnx"/><stop offset="1" class="vixjclbte"/></radialGradient><filter id="iDi1Sxc" width="25.02" height="20.828" x="3.49" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.25098 0 0 0 0 0.145098 0 0 0 0 0.239216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3129"/></filter><filter id="imm3Egd" width="18.678" height="12.194" x="7.28" y="9.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3129" stdDeviation="1.5"/></filter><filter id="iYPQWDK" width="24.653" height="14.935" x="3.21" y="3.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3129" stdDeviation="1"/></filter><filter id="i4WeuCn" width="12.76" height="8.553" x="17.128" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3129" stdDeviation=".85"/></filter><linearGradient id="iy6lYYL" x1="20.393" x2="8.571" y1="17.241" y2="21.196" gradientUnits="userSpaceOnUse"><stop class="ix_ijnsqw"/><stop offset="1" class="w5ti65fxv"/></linearGradient><linearGradient id="imP5mTd" x1="19.828" x2="31.13" y1="12.402" y2="16.093" gradientUnits="userSpaceOnUse"><stop class="n9qredbtw"/><stop offset="1" class="p275leyrc"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-fist-dark" /></template>
<style>
.a5c9r5b5q {
  stop-color: var(--svg-color--64504e, #64504E);
}

.b4qwoqbba {
  stop-color: var(--svg-color--221012, #221012);
  stop-opacity: 0;
}

.dii1v3btn {
  stop-color: var(--svg-color--381e2a, #381E2A);
  stop-opacity: 0;
}

.dud306bbg {
  stop-color: var(--svg-color--3e2828, #3E2828);
  stop-opacity: 0;
}

.dzz3qsbnx {
  stop-color: var(--svg-color--43302f, #43302F);
}

.e599lnq0o {
  d: path("M14.78 5.675c0-1.847 1.498-3.166 3.345-3.166a3.345 3.345 0 0 1 3.346 3.346v6.192a3.345 3.345 0 0 1-6.69 0z");
}

.es6vmmb9b {
  stop-color: var(--svg-color--241210, #241210);
}

.f_-18gbax {
  fill: var(--svg-color--17080c, #17080C);
  d: path("M15.024 14.283c-.504.868-1.422 1.472-2.47 1.472c-.93 0-1.757-.314-2.283-.987a2.882 2.882 0 0 1-5.06-1.886v-2.704a2.882 2.882 0 0 1 4.61-2.306c.383-1.244 1.462-1.81 2.733-1.81c.936 0 1.768.447 2.294 1.138c.26-1.272 1.408-2.135 2.785-2.135a2.84 2.84 0 0 1 2.674 1.884a2.882 2.882 0 0 1 5.556 1.074v4.335a2.882 2.882 0 0 1-5.44 1.327a2.84 2.84 0 0 1-5.4.598");
}

.ft5dv1b6b {
  fill: none;
}

.g8yemxb4v {
  stop-color: var(--svg-color--381e2a, #381E2A);
}

.ix_ijnsqw {
  stop-color: var(--svg-color--211013, #211013);
}

.jd-z1nwds {
  stop-color: var(--svg-color--3c202f, #3C202F);
}

.k0zn1ebow {
  d: path("M18.339 9.797c-1.965 0-3.559 1.507-3.559 3.365s1.594 3.365 3.559 3.365h2.602c1.168 0 2.115.896 2.115 2v2.998h.2c3.464 0 5.254-3.02 5.254-5.765c0-3.293-2.823-5.963-6.306-5.963z");
}

.k5ghui_bl {
  stop-color: var(--svg-color--422731, #422731);
}

.kgq1yxb-w {
  width: 12.678px;
  height: 6.195px;
  x: 10.28px;
  y: 12.903px;
  rx: 3.097px;
}

.ku8qdqe8t {
  stop-color: var(--svg-color--584545, #584545);
}

.mhcyt_btx {
  stop-color: var(--svg-color--553b37, #553B37);
}

.mt3j0vb9i {
  stop-color: var(--svg-color--221012, #221012);
}

.n9qredbtw {
  stop-color: var(--svg-color--5e4948, #5E4948);
}

.nq9o5_b-r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.828 12.25h2.14c3.187-.131 4.706 1.01 5.22 3.143");
}

.ohrh-ib0s {
  stop-color: var(--svg-color--2a1714, #2A1714);
}

.okk48gb0v {
  stop-color: var(--svg-color--4a2f2a, #4A2F2A);
  stop-opacity: 0;
}

.oz1mwln8e {
  stop-color: var(--svg-color--4e4341, #4E4341);
}

.oz9fqcisu {
  d: path("M8.747 7.08c0-2.35 1.52-3.396 3.395-3.396a3.395 3.395 0 0 1 3.395 3.395v4.509c0 1.875-1.52 3.516-3.395 3.516s-3.395-1.085-3.395-3.516z");
}

.p275leyrc {
  stop-color: var(--svg-color--5e4948, #5E4948);
  stop-opacity: 0;
}

.pwmb7xbsq {
  stop-color: var(--svg-color--241210, #241210);
  stop-opacity: 0;
}

.q1vclbzpe {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  fill: var(--svg-color--7dde5b, #7DDE5B);
  fill-opacity: var(--svg-fill-opacity--0-55, 0.55);
  rx: 3.395px;
}

.r-xeijbgi {
  stop-color: var(--svg-color--4e4341, #4E4341);
  stop-opacity: 0;
}

.tcvr7tulc {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  rx: 3.395px;
}

.thc9rbyed {
  stop-color: var(--svg-color--3f272d, #3F272D);
  stop-opacity: 0;
}

.v_3957bgx {
  stop-color: var(--svg-color--2a1714, #2A1714);
  stop-opacity: 0;
}

.vgekv3bdy {
  stop-color: var(--svg-color--3e2828, #3E2828);
}

.vixjclbte {
  stop-color: var(--svg-color--43302f, #43302F);
  stop-opacity: 0;
}

.w5ti65fxv {
  stop-color: var(--svg-color--211013, #211013);
  stop-opacity: 0;
}

.waud5kbkr {
  stop-color: var(--svg-color--4a2f2a, #4A2F2A);
}

.wf6fztybg {
  stop-color: var(--svg-color--402c29, #402C29);
}

.yhq7pzb7h {
  stop-color: var(--svg-color--3f272d, #3F272D);
}

.yqrsv_hxq {
  width: 6.79px;
  height: 9.976px;
  x: 3.49px;
  y: 5.138px;
  rx: 3.395px;
}

.z_ok4qbes {
  stop-color: var(--svg-color--66524f, #66524F);
}

.z_wfxjr5n {
  stop-color: var(--svg-color--392526, #392526);
}

.z1jsyjv2f {
  stop-color: var(--svg-color--3e2521, #3E2521);
}

.z5gkcf-av {
  d: path("M27.823 9.479H3.49v9.328c0 6.351 5.149 11.5 11.5 11.5h1.333c2.153 0 4.168-.592 5.89-1.621l.005.018c2.518-1.454 5.089-4.099 5.904-7.358c.83-3.325.134-5.707-.3-6.552z");
}

</style>
