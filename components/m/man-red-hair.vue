<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#igTC0tb)" class="c3vm8kt4c"/><g filter="url(#iwyg9Yd)"><circle fill="url(#iQUlG6c)" class="n73l6to2h"/></g><g filter="url(#iq18dGc)"><circle fill="url(#iTt8vEc)" class="jvwpinbbf"/><circle fill="url(#iw62rKa)" class="jvwpinbbf"/></g><g filter="url(#ifN0Jme)"><circle class="hesy95r-g"/><circle fill="url(#iynzOrb)" class="xq483lxba"/><circle fill="url(#i8VnHYO)" class="xq483lxba"/></g><g filter="url(#iDITfLc)"><path fill="url(#iNe4Rke)" class="bhop8fbem"/><path fill="url(#i6nMRed)" class="bhop8fbem"/><path fill="url(#iY5ZJSd)" class="bhop8fbem"/><path fill="url(#i7F6Z3b)" class="bhop8fbem"/><path fill="url(#itJ5Z3k)" class="bhop8fbem"/><path fill="url(#iE7NDSc)" class="bhop8fbem"/><path fill="url(#iTLCeJv)" class="bhop8fbem"/></g><g filter="url(#iyL0GDe)"><path fill="url(#iikl6sd)" class="ynsl3-bvt"/><path fill="url(#iq28ndc)" class="ynsl3-bvt"/><path fill="url(#iaLExbc)" class="ynsl3-bvt"/><path fill="url(#iZXjRPb)" class="ynsl3-bvt"/><path fill="url(#iHC9ARb)" class="ynsl3-bvt"/><path fill="url(#i42KZxc)" class="ynsl3-bvt"/></g><path fill="url(#iFldDEc)" class="ynsl3-bvt"/><path fill="url(#i0riIbb)" class="ynsl3-bvt"/><path fill="url(#iBJdSec)" class="ynsl3-bvt"/><g filter="url(#i6VflIV)"><path class="abkzm39fd"/></g><g filter="url(#ifnTH7b)"><path class="p2zchrbfq"/><path fill="url(#iYnoQDb)" class="bdg888bzf"/><path fill="url(#iKQaUzH)" class="bdg888bzf"/><path fill="url(#iu9NsHd)" class="bdg888bzf"/></g><path fill="url(#ib9yrwb)" class="bdg888bzf"/><path stroke="url(#ixo9UPd)" class="sum2zwpft"/><g filter="url(#ibvw6bd)"><path class="b8xw-pban"/></g><g filter="url(#iu5bBQP)"><path class="bmrvapbje"/></g><path class="pdv4ldbpr"/><path fill="url(#i0o1nfc)" class="ysuyqjbga"/><path class="heacg5ncs"/><g filter="url(#iDIrMFf)"><path class="z98s40bed"/><path fill="url(#iO48bjt)" class="z20bumf_j"/></g><g filter="url(#ian76Vb)"><path fill="url(#ikMrDfd)" class="i_ux49j5u"/></g><path class="l6wzmlbrw"/><path fill="url(#i4phFUc)" class="pymlyd-1i"/><path class="uozffyiai"/><g filter="url(#ilc2j6d)"><path fill="url(#itFLHzb)" class="sow05c3ou"/></g><g filter="url(#iEHYi2b)"><ellipse transform="rotate(-27.914 11.367 16.608)" class="xk1wlybvw"/><ellipse fill="url(#ivdEdNn)" transform="rotate(-27.914 11.367 16.608)" class="bz40dzb6n"/></g><g filter="url(#iP9DKxR)"><path stroke="url(#iXjGS9b)" class="khbuz0hlc"/></g><g filter="url(#iwqz7Gd)"><path stroke="url(#iwy8RVb)" class="ut7qi9bnx"/></g><defs><radialGradient id="igTC0tb" cx="0" cy="0" r="1" gradientTransform="matrix(3.27255 0 0 5.72699 3.979 18.059)" gradientUnits="userSpaceOnUse"><stop offset=".351" class="p8hteacus"/><stop offset="1" class="ez11m_bio"/></radialGradient><radialGradient id="iw62rKa" cx="0" cy="0" r="1" gradientTransform="matrix(1.54168 -1.12256 1.28126 1.75963 25.527 17.564)" gradientUnits="userSpaceOnUse"><stop offset=".543" class="ykvv4rhnl"/><stop offset="1" class="rixtyr4np"/></radialGradient><radialGradient id="iynzOrb" cx="0" cy="0" r="1" gradientTransform="matrix(1.53153 -2.8169 1.64874 .8964 24.756 19.59)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="mrmfxebtr"/><stop offset="1" class="avncbf64d"/></radialGradient><radialGradient id="i8VnHYO" cx="0" cy="0" r="1" gradientTransform="rotate(44.708 -9.54 39.223)scale(.68036 .87707)" gradientUnits="userSpaceOnUse"><stop class="q8bsowbrp"/><stop offset="1" class="p-73vab8n"/></radialGradient><radialGradient id="iNe4Rke" cx="0" cy="0" r="1" gradientTransform="matrix(-12.8125 0 0 -25.0154 24.188 20.375)" gradientUnits="userSpaceOnUse"><stop class="mbmro29rs"/><stop offset="1" class="p-0vkdb7g"/></radialGradient><radialGradient id="iY5ZJSd" cx="0" cy="0" r="1" gradientTransform="matrix(0 16.3495 -27.7163 0 17.216 14.246)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="h2hpuvpsb"/><stop offset=".962" class="kj9y-cisp"/></radialGradient><radialGradient id="i7F6Z3b" cx="0" cy="0" r="1" gradientTransform="matrix(-4.125 0 0 -4.75 19.688 17.688)" gradientUnits="userSpaceOnUse"><stop class="yd0_zxcwu"/><stop offset="1" class="zy88rt23j"/></radialGradient><radialGradient id="itJ5Z3k" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.5 4.06143 0 20.321 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".237" class="yb96e7s0v"/><stop offset="1" class="khfsvmb7n"/></radialGradient><radialGradient id="iE7NDSc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -2.59375 3.22556 0 11.821 15.625)" gradientUnits="userSpaceOnUse"><stop class="pyc1d3hnt"/><stop offset="1" class="na6rt0ild"/></radialGradient><radialGradient id="iTLCeJv" cx="0" cy="0" r="1" gradientTransform="matrix(-11.18747 6.4375 -5.55213 -9.64882 26.313 10.25)" gradientUnits="userSpaceOnUse"><stop class="f7lp6gbax"/><stop offset="1" class="fqu1zvbau"/></radialGradient><radialGradient id="iq28ndc" cx="0" cy="0" r="1" gradientTransform="rotate(-169.032 11.112 3.065)scale(8.21251 6.30254)" gradientUnits="userSpaceOnUse"><stop offset=".223" class="tzxi8pb6h"/><stop offset="1" class="hmx8eit6p"/></radialGradient><radialGradient id="iaLExbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56248 -7.49998 14.07497 -1.05559 26.813 17.017)" gradientUnits="userSpaceOnUse"><stop class="gg3p-v-oi"/><stop offset="1" class="go8dnjb_b"/></radialGradient><radialGradient id="iZXjRPb" cx="0" cy="0" r="1" gradientTransform="matrix(3.8125 -.625 1.78488 10.88777 3.813 11.563)" gradientUnits="userSpaceOnUse"><stop class="zk1gozblh"/><stop offset="1" class="o7liw8bnz"/></radialGradient><radialGradient id="iHC9ARb" cx="0" cy="0" r="1" gradientTransform="matrix(1.1875 1.40625 -6.20388 5.23883 7.813 4.813)" gradientUnits="userSpaceOnUse"><stop class="hchmvbcwb"/><stop offset="1" class="ei1bt-b0e"/></radialGradient><radialGradient id="i42KZxc" cx="0" cy="0" r="1" gradientTransform="rotate(80.538 7.776 11.423)scale(1.61573 2.88964)" gradientUnits="userSpaceOnUse"><stop offset=".173" class="e_h6jabwf"/><stop offset="1" class="moyyndcqm"/></radialGradient><radialGradient id="iFldDEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.25 -4.59375 1.72724 -.094 8.219 11.813)" gradientUnits="userSpaceOnUse"><stop offset=".169" class="sn-n94bif"/><stop offset="1" class="vu7vn7bhc"/></radialGradient><radialGradient id="i0riIbb" cx="0" cy="0" r="1" gradientTransform="matrix(-.69638 -4.375 1.72998 -.27536 4.196 11.125)" gradientUnits="userSpaceOnUse"><stop class="sdjph8tjs"/><stop offset="1" class="xhmtc9b9f"/></radialGradient><radialGradient id="iBJdSec" cx="0" cy="0" r="1" gradientTransform="matrix(1.11615 -6 2.3152 .43068 27.696 14.375)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="t7o6ccjes"/><stop offset="1" class="kd9fr-txf"/></radialGradient><radialGradient id="i0o1nfc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68424 -1.9929 0 20.01 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="iO48bjt" cx="0" cy="0" r="1" gradientTransform="rotate(-127.812 13.941 3.676)scale(.70528 .97101)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><radialGradient id="i4phFUc" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.68433 -1.993 0 11.873 17.409)" gradientUnits="userSpaceOnUse"><stop offset=".75" class="v60bq3cin"/><stop offset="1" class="mbk9t98yd"/><stop offset="1" class="qvv2y8bvl"/><stop offset="1" class="gh784hb2c"/></radialGradient><radialGradient id="ivdEdNn" cx="0" cy="0" r="1" gradientTransform="rotate(-90.897 14.134 3.016)scale(.92129 1.10743)" gradientUnits="userSpaceOnUse"><stop offset=".766" class="lhxedz0io"/><stop offset=".966" class="od4qh9blv"/></radialGradient><filter id="iwyg9Yd" width="4.711" height="4.711" x="4.737" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".25"/></filter><filter id="iq18dGc" width="6.477" height="6.477" x="21.72" y="14.695" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.85098 0 0 0 0 0.560784 0 0 0 0 0.376471 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20014"/></filter><filter id="ifN0Jme" width="4.711" height="4.711" x="22.478" y="15.703" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".25"/></filter><filter id="iDITfLc" width="19.345" height="22.63" x="6.327" y="7.57" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.443137 0 0 0 0 0.0117647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20014"/></filter><filter id="iyL0GDe" width="23.5" height="15.5" x="4.196" y="1.519" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.5"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.701961 0 0 0 0 0.262745 0 0 0 0 0.121569 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20014"/></filter><filter id="i6VflIV" width="4.782" height="6.5" x="13.11" y="16.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".375"/></filter><filter id="ifnTH7b" width="4" height="5.5" x="13.946" y="16.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".125"/></filter><filter id="ibvw6bd" width="5.34" height="3.147" x="18.151" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.282353 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20014"/></filter><filter id="iu5bBQP" width="5.341" height="3.147" x="8.551" y="11.6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy="-.4"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.623529 0 0 0 0 0.282353 0 0 0 0 0.188235 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_3987_20014"/></filter><filter id="iDIrMFf" width="1.294" height="1.125" x="18.727" y="16.053" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".05"/></filter><filter id="ian76Vb" width="1.316" height="1.357" x="20.38" y="16.279" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".1"/></filter><filter id="ilc2j6d" width="1.493" height="1.594" x="12.097" y="16.161" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".1"/></filter><filter id="iEHYi2b" width="1.529" height="1.141" x="10.603" y="16.038" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".05"/></filter><filter id="iP9DKxR" width="4.949" height="2.304" x="18.293" y="11.905" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".25"/></filter><filter id="iwqz7Gd" width="5.094" height="2.41" x="8.56" y="12.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_3987_20014" stdDeviation=".25"/></filter><linearGradient id="iQUlG6c" x1="7.092" x2="5.898" y1="18.578" y2="18.578" gradientUnits="userSpaceOnUse"><stop class="k94wnob3w"/><stop offset="1" class="pxzrjgb8y"/></linearGradient><linearGradient id="iTt8vEc" x1="26.859" x2="25.332" y1="16.023" y2="20.753" gradientUnits="userSpaceOnUse"><stop class="s5fwd11en"/><stop offset="1" class="tsum8q2zl"/></linearGradient><linearGradient id="i6nMRed" x1="6.327" x2="9.469" y1="23.406" y2="23" gradientUnits="userSpaceOnUse"><stop offset=".232" class="gmlznsb6t"/><stop offset="1" class="qo089imcw"/></linearGradient><linearGradient id="iikl6sd" x1="6.875" x2="28.817" y1="11.365" y2="11.365" gradientUnits="userSpaceOnUse"><stop class="othda_4vm"/><stop offset=".349" class="g7i6ig2lc"/><stop offset="1" class="q1uq6hbwz"/></linearGradient><linearGradient id="iYnoQDb" x1="14.335" x2="16.084" y1="20.014" y2="20.014" gradientUnits="userSpaceOnUse"><stop class="vrar8hnmh"/><stop offset="1" class="ry_l2ebgl"/></linearGradient><linearGradient id="iKQaUzH" x1="17.696" x2="15.784" y1="20.616" y2="20.588" gradientUnits="userSpaceOnUse"><stop class="hmiraywql"/><stop offset="1" class="l99c_58cs"/></linearGradient><linearGradient id="iu9NsHd" x1="16.309" x2="16.309" y1="22" y2="20.931" gradientUnits="userSpaceOnUse"><stop class="wno2x162j"/><stop offset="1" class="hog28xbdu"/></linearGradient><linearGradient id="ib9yrwb" x1="16.181" x2="16.181" y1="22.078" y2="21.766" gradientUnits="userSpaceOnUse"><stop class="hi_3gxb3d"/><stop offset="1" class="uco9ljbwd"/></linearGradient><linearGradient id="ixo9UPd" x1="14.622" x2="15.415" y1="25.131" y2="23.568" gradientUnits="userSpaceOnUse"><stop class="q0k9-hbaq"/><stop offset="1" class="mhbvyzb9x"/></linearGradient><linearGradient id="ikMrDfd" x1="21.46" x2="20.875" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="itFLHzb" x1="13.26" x2="12.675" y1="16.887" y2="17.248" gradientUnits="userSpaceOnUse"><stop class="pkjdwtbdo"/><stop offset="1" class="ckw4b5bec"/></linearGradient><linearGradient id="iXjGS9b" x1="21.489" x2="20.706" y1="12.897" y2="11.296" gradientUnits="userSpaceOnUse"><stop class="qset0sb2e"/><stop offset="1" class="kzba7_bcd"/></linearGradient><linearGradient id="iwy8RVb" x1="11.597" x2="9.379" y1="12.659" y2="11.729" gradientUnits="userSpaceOnUse"><stop class="qset0sb2e"/><stop offset="1" class="kzba7_bcd"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:man-red-hair" /></template>
<style>
.abkzm39fd {
  fill: var(--svg-color--f1901c, #F1901C);
  d: path("M15.433 17.83L13.903 21c-.19.652.266 1.304.91 1.304h1.375c.645 0 1.1-.662.91-1.304l-.929-3.17c-.199-.701-.527-.701-.736 0");
}

.avncbf64d {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
}

.b8xw-pban {
  fill: var(--svg-color--c35230, #C35230);
  d: path("m22.883 12.986l-.002-.002l-.004-.002l-.008-.007l-.023-.018l-.067-.05a4 4 0 0 0-.221-.15a5 5 0 0 0-.783-.394a5.3 5.3 0 0 0-2.784-.295a.995.995 0 1 0 .31 1.967a3.3 3.3 0 0 1 1.742.18a2.8 2.8 0 0 1 .56.297l.015.011a.995.995 0 0 0 1.265-1.537");
}

.bdg888bzf {
  d: path("m15.234 17.527l-.991 3.17a1.005 1.005 0 0 0 .97 1.303h1.466c.688 0 1.173-.662.971-1.304l-.99-3.17c-.213-.701-1.204-.701-1.427 0");
}

.bhop8fbem {
  d: path("M6.327 14.234c0-.498.2-1.094.6-1.393l.3-.298c.5-.398.7-.995.7-1.591V9.36c0-.497.301-.895.801-.994c1.2-.299 3.701-.796 7.302-.796s6.102.497 7.302.796c.4.099.8.497.8.994v1.592c0 .596.3 1.193.7 1.59c.937.657.879 1.018.801 1.791c-.1.995-.2 2.685-.2 2.685h.034L24.97 24.4c-.3 3.3-2.894 5.6-5.987 5.6h-5.987c-3.193 0-5.687-2.3-5.987-5.6c-.26-3.387-.373-6.785-.683-10.166");
}

.bmrvapbje {
  fill: var(--svg-color--c35230, #C35230);
  d: path("m8.91 12.987l.002-.002l.004-.002l.008-.007l.022-.018l.067-.05q.083-.061.222-.15c.186-.117.45-.262.783-.394a5.3 5.3 0 0 1 2.784-.295a.995.995 0 1 1-.31 1.967a3.3 3.3 0 0 0-1.742.18a3 3 0 0 0-.56.297l-.015.011a.995.995 0 0 1-1.266-1.536");
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

.ckw4b5bec {
  stop-color: var(--svg-color--b4948d, #B4948D);
  stop-opacity: 0;
}

.e_h6jabwf {
  stop-color: var(--svg-color--bd765f, #BD765F);
}

.ei1bt-b0e {
  stop-color: var(--svg-color--af725f, #AF725F);
  stop-opacity: 0;
}

.ez11m_bio {
  stop-color: var(--svg-color--ca8f29, #CA8F29);
}

.f7lp6gbax {
  stop-color: var(--svg-color--ffeb45, #FFEB45);
}

.fqu1zvbau {
  stop-color: var(--svg-color--ffeb45, #FFEB45);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g7i6ig2lc {
  stop-color: var(--svg-color--da6432, #DA6432);
}

.gg3p-v-oi {
  stop-color: var(--svg-color--d56a42, #D56A42);
}

.gh784hb2c {
  stop-color: var(--svg-color--85534d, #85534D);
}

.gmlznsb6t {
  stop-color: var(--svg-color--d1a153, #D1A153);
}

.go8dnjb_b {
  stop-color: var(--svg-color--d56a42, #D56A42);
  stop-opacity: 0;
}

.h2hpuvpsb {
  stop-color: var(--svg-color--f2963b, #F2963B);
  stop-opacity: 0;
}

.hchmvbcwb {
  stop-color: var(--svg-color--af725f, #AF725F);
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

.hmx8eit6p {
  stop-color: var(--svg-color--f78d61, #F78D61);
  stop-opacity: 0;
}

.hog28xbdu {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
  stop-opacity: 0;
}

.i_ux49j5u {
  d: path("M21.496 17.342a1.57 1.57 0 0 0-.432-.862l-.484.531l.218.426z");
}

.jvwpinbbf {
  cx: 24.833px;
  cy: 18.059px;
  r: 3.113px;
}

.k94wnob3w {
  stop-color: var(--svg-color--bd6a1e, #BD6A1E);
}

.kd9fr-txf {
  stop-color: var(--svg-color--d57852, #D57852);
  stop-opacity: 0;
}

.khbuz0hlc {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M19.043 12.717c.802-.14 2.366-.1 3.449.742");
}

.khfsvmb7n {
  stop-color: var(--svg-color--ffb825, #FFB825);
  stop-opacity: 0;
}

.kj9y-cisp {
  stop-color: var(--svg-color--d87970, #D87970);
}

.kzba7_bcd {
  stop-color: var(--svg-color--ce725e, #CE725E);
  stop-opacity: 0;
}

.l6wzmlbrw {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.484 15.39c-1.218 0-2.247.84-2.526 1.975a.51.51 0 0 0 .499.635h4.16a.43.43 0 0 0 .423-.507a2.61 2.61 0 0 0-2.556-2.102");
}

.l99c_58cs {
  stop-color: var(--svg-color--ffe721, #FFE721);
  stop-opacity: 0;
}

.lhxedz0io {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
  stop-opacity: 0;
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

.moyyndcqm {
  stop-color: var(--svg-color--bd765f, #BD765F);
  stop-opacity: 0;
}

.mrmfxebtr {
  stop-color: var(--svg-color--f4a51a, #F4A51A);
  stop-opacity: 0;
}

.n73l6to2h {
  cx: 7.092px;
  cy: 18.059px;
  r: 1.855px;
}

.na6rt0ild {
  stop-color: var(--svg-color--ef9323, #EF9323);
  stop-opacity: 0;
}

.o7liw8bnz {
  stop-color: var(--svg-color--ba7260, #BA7260);
  stop-opacity: 0;
}

.od4qh9blv {
  stop-color: var(--svg-color--ffe6e2, #FFE6E2);
}

.othda_4vm {
  stop-color: var(--svg-color--c95e3b, #C95E3B);
}

.p-0vkdb7g {
  stop-color: var(--svg-color--f19e2a, #F19E2A);
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

.pyc1d3hnt {
  stop-color: var(--svg-color--ef9323, #EF9323);
}

.pymlyd-1i {
  d: path("M11.87 15.897A1.664 1.664 0 0 0 10.266 18h3.214c.038-.144.061-.287.061-.439a1.675 1.675 0 0 0-1.671-1.664");
}

.q0k9-hbaq {
  stop-color: var(--svg-color--feac35, #FEAC35);
}

.q1uq6hbwz {
  stop-color: var(--svg-color--ea8455, #EA8455);
}

.q8bsowbrp {
  stop-color: var(--svg-color--e59b1f, #E59B1F);
}

.qo089imcw {
  stop-color: var(--svg-color--d1a153, #D1A153);
  stop-opacity: 0;
}

.qset0sb2e {
  stop-color: var(--svg-color--ce725e, #CE725E);
}

.qvv2y8bvl {
  stop-color: var(--svg-color--804d49, #804D49);
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

.sdjph8tjs {
  stop-color: var(--svg-color--b97362, #B97362);
}

.sn-n94bif {
  stop-color: var(--svg-color--de6f4f, #DE6F4F);
}

.sow05c3ou {
  d: path("M13.39 17.366c0-.538-.438-.896-.556-1.005l-.537.52l.33.674z");
}

.sum2zwpft {
  fill: var(--svg-color--8a004f, #8A004F);
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M13.386 23.239a.335.335 0 0 0-.4.069a.305.305 0 0 0-.033.393a3.58 3.58 0 0 0 2.993 1.599a3.58 3.58 0 0 0 2.994-1.6a.31.31 0 0 0-.034-.396a.34.34 0 0 0-.4-.066a5.5 5.5 0 0 1-2.56.607c-.938 0-1.82-.22-2.56-.606Z");
}

.t7o6ccjes {
  stop-color: var(--svg-color--d57852, #D57852);
}

.tsum8q2zl {
  stop-color: var(--svg-color--ffc339, #FFC339);
}

.tzxi8pb6h {
  stop-color: var(--svg-color--f78d61, #F78D61);
}

.uco9ljbwd {
  stop-color: var(--svg-color--e88613, #E88613);
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

.vrar8hnmh {
  stop-color: var(--svg-color--faa416, #FAA416);
}

.vu7vn7bhc {
  stop-color: var(--svg-color--de6f4f, #DE6F4F);
  stop-opacity: 0;
}

.wno2x162j {
  stop-color: var(--svg-color--eb8a1c, #EB8A1C);
}

.xhmtc9b9f {
  stop-color: var(--svg-color--b97362, #B97362);
  stop-opacity: 0;
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

.yb96e7s0v {
  stop-color: var(--svg-color--e9a820, #E9A820);
}

.yd0_zxcwu {
  stop-color: var(--svg-color--ffed47, #FFED47);
}

.ykvv4rhnl {
  stop-color: var(--svg-color--ffc532, #FFC532);
}

.ynsl3-bvt {
  d: path("m24.933 5.979l.8.397c1.4.697 2.2 2.288 1.9 3.979l-1.1 5.669c-.098.585-.485.98-1.066.994h-.034s.1-1.69.2-2.685c.081-.808-.06-1.054-.8-1.79c-.4-.398-.7-.995-.7-1.591V9.36c0-.497-.4-.895-.8-.994c-1.201-.299-3.702-.796-7.303-.796s-6.102.497-7.302.796c-.5.099-.8.497-.8.994v1.592c0 .596-.2 1.193-.7 1.59l-.3.3c-.4.298-.6.894-.6 1.392c.1 1.094.2 2.685.2 2.685l-.092-.003a1.18 1.18 0 0 1-1.109-.992l-1.1-5.669c-.2-1.591.6-3.182 2-3.879l.8-.397c.5-.299 1-.697 1.501-1.095l1.8-1.89c1.1-.994 2.701-1.292 4.102-.596c1.03.513 2.1.298 3.1 0c1.501-.497 3.202-.1 4.402.995l1.5 1.491c.4.498.9.796 1.5 1.095");
}

.ysuyqjbga {
  d: path("M20.013 15.898A1.664 1.664 0 0 1 21.617 18h-3.215a1.7 1.7 0 0 1-.06-.439a1.67 1.67 0 0 1 1.671-1.663");
}

.z20bumf_j {
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.z98s40bed {
  fill: var(--svg-color--c7a7a3, #C7A7A3);
  d: path("M19.891 16.25c.119.158-.13.351-.41.562c-.283.21-.492.358-.61.2c-.119-.159.014-.458.295-.669c.282-.21.607-.252.725-.094");
}

.zk1gozblh {
  stop-color: var(--svg-color--ba7260, #BA7260);
}

.zy88rt23j {
  stop-color: var(--svg-color--ffed47, #FFED47);
  stop-opacity: 0;
}

</style>
