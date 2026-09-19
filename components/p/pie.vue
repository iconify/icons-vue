<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#ieOmDgc)" class="arkh2ebzy"/><path class="l_iaeyblr"/><path fill="url(#iqk7Dwc)" class="h8p6sfbng"/><path fill="url(#ikPth8b)" class="h8p6sfbng"/><g filter="url(#ivDf72k)"><path fill="url(#iOX7D6J)" class="gn6vjhb5d"/><path fill="url(#iihdiHe)" class="gn6vjhb5d"/></g><path class="tvqdcacjt"/><path fill="url(#iNv867b)" class="uhwj2yuxe"/><path fill="url(#i9uGHMs)" class="uhwj2yuxe"/><path fill="url(#in8YlZd)" class="uhwj2yuxe"/><path fill="url(#iJk3B1d)" class="uhwj2yuxe"/><path stroke="url(#iikKlbd)" class="x6dl5zb1p"/><path stroke="url(#ihmngbd)" class="r51r64vue"/><path stroke="url(#icloFEX)" class="yir50orch"/><path stroke="url(#iCwcnGy)" class="e9qohac6d"/><g filter="url(#iUmhHFd)"><path stroke="url(#ibyX5Kb)" class="eyvewvb0w"/></g><defs><radialGradient id="ieOmDgc" cx="0" cy="0" r="1" gradientTransform="rotate(90 -1.65 17.56)scale(10.14)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="adtfrjbfh"/><stop offset="1" class="asog1mi3x"/></radialGradient><radialGradient id="iqk7Dwc" cx="0" cy="0" r="1" gradientTransform="rotate(38.219 5.757 27.403)scale(19.7289 5.35389)" gradientUnits="userSpaceOnUse"><stop offset=".593" class="yf1rnh11n"/><stop offset="1" class="a58idw3dc"/></radialGradient><radialGradient id="ikPth8b" cx="0" cy="0" r="1" gradientTransform="matrix(-15.62495 14.8125 -6.42472 -6.77711 12.875 3.313)" gradientUnits="userSpaceOnUse"><stop offset=".3" class="yhvnhmbji"/><stop offset=".712" class="hyek05myj"/></radialGradient><radialGradient id="iihdiHe" cx="0" cy="0" r="1" gradientTransform="matrix(18.8125 -12.1875 12.61437 19.47142 4.938 20.813)" gradientUnits="userSpaceOnUse"><stop class="a-otn_bqm"/><stop offset="1" class="rvx5r7byt"/></radialGradient><radialGradient id="iNv867b" cx="0" cy="0" r="1" gradientTransform="rotate(124.37 7.203 11.03)scale(14.6139)" gradientUnits="userSpaceOnUse"><stop class="lmlg9_bci"/><stop offset=".894" class="safgxbczs"/></radialGradient><radialGradient id="i9uGHMs" cx="0" cy="0" r="1" gradientTransform="matrix(38.8126 17.37472 -21.33388 47.65677 18.312 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".142" class="bgesy6_2v"/><stop offset=".206" class="r4j91egeh"/><stop offset=".34" class="ejclmxblz"/></radialGradient><radialGradient id="in8YlZd" cx="0" cy="0" r="1" gradientTransform="rotate(-52.921 31.087 2.546)scale(20.5251)" gradientUnits="userSpaceOnUse"><stop offset=".058" class="fu4f3fo2v"/><stop offset=".354" class="igvb7abvj"/><stop offset="1" class="ah7zxi69y"/></radialGradient><radialGradient id="iJk3B1d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.375 9 -9 -3.375 21.5 10.625)" gradientUnits="userSpaceOnUse"><stop class="i3xmdnbqt"/><stop offset="1" class="zurl8sfru"/></radialGradient><radialGradient id="ibyX5Kb" cx="0" cy="0" r="1" gradientTransform="rotate(110.583 7.884 17.993)scale(15.2885 7.45531)" gradientUnits="userSpaceOnUse"><stop offset=".176" class="ii7vfwygc"/><stop offset=".429" class="fjpwn_rrp"/><stop offset=".738" class="yx_kbynkj"/><stop offset="1" class="btnyw0bgb"/></radialGradient><linearGradient id="iOX7D6J" x1="16" x2="16" y1="26.226" y2="2.726" gradientUnits="userSpaceOnUse"><stop offset=".006" class="ct_p4b9sh"/><stop offset=".198" class="b2466db0t"/><stop offset=".496" class="h7p_dybsq"/><stop offset=".795" class="new88gb5o"/><stop offset="1" class="kdmjl1yoc"/></linearGradient><linearGradient id="iikKlbd" x1="10.52" x2="14.3" y1="8.978" y2="11.708" gradientUnits="userSpaceOnUse"><stop class="qwi1zyk_h"/><stop offset="1" class="h-ltbybcc"/></linearGradient><linearGradient id="ihmngbd" x1="17.52" x2="21.75" y1="12.063" y2="8.978" gradientUnits="userSpaceOnUse"><stop class="u9n51db0o"/><stop offset="1" class="tyl0wcccz"/></linearGradient><linearGradient id="icloFEX" x1="17.52" x2="21.3" y1="14.978" y2="17.708" gradientUnits="userSpaceOnUse"><stop class="o076tybgn"/><stop offset="1" class="ix76lqgym"/></linearGradient><linearGradient id="iCwcnGy" x1="10.52" x2="14.3" y1="17.708" y2="14.978" gradientUnits="userSpaceOnUse"><stop class="k7l8nlbep"/><stop offset="1" class="jf2bj8m1f"/></linearGradient><filter id="ivDf72k" width="25.785" height="25.13" x="2.871" y="1.715" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29374" stdDeviation=".25"/></filter><filter id="iUmhHFd" width="9.552" height="15.175" x="19.594" y="11.729" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29374" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pie" /></template>
<style>
.a-otn_bqm {
  stop-color: var(--svg-color--cf8255, #CF8255);
}

.a58idw3dc {
  stop-color: var(--svg-color--ffd690, #FFD690);
  stop-opacity: 0;
}

.adtfrjbfh {
  stop-color: var(--svg-color--8962a9, #8962A9);
}

.ah7zxi69y {
  stop-color: var(--svg-color--f28d6f, #F28D6F);
  stop-opacity: 0;
}

.arkh2ebzy {
  d: path("M15.91 29.348c5.6 0 10.14-4.54 10.14-10.14s-4.54-10.14-10.14-10.14s-10.14 4.54-10.14 10.14s4.54 10.14 10.14 10.14");
}

.asog1mi3x {
  stop-color: var(--svg-color--694b82, #694B82);
}

.b2466db0t {
  stop-color: var(--svg-color--f59e60, #F59E60);
}

.bgesy6_2v {
  stop-color: var(--svg-color--f9c377, #F9C377);
  stop-opacity: 0;
}

.btnyw0bgb {
  stop-color: var(--svg-color--f1996a, #F1996A);
  stop-opacity: 0;
}

.ct_p4b9sh {
  stop-color: var(--svg-color--f79d62, #F79D62);
}

.e9qohac6d {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("m14.3 14.978l-3.78 2.73");
}

.ejclmxblz {
  stop-color: var(--svg-color--ac834b, #AC834B);
}

.eyvewvb0w {
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M27.719 12.375c.406.563 1.403 2.181-.219 4.438c-1.553 2.16-.427 3.288-1.25 4.562s-2.594 1.438-3.625 2.25s-1.375 1.969-2.406 2.563");
}

.fjpwn_rrp {
  stop-color: var(--svg-color--ffbe82, #FFBE82);
  stop-opacity: 0.42;
}

.ft5dv1b6b {
  fill: none;
}

.fu4f3fo2v {
  stop-color: var(--svg-color--eb8775, #EB8775);
}

.gn6vjhb5d {
  d: path("M17.309 2.484c2.093-.79 3.444.274 4.391 1.72c.498.76 1.248 1.496 2.121 1.73a3.68 3.68 0 0 1 2.712 3.736a3.7 3.7 0 0 0 .807 2.497a3.674 3.674 0 0 1 0 4.618a3.7 3.7 0 0 0-.807 2.496a3.68 3.68 0 0 1-2.712 3.736a3.7 3.7 0 0 0-2.12 1.54a3.68 3.68 0 0 1-4.392 1.426a3.7 3.7 0 0 0-2.618 0c-1.614.62-3.493.525-4.441-.92c-.497-.76-1.44-1.453-2.312-1.688c-1.67-.45-2.835-1.554-2.75-3.281c.046-.901-.437-2.609-1-3.313c-1.089-1.351-1.089-2.96 0-4.312c.563-.714 1.046-1.898 1-2.799c-.1-1.906.657-3.376 2.328-3.826c.872-.235 1.877-.698 2.375-1.45c1.332-2.011 3.186-2.53 4.8-1.91a3.7 3.7 0 0 0 2.618 0");
}

.h-ltbybcc {
  stop-color: var(--svg-color--e28f4c, #E28F4C);
}

.h7p_dybsq {
  stop-color: var(--svg-color--f7a15e, #F7A15E);
}

.h8p6sfbng {
  d: path("M17.35 2.258c1.72-.66 3.67-.02 4.68 1.52c.53.81 1.33 1.39 2.26 1.64c1.78.48 2.98 2.14 2.89 3.98c-.05.96.26 1.91.86 2.66a3.91 3.91 0 0 1 0 4.92c-.6.75-.91 1.69-.86 2.66c.09 1.84-1.11 3.5-2.89 3.98c-.93.25-1.73.84-2.26 1.64a3.925 3.925 0 0 1-4.68 1.52c-.9-.34-1.89-.34-2.79 0c-1.72.66-3.67.02-4.68-1.52a3.9 3.9 0 0 0-2.26-1.64a3.92 3.92 0 0 1-2.89-3.98c.05-.96-.26-1.91-.86-2.66a3.91 3.91 0 0 1 0-4.92c.6-.76.91-1.7.86-2.66a3.92 3.92 0 0 1 2.89-3.98a3.95 3.95 0 0 0 2.26-1.64a3.925 3.925 0 0 1 4.68-1.52c.9.34 1.89.34 2.79 0");
}

.hyek05myj {
  stop-color: var(--svg-color--ba8e50, #BA8E50);
  stop-opacity: 0;
}

.i3xmdnbqt {
  stop-color: var(--svg-color--ffe195, #FFE195);
}

.igvb7abvj {
  stop-color: var(--svg-color--fa9473, #FA9473);
}

.ii7vfwygc {
  stop-color: var(--svg-color--ffbe82, #FFBE82);
}

.ix76lqgym {
  stop-color: var(--svg-color--ec8840, #EC8840);
}

.jf2bj8m1f {
  stop-color: var(--svg-color--e38b50, #E38B50);
}

.k7l8nlbep {
  stop-color: var(--svg-color--c46a38, #C46A38);
}

.kdmjl1yoc {
  stop-color: var(--svg-color--f7cc80, #F7CC80);
}

.l_iaeyblr {
  fill: var(--svg-color--e78d60, #E78D60);
  d: path("M17.35 2.258c1.72-.66 3.67-.02 4.68 1.52c.53.81 1.33 1.39 2.26 1.64c1.78.48 2.98 2.14 2.89 3.98c-.05.96.26 1.91.86 2.66a3.91 3.91 0 0 1 0 4.92c-.6.75-.91 1.69-.86 2.66c.09 1.84-1.11 3.5-2.89 3.98c-.93.25-1.73.84-2.26 1.64a3.925 3.925 0 0 1-4.68 1.52c-.9-.34-1.89-.34-2.79 0c-1.72.66-3.67.02-4.68-1.52a3.9 3.9 0 0 0-2.26-1.64a3.92 3.92 0 0 1-2.89-3.98c.05-.96-.26-1.91-.86-2.66a3.91 3.91 0 0 1 0-4.92c.6-.76.91-1.7.86-2.66a3.92 3.92 0 0 1 2.89-3.98a3.95 3.95 0 0 0 2.26-1.64a3.925 3.925 0 0 1 4.68-1.52c.9.34 1.89.34 2.79 0");
}

.lmlg9_bci {
  stop-color: var(--svg-color--ffe198, #FFE198);
}

.new88gb5o {
  stop-color: var(--svg-color--f5ba73, #F5BA73);
}

.o076tybgn {
  stop-color: var(--svg-color--f19655, #F19655);
}

.qwi1zyk_h {
  stop-color: var(--svg-color--b8702f, #B8702F);
}

.r4j91egeh {
  stop-color: var(--svg-color--f0bf72, #F0BF72);
}

.r51r64vue {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("m17.52 11.708l3.78-2.73");
}

.rvx5r7byt {
  stop-color: var(--svg-color--dca15d, #DCA15D);
  stop-opacity: 0;
}

.safgxbczs {
  stop-color: var(--svg-color--ffe19a, #FFE19A);
  stop-opacity: 0;
}

.tvqdcacjt {
  fill: var(--svg-color--ffb663, #FFB663);
  d: path("M15.91 25.348c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11");
}

.tyl0wcccz {
  stop-color: var(--svg-color--f0933a, #F0933A);
}

.u9n51db0o {
  stop-color: var(--svg-color--f0994f, #F0994F);
}

.uhwj2yuxe {
  d: path("M15.91 25.348c6.075 0 11-4.925 11-11s-4.925-11-11-11s-11 4.925-11 11s4.925 11 11 11");
}

.x6dl5zb1p {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("m14.3 11.708l-3.78-2.73");
}

.yf1rnh11n {
  stop-color: var(--svg-color--ffd690, #FFD690);
}

.yhvnhmbji {
  stop-color: var(--svg-color--c19f65, #C19F65);
}

.yir50orch {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-miterlimit: 10;
  d: path("m21.3 17.708l-3.78-2.73");
}

.yx_kbynkj {
  stop-color: var(--svg-color--fca56c, #FCA56C);
}

.zurl8sfru {
  stop-color: var(--svg-color--ffcc80, #FFCC80);
  stop-opacity: 0;
}

</style>
