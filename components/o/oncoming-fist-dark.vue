<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect transform="rotate(70.668 28.202 17.267)" class="u8dju3b9i"/><rect fill="url(#iIOSCzd)" transform="rotate(70.668 28.202 17.267)" class="qov_v9bvg"/><rect fill="url(#iPhOqmc)" transform="rotate(70.668 28.202 17.267)" class="qov_v9bvg"/><g filter="url(#iClTAye)"><path fill="url(#i8zjk4c)" class="x5bb3s_jf"/></g><path fill="url(#i0I3bmd)" class="x5bb3s_jf"/><path fill="url(#iaiujQc)" class="x5bb3s_jf"/><path fill="url(#iSYdIwe)" class="e08d66buv"/><path fill="url(#iRnrZce)" class="e08d66buv"/><path fill="url(#iyfNrqe)" class="e08d66buv"/><path fill="url(#iU6Xmbb)" class="vi72u84dw"/><path fill="url(#iVZFlQb)" class="vi72u84dw"/><path fill="url(#ixC03Ub)" class="vi72u84dw"/><path fill="url(#i3Z1Dvd)" class="vi72u84dw"/><path fill="url(#iy00Rpe)" class="vi72u84dw"/><rect fill="url(#i16GhPd)" class="nni30rf2x"/><rect fill="url(#izRX60c)" class="nni30rf2x"/><rect fill="url(#iX9kwPd)" class="nni30rf2x"/><rect fill="url(#i6mL8pd)" class="nni30rf2x"/><path fill="url(#i9Gr8Ac)" class="ch-wr6b8u"/><path fill="url(#iNwO8Fc)" class="ch-wr6b8u"/><path fill="url(#i1Ll57D)" class="ch-wr6b8u"/><g filter="url(#iVtGxse)"><path fill="url(#iVC1rdd)" class="ahcbeeqnb"/></g><g filter="url(#idyL51d)"><path fill="url(#iBnXArd)" class="biz8hzbxr"/></g><g filter="url(#iwUDLDd)"><path fill="url(#iiio9CC)" class="zv_6jguez"/></g><g filter="url(#i9HQ5Cd)"><path fill="url(#iuOv3Oe)" class="jfl3vtq7y"/></g><defs><linearGradient id="iIOSCzd" x1="36.127" x2="34.569" y1="24.75" y2="24.795" gradientUnits="userSpaceOnUse"><stop class="lc75s3qjb"/><stop offset="1" class="johgayerk"/></linearGradient><linearGradient id="i8zjk4c" x1="32.991" x2="17.797" y1="7.313" y2="19.415" gradientUnits="userSpaceOnUse"><stop class="x_cmizb4i"/><stop offset="1" class="ipxffnbnj"/></linearGradient><linearGradient id="i0I3bmd" x1="2.008" x2="4.252" y1="16.017" y2="16.017" gradientUnits="userSpaceOnUse"><stop class="p1xawgtbo"/><stop offset="1" class="b-lwpabjo"/></linearGradient><linearGradient id="iSYdIwe" x1="10.131" x2="10.131" y1="24.891" y2="13.968" gradientUnits="userSpaceOnUse"><stop class="h4sla7j9c"/><stop offset="1" class="ln66tyu0f"/></linearGradient><linearGradient id="iRnrZce" x1="8.977" x2="7.652" y1="17.929" y2="17.929" gradientUnits="userSpaceOnUse"><stop class="jmixq9yub"/><stop offset="1" class="fnhtdvm3s"/></linearGradient><linearGradient id="iU6Xmbb" x1="17.209" x2="17.209" y1="25.904" y2="12.191" gradientUnits="userSpaceOnUse"><stop class="h4sla7j9c"/><stop offset="1" class="ln66tyu0f"/></linearGradient><linearGradient id="ixC03Ub" x1="16.014" x2="14.641" y1="17.163" y2="17.163" gradientUnits="userSpaceOnUse"><stop class="jmixq9yub"/><stop offset="1" class="fnhtdvm3s"/></linearGradient><linearGradient id="i3Z1Dvd" x1="14.889" x2="14.889" y1="10.188" y2="13.625" gradientUnits="userSpaceOnUse"><stop class="p7rzgf4vc"/><stop offset="1" class="kis1f5bjl"/></linearGradient><linearGradient id="i16GhPd" x1="14.389" x2="19.406" y1="20.829" y2="20.829" gradientUnits="userSpaceOnUse"><stop class="hitwx9h6v"/><stop offset="1" class="lhib44xat"/></linearGradient><linearGradient id="iX9kwPd" x1="19.406" x2="19.406" y1="7.563" y2="14.454" gradientUnits="userSpaceOnUse"><stop class="wlre5ob-u"/><stop offset="1" class="jnrp2cc9d"/></linearGradient><linearGradient id="i9Gr8Ac" x1="21.877" x2="25.878" y1="21.329" y2="20.772" gradientUnits="userSpaceOnUse"><stop class="sgmt3fb2a"/><stop offset="1" class="c40z1474u"/></linearGradient><linearGradient id="iVC1rdd" x1="6.461" x2="6.461" y1="10.967" y2="26.049" gradientUnits="userSpaceOnUse"><stop class="vzg6eudmh"/><stop offset="1" class="zp_nx8bjr"/></linearGradient><linearGradient id="iBnXArd" x1="13.274" x2="13.274" y1="8.766" y2="26.554" gradientUnits="userSpaceOnUse"><stop class="vzg6eudmh"/><stop offset="1" class="zp_nx8bjr"/></linearGradient><linearGradient id="iiio9CC" x1="20.928" x2="20.928" y1="5.235" y2="28.98" gradientUnits="userSpaceOnUse"><stop class="oi3z-hbab"/><stop offset="1" class="n94_szb-u"/></linearGradient><linearGradient id="iuOv3Oe" x1="27.695" x2="27.695" y1="7.266" y2="28.514" gradientUnits="userSpaceOnUse"><stop class="oi3z-hbab"/><stop offset="1" class="n94_szb-u"/></linearGradient><radialGradient id="iPhOqmc" cx="0" cy="0" r="1" gradientTransform="rotate(-65.982 41.664 -7.47)scale(1.80013 4.07406)" gradientUnits="userSpaceOnUse"><stop class="j9te750_s"/><stop offset="1" class="umi0gzb8q"/></radialGradient><radialGradient id="iaiujQc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.41485 3.40558 -4.95105 -3.51073 29.151 5.984)" gradientUnits="userSpaceOnUse"><stop class="w9oyexe9y"/><stop offset="1" class="uh0yn9b_x"/></radialGradient><radialGradient id="iyfNrqe" cx="0" cy="0" r="1" gradientTransform="matrix(0 14.3638 -10.4214 0 5.941 10.967)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="rq0zkccsi"/><stop offset="1" class="kwxs_ibqc"/></radialGradient><radialGradient id="iVZFlQb" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.0323 -10.7984 0 12.872 8.44)" gradientUnits="userSpaceOnUse"><stop offset=".789" class="r-ag40bgp"/><stop offset="1" class="tt7eg3bmb"/></radialGradient><radialGradient id="iy00Rpe" cx="0" cy="0" r="1" gradientTransform="matrix(-.48591 17.47465 -7.74862 -.21546 12.889 8.594)" gradientUnits="userSpaceOnUse"><stop offset=".952" class="y4_p5tbgk"/><stop offset="1" class="mm-lvachd"/></radialGradient><radialGradient id="izRX60c" cx="0" cy="0" r="1" gradientTransform="matrix(0 19.7805 -10.7947 0 19.898 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="g0r5sc7jj"/><stop offset="1" class="i5c5eto6f"/></radialGradient><radialGradient id="i6mL8pd" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.6391 -8.29832 0 19.406 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".958" class="y4_p5tbgk"/><stop offset="1" class="mm-lvachd"/></radialGradient><radialGradient id="iNwO8Fc" cx="0" cy="0" r="1" gradientTransform="matrix(0 18.7256 -10.1586 0 26.852 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".795" class="fokhidb3o"/><stop offset="1" class="mxaztjs3a"/></radialGradient><radialGradient id="i1Ll57D" cx="0" cy="0" r="1" gradientTransform="matrix(0 17.645 -7.80931 0 26.388 8.423)" gradientUnits="userSpaceOnUse"><stop offset=".958" class="y4_p5tbgk"/><stop offset="1" class="mm-lvachd"/></radialGradient><filter id="iClTAye" width="27.985" height="23.056" x="2.008" y="3.832" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".75"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.227451 0 0 0 0 0.121569 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5705"/></filter><filter id="iVtGxse" width="6.044" height="15.266" x="3.439" y="9.467" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5705" stdDeviation=".75"/></filter><filter id="idyL51d" width="6.044" height="17.467" x="10.252" y="7.266" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5705" stdDeviation=".75"/></filter><filter id="iwUDLDd" width="6.044" height="22.312" x="17.906" y="3.735" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5705" stdDeviation=".75"/></filter><filter id="i9HQ5Cd" width="5.613" height="20.281" x="24.888" y="5.766" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5705" stdDeviation=".75"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:oncoming-fist-dark" /></template>
<style>
.ahcbeeqnb {
  d: path("M4.94 10.968a3.97 3.97 0 0 1 3.044 3.858v6.885a1.522 1.522 0 1 1-3.044 0z");
}

.b-lwpabjo {
  stop-color: var(--svg-color--402d2f, #402D2F);
  stop-opacity: 0;
}

.biz8hzbxr {
  d: path("m11.752 8.766l.13.037a4 4 0 0 1 2.914 3.85v9.058a1.522 1.522 0 1 1-3.044 0z");
}

.c40z1474u {
  stop-color: var(--svg-color--2a1315, #2A1315);
  stop-opacity: 0;
}

.ch-wr6b8u {
  d: path("M23.035 24.285a3.83 3.83 0 0 0 6.957-2.21v-9.822a3.83 3.83 0 0 0-5.958-3.184c-.976.653-.799 2.01-.799 3.184V23.06c0 .428-.07.84-.2 1.226");
}

.e08d66buv {
  d: path("M8.792 13.08c0-.466-.15-.931-.507-1.229a3.83 3.83 0 0 0-6.277 2.946v6.265a3.83 3.83 0 0 0 6.97 2.193a3.8 3.8 0 0 1-.186-1.181z");
}

.fnhtdvm3s {
  stop-color: var(--svg-color--1d0b0e, #1D0B0E);
  stop-opacity: 0;
}

.fokhidb3o {
  stop-color: var(--svg-color--3d2139, #3D2139);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0r5sc7jj {
  stop-color: var(--svg-color--3d2138, #3D2138);
  stop-opacity: 0;
}

.h4sla7j9c {
  stop-color: var(--svg-color--40262e, #40262E);
}

.hitwx9h6v {
  stop-color: var(--svg-color--2e191c, #2E191C);
}

.i5c5eto6f {
  stop-color: var(--svg-color--3d2138, #3D2138);
}

.ipxffnbnj {
  stop-color: var(--svg-color--432d2a, #432D2A);
}

.j9te750_s {
  stop-color: var(--svg-color--493737, #493737);
}

.jfl3vtq7y {
  d: path("m26.388 7.266l.076.03a4 4 0 0 1 2.538 3.723v12.222a1.307 1.307 0 1 1-2.613 0z");
}

.jmixq9yub {
  stop-color: var(--svg-color--1d0b0e, #1D0B0E);
}

.jnrp2cc9d {
  stop-color: var(--svg-color--513b38, #513B38);
  stop-opacity: 0;
}

.johgayerk {
  stop-color: var(--svg-color--42293d, #42293D);
  stop-opacity: 0;
}

.kis1f5bjl {
  stop-color: var(--svg-color--47312e, #47312E);
  stop-opacity: 0;
}

.kwxs_ibqc {
  stop-color: var(--svg-color--3c2032, #3C2032);
}

.lc75s3qjb {
  stop-color: var(--svg-color--42293d, #42293D);
}

.lhib44xat {
  stop-color: var(--svg-color--2e191c, #2E191C);
  stop-opacity: 0;
}

.ln66tyu0f {
  stop-color: var(--svg-color--40262e, #40262E);
  stop-opacity: 0;
}

.mm-lvachd {
  stop-color: var(--svg-color--564354, #564354);
}

.mxaztjs3a {
  stop-color: var(--svg-color--3d2139, #3D2139);
}

.n94_szb-u {
  stop-color: var(--svg-color--77605e, #77605E);
  stop-opacity: 0;
}

.nni30rf2x {
  width: 7.66px;
  height: 18.465px;
  x: 15.576px;
  y: 8.423px;
  rx: 3.83px;
}

.oi3z-hbab {
  stop-color: var(--svg-color--77605e, #77605E);
}

.p1xawgtbo {
  stop-color: var(--svg-color--402d2f, #402D2F);
}

.p7rzgf4vc {
  stop-color: var(--svg-color--47312e, #47312E);
}

.qov_v9bvg {
  width: 7.66px;
  height: 16.279px;
  x: 28.202px;
  y: 17.267px;
  rx: 3.83px;
}

.r-ag40bgp {
  stop-color: var(--svg-color--3c2035, #3C2035);
  stop-opacity: 0;
}

.rq0zkccsi {
  stop-color: var(--svg-color--3c2032, #3C2032);
  stop-opacity: 0;
}

.sgmt3fb2a {
  stop-color: var(--svg-color--2a1315, #2A1315);
}

.tt7eg3bmb {
  stop-color: var(--svg-color--3c2035, #3C2035);
}

.u8dju3b9i {
  width: 7.66px;
  height: 16.279px;
  x: 28.202px;
  y: 17.267px;
  fill: var(--svg-color--311c25, #311C25);
  rx: 3.83px;
}

.uh0yn9b_x {
  stop-color: var(--svg-color--634c49, #634C49);
  stop-opacity: 0;
}

.umi0gzb8q {
  stop-color: var(--svg-color--493737, #493737);
  stop-opacity: 0;
}

.vi72u84dw {
  d: path("M12.622 8.423a3.83 3.83 0 0 0-3.83 3.83v9.82a3.83 3.83 0 0 0 6.976 2.185a3.8 3.8 0 0 1-.192-1.2V12.254c0-.642.158-1.248.438-1.78a3.83 3.83 0 0 0-3.392-2.05");
}

.vzg6eudmh {
  stop-color: var(--svg-color--5b4848, #5B4848);
}

.w9oyexe9y {
  stop-color: var(--svg-color--634c49, #634C49);
}

.wlre5ob-u {
  stop-color: var(--svg-color--513b38, #513B38);
}

.x_cmizb4i {
  stop-color: var(--svg-color--654f4b, #654F4B);
}

.x5bb3s_jf {
  d: path("M2.008 12.711v8.35a3.83 3.83 0 0 0 6.97 2.194a3.831 3.831 0 0 0 6.79 1.003a3.831 3.831 0 0 0 7.267.027a3.83 3.83 0 0 0 6.957-2.21V9.359a4.25 4.25 0 0 0-4.46-4.245l-1.633.08a5.47 5.47 0 0 1-3.088-.776a4.1 4.1 0 0 0-3.883-.186l-1.298.621a6 6 0 0 1-2.589.588h-1.396a4 4 0 0 0-2.42.814L7.578 7.51c-.37.28-.796.566-1.228.734l-1.773.742c-1.703.691-2.568 2.078-2.568 3.726");
}

.y4_p5tbgk {
  stop-color: var(--svg-color--564354, #564354);
  stop-opacity: 0;
}

.zp_nx8bjr {
  stop-color: var(--svg-color--5b4848, #5B4848);
  stop-opacity: 0;
}

.zv_6jguez {
  d: path("m19.406 5.235l.454.172a4 4 0 0 1 2.59 3.743v13.876a1.522 1.522 0 0 1-3.044 0z");
}

</style>
