<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><path class="nbpxr8b7y"/><path class="f9vnqobbf"/><path fill="url(#i8e1ldF)" class="i_-9r_oss"/><path class="wh6b0-b2l"/><path fill="url(#iuezoob)" class="zannmacjr"/><path fill="url(#iE8QcEd)" class="zannmacjr"/><path fill="url(#ivEnSkc)" class="zannmacjr"/><path fill="url(#iWiImqb)" class="maobbcvxh"/><path fill="url(#ibBjvec)" class="zannmacjr"/><path fill="url(#ipSnfmL)" class="zannmacjr"/><path fill="url(#ilqJk5c)" class="zannmacjr"/><path fill="url(#i6j9Pab)" class="zannmacjr"/><g filter="url(#iWiXvGe)" class="ljb4srbfs"><path fill="url(#igcbK4c)" class="gon5fk4jy"/><path fill="url(#igcbK4c)" class="o805zybpl"/></g><path fill="url(#iMYQlKc)" class="dhw7jubve"/><path fill="url(#i0Cjz8d)" class="rrolimf3f"/><g filter="url(#iBZ9Sjb)"><path fill="url(#inry0hb)" class="hqmdf2sgv"/><path fill="url(#inry0hb)" class="n1yspsnij"/></g><path fill="url(#iEPexKy)" class="vj1k3sm5y"/><path fill="url(#itm2nKc)" class="iij55h77y"/><path stroke="url(#iXYEvcd)" class="vv90dsabj"/><path stroke="url(#i8AYw1b)" class="vv90dsabj"/><path stroke="url(#ibGuudc)" class="il6pwxbdq"/><path fill="url(#ieRAlzb)" class="sezhbclzr"/><path fill="url(#i8jntdd)" clip-rule="evenodd" class="tqvyrybuy"/></g><defs><radialGradient id="iuezoob" cx="0" cy="0" r="1" gradientTransform="rotate(132.839 10.786 10.065)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="iE8QcEd" cx="0" cy="0" r="1" gradientTransform="rotate(131.878 10.74 10.193)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ivEnSkc" cx="0" cy="0" r="1" gradientTransform="rotate(101.31 2.876 12.808)scale(17.8466 22.8581)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="iWiImqb" cx="0" cy="0" r="1" gradientTransform="matrix(-29 29 -29 -29 18 14)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="ibBjvec" cx="0" cy="0" r="1" gradientTransform="rotate(77.692 -2.555 18.434)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ipSnfmL" cx="0" cy="0" r="1" gradientTransform="matrix(7.5 10.99996 -7.97335 5.4364 16.5 16.5)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="ilqJk5c" cx="0" cy="0" r="1" gradientTransform="matrix(11.49998 2 -2 11.49998 20.5 18)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="i6j9Pab" cx="0" cy="0" r="1" gradientTransform="rotate(43.971 -9.827 29.173)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="igcbK4c" cx="0" cy="0" r="1" gradientTransform="matrix(-2.62502 7.125 -9.31237 -3.4309 9.781 10.438)" gradientUnits="userSpaceOnUse"><stop class="vn4n3no1s"/><stop offset=".889" class="ixmaddcbc"/></radialGradient><radialGradient id="inry0hb" cx="0" cy="0" r="1" gradientTransform="rotate(-135.995 16.937 3.298)scale(13.3597 17.4611)" gradientUnits="userSpaceOnUse"><stop class="kb93-db6z"/><stop offset=".802" class="z-xmlwmhd"/></radialGradient><radialGradient id="i8AYw1b" cx="0" cy="0" r="1" gradientTransform="matrix(2.5 3.5 -3.5 2.5 7 5)" gradientUnits="userSpaceOnUse"><stop offset=".542" class="j2t0-ibcg"/><stop offset=".807" class="scgg1abqz"/><stop offset=".955" class="zg8znn0_h"/></radialGradient><radialGradient id="ibGuudc" cx="0" cy="0" r="1" gradientTransform="rotate(125.538 11.213 8.933)scale(4.30116)" gradientUnits="userSpaceOnUse"><stop class="hyejxlbwh"/><stop offset=".887" class="dnexucbbp"/><stop offset="1" class="zg8znn0_h"/></radialGradient><radialGradient id="ieRAlzb" cx="0" cy="0" r="1" gradientTransform="matrix(0 -10.5 28.4095 0 16 27)" gradientUnits="userSpaceOnUse"><stop class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="i8jntdd" cx="0" cy="0" r="1" gradientTransform="matrix(2.99933 -3.5 4.77631 4.09307 15 19.5)" gradientUnits="userSpaceOnUse"><stop offset=".454" class="vc--wpv5i"/><stop offset=".84" class="nvahlubfz"/><stop offset="1" class="kyk_hxbet"/></radialGradient><linearGradient id="i8e1ldF" x1="15.999" x2="15.999" y1="28.917" y2="4.374" gradientUnits="userSpaceOnUse"><stop class="yiq__d07e"/><stop offset="1" class="nzecdosuq"/></linearGradient><linearGradient id="iMYQlKc" x1="10.578" x2="8" y1="16.732" y2="11.388" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="i0Cjz8d" x1="8.86" x2="11.25" y1="13.139" y2="8.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iEPexKy" x1="21.406" x2="23.985" y1="16.732" y2="11.388" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="itm2nKc" x1="23.125" x2="20.734" y1="13.139" y2="8.451" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iXYEvcd" x1="9.5" x2="9.5" y1="5" y2="6.5" gradientUnits="userSpaceOnUse"><stop offset=".03" class="ii_r00eab"/><stop offset="1" class="zg8znn0_h"/></linearGradient><filter id="iWiXvGe" width="7" height="6.996" x="7.5" y="9.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1686" stdDeviation=".25"/></filter><filter id="iBZ9Sjb" width="7" height="6.996" x="16.906" y="9.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_31_1686" stdDeviation=".25"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tired-face" /></template>
<style>
.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.dhw7jubve {
  d: path("M9.447 15.89a1 1 0 1 1-.894-1.789l2.206-1.103H14a1 1 0 0 1-.553.892z");
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.dnexucbbp {
  stop-color: var(--svg-color--462b45, #462B45);
}

.f9vnqobbf {
  stroke: var(--svg-color--533468, #533468);
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M10.42 4.53c0 2.15-1.74 3.89-3.89 3.89m15-3.89c0 2.15 1.74 3.89 3.89 3.89");
}

.fqgjm_v0b {
  stop-color: var(--svg-color--715b32, #715B32);
}

.ft5dv1b6b {
  fill: none;
}

.g4z4xncfo {
  stop-color: var(--svg-color--ffb849, #FFB849);
}

.gon5fk4jy {
  d: path("M9.447 16.328a1 1 0 1 1-.894-1.79l2.206-1.103H14a1 1 0 0 1-.553.893z");
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hqmdf2sgv {
  d: path("M21.959 16.328a1 1 0 0 0 .895-1.79l-2.207-1.103h-3.24a1 1 0 0 0 .552.893z");
}

.hyejxlbwh {
  stop-color: var(--svg-color--c2b4b5, #C2B4B5);
}

.i_-9r_oss {
  d: path("M8.14 24.92c-.64 0-1.14-.56-1.06-1.19A8.994 8.994 0 0 1 16 15.92c4.57 0 8.34 3.4 8.92 7.81c.08.63-.42 1.19-1.06 1.19z");
}

.ii_r00eab {
  stop-color: var(--svg-color--524049, #524049);
}

.iij55h77y {
  d: path("M22.537 10.106a1 1 0 1 1 .895 1.789l-2.207 1.103h-3.24a1 1 0 0 1 .552-.892z");
}

.il6pwxbdq {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M21.5 5.5s.5 3 4 3");
}

.ixmaddcbc {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
  stop-opacity: 0;
}

.j2t0-ibcg {
  stop-color: var(--svg-color--493032, #493032);
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kb93-db6z {
  stop-color: var(--svg-color--e9830a, #E9830A);
}

.kyk_hxbet {
  stop-color: var(--svg-color--d590ff, #D590FF);
}

.ljb4srbfs {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
}

.maobbcvxh {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.n1yspsnij {
  d: path("M21.959 10.543a1 1 0 0 1 .895 1.79l-2.207 1.102h-3.24a1 1 0 0 1 .552-.892z");
}

.nbpxr8b7y {
  fill: var(--svg-color--533566, #533566);
  d: path("m13.45 12.03l-4-2c-.5-.25-1.1-.05-1.35.44a1 1 0 0 0 .45 1.34l2.21 1.11l-2.21 1.11c-.49.25-.69.85-.45 1.34s.85.69 1.34.45l4-2c.34-.18.56-.52.56-.9s-.22-.73-.55-.89m10 2l-2.21-1.11l2.21-1.11c.49-.25.69-.85.45-1.34s-.85-.69-1.34-.45l-4 2c-.35.17-.56.52-.56.9s.21.73.55.89l4 2c.49.25 1.09.05 1.34-.45s.05-1.09-.44-1.33");
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.nzecdosuq {
  stop-color: var(--svg-color--68217a, #68217A);
}

.o805zybpl {
  d: path("M9.447 10.543a1 1 0 1 0-.894 1.79l2.206 1.102H14a1 1 0 0 0-.553-.892z");
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rrolimf3f {
  d: path("M9.447 10.106a1 1 0 1 0-.894 1.789l2.206 1.103H14a1 1 0 0 0-.553-.892z");
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.scgg1abqz {
  stop-color: var(--svg-color--5e445a, #5E445A);
}

.sezhbclzr {
  d: path("M24.657 22.531C25.035 23.86 23.881 25 22.5 25h-13c-1.381 0-2.535-1.14-2.157-2.469a9.004 9.004 0 0 1 17.314 0");
}

.tqvyrybuy {
  fill-rule: evenodd;
  d: path("M21.657 18H10.343A8.96 8.96 0 0 1 16 16c2.143 0 4.112.75 5.657 2");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vj1k3sm5y {
  d: path("M22.537 15.89a1 1 0 1 0 .895-1.789l-2.207-1.103h-3.24a1 1 0 0 0 .552.892z");
}

.vn4n3no1s {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
}

.vv90dsabj {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-25px, 1.25px);
  d: path("M10.5 5.5s-.5 3-4 3");
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wh6b0-b2l {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.28 17.97A8.97 8.97 0 0 1 16 15.92c2.17 0 4.16.77 5.72 2.05");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.yiq__d07e {
  stop-color: var(--svg-color--e81123, #E81123);
}

.z-xmlwmhd {
  stop-color: var(--svg-color--f08b13, #F08B13);
  stop-opacity: 0;
}

.zannmacjr {
  d: path("M15.999 29.998c9.334 0 13.999-6.268 13.999-14c0-7.73-4.665-13.998-14-13.998C6.665 2 2 8.268 2 15.999s4.664 13.999 13.999 13.999");
}

.zg8znn0_h {
  stop-color: var(--svg-color--4a2c42, #4A2C42);
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

</style>
