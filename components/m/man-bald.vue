<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#igTC0tb)" class="c3vm8kt4c"/><g filter="url(#i4m2qeb)"><circle fill="url(#iQUlG6c)" class="n73l6to2h"/></g><g filter="url(#il1l2lb)"><circle fill="url(#iTt8vEc)" class="jvwpinbbf"/><circle fill="url(#iw62rKa)" class="jvwpinbbf"/></g><g filter="url(#iPp2jmd)"><circle class="hesy95r-g"/><circle fill="url(#iynzOrb)" class="xq483lxba"/><circle fill="url(#i8VnHYO)" class="xq483lxba"/></g><g filter="url(#iGv75Ic)"><path fill="url(#i0xsRUb)" class="lc4gsmbvx"/><path fill="url(#ie4euPd)" class="lc4gsmbvx"/><path fill="url(#iKTylIt)" class="lc4gsmbvx"/><path fill="url(#iBWxMDb)" class="lc4gsmbvx"/></g><path fill="url(#izQ0TDd)" class="lc4gsmbvx"/><path fill="url(#idV2WVc)" class="lc4gsmbvx"/><g filter="url(#izt4j0d)"><path class="abkzm39fd"/></g><g filter="url(#ita5nxc)"><path class="p2zchrbfq"/><path fill="url(#iYnoQDb)" class="bdg888bzf"/><path fill="url(#iKQaUzH)" class="bdg888bzf"/><path fill="url(#iu9NsHd)" class="bdg888bzf"/></g><path fill="url(#ib9yrwb)" class="bdg888bzf"/><path stroke="url(#ixo9UPd)" class="sum2zwpft"/><g filter="url(#ie2lVNc)"><path class="khd-okbzs"/></g><g filter="url(#iNLOT1d)"><path class="n9e7duxny"/></g><path class="pdv4ldbpr"/><path fill="url(#i0o1nfc)" class="m8cdxvtli"/><path class="heacg5ncs"/><g filter="url(#iLPCqrF)"><path class="vxy28rbkx"/><path fill="url(#iO48bjt)" class="y1c__-95e"/></g><g filter="url(#iKxYl6c)"><path fill="url(#ikMrDfd)" class="i_ux49j5u"/></g><path class="l6wzmlbrw"/><path fill="url(#i4phFUc)" class="pymlyd-1i"/><path class="uozffyiai"/><g filter="url(#ietsRBJ)"><path fill="url(#itFLHzb)" class="sow05c3ou"/></g><g filter="url(#ivF4EQb)"><ellipse transform="rotate(-27.914 11.367 16.608)" class="xk1wlybvw"/><ellipse fill="url(#ivdEdNn)" transform="rotate(-27.914 11.367 16.608)" class="bz40dzb6n"/></g><g filter="url(#inGYaBc)"><path stroke="url(#izv8Yhc)" class="khbuz0hlc"/></g><g filter="url(#iulShsd)"><path stroke="url(#iJlHw4Z)" class="ut7qi9bnx"/></g><defs><radialGradient id="igTC0tb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iw62rKa" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.564)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iynzOrb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="i8VnHYO" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.54 39.223)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="i0xsRUb" cx="0" cy="0" r="1" gradientTransform="matrix(-16.18747 8.8125 -13.4027 -24.61908 23.188 15.438)" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset=".794" class="cinf4eb0k"/><stop offset="1" class="fbh452boa"/></radialGradient><radialGradient id="ie4euPd" cx="0" cy="0" r="1" gradientTransform="matrix(-9.43755 7.37501 -6.8435 -8.7574 23.875 6.938)" gradientUnits="userSpaceOnUse"><stop class="bxzm90wdr"/><stop offset="1" class="vbc1pcc0r"/></radialGradient><radialGradient id="iKTylIt" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.1875 2.45313 0 12.031 15.781)" gradientUnits="userSpaceOnUse"><stop class="j_u87qc-m"/><stop offset="1" class="n1kfg0b8x"/></radialGradient><radialGradient id="iBWxMDb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.9375 2.96875 0 20.406 15.813)" gradientUnits="userSpaceOnUse"><stop class="ht-7f4bgu"/><stop offset="1" class="e7g5x3bay"/></radialGradient><radialGradient id="izQ0TDd" cx="0" cy="0" r="1" gradientTransform="matrix(14.3125 0 0 5.68982 13 30.563)" gradientUnits="userSpaceOnUse"><stop class="e0h1l8b0l"/><stop offset="1" class="d3n1b2bau"/></radialGradient><radialGradient id="idV2WVc" cx="0" cy="0" r="1" gradientTransform="matrix(4.50363 7.7157 -16.41308 9.58028 8.06 2.784)" gradientUnits="userSpaceOnUse"><stop class="fnw5mhojs"/><stop offset="1" class="ipq68ubst"/></radialGradient><radialGradient id="i0o1nfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iO48bjt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.941 3.676)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4phFUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ivdEdNn" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.134 3.016)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="i4m2qeb" width="4.711" height="4.711" x="4.737" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".25"/></filter><filter id="il1l2lb" width="6.477" height="6.477" x="21.72" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19801"/></filter><filter id="iPp2jmd" width="4.711" height="4.711" x="22.478" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".25"/></filter><filter id="iGv75Ic" width="20.719" height="25.719" x="6.266" y="4.441" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1.25" dy=".25"/><feGaussianBlur stdDeviation=".625"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.631373 0 0 0 0 0.301961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19801"/></filter><filter id="izt4j0d" width="4.782" height="6.5" x="13.11" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".375"/></filter><filter id="ita5nxc" width="4" height="5.5" x="13.946" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".125"/></filter><filter id="ie2lVNc" width="5.34" height="3.147" x="18.151" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19801"/></filter><filter id="iNLOT1d" width="5.341" height="3.147" x="8.551" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.615686 0 0 0 0 0.243137 0 0 0 0 0.0901961 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_19801"/></filter><filter id="iLPCqrF" width="1.294" height="1.125" x="18.727" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".05"/></filter><filter id="iKxYl6c" width="1.316" height="1.357" x="20.38" y="16.28" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".1"/></filter><filter id="ietsRBJ" width="1.493" height="1.594" x="12.097" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".1"/></filter><filter id="ivF4EQb" width="1.529" height="1.141" x="10.603" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".05"/></filter><filter id="inGYaBc" width="4.949" height="2.304" x="18.293" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".25"/></filter><filter id="iulShsd" width="5.094" height="2.41" x="8.56" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_19801" stdDeviation=".25"/></filter><linearGradient id="iQUlG6c" x1="7.092" x2="5.898" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iTt8vEc" x1="26.859" x2="25.332" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="iYnoQDb" x1="14.335" x2="16.084" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iKQaUzH" x1="17.696" x2="15.784" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iu9NsHd" x1="16.309" x2="16.309" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="ib9yrwb" x1="16.181" x2="16.181" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="ixo9UPd" x1="14.622" x2="15.415" y1="25.131" y2="23.568" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ikMrDfd" x1="21.46" x2="20.875" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itFLHzb" x1="13.26" x2="12.675" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="izv8Yhc" x1="21.489" x2="20.706" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="rd2dtjb_d"/><stop offset="1" class="ugw3yibbz"/></linearGradient><linearGradient id="iJlHw4Z" x1="11.829" x2="10.231" y1="12.852" y2="11.809" gradientUnits="userSpaceOnUse"><stop offset=".456" class="rd2dtjb_d"/><stop offset="1" class="ugw3yibbz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-bald" /></template>
<style>
.abkzm39fd {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("M15.433 17.83L13.903 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.bdg888bzf {
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.bxzm90wdr {
  stop-color: var(--svg-color--ffea45, #FFEA45);
}

.bz40dzb6n {
  cx: 11.367px;
  cy: 16.608px;
  rx: 0.726px;
  ry: 0.368px;
}

.c3vm8kt4c {
  cx: 7.092px;
  cy: 18.059px;
  r: 3.113px;
}

.cinf4eb0k {
  stop-color: var(--svg-color--f5a726, #F5A726);
}

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.d3n1b2bau {
  stop-color: var(--svg-color--d6765b, #D6765B);
  stop-opacity: 0;
}

.e0h1l8b0l {
  stop-color: var(--svg-color--d6765b, #D6765B);
}

.e7g5x3bay {
  stop-color: var(--svg-color--ffba36, #FFBA36);
  stop-opacity: 0;
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.fbh452boa {
  stop-color: var(--svg-color--e49333, #E49333);
}

.fnw5mhojs {
  stop-color: var(--svg-color--c8a04a, #C8A04A);
}

.ft5dv1b6b {
  fill: none;
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.heacg5ncs {
  fill: var(--svg-color--000, #000);
  d: path("M19.06 17.561c0-.53.424-.953.953-.953c.53 0 .953.424.953.953a.94.94 0 0 1-.106.439h-1.686a.86.86 0 0 1-.113-.439");
}

.hesy95r-g {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
  fill: var(--svg-color--ffbf34, #FFBF34);
}

.hi_3gxb3d {
  stop-color: var(--svg-color--e88613, #E88613);
}

.hmiraywql {
  stop-color: var(--svg-color--ffe721, #FFE721);
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.ht-7f4bgu {
  stop-color: var(--svg-color--ffba36, #FFBA36);
}

.i_ux49j5u {
  d: path("M21.496 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.ipq68ubst {
  stop-color: var(--svg-color--c8a04a, #C8A04A);
  stop-opacity: 0;
}

.j_u87qc-m {
  stop-color: var(--svg-color--ee9230, #EE9230);
}

.jvwpinbbf {
  cx: 24.833px;
  cy: 18.059px;
  r: 3.113px;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.khbuz0hlc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.717c.802-.14 2.366-.1 3.449.742");
}

.khd-okbzs {
  fill: var(--svg-color--c85c2f, #C85C2F);
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.l6wzmlbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lc4gsmbvx {
  d: path("m6.344 15.05l.463 9.231a6 6 0 0 0 5.989 5.63h6.408a6 6 0 0 0 5.988-5.63l.464-9.23c.625-6.547-2.515-10.344-8.78-10.61h-1.751c-6.265.266-9.406 4.063-8.781 10.61");
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
}

.m8cdxvtli {
  d: path("M20.013 15.897A1.664 1.664 0 0 1 21.617 18h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.664");
}

.mbk9t98yd {
  stop-color: var(--svg-color--694b43, #694B43);
}

.mbmro29rs {
  stop-color: var(--svg-color--ffe833, #FFE833);
}

.mhbvyzb9x {
  stop-color: var(--svg-color--feac35, #FEAC35);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n1kfg0b8x {
  stop-color: var(--svg-color--ee9230, #EE9230);
  stop-opacity: 0;
}

.n73l6to2h {
  cx: 7.092px;
  cy: 18.059px;
  r: 1.855px;
}

.n9e7duxny {
  fill: var(--svg-color--c85c2f, #C85C2F);
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.p-73vab8n {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
  stop-opacity: 0;
}

.p2zchrbfq {
  fill: var(--svg-color--ffcc28, #FFCC28);
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.p8hteacus {
  stop-color: var(--svg-color--e6962b, #E6962B);
}

.pdv4ldbpr {
  fill: var(--svg-color--fff, #fff);
  d: path("M20.4 15.39c1.217 0 2.245.84 2.525 1.975a.51.51 0 0 1-.499.635h-4.16a.43.43 0 0 1-.423-.507a2.606 2.606 0 0 1 2.556-2.102");
}

.pkjdwtbdo {
  stop-color: var(--svg-color--b4948d, #B4948D);
}

.pxzrjgb8y {
  stop-color: var(--svg-color--d77a1c, #D77A1C);
}

.pymlyd-1i {
  d: path("M11.87 15.897A1.664 1.664 0 0 0 10.266 18h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
}

.rd2dtjb_d {
  stop-color: var(--svg-color--cf715d, #CF715D);
}

.rixtyr4np {
  stop-color: var(--svg-color--ffc532, #FFC532);
  stop-opacity: 0;
}

.ry_l2ebgl {
  stop-color: var(--svg-color--faa416, #FAA416);
  stop-opacity: 0;
}

.s5fwd11en {
  stop-color: var(--svg-color--ffe446, #FFE446);
}

.sow05c3ou {
  d: path("M13.39 17.366c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.sum2zwpft {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.239a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
  stop-opacity: 0;
}

.ugw3yibbz {
  stop-color: var(--svg-color--cf715d, #CF715D);
  stop-opacity: 0;
}

.uozffyiai {
  fill: var(--svg-color--000, #000);
  d: path("M12.823 17.561a.95.95 0 0 0-.953-.953a.95.95 0 0 0-.953.953c0 .16.037.31.105.439h1.687a.95.95 0 0 0 .114-.439");
}

.ut7qi9bnx {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M9.31 13.684c.61-.54 1.942-1.107 3.593-.844");
}

.v60bq3cin {
  stop-color: var(--svg-color--925c51, #925C51);
}

.vbc1pcc0r {
  stop-color: var(--svg-color--ffea45, #FFEA45);
  stop-opacity: 0;
}

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vxy28rbkx {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.xk1wlybvw {
  cx: 11.367px;
  cy: 16.608px;
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  fill-opacity: var(--svg-fill-opacity--0-9, 0.9);
  rx: 0.726px;
  ry: 0.368px;
}

.xq483lxba {
  cx: 24.833px;
  cy: 18.059px;
  r: 1.855px;
}

.y1c__-95e {
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.359-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

</style>
