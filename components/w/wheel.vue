<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="sz-22zbdk"/><path fill="url(#iYLVpdc)" class="mw5shzbui"/><path class="err6j8qep"/><path fill="url(#is2aYRb)" class="qro_g4beo"/><path class="vrzyb8bqx"/><path fill="url(#iGDTaie)" class="egy4d-bay"/><path class="l3ade03jg"/><path fill="url(#iV7OBRb)" class="ptpur5mzf"/><path class="mew4r_bou"/><path fill="url(#isMQXYd)" class="py_8dqsjl"/><path class="b_duywbmp"/><path fill="url(#i6VRdmc)" class="wurvu2bvj"/><path class="yaxkjybfy"/><path fill="url(#iq1hIGb)" class="u8l8c3b3g"/><path class="i03273buq"/><path fill="url(#imRpu4d)" class="lz-9jibpl"/><path class="yncc1pzup"/><path fill="url(#isj8SAb)" class="bgwvz-bvk"/><path class="kb7dcfitx"/><path fill="url(#iqALwle)" class="unu4x3bdi"/><path fill="url(#itUHZfb)" class="rfj7q-bvp"/><path fill="url(#iCQQ9Me)" class="rfj7q-bvp"/><path fill="url(#iYwCWMj)" class="rfj7q-bvp"/><path fill="url(#i94RUDw)" class="l8ndfvlxp"/><path fill="url(#ixMS7ey)" class="l8ndfvlxp"/><path fill="url(#i7U1abe)" class="l8ndfvlxp"/><path fill="url(#ibg1Gde)" class="l8ndfvlxp"/><path fill="url(#ixZCwYc)" class="l8ndfvlxp"/><path fill="url(#iAVm4XB)" class="q9bg_wb4r"/><path class="e_h4tyfuo"/><path fill="url(#iKiCmzD)" class="mv1jlib5b"/><path fill="url(#ibvmNyc)" class="mv1jlib5b"/><path fill="url(#i5r6XgC)" class="ghder5trp"/><path fill="url(#ieVsyZU)" class="lfy5bl0xi"/><defs><radialGradient id="iYLVpdc" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75 -1.17537 0 16.219 11.469)" gradientUnits="userSpaceOnUse"><stop class="ij9bgo8-q"/><stop offset=".343" class="lq30g6bfs"/><stop offset=".65" class="vvgytacol"/><stop offset="1" class="m5goz4bqh"/></radialGradient><radialGradient id="is2aYRb" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.75 -1.17537 0 16.219 23.858)" gradientUnits="userSpaceOnUse"><stop class="ij9bgo8-q"/><stop offset=".343" class="lq30g6bfs"/><stop offset=".65" class="vvgytacol"/><stop offset="1" class="m5goz4bqh"/></radialGradient><radialGradient id="iGDTaie" cx="0" cy="0" r="1" gradientTransform="matrix(5.1875 7.417 -1.05911 .74075 12.75 10.927)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="c1e0nw8-h"/><stop offset=".353" class="lq30g6bfs"/><stop offset=".65" class="vvgytacol"/><stop offset="1" class="m5goz4bqh"/></radialGradient><radialGradient id="iV7OBRb" cx="0" cy="0" r="1" gradientTransform="matrix(4.27751 6.22757 -.93124 .63964 19.813 21.094)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="ij9bgo8-q"/><stop offset=".378" class="lq30g6bfs"/><stop offset=".702" class="vvgytacol"/><stop offset="1" class="m5goz4bqh"/></radialGradient><radialGradient id="isMQXYd" cx="0" cy="0" r="1" gradientTransform="matrix(9.62498 3.43749 -.38979 1.0914 8.5 12.969)" gradientUnits="userSpaceOnUse"><stop offset=".05" class="c1e0nw8-h"/><stop offset=".353" class="lq30g6bfs"/><stop offset=".65" class="vvgytacol"/><stop offset="1" class="m5goz4bqh"/></radialGradient><radialGradient id="i6VRdmc" cx="0" cy="0" r="1" gradientTransform="rotate(-159.652 12.618 7.042)scale(10.0656 1.22956)" gradientUnits="userSpaceOnUse"><stop class="ij9bgo8-q"/><stop offset=".268" class="lq30g6bfs"/><stop offset=".507" class="b-p7as4xu"/><stop offset="1" class="m5goz4bqh"/></radialGradient><radialGradient id="iq1hIGb" cx="0" cy="0" r="1" gradientTransform="matrix(10.43754 -2.5625 .24043 .9793 5.188 18.719)" gradientUnits="userSpaceOnUse"><stop class="lq30g6bfs"/><stop offset=".65" class="cy9neq3yz"/><stop offset="1" class="mv0yn6bnz"/></radialGradient><radialGradient id="imRpu4d" cx="0" cy="0" r="1" gradientTransform="matrix(-9.1875 2.68748 -.39094 -1.33649 21.188 14.594)" gradientUnits="userSpaceOnUse"><stop class="ij9bgo8-q"/><stop offset=".268" class="lq30g6bfs"/><stop offset=".662" class="t64h1bcoi"/><stop offset="1" class="m5goz4bqh"/></radialGradient><radialGradient id="isj8SAb" cx="0" cy="0" r="1" gradientTransform="matrix(4.75 -5.625 1.12378 .94897 10.375 23.531)" gradientUnits="userSpaceOnUse"><stop offset=".116" class="lq30g6bfs"/><stop offset=".694" class="cy9neq3yz"/><stop offset="1" class="mv0yn6bnz"/></radialGradient><radialGradient id="iqALwle" cx="0" cy="0" r="1" gradientTransform="matrix(-5.18754 6.06247 -1.43048 -1.22404 19.688 11.656)" gradientUnits="userSpaceOnUse"><stop class="ij9bgo8-q"/><stop offset=".268" class="lq30g6bfs"/><stop offset=".643" class="jsfxnibhc"/><stop offset="1" class="m5goz4bqh"/></radialGradient><radialGradient id="iCQQ9Me" cx="0" cy="0" r="1" gradientTransform="matrix(.25001 14.52965 -14.52795 .24998 16.25 16.002)" gradientUnits="userSpaceOnUse"><stop offset=".686" class="fni09-zpx"/><stop offset=".781" class="z_dx3-b3x"/><stop offset=".933" class="ohbgz4bua"/><stop offset="1" class="n0nwenbpt"/></radialGradient><radialGradient id="iYwCWMj" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.0016 -14 0 16 16)" gradientUnits="userSpaceOnUse"><stop offset=".81" class="hml-15u7r"/><stop offset=".832" class="bz-g--b9p"/></radialGradient><radialGradient id="ixMS7ey" cx="0" cy="0" r="1" gradientTransform="matrix(3.1875 5 -5 3.1875 9.125 8.656)" gradientUnits="userSpaceOnUse"><stop class="xydhhsb0b"/><stop offset="1" class="iimo5s42s"/></radialGradient><radialGradient id="i7U1abe" cx="0" cy="0" r="1" gradientTransform="rotate(-125.34 18.005 6.95)scale(4.214 4.21401)" gradientUnits="userSpaceOnUse"><stop class="xydhhsb0b"/><stop offset="1" class="iimo5s42s"/></radialGradient><radialGradient id="ibg1Gde" cx="0" cy="0" r="1" gradientTransform="matrix(-.8125 7.75 -7.75 -.8125 21.5 8.656)" gradientUnits="userSpaceOnUse"><stop class="xydhhsb0b"/><stop offset="1" class="iimo5s42s"/></radialGradient><radialGradient id="ixZCwYc" cx="0" cy="0" r="1" gradientTransform="rotate(90 0 16.002)scale(11.2673)" gradientUnits="userSpaceOnUse"><stop/><stop offset=".973" class="gjfth9sav"/><stop offset="1" class="vjd-xbbpz"/></radialGradient><radialGradient id="iKiCmzD" cx="0" cy="0" r="1" gradientTransform="matrix(1.5625 1.875 -2.37562 1.97969 14.875 17.031)" gradientUnits="userSpaceOnUse"><stop class="owln6zo6r"/><stop offset="1" class="r57r68-_l"/></radialGradient><radialGradient id="ibvmNyc" cx="0" cy="0" r="1" gradientTransform="rotate(90 0 16.002)scale(3.25136)" gradientUnits="userSpaceOnUse"><stop offset=".49" class="zoq-wvb0z"/><stop offset=".547" class="zpghwpbrt"/></radialGradient><linearGradient id="itUHZfb" x1="5.688" x2="25.25" y1="29.469" y2="5.156" gradientUnits="userSpaceOnUse"><stop class="js473-bui"/><stop offset=".871" class="dicnqub6r"/></linearGradient><linearGradient id="i94RUDw" x1="23.375" x2="8.188" y1="7.594" y2="24.281" gradientUnits="userSpaceOnUse"><stop class="x2lnxlz-x"/><stop offset=".589" class="ttj5-3bvi"/></linearGradient><linearGradient id="iAVm4XB" x1="18.625" x2="13.938" y1="13.656" y2="18.281" gradientUnits="userSpaceOnUse"><stop class="szh-qeb6h"/><stop offset=".757" class="ap4wmh3-t"/></linearGradient><linearGradient id="i5r6XgC" x1="17.125" x2="14.428" y1="14.781" y2="17.031" gradientUnits="userSpaceOnUse"><stop class="isw_c3b-k"/><stop offset=".263" class="jmqq59fxl"/><stop offset="1" class="gr3btmb2h"/></linearGradient><linearGradient id="ieVsyZU" x1="17.25" x2="15.625" y1="15.406" y2="16.781" gradientUnits="userSpaceOnUse"><stop class="kfshr1pwf"/><stop offset="1" class="c-n8pmnch"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wheel" /></template>
<style>
.ap4wmh3-t {
  stop-color: var(--svg-color--7d484f, #7D484F);
}

.b_duywbmp {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M27.375 20.736a.7.7 0 0 1-.209-.035L16.12 16.678a.605.605 0 1 1 .414-1.138l11.05 4.023a.605.605 0 0 1-.21 1.173");
}

.b-p7as4xu {
  stop-color: var(--svg-color--f2916d, #F2916D);
}

.bgwvz-bvk {
  d: path("M8.27 25.855a.605.605 0 0 1-.462-.994l7.559-9.007a.605.605 0 1 1 .926.778L8.732 25.64a.6.6 0 0 1-.462.215");
}

.bz-g--b9p {
  stop-color: var(--svg-color--854748, #854748);
  stop-opacity: 0;
}

.c-n8pmnch {
  stop-color: var(--svg-color--d5947e, #D5947E);
}

.c1e0nw8-h {
  stop-color: var(--svg-color--ffebab, #FFEBAB);
}

.cy9neq3yz {
  stop-color: var(--svg-color--d0966b, #D0966B);
}

.dicnqub6r {
  stop-color: var(--svg-color--d69584, #D69584);
}

.e_h4tyfuo {
  fill: var(--svg-color--b97c6f, #B97C6F);
  d: path("M16.002 19.253a3.251 3.251 0 1 0 0-6.503a3.251 3.251 0 0 0 0 6.503");
}

.egy4d-bay {
  d: path("M15.848 16.348a.6.6 0 0 1-.497-.26L8.61 6.458a.606.606 0 0 1 .99-.695l6.745 9.633a.606.606 0 0 1-.497.952");
}

.err6j8qep {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M16.03 28.68a.607.607 0 0 1-.605-.606V16.316a.607.607 0 0 1 1.211 0v11.758a.605.605 0 0 1-.606.605");
}

.fni09-zpx {
  stop-color: var(--svg-color--7b473b, #7B473B);
}

.ft5dv1b6b {
  fill: none;
}

.ghder5trp {
  d: path("M16.002 17.576a1.574 1.574 0 1 0 0-3.148a1.574 1.574 0 0 0 0 3.148");
}

.gjfth9sav {
  stop-color: var(--svg-color--2f0e23, #2F0E23);
  stop-opacity: 0;
}

.gr3btmb2h {
  stop-color: var(--svg-color--c28472, #C28472);
}

.hml-15u7r {
  stop-color: var(--svg-color--834646, #834646);
}

.i03273buq {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M16.335 16.524a.605.605 0 0 1-.154-1.19l11.354-3.045a.604.604 0 1 1 .31 1.17L16.49 16.501a.5.5 0 0 1-.154.023");
}

.iimo5s42s {
  stop-color: var(--svg-color--8f6660, #8F6660);
  stop-opacity: 0;
}

.ij9bgo8-q {
  stop-color: var(--svg-color--ffdfa1, #FFDFA1);
}

.isw_c3b-k {
  stop-color: var(--svg-color--f5b59b, #F5B59B);
}

.jmqq59fxl {
  stop-color: var(--svg-color--da9680, #DA9680);
}

.js473-bui {
  stop-color: var(--svg-color--8f5c5b, #8F5C5B);
}

.jsfxnibhc {
  stop-color: var(--svg-color--ba715c, #BA715C);
}

.kb7dcfitx {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M16.232 16.363a.605.605 0 0 1-.462-.994l7.56-9.007a.605.605 0 1 1 .926.78l-7.559 9.007a.6.6 0 0 1-.465.214");
}

.kfshr1pwf {
  stop-color: var(--svg-color--dd9881, #DD9881);
}

.l3ade03jg {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M22.955 26.496a.6.6 0 0 1-.497-.26l-6.741-9.629a.606.606 0 0 1 .99-.695l6.744 9.632a.606.606 0 0 1-.497.952");
}

.l8ndfvlxp {
  d: path("M16.002 5.738a10.24 10.24 0 0 1 9.456 6.266a10.2 10.2 0 0 1 .805 3.995a10.24 10.24 0 0 1-6.267 9.456c-1.266.535-2.61.804-3.994.804s-2.731-.272-3.994-.804a10.2 10.2 0 0 1-3.264-2.2A10.23 10.23 0 0 1 5.741 16a10.23 10.23 0 0 1 3.004-7.257a10.23 10.23 0 0 1 7.257-3.004m0-1.004C9.78 4.734 4.734 9.78 4.734 16.002S9.78 27.269 16.002 27.269s11.267-5.045 11.267-11.267C27.266 9.78 22.224 4.734 16.002 4.734");
}

.lfy5bl0xi {
  d: path("M16.002 17.25a1.248 1.248 0 1 0 0-2.497a1.248 1.248 0 0 0 0 2.497");
}

.lq30g6bfs {
  stop-color: var(--svg-color--ffcb94, #FFCB94);
}

.lz-9jibpl {
  d: path("M16.335 16.524a.605.605 0 0 1-.154-1.19l11.354-3.045a.604.604 0 1 1 .31 1.17L16.49 16.501a.5.5 0 0 1-.154.023");
}

.m5goz4bqh {
  stop-color: var(--svg-color--f0a25e, #F0A25E);
  stop-opacity: 0;
}

.mew4r_bou {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M15.732 16.499a.7.7 0 0 1-.208-.035L4.478 12.44a.605.605 0 1 1 .413-1.138l11.05 4.022a.605.605 0 0 1-.209 1.174");
}

.mv0yn6bnz {
  stop-color: var(--svg-color--b76c3e, #B76C3E);
}

.mv1jlib5b {
  d: path("M16.002 19.253a3.251 3.251 0 1 0 0-6.503a3.251 3.251 0 0 0 0 6.503");
}

.mw5shzbui {
  d: path("M16.03 16.29a.607.607 0 0 1-.605-.606V3.926c0-.333.272-.606.605-.606c.334 0 .606.273.606.606v11.758a.605.605 0 0 1-.606.606");
}

.n0nwenbpt {
  stop-color: var(--svg-color--7a544c, #7A544C);
}

.ohbgz4bua {
  stop-color: var(--svg-color--693e63, #693E63);
  stop-opacity: 0;
}

.owln6zo6r {
  stop-color: var(--svg-color--5b2a26, #5B2A26);
}

.ptpur5mzf {
  d: path("M22.955 26.496a.6.6 0 0 1-.497-.26l-6.741-9.629a.606.606 0 0 1 .99-.695l6.744 9.632a.606.606 0 0 1-.497.952");
}

.py_8dqsjl {
  d: path("M15.732 16.499a.7.7 0 0 1-.208-.035L4.478 12.44a.605.605 0 1 1 .413-1.138l11.05 4.022a.605.605 0 0 1-.209 1.174");
}

.q9bg_wb4r {
  d: path("M16.002 19.377a3.375 3.375 0 1 0 0-6.751a3.375 3.375 0 0 0 0 6.75");
}

.qro_g4beo {
  d: path("M16.03 28.68a.607.607 0 0 1-.605-.606V16.316a.607.607 0 0 1 1.211 0v11.758a.605.605 0 0 1-.606.605");
}

.r57r68-_l {
  stop-color: var(--svg-color--623330, #623330);
  stop-opacity: 0;
}

.rfj7q-bvp {
  d: path("M16.002 2C8.27 2 2 8.27 2 16.002c0 7.731 6.27 14.001 14.002 14.001c7.731 0 13.998-6.27 13.998-14.001C30 8.27 23.733 2 16.002 2m0 25.266c-6.222 0-11.268-5.046-11.268-11.268c0-6.221 5.046-11.267 11.268-11.267s11.267 5.046 11.267 11.267c-.003 6.226-5.045 11.268-11.267 11.268");
}

.sz-22zbdk {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M16.03 16.29a.607.607 0 0 1-.605-.606V3.926c0-.333.272-.606.605-.606c.334 0 .606.273.606.606v11.758a.605.605 0 0 1-.606.606");
}

.szh-qeb6h {
  stop-color: var(--svg-color--cf998b, #CF998B);
}

.t64h1bcoi {
  stop-color: var(--svg-color--e58b68, #E58B68);
}

.ttj5-3bvi {
  stop-color: var(--svg-color--805d56, #805D56);
}

.u8l8c3b3g {
  d: path("M4.366 19.733a.605.605 0 0 1-.154-1.19l11.357-3.042a.604.604 0 1 1 .31 1.17L4.524 19.71a.5.5 0 0 1-.157.023");
}

.unu4x3bdi {
  d: path("M16.232 16.363a.605.605 0 0 1-.462-.994l7.56-9.007a.605.605 0 1 1 .926.78l-7.559 9.007a.6.6 0 0 1-.465.214");
}

.vjd-xbbpz {
  stop-color: var(--svg-color--371029, #371029);
}

.vrzyb8bqx {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M15.848 16.348a.6.6 0 0 1-.497-.26L8.61 6.458a.606.606 0 0 1 .99-.695l6.745 9.633a.606.606 0 0 1-.497.952");
}

.vvgytacol {
  stop-color: var(--svg-color--f0a25e, #F0A25E);
}

.wurvu2bvj {
  d: path("M27.375 20.736a.7.7 0 0 1-.209-.035L16.12 16.678a.605.605 0 1 1 .414-1.138l11.05 4.023a.605.605 0 0 1-.21 1.173");
}

.x2lnxlz-x {
  stop-color: var(--svg-color--603c3e, #603C3E);
}

.xydhhsb0b {
  stop-color: var(--svg-color--916861, #916861);
}

.yaxkjybfy {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M4.366 19.733a.605.605 0 0 1-.154-1.19l11.357-3.042a.604.604 0 1 1 .31 1.17L4.524 19.71a.5.5 0 0 1-.157.023");
}

.yncc1pzup {
  fill: var(--svg-color--b4714e, #B4714E);
  d: path("M8.27 25.855a.605.605 0 0 1-.462-.994l7.559-9.007a.605.605 0 1 1 .926.778L8.732 25.64a.6.6 0 0 1-.462.215");
}

.z_dx3-b3x {
  stop-color: var(--svg-color--73434c, #73434C);
  stop-opacity: 0;
}

.zoq-wvb0z {
  stop-color: var(--svg-color--6b3032, #6B3032);
}

.zpghwpbrt {
  stop-color: var(--svg-color--843b4a, #843B4A);
  stop-opacity: 0;
}

</style>
