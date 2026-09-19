<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iA3Unlb)" class="qxyngabmv"/><path fill="url(#iiptT4b)" class="qxyngabmv"/><path fill="url(#ieZMO7O)" class="qxyngabmv"/><path fill="url(#ieHbjde)" class="qxyngabmv"/><path fill="url(#i4bn3Zb)" class="qxyngabmv"/><path fill="url(#ivaLIDc)" class="n9g6kr-ch"/><path fill="url(#ieOMBGb)" class="n9g6kr-ch"/><path class="y_fgymhdt"/><path fill="url(#iXwpVRr)" class="vx9z_7bmj"/><path fill="url(#iDnNE6n)" class="vx9z_7bmj"/><path class="jqxu3k7sg"/><path fill="url(#iXe6sdd)" class="zn6gjcd9f"/><path fill="url(#iObV3ob)" class="zn6gjcd9f"/><path fill="url(#iL7Y3Ud)" class="zn6gjcd9f"/><path fill="url(#is0H3Kd)" class="zn6gjcd9f"/><path fill="url(#iKxIUVb)" class="ewmfvg05j"/><path fill="url(#iJOmD4b)" class="ewmfvg05j"/><path fill="url(#ia3g2Rb)" class="ewmfvg05j"/><path fill="url(#iTQZfYf)" class="ewmfvg05j"/><path fill="url(#ihizuNe)" class="nghsumber"/><path fill="url(#i4gLbPe)" class="ef9op30th"/><path fill="url(#iM11Goc)" class="ef9op30th"/><path fill="url(#imZIPwm)" class="s5_jsmynw"/><defs><radialGradient id="iA3Unlb" cx="0" cy="0" r="1" gradientTransform="rotate(137.712 12.267 10.073)scale(28.5867 28.5479)" gradientUnits="userSpaceOnUse"><stop class="xhcvfwb5p"/><stop offset="1" class="ibdaaw5ql"/></radialGradient><radialGradient id="iiptT4b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.85638 4.10835 -4.10989 -3.85782 29.176 7.59)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="aisypzlte"/><stop offset="1" class="qiuln5bhg"/></radialGradient><radialGradient id="ieZMO7O" cx="0" cy="0" r="1" gradientTransform="matrix(1.11958 7.4795 -23.02429 3.44643 12.134 30.115)" gradientUnits="userSpaceOnUse"><stop class="c72mj05wp"/><stop offset="1" class="c0r-86_-p"/></radialGradient><radialGradient id="ieHbjde" cx="0" cy="0" r="1" gradientTransform="matrix(11.3194 10.17955 -10.17841 11.31813 4.083 6.603)" gradientUnits="userSpaceOnUse"><stop class="mn-63tw_u"/><stop offset="1" class="mx0ly4blc"/></radialGradient><radialGradient id="i4bn3Zb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.60755 -1.83631 15.79091 -31.02219 26.657 11.854)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="ju14yzb2x"/><stop offset=".261" class="ik69p4bdd"/></radialGradient><radialGradient id="ivaLIDc" cx="0" cy="0" r="1" gradientTransform="rotate(137.427 12.202 8.165)scale(29.008 29.0122)" gradientUnits="userSpaceOnUse"><stop class="gw_93kxmw"/><stop offset="1" class="fq1dgjb-s"/></radialGradient><radialGradient id="ieOMBGb" cx="0" cy="0" r="1" gradientTransform="rotate(146.582 12.972 8.003)scale(5.51061 5.52417)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="aisypzlte"/><stop offset="1" class="qiuln5bhg"/></radialGradient><radialGradient id="iXwpVRr" cx="0" cy="0" r="1" gradientTransform="matrix(-21.52085 20.04395 -20.03877 -21.51529 26.715 5.832)" gradientUnits="userSpaceOnUse"><stop class="gw_93kxmw"/><stop offset="1" class="fq1dgjb-s"/></radialGradient><radialGradient id="iDnNE6n" cx="0" cy="0" r="1" gradientTransform="rotate(146.179 12.993 8.02)scale(5.59175 5.59343)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="aisypzlte"/><stop offset="1" class="qiuln5bhg"/></radialGradient><radialGradient id="iXe6sdd" cx="0" cy="0" r="1" gradientTransform="matrix(-21.52085 20.04395 -20.03877 -21.51529 27.159 6.448)" gradientUnits="userSpaceOnUse"><stop class="gw_93kxmw"/><stop offset="1" class="fq1dgjb-s"/></radialGradient><radialGradient id="iObV3ob" cx="0" cy="0" r="1" gradientTransform="rotate(146.179 13.12 8.395)scale(5.59175 5.59343)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="aisypzlte"/><stop offset="1" class="qiuln5bhg"/></radialGradient><radialGradient id="iL7Y3Ud" cx="0" cy="0" r="1" gradientTransform="rotate(82.953 -11.077 21.426)scale(6.08403 24.5574)" gradientUnits="userSpaceOnUse"><stop class="c72mj05wp"/><stop offset="1" class="c0r-86_-p"/></radialGradient><radialGradient id="is0H3Kd" cx="0" cy="0" r="1" gradientTransform="matrix(18.28636 -19.60834 19.77604 18.44274 10.89 27.387)" gradientUnits="userSpaceOnUse"><stop class="zn8t_5bki"/><stop offset=".735" class="y75-wg5zk"/><stop offset="1" class="cw208tbkw"/></radialGradient><radialGradient id="iKxIUVb" cx="0" cy="0" r="1" gradientTransform="matrix(-21.52085 20.04395 -20.03877 -21.51529 26.875 5.973)" gradientUnits="userSpaceOnUse"><stop class="gw_93kxmw"/><stop offset="1" class="fq1dgjb-s"/></radialGradient><radialGradient id="iJOmD4b" cx="0" cy="0" r="1" gradientTransform="rotate(146.179 13.051 8.115)scale(5.59175 5.59343)" gradientUnits="userSpaceOnUse"><stop offset=".26" class="aisypzlte"/><stop offset="1" class="qiuln5bhg"/></radialGradient><radialGradient id="ia3g2Rb" cx="0" cy="0" r="1" gradientTransform="rotate(82.953 -10.95 21.029)scale(6.08403 24.5574)" gradientUnits="userSpaceOnUse"><stop class="c72mj05wp"/><stop offset="1" class="c0r-86_-p"/></radialGradient><radialGradient id="iTQZfYf" cx="0" cy="0" r="1" gradientTransform="matrix(10.32506 9.27498 -9.27285 10.32268 4.732 6.97)" gradientUnits="userSpaceOnUse"><stop class="mn-63tw_u"/><stop offset="1" class="mx0ly4blc"/></radialGradient><radialGradient id="ihizuNe" cx="0" cy="0" r="1" gradientTransform="rotate(62.166 1.463 30.564)scale(12.389 26.4855)" gradientUnits="userSpaceOnUse"><stop class="ep2klqc6i"/><stop offset=".518" class="iu3dv_zbj"/><stop offset="1" class="mujc4sb8s"/></radialGradient><radialGradient id="i4gLbPe" cx="0" cy="0" r="1" gradientTransform="matrix(5.59792 7.65652 -22.45008 16.41395 12.818 8.96)" gradientUnits="userSpaceOnUse"><stop offset=".358" class="qtb9w48ih"/><stop offset=".391" class="zp7cywbea"/></radialGradient><radialGradient id="iM11Goc" cx="0" cy="0" r="1" gradientTransform="rotate(31.504 -28.798 14.44)scale(9.41075 17.0398)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="cqqwizb7b"/><stop offset=".765" class="plg2u-29l"/></radialGradient><radialGradient id="imZIPwm" cx="0" cy="0" r="1" gradientTransform="matrix(-20.02804 15.31314 -27.55338 -36.03703 24.636 5.599)" gradientUnits="userSpaceOnUse"><stop offset=".13" class="e086xjopr"/><stop offset=".533" class="cdqpeubnt"/><stop offset="1" class="ctu288unr"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rugby-football" /></template>
<style>
.aisypzlte {
  stop-color: var(--svg-color--ff935f, #FF935F);
}

.c0r-86_-p {
  stop-color: var(--svg-color--ff4d85, #FF4D85);
  stop-opacity: 0;
}

.c72mj05wp {
  stop-color: var(--svg-color--ff4d85, #FF4D85);
}

.cdqpeubnt {
  stop-color: var(--svg-color--ffb85c, #FFB85C);
}

.cqqwizb7b {
  stop-color: var(--svg-color--fd9740, #FD9740);
}

.ctu288unr {
  stop-color: var(--svg-color--fb9258, #FB9258);
}

.cw208tbkw {
  stop-color: var(--svg-color--ff621d, #FF621D);
}

.e086xjopr {
  stop-color: var(--svg-color--ffe366, #FFE366);
}

.ef9op30th {
  d: path("m2.078 17.735l.002-.013C2.866 11.03 8.275 6.082 12.178 3.92c3.123-1.73 6.555-2.008 7.371-1.846c-1.275.421-1.01.358-4.525 1.939C8.377 7 5.539 11.878 3.856 15.31c-.469.954-1.373 2.91-1.776 4.373c-.189-.358-.05-1.532-.002-1.948");
}

.ep2klqc6i {
  stop-color: var(--svg-color--fd6, #FD6);
}

.ewmfvg05j {
  d: path("M22.288 2.814c2.942-.292 4.64.46 5.38 1.245c.792.841.897 2.306.56 3.75c-1.894 8.107-9.968 16.046-17.245 19.345c-2.433 1.103-5.284 1.85-6.996.544c-1-.762-1.286-3.772-1.165-5.026c1.025-10.656 9.59-18.877 19.466-19.858");
}

.fq1dgjb-s {
  stop-color: var(--svg-color--ef4f38, #EF4F38);
}

.ft5dv1b6b {
  fill: none;
}

.gw_93kxmw {
  stop-color: var(--svg-color--ff8043, #FF8043);
}

.ibdaaw5ql {
  stop-color: var(--svg-color--eb503a, #EB503A);
}

.ik69p4bdd {
  stop-color: var(--svg-color--ff8f5c, #FF8F5C);
  stop-opacity: 0;
}

.iu3dv_zbj {
  stop-color: var(--svg-color--ffbf6c, #FFBF6C);
}

.jqxu3k7sg {
  fill: var(--svg-color--e33c36, #E33C36);
  d: path("M22.023 2.983c2.942-.292 4.746.148 5.486.933c.791.842.896 2.306.56 3.75c-1.894 8.107-9.968 16.046-17.245 19.345c-2.433 1.103-5.285 1.851-6.996.545c-1-.763-1.286-3.773-1.165-5.027c1.03-10.71 9.485-18.565 19.36-19.546");
}

.ju14yzb2x {
  stop-color: var(--svg-color--ff9060, #FF9060);
}

.mn-63tw_u {
  stop-color: var(--svg-color--fe6333, #FE6333);
}

.mujc4sb8s {
  stop-color: var(--svg-color--ff8679, #FF8679);
}

.mx0ly4blc {
  stop-color: var(--svg-color--fe6333, #FE6333);
  stop-opacity: 0;
}

.n9g6kr-ch {
  d: path("M22.21 2.657c2.892-.31 4.58.595 5.3 1.379c.771.84.86 2.29.515 3.715c-1.94 8.002-9.958 15.78-17.149 18.974c-2.403 1.068-5.216 1.78-6.886.472c-.976-.764-.93-3.942-.798-5.182c1.11-10.531 9.16-18.3 19.018-19.358");
}

.nghsumber {
  d: path("M28.645 12.806c.54-.419.918-.514 1.229-.36c.55.275-.234 3.736-.84 5.26l-.017.044c-.908 2.283-2.878 7.24-9.966 10.804c-1.377.693-6.326 2.137-6.617 1.323c-.314-.88.893-1.813 1.407-2.203c2.01-1.53 5.213-3.602 7.465-5.797c1.686-1.643 4.219-5.016 5.318-6.676c.42-.601 1.411-1.923 2.021-2.395");
}

.plg2u-29l {
  stop-color: var(--svg-color--fd9740, #FD9740);
  stop-opacity: 0;
}

.qiuln5bhg {
  stop-color: var(--svg-color--ff935f, #FF935F);
  stop-opacity: 0;
}

.qtb9w48ih {
  stop-color: var(--svg-color--ffbe54, #FFBE54);
}

.qxyngabmv {
  d: path("M29.672 7.513c-.412-2.024-1.555-3.076-1.928-3.253c-.498-.664-2.704-2.708-7.898-2.21c-8.37.801-17.727 10.77-17.883 19.048c-.087 4.579 1.896 6.412 1.896 6.412S5.166 29.595 8.774 30c12.324 1.382 23.449-9.96 20.898-22.487");
}

.s5_jsmynw {
  d: path("M22.974 5.647c3.17 2.608 3.623 6.707-3.784 14.185c-6.232 6.292-10.61 6.36-13.243 3.663s-.682-9.245 3.917-13.74s10.41-6.328 13.11-4.107");
}

.vx9z_7bmj {
  d: path("M22.023 2.983c2.942-.292 4.746.148 5.486.933c.791.842.896 2.306.56 3.75c-1.894 8.107-9.968 16.046-17.245 19.345c-2.433 1.103-5.285 1.851-6.996.545c-1-.763-1.286-3.773-1.165-5.027c1.03-10.71 9.485-18.565 19.36-19.546");
}

.xhcvfwb5p {
  stop-color: var(--svg-color--ff7f45, #FF7F45);
}

.y_fgymhdt {
  fill: var(--svg-color--ff8658, #FF8658);
  d: path("M22.21 2.657c2.892-.31 4.58.595 5.3 1.379c.771.84.86 2.29.515 3.715c-1.94 8.002-9.958 15.78-17.149 18.974c-2.403 1.068-5.216 1.78-6.886.472c-.976-.764-.93-3.942-.798-5.182c1.11-10.531 9.16-18.3 19.018-19.358");
}

.y75-wg5zk {
  stop-color: var(--svg-color--ff4b05, #FF4B05);
}

.zn6gjcd9f {
  d: path("M22.572 3.289c2.942-.292 4.641.46 5.38 1.245c.792.841.842 2.15.478 3.587c-2.022 7.968-9.706 15.773-17.136 19.141c-2.432 1.103-5.13 1.96-6.841.654c-1-.763-1.468-3.515-1.347-4.77C4.132 12.491 12.696 4.27 22.572 3.29");
}

.zn8t_5bki {
  stop-color: var(--svg-color--f93315, #F93315);
}

.zp7cywbea {
  stop-color: var(--svg-color--f89e41, #F89E41);
}

</style>
