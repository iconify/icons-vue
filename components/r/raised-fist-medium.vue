<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iLyMkre)"><path fill="url(#iE8p1gd)" class="z5gkcf-av"/></g><path fill="url(#izTwhoh)" class="z5gkcf-av"/><path fill="url(#itgx2Vd)" class="z5gkcf-av"/><g filter="url(#iEq235c)"><rect fill="url(#iYCKcvb)" class="kgq1yxb-w"/></g><g filter="url(#iotfXMe)"><path class="fy483t18j"/></g><rect fill="url(#ikvoflb)" class="yqrsv_hxq"/><rect fill="url(#iK2svsD)" class="yqrsv_hxq"/><rect fill="url(#i3PECBb)" class="yqrsv_hxq"/><rect fill="url(#izpMx4c)" class="yqrsv_hxq"/><path fill="url(#iuwIOKb)" class="oz9fqcisu"/><path fill="url(#iKc81Vb)" class="oz9fqcisu"/><path fill="url(#inEtTfd)" class="oz9fqcisu"/><path fill="url(#iBiLXbb)" class="oz9fqcisu"/><rect class="q1vclbzpe"/><rect fill="url(#ieosfgd)" class="tcvr7tulc"/><rect fill="url(#itwygZb)" class="tcvr7tulc"/><path fill="url(#iICauPb)" class="e599lnq0o"/><path fill="url(#iUkDsDb)" class="e599lnq0o"/><path fill="url(#iAeVpFc)" class="e599lnq0o"/><path fill="url(#ioshfxd)" class="e599lnq0o"/><path fill="url(#iLQyyVb)" class="k0zn1ebow"/><path fill="url(#iKW2n7c)" class="k0zn1ebow"/><path fill="url(#iPbIwfc)" class="k0zn1ebow"/><path fill="url(#iXcHReb)" class="k0zn1ebow"/><path fill="url(#isS0cVq)" class="k0zn1ebow"/><path fill="url(#i7csJIc)" class="k0zn1ebow"/><g filter="url(#iE5K2Le)"><path stroke="url(#iD3n5vb)" class="nq9o5_b-r"/></g><defs><radialGradient id="iE8p1gd" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3034 -15.1439 0 16 17.516)" gradientUnits="userSpaceOnUse"><stop class="zzi2hb-yn"/><stop offset="1" class="shce70u_a"/></radialGradient><radialGradient id="izTwhoh" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0399 -20.6277 0 16 18.075)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="d8rgnmblk"/><stop offset="1" class="e16m8h_rf"/></radialGradient><radialGradient id="itgx2Vd" cx="0" cy="0" r="1" gradientTransform="rotate(136.801 4.779 12.054)scale(14.2398 19.6064)" gradientUnits="userSpaceOnUse"><stop offset=".779" class="can-iz3yi"/><stop offset="1" class="ytt_t5bbb"/></radialGradient><radialGradient id="ikvoflb" cx="0" cy="0" r="1" gradientTransform="matrix(-2.86026 0 0 -6.52072 8.233 10.438)" gradientUnits="userSpaceOnUse"><stop class="gpm8n5jae"/><stop offset="1" class="l3172sb8e"/></radialGradient><radialGradient id="iK2svsD" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.80979 -6.7763 0 6.885 7.064)" gradientUnits="userSpaceOnUse"><stop offset=".5" class="c-iffccrk"/><stop offset="1" class="sxt9otg6x"/></radialGradient><radialGradient id="i3PECBb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67954 0 0 -10.0187 9.663 10.126)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="uyxopq3zq"/><stop offset="1" class="s28y23brv"/></radialGradient><radialGradient id="izpMx4c" cx="0" cy="0" r="1" gradientTransform="matrix(1.22807 1.63545 -3.19277 2.39747 4.202 5.531)" gradientUnits="userSpaceOnUse"><stop class="q1lla5xtl"/><stop offset="1" class="zvybr_bcw"/></radialGradient><radialGradient id="iuwIOKb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.07788 0 0 -13.2516 13.49 9.752)" gradientUnits="userSpaceOnUse"><stop class="cu9gv7ced"/><stop offset=".708" class="l3172sb8e"/><stop offset="1" class="igu-flb-x"/></radialGradient><radialGradient id="iKc81Vb" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.57207 -7.25544 0 12.142 5.89)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="h49cr7b_r"/><stop offset="1" class="aya7a3bqt"/></radialGradient><radialGradient id="inEtTfd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.75619 0 0 -11.9919 15.537 9.394)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="q3y1vh5-t"/><stop offset="1" class="u6sqbo62y"/></radialGradient><radialGradient id="iBiLXbb" cx="0" cy="0" r="1" gradientTransform="rotate(56.736 .901 10.826)scale(2.23897 4.17494)" gradientUnits="userSpaceOnUse"><stop class="q1lla5xtl"/><stop offset="1" class="zvybr_bcw"/></radialGradient><radialGradient id="ieosfgd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.74326 0 0 -14.307 25.776 8.92)" gradientUnits="userSpaceOnUse"><stop class="eo24s8bon"/><stop offset=".615" class="dtnee9b6l"/><stop offset="1" class="d846hcb-i"/></radialGradient><radialGradient id="itwygZb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.02456 0 0 -21.5171 30.381 8.548)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="m1-n9eimp"/><stop offset="1" class="u6sqbo62y"/><stop offset="1" class="qauqg0hpg"/></radialGradient><radialGradient id="iICauPb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.67371 0 0 -15.4923 19.454 9.354)" gradientUnits="userSpaceOnUse"><stop class="eo24s8bon"/><stop offset=".615" class="dtnee9b6l"/><stop offset="1" class="d846hcb-i"/></radialGradient><radialGradient id="iUkDsDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.7988 -7.14906 0 18.125 4.997)" gradientUnits="userSpaceOnUse"><stop offset=".536" class="h49cr7b_r"/><stop offset="1" class="aya7a3bqt"/></radialGradient><radialGradient id="iAeVpFc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.81294 0 0 -14.1738 22.696 8.951)" gradientUnits="userSpaceOnUse"><stop offset=".229" class="m1-n9eimp"/><stop offset="1" class="u6sqbo62y"/><stop offset="1" class="qauqg0hpg"/></radialGradient><radialGradient id="ioshfxd" cx="0" cy="0" r="1" gradientTransform="rotate(60.19 5.138 14.865)scale(2.43413 4.26884)" gradientUnits="userSpaceOnUse"><stop class="q1lla5xtl"/><stop offset="1" class="zvybr_bcw"/></radialGradient><radialGradient id="iLQyyVb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30518 5.45366 -11.83567 -2.83254 23.77 10.987)" gradientUnits="userSpaceOnUse"><stop class="hiyftsb_l"/><stop offset="1" class="pf7p_5brz"/></radialGradient><radialGradient id="iKW2n7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.77179 -6.41638 0 19.836 17.548)" gradientUnits="userSpaceOnUse"><stop offset=".412" class="yo1dcgyuf"/><stop offset="1" class="qbskpd8ec"/></radialGradient><radialGradient id="iPbIwfc" cx="0" cy="0" r="1" gradientTransform="rotate(-54.289 32.947 -12.554)scale(7.88263 9.03463)" gradientUnits="userSpaceOnUse"><stop class="a4i9-qnlz"/><stop offset="1" class="yjrrwwncj"/></radialGradient><radialGradient id="iXcHReb" cx="0" cy="0" r="1" gradientTransform="matrix(3.74677 0 0 5.4251 14.24 13.267)" gradientUnits="userSpaceOnUse"><stop class="n97z1_bjk"/><stop offset="1" class="zi46wu1tm"/></radialGradient><radialGradient id="isS0cVq" cx="0" cy="0" r="1" gradientTransform="matrix(2.9832 -2.51707 2.60763 3.09052 16.171 16.72)" gradientUnits="userSpaceOnUse"><stop class="yo1dcgyuf"/><stop offset="1" class="qbskpd8ec"/></radialGradient><radialGradient id="i7csJIc" cx="0" cy="0" r="1" gradientTransform="matrix(1.14015 -.98439 1.64762 1.90833 15.307 15.661)" gradientUnits="userSpaceOnUse"><stop class="sso-z9b1d"/><stop offset="1" class="si-y-4bpl"/></radialGradient><filter id="iLyMkre" width="25.02" height="20.828" x="3.49" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.576471 0 0 0 0 0.388235 0 0 0 0 0.4 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3152"/></filter><filter id="iEq235c" width="18.678" height="12.194" x="7.28" y="9.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3152" stdDeviation="1.5"/></filter><filter id="iotfXMe" width="24.653" height="14.935" x="3.21" y="3.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3152" stdDeviation="1"/></filter><filter id="iE5K2Le" width="12.76" height="8.553" x="17.128" y="9.54" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3152" stdDeviation=".85"/></filter><linearGradient id="iYCKcvb" x1="20.393" x2="8.571" y1="17.241" y2="21.196" gradientUnits="userSpaceOnUse"><stop class="i39kpus4t"/><stop offset="1" class="xjdfi3bun"/></linearGradient><linearGradient id="iD3n5vb" x1="19.828" x2="31.13" y1="12.402" y2="16.093" gradientUnits="userSpaceOnUse"><stop class="wph0opaub"/><stop offset="1" class="cvo9a4s4m"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-fist-medium" /></template>
<style>
.a4i9-qnlz {
  stop-color: var(--svg-color--9c6d6d, #9C6D6D);
}

.aya7a3bqt {
  stop-color: var(--svg-color--8c5467, #8C5467);
}

.c-iffccrk {
  stop-color: var(--svg-color--8d5566, #8D5566);
  stop-opacity: 0;
}

.can-iz3yi {
  stop-color: var(--svg-color--9d716a, #9D716A);
  stop-opacity: 0;
}

.cu9gv7ced {
  stop-color: var(--svg-color--c39c87, #C39C87);
}

.cvo9a4s4m {
  stop-color: var(--svg-color--c79e8a, #C79E8A);
  stop-opacity: 0;
}

.d846hcb-i {
  stop-color: var(--svg-color--7b533f, #7B533F);
}

.d8rgnmblk {
  stop-color: var(--svg-color--9b5a88, #9B5A88);
  stop-opacity: 0;
}

.dtnee9b6l {
  stop-color: var(--svg-color--987360, #987360);
}

.e16m8h_rf {
  stop-color: var(--svg-color--9b5a88, #9B5A88);
}

.e599lnq0o {
  d: path("M14.78 5.675c0-1.847 1.498-3.166 3.345-3.166a3.345 3.345 0 0 1 3.346 3.346v6.192a3.345 3.345 0 0 1-6.69 0z");
}

.eo24s8bon {
  stop-color: var(--svg-color--cda58c, #CDA58C);
}

.ft5dv1b6b {
  fill: none;
}

.fy483t18j {
  fill: var(--svg-color--5a3139, #5A3139);
  d: path("M15.024 14.283c-.504.868-1.422 1.472-2.47 1.472c-.93 0-1.757-.314-2.283-.987a2.882 2.882 0 0 1-5.06-1.886v-2.704a2.882 2.882 0 0 1 4.61-2.306c.383-1.244 1.462-1.81 2.733-1.81c.936 0 1.768.447 2.294 1.138c.26-1.272 1.408-2.135 2.785-2.135a2.84 2.84 0 0 1 2.674 1.884a2.882 2.882 0 0 1 5.556 1.074v4.335a2.882 2.882 0 0 1-5.44 1.327a2.84 2.84 0 0 1-5.4.598");
}

.gpm8n5jae {
  stop-color: var(--svg-color--b69080, #B69080);
}

.h49cr7b_r {
  stop-color: var(--svg-color--8c5467, #8C5467);
  stop-opacity: 0;
}

.hiyftsb_l {
  stop-color: var(--svg-color--bb9678, #BB9678);
}

.i39kpus4t {
  stop-color: var(--svg-color--6c4143, #6C4143);
}

.igu-flb-x {
  stop-color: var(--svg-color--836150, #836150);
}

.k0zn1ebow {
  d: path("M18.339 9.797c-1.965 0-3.559 1.507-3.559 3.365s1.594 3.365 3.559 3.365h2.602c1.168 0 2.115.896 2.115 2v2.998h.2c3.464 0 5.254-3.02 5.254-5.765c0-3.293-2.823-5.963-6.306-5.963z");
}

.kgq1yxb-w {
  width: 12.678px;
  height: 6.195px;
  x: 10.28px;
  y: 12.903px;
  rx: 3.097px;
}

.l3172sb8e {
  stop-color: var(--svg-color--987361, #987361);
}

.m1-n9eimp {
  stop-color: var(--svg-color--9d795c, #9D795C);
}

.n97z1_bjk {
  stop-color: var(--svg-color--886654, #886654);
}

.nq9o5_b-r {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.828 12.25h2.14c3.187-.131 4.706 1.01 5.22 3.143");
}

.oz9fqcisu {
  d: path("M8.747 7.08c0-2.35 1.52-3.396 3.395-3.396a3.395 3.395 0 0 1 3.395 3.395v4.509c0 1.875-1.52 3.516-3.395 3.516s-3.395-1.085-3.395-3.516z");
}

.pf7p_5brz {
  stop-color: var(--svg-color--a0756b, #A0756B);
}

.q1lla5xtl {
  stop-color: var(--svg-color--917766, #917766);
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

.q3y1vh5-t {
  stop-color: var(--svg-color--664936, #664936);
}

.qauqg0hpg {
  stop-color: var(--svg-color--9d795c, #9D795C);
  stop-opacity: 0;
}

.qbskpd8ec {
  stop-color: var(--svg-color--935772, #935772);
  stop-opacity: 0;
}

.s28y23brv {
  stop-color: var(--svg-color--775945, #775945);
  stop-opacity: 0;
}

.shce70u_a {
  stop-color: var(--svg-color--a27074, #A27074);
}

.si-y-4bpl {
  stop-color: var(--svg-color--946866, #946866);
  stop-opacity: 0;
}

.sso-z9b1d {
  stop-color: var(--svg-color--946866, #946866);
}

.sxt9otg6x {
  stop-color: var(--svg-color--8d5566, #8D5566);
}

.tcvr7tulc {
  width: 6.79px;
  height: 11.898px;
  x: 21.033px;
  y: 2.599px;
  rx: 3.395px;
}

.u6sqbo62y {
  stop-color: var(--svg-color--664936, #664936);
  stop-opacity: 0;
}

.uyxopq3zq {
  stop-color: var(--svg-color--775945, #775945);
}

.wph0opaub {
  stop-color: var(--svg-color--c79e8a, #C79E8A);
}

.xjdfi3bun {
  stop-color: var(--svg-color--6c4143, #6C4143);
  stop-opacity: 0;
}

.yjrrwwncj {
  stop-color: var(--svg-color--9c6d6d, #9C6D6D);
  stop-opacity: 0;
}

.yo1dcgyuf {
  stop-color: var(--svg-color--935772, #935772);
}

.yqrsv_hxq {
  width: 6.79px;
  height: 9.976px;
  x: 3.49px;
  y: 5.138px;
  rx: 3.395px;
}

.ytt_t5bbb {
  stop-color: var(--svg-color--9d716a, #9D716A);
}

.z5gkcf-av {
  d: path("M27.823 9.479H3.49v9.328c0 6.351 5.149 11.5 11.5 11.5h1.333c2.153 0 4.168-.592 5.89-1.621l.005.018c2.518-1.454 5.089-4.099 5.904-7.358c.83-3.325.134-5.707-.3-6.552z");
}

.zi46wu1tm {
  stop-color: var(--svg-color--886654, #886654);
  stop-opacity: 0;
}

.zvybr_bcw {
  stop-color: var(--svg-color--917766, #917766);
  stop-opacity: 0;
}

.zzi2hb-yn {
  stop-color: var(--svg-color--926862, #926862);
}

</style>
