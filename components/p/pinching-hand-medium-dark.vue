<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iq7TXMb)"><path class="s-g6yerjk"/><path fill="url(#iLSu9Ob)" class="ztp1kg2ek"/></g><path fill="url(#itJk5Cd)" class="ztp1kg2ek"/><path fill="url(#iikEDHd)" class="ztp1kg2ek"/><path fill="url(#iSXGG2c)" class="ztp1kg2ek"/><path fill="url(#ijXgP1b)" class="ztp1kg2ek"/><path fill="url(#i0LXLZx)" class="ztp1kg2ek"/><g filter="url(#i0ce4MW)" class="pt2tz0kee"><path class="oul46ac7u"/><path class="cim4wckhz"/><path class="vtm2vdbkm"/></g><path class="nddv2zb6k"/><path fill="url(#iz4FWkq)" class="dnecupmnb"/><path fill="url(#ipx5GKb)" class="dnecupmnb"/><path fill="url(#iquNcde)" class="dnecupmnb"/><path fill="url(#i78xzEd)" class="dnecupmnb"/><g filter="url(#icOUrdb)"><rect class="b27ac4bur"/></g><path class="ljm6ycc_q"/><path fill="url(#ihyESne)" class="iqlj9abgt"/><path fill="url(#iDrDynb)" class="iqlj9abgt"/><path fill="url(#iX9btua)" class="iqlj9abgt"/><g filter="url(#iJZcMob)"><rect class="tgqq_ddww"/></g><path class="qmgd5dbwp"/><path fill="url(#i6Jb8Eb)" class="rdvdf0bjy"/><path fill="url(#izZ2Jnd)" class="rdvdf0bjy"/><path fill="url(#i2z2Fib)" class="rdvdf0bjy"/><path fill="url(#id0JmWS)" class="jbdw0hbfy"/><path fill="url(#iYxqW8c)" class="jbdw0hbfy"/><path fill="url(#iX0OGRc)" class="jbdw0hbfy"/><defs><radialGradient id="iLSu9Ob" cx="0" cy="0" r="1" gradientTransform="rotate(138.108 7.637 12.69)scale(14.0119 10.4377)" gradientUnits="userSpaceOnUse"><stop class="n4l_1jbbj"/><stop offset="1" class="l_eihfnjb"/></radialGradient><radialGradient id="itJk5Cd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.56813 -3.0232 2.6919 -2.28669 25.207 10.184)" gradientUnits="userSpaceOnUse"><stop class="dru288bhp"/><stop offset="1" class="zy04nb1ry"/></radialGradient><radialGradient id="iikEDHd" cx="0" cy="0" r="1" gradientTransform="rotate(153.85 12.41 5.889)scale(2.56455 2.04967)" gradientUnits="userSpaceOnUse"><stop class="w_hk5lg8e"/><stop offset="1" class="dm6i-m3cm"/></radialGradient><radialGradient id="iSXGG2c" cx="0" cy="0" r="1" gradientTransform="matrix(1.61753 1.77534 -9.13543 8.3234 17.984 4.526)" gradientUnits="userSpaceOnUse"><stop class="bfk05-1mc"/><stop offset="1" class="fx2hnhcgh"/></radialGradient><radialGradient id="ijXgP1b" cx="0" cy="0" r="1" gradientTransform="matrix(1.14411 0 0 3.35343 16.997 7.604)" gradientUnits="userSpaceOnUse"><stop class="u--0rebjh"/><stop offset="1" class="s15qcacwx"/></radialGradient><radialGradient id="i0LXLZx" cx="0" cy="0" r="1" gradientTransform="matrix(-23.07864 10.46505 -10.22957 -22.55934 26.612 12.601)" gradientUnits="userSpaceOnUse"><stop offset=".927" class="y652_po6l"/><stop offset="1" class="e7lrplx5j"/></radialGradient><radialGradient id="ipx5GKb" cx="0" cy="0" r="1" gradientTransform="matrix(4.61755 5.37902 -4.6731 4.01156 2.518 8.235)" gradientUnits="userSpaceOnUse"><stop offset=".552" class="gdbdy9bwh"/><stop offset="1" class="w1zd2nt2x"/></radialGradient><radialGradient id="iquNcde" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.74306 -1.49874 0 5.87 10.657)" gradientUnits="userSpaceOnUse"><stop class="e4z4pt61u"/><stop offset="1" class="o-la9rblc"/></radialGradient><radialGradient id="iDrDynb" cx="0" cy="0" r="1" gradientTransform="matrix(4.76725 6.57316 -5.51324 3.99854 7.308 7.58)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="nyz96lgrt"/><stop offset="1" class="sdzm7cbbv"/></radialGradient><radialGradient id="iX9btua" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.21375 -1.4605 0 10.574 10.307)" gradientUnits="userSpaceOnUse"><stop class="uiouo0b9u"/><stop offset="1" class="kyuw4ebbn"/></radialGradient><radialGradient id="izZ2Jnd" cx="0" cy="0" r="1" gradientTransform="rotate(67.804 2.01 13.864)scale(7.84411 6.60719)" gradientUnits="userSpaceOnUse"><stop offset=".563" class="nyz96lgrt"/><stop offset="1" class="sdzm7cbbv"/></radialGradient><radialGradient id="i2z2Fib" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.4644 -1.88757 0 16.029 10.175)" gradientUnits="userSpaceOnUse"><stop class="uiouo0b9u"/><stop offset="1" class="kyuw4ebbn"/></radialGradient><radialGradient id="iYxqW8c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.7342 1.76829 -1.38594 -2.14299 28.136 13.78)" gradientUnits="userSpaceOnUse"><stop class="pgj76mb-f"/><stop offset="1" class="oaopunb0a"/></radialGradient><radialGradient id="iX0OGRc" cx="0" cy="0" r="1" gradientTransform="matrix(1.46286 .58513 -2.0674 5.16858 21.468 15.482)" gradientUnits="userSpaceOnUse"><stop offset=".442" class="ry-9r2-3h"/><stop offset="1" class="w4u04bxli"/></radialGradient><linearGradient id="iz4FWkq" x1="2.489" x2="5.312" y1="11.628" y2="11.628" gradientUnits="userSpaceOnUse"><stop class="i19dw1b1s"/><stop offset="1" class="hta837b3n"/></linearGradient><linearGradient id="i78xzEd" x1="1.816" x2="2.425" y1="10.657" y2="10.657" gradientUnits="userSpaceOnUse"><stop class="jz_7e_bsm"/><stop offset="1" class="gjh_usb_b"/></linearGradient><linearGradient id="ihyESne" x1="7.279" x2="10.031" y1="11.401" y2="11.401" gradientUnits="userSpaceOnUse"><stop class="mqglxvbco"/><stop offset="1" class="msg50_fgb"/></linearGradient><linearGradient id="i6Jb8Eb" x1="12.178" x2="14.973" y1="11.271" y2="11.271" gradientUnits="userSpaceOnUse"><stop class="mqglxvbco"/><stop offset="1" class="msg50_fgb"/></linearGradient><linearGradient id="id0JmWS" x1="23.952" x2="25.919" y1="12.705" y2="16.378" gradientUnits="userSpaceOnUse"><stop class="lhmiyptzu"/><stop offset="1" class="eg6i6hivg"/></linearGradient><filter id="iq7TXMb" width="27.675" height="25.549" x="1.924" y="2.589" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".75" dy="-.5"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.486275 0 0 0 0 0.254902 0 0 0 0 0.423529 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_1983"/></filter><filter id="i0ce4MW" width="16.091" height="12.26" x="1.295" y="6.076" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1983" stdDeviation="1"/></filter><filter id="icOUrdb" width="2.266" height="8.313" x="5.635" y="6.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1983" stdDeviation=".375"/></filter><filter id="iJZcMob" width="2.266" height="8.719" x="10.572" y="5.998" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_1983" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pinching-hand-medium-dark" /></template>
<style>
.b27ac4bur {
  width: 0.766px;
  height: 6.813px;
  x: 6.385px;
  y: 7.154px;
  fill: var(--svg-color--633a2f, #633A2F);
  rx: 0.383px;
}

.bfk05-1mc {
  stop-color: var(--svg-color--70564c, #70564C);
}

.cim4wckhz {
  d: path("M8.917 8.48a2.527 2.527 0 0 0-2.532 2.514v2.829a2.527 2.527 0 0 0 2.532 2.514a2.526 2.526 0 0 0 2.532-2.514v-2.83A2.52 2.52 0 0 0 8.917 8.48");
}

.dm6i-m3cm {
  stop-color: var(--svg-color--a07b70, #A07B70);
  stop-opacity: 0;
}

.dnecupmnb {
  d: path("M4.836 6.19c-1.606 0-2.912 1.192-2.912 2.656v3.622c0 1.464 1.306 2.655 2.912 2.655s2.912-1.19 2.912-2.655V8.846c0-1.464-1.306-2.655-2.912-2.655");
}

.dru288bhp {
  stop-color: var(--svg-color--6b384e, #6B384E);
}

.e4z4pt61u {
  stop-color: var(--svg-color--896b64, #896B64);
}

.e7lrplx5j {
  stop-color: var(--svg-color--835c59, #835C59);
}

.eg6i6hivg {
  stop-color: var(--svg-color--6e4538, #6E4538);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fx2hnhcgh {
  stop-color: var(--svg-color--70564c, #70564C);
  stop-opacity: 0;
}

.gdbdy9bwh {
  stop-color: var(--svg-color--6f3f4f, #6F3F4F);
  stop-opacity: 0;
}

.gjh_usb_b {
  stop-color: var(--svg-color--856359, #856359);
  stop-opacity: 0;
}

.hta837b3n {
  stop-color: var(--svg-color--785649, #785649);
  stop-opacity: 0;
}

.i19dw1b1s {
  stop-color: var(--svg-color--785649, #785649);
}

.iqlj9abgt {
  d: path("M9.566 5.28c-1.565 0-2.838 1.23-2.838 2.743v4.569c0 1.512 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.jbdw0hbfy {
  d: path("M23.932 12.873c1.546-1.344 3.412-.999 4.375.438c1.525 2.275-.461 4.16-2.356 5.96a28 28 0 0 0-1.348 1.336c-.884.823-1.6 1.536-2.253 2.187a51 51 0 0 1-1.967 1.893c-.446.4-.886.769-1.328 1.104l3.427-11.924c.252.078.71-.333 1.167-.743q.143-.129.282-.25");
}

.jz_7e_bsm {
  stop-color: var(--svg-color--856359, #856359);
}

.kyuw4ebbn {
  stop-color: var(--svg-color--97766e, #97766E);
  stop-opacity: 0;
}

.l_eihfnjb {
  stop-color: var(--svg-color--a17a6e, #A17A6E);
  stop-opacity: 0;
}

.lhmiyptzu {
  stop-color: var(--svg-color--6e4538, #6E4538);
}

.ljm6ycc_q {
  fill: var(--svg-color--865f52, #865F52);
  d: path("M9.566 5.28c-1.565 0-2.838 1.23-2.838 2.743v4.569c0 1.512 1.273 2.743 2.838 2.743s2.838-1.23 2.838-2.743v-4.58c0-1.512-1.273-2.733-2.838-2.733");
}

.mqglxvbco {
  stop-color: var(--svg-color--623c34, #623C34);
}

.msg50_fgb {
  stop-color: var(--svg-color--623c34, #623C34);
  stop-opacity: 0;
}

.n4l_1jbbj {
  stop-color: var(--svg-color--a17a6e, #A17A6E);
}

.nddv2zb6k {
  fill: var(--svg-color--825d51, #825D51);
  d: path("M4.836 6.19c-1.606 0-2.912 1.192-2.912 2.656v3.622c0 1.464 1.306 2.655 2.912 2.655s2.912-1.19 2.912-2.655V8.846c0-1.464-1.306-2.655-2.912-2.655");
}

.nyz96lgrt {
  stop-color: var(--svg-color--754356, #754356);
  stop-opacity: 0;
}

.o-la9rblc {
  stop-color: var(--svg-color--896b64, #896B64);
  stop-opacity: 0;
}

.oaopunb0a {
  stop-color: var(--svg-color--a57f74, #A57F74);
  stop-opacity: 0;
}

.oul46ac7u {
  d: path("M12.724 8.076a2.656 2.656 0 0 0-2.662 2.643v2.974c0 1.457 1.194 2.644 2.662 2.644s2.662-1.187 2.662-2.644V10.72a2.65 2.65 0 0 0-2.662-2.643");
}

.pgj76mb-f {
  stop-color: var(--svg-color--a57f74, #A57F74);
}

.pt2tz0kee {
  fill: var(--svg-color--45212b, #45212B);
}

.qmgd5dbwp {
  fill: var(--svg-color--865f52, #865F52);
  d: path("M14.502 5.139c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862V8a2.87 2.87 0 0 0-2.883-2.861");
}

.rdvdf0bjy {
  d: path("M14.502 5.139c-1.59 0-2.883 1.284-2.883 2.862v4.349c0 1.578 1.294 2.862 2.883 2.862s2.883-1.284 2.883-2.862V8a2.87 2.87 0 0 0-2.883-2.861");
}

.ry-9r2-3h {
  stop-color: var(--svg-color--977369, #977369);
}

.s-g6yerjk {
  fill: var(--svg-color--85595a, #85595A);
  d: path("M28.307 13.31c-.963-1.436-2.829-1.78-4.375-.437c-.762.661-1.649 1.618-1.649.464V10.24c.07-1.281.828-1.625 2.063-1.203c1.756.445 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H1.924v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.452c1.31-1.174 2.412-2.397 4.22-4.08c2.032-2.218 5.61-4.453 3.703-7.296");
}

.s15qcacwx {
  stop-color: var(--svg-color--60372a, #60372A);
  stop-opacity: 0;
}

.sdzm7cbbv {
  stop-color: var(--svg-color--754356, #754356);
}

.tgqq_ddww {
  width: 0.766px;
  height: 7.219px;
  x: 11.322px;
  y: 6.748px;
  fill: var(--svg-color--633a2f, #633A2F);
  rx: 0.383px;
}

.u--0rebjh {
  stop-color: var(--svg-color--60372a, #60372A);
}

.uiouo0b9u {
  stop-color: var(--svg-color--97766e, #97766E);
}

.vtm2vdbkm {
  d: path("M5.578 8.665a2.28 2.28 0 0 0-2.283 2.266v2.55a2.28 2.28 0 0 0 2.283 2.267A2.28 2.28 0 0 0 7.86 13.48v-2.55a2.273 2.273 0 0 0-2.282-2.266");
}

.w_hk5lg8e {
  stop-color: var(--svg-color--a07b70, #A07B70);
}

.w1zd2nt2x {
  stop-color: var(--svg-color--6f3f4f, #6F3F4F);
}

.w4u04bxli {
  stop-color: var(--svg-color--977369, #977369);
  stop-opacity: 0;
}

.y652_po6l {
  stop-color: var(--svg-color--835c59, #835C59);
  stop-opacity: 0;
}

.ztp1kg2ek {
  d: path("M28.307 13.31c-.963-1.436-2.829-1.78-4.375-.437c-.762.661-1.649 1.618-1.649.464V10.24c.07-1.281.828-1.625 2.063-1.203c1.756.445 3.168-.964 3.43-2.164c.203-.938-.008-2.441-1.61-3.203c-3.297-1.422-7.36-.203-8.9 3.333l-3.302 2.334H1.924v6.583c0 7.719 3.982 12.219 10.456 12.219c3.26 0 5.55-1.252 8.003-3.452c1.31-1.174 2.412-2.397 4.22-4.08c2.032-2.218 5.61-4.453 3.703-7.296");
}

.zy04nb1ry {
  stop-color: var(--svg-color--6b384e, #6B384E);
  stop-opacity: 0;
}

</style>
