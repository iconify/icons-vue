<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iAZdQyc)" class="vjgsribzq"/><path fill="url(#iVuM6Zc)" class="efbn9x6af"/><path fill="url(#igisORc)" class="efbn9x6af"/><g class="mc2zb0bvp"><path fill="url(#i6oYkEr)" class="jx3fnpbms"/><path fill="url(#iuoL3By)" class="jx3fnpbms"/></g><path fill="url(#idAmh6d)" class="qyuu4-csi"/><path fill="url(#iyIv9Wb)" class="qyuu4-csi"/><path fill="url(#itSdPCb)" class="qyuu4-csi"/><path fill="url(#ihHirxc)" class="qyuu4-csi"/><path fill="url(#iM1WDyb)" class="zmhyvgglu"/><path fill="url(#iI3h7ec)" class="zmhyvgglu"/><path fill="url(#iFBXwFe)" class="zmhyvgglu"/><path fill="url(#ihcWxib)" class="q64djcbcz"/><path fill="url(#i7h39Pc)" class="tmy9x9yhg"/><path fill="url(#iZ6FcGf)" class="tmy9x9yhg"/><g filter="url(#iPcSmac)"><path fill="url(#iAMqFvd)" class="sy5ga3v_w"/><path fill="url(#ikWwxjd)" class="sy5ga3v_w"/><path class="r67rx883r"/></g><path fill="url(#iW0pWHd)" class="qu1wo5lbe"/><path fill="url(#iXQSEie)" class="qu1wo5lbe"/><path fill="url(#iPI1HJe)" class="qu1wo5lbe"/><path fill="url(#ityTjZO)" class="qu1wo5lbe"/><defs><radialGradient id="iAZdQyc" cx="0" cy="0" r="1" gradientTransform="matrix(1.7953 0 0 1.80973 13.046 19.926)" gradientUnits="userSpaceOnUse"><stop class="ujtnbqbex"/><stop offset="1" class="xspqbhqhs"/></radialGradient><radialGradient id="iyIv9Wb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.0625 2.25 -3.7039 -1.74909 20.938 6.875)" gradientUnits="userSpaceOnUse"><stop class="nk8h5wixq"/><stop offset="1" class="mi9qai-vj"/></radialGradient><radialGradient id="itSdPCb" cx="0" cy="0" r="1" gradientTransform="rotate(82.648 4.009 13.805)scale(5.86069 10.89)" gradientUnits="userSpaceOnUse"><stop offset=".454" class="xeoh-uoct"/><stop offset=".662" class="dfb07ngug"/></radialGradient><radialGradient id="ihHirxc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.6875 .18751 -.47932 -9.42616 17.906 4.469)" gradientUnits="userSpaceOnUse"><stop offset=".128" class="pquvpov8y"/><stop offset=".347" class="n03tmgbfr"/><stop offset=".646" class="enu6wibfc"/></radialGradient><radialGradient id="iI3h7ec" cx="0" cy="0" r="1" gradientTransform="matrix(-14.12504 1.4375 -.79334 -7.79536 20.438 10.938)" gradientUnits="userSpaceOnUse"><stop offset=".685" class="bg98urbrr"/><stop offset=".78" class="tp9qrnbeg"/><stop offset=".88" class="qse4dwd9h"/></radialGradient><radialGradient id="iFBXwFe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3125 2 -3.05685 -2.00606 22.875 10.563)" gradientUnits="userSpaceOnUse"><stop class="jiw0bfxjb"/><stop offset="1" class="y3iv3o0sd"/></radialGradient><radialGradient id="ihcWxib" cx="0" cy="0" r="1" gradientTransform="matrix(7.523 0 0 7.58349 15.782 16.832)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="tuintsbtg"/><stop offset="1" class="xspqbhqhs"/></radialGradient><radialGradient id="ikWwxjd" cx="0" cy="0" r="1" gradientTransform="rotate(83.325 .264 18.455)scale(5.91509 13.7581)" gradientUnits="userSpaceOnUse"><stop offset=".72" class="mm0998f9n"/><stop offset="1" class="ytx-8cb1b"/></radialGradient><radialGradient id="iXQSEie" cx="0" cy="0" r="1" gradientTransform="rotate(83.325 .607 18.15)scale(5.91509 13.7581)" gradientUnits="userSpaceOnUse"><stop offset=".72" class="mm0998f9n"/><stop offset=".925" class="ytx-8cb1b"/></radialGradient><radialGradient id="iPI1HJe" cx="0" cy="0" r="1" gradientTransform="rotate(113.929 7.3 15.374)scale(2.7736 3.64835)" gradientUnits="userSpaceOnUse"><stop class="jiw0bfxjb"/><stop offset="1" class="m-zder2uu"/></radialGradient><radialGradient id="ityTjZO" cx="0" cy="0" r="1" gradientTransform="matrix(1.40625 -.125 .22207 2.49825 13.313 20.844)" gradientUnits="userSpaceOnUse"><stop offset=".197" class="lbt0xbcfr"/><stop offset=".407" class="zx27c-avk"/><stop offset=".831" class="wdkeu2b4g"/></radialGradient><linearGradient id="iVuM6Zc" x1="11.125" x2="21.25" y1="26.75" y2="26.75" gradientUnits="userSpaceOnUse"><stop class="kmubh8kzn"/><stop offset=".216" class="zmsmh186p"/><stop offset=".568" class="vu5nfsqka"/><stop offset="1" class="k-o25mbus"/></linearGradient><linearGradient id="igisORc" x1="16.177" x2="16.177" y1="22.629" y2="29.988" gradientUnits="userSpaceOnUse"><stop offset=".883" class="d27iilbvg"/><stop offset="1" class="xg1__jbog"/></linearGradient><linearGradient id="i6oYkEr" x1="10.902" x2="21.432" y1="25.75" y2="25.75" gradientUnits="userSpaceOnUse"><stop class="e77er8b8i"/><stop offset=".425" class="tyxtlj-gn"/><stop offset=".757" class="kup0_557w"/><stop offset="1" class="kp6avnb4k"/></linearGradient><linearGradient id="iuoL3By" x1="16.167" x2="16.167" y1="22.629" y2="29.988" gradientUnits="userSpaceOnUse"><stop offset=".917" class="n3xfxob9x"/><stop offset="1" class="wnbwqsbcb"/></linearGradient><linearGradient id="idAmh6d" x1="16.25" x2="15.598" y1="9.844" y2="3.192" gradientUnits="userSpaceOnUse"><stop offset=".028" class="nvl2p-5ya"/><stop offset=".144" class="g3z18qbut"/><stop offset=".251" class="rogluyn_n"/></linearGradient><linearGradient id="iM1WDyb" x1="16.905" x2="16.521" y1="13.754" y2="9.549" gradientUnits="userSpaceOnUse"><stop offset=".057" class="nvl2p-5ya"/><stop offset=".158" class="g3z18qbut"/><stop offset=".356" class="e2a7rcbkj"/><stop offset=".846" class="jiq6nebbu"/><stop offset=".968" class="kogi9ibcq"/></linearGradient><linearGradient id="i7h39Pc" x1="9.392" x2="22.625" y1="21.625" y2="21.625" gradientUnits="userSpaceOnUse"><stop class="cx2c-0bdn"/><stop offset=".088" class="lfhi7188t"/><stop offset=".32" class="jg9ct6bqn"/><stop offset=".745" class="v3h8dvbst"/><stop offset="1" class="jj6qprbvt"/></linearGradient><linearGradient id="iZ6FcGf" x1="16.232" x2="16.232" y1="19.202" y2="22.629" gradientUnits="userSpaceOnUse"><stop offset=".798" class="hbqctvbfk"/><stop offset=".898" class="m2mxadbbx"/><stop offset="1" class="zrwi8mbyq"/></linearGradient><linearGradient id="iAMqFvd" x1="17" x2="16.563" y1="20.985" y2="14.236" gradientUnits="userSpaceOnUse"><stop offset=".03" class="acwjz8lvo"/><stop offset=".313" class="lo4ldxbms"/><stop offset=".577" class="d-eg1cc4i"/><stop offset=".841" class="tbsziibgm"/><stop offset=".978" class="kogi9ibcq"/></linearGradient><linearGradient id="iW0pWHd" x1="17" x2="16.563" y1="20.375" y2="13.625" gradientUnits="userSpaceOnUse"><stop offset=".03" class="acwjz8lvo"/><stop offset=".313" class="lo4ldxbms"/><stop offset=".577" class="d-eg1cc4i"/><stop offset=".841" class="tbsziibgm"/><stop offset=".978" class="kogi9ibcq"/></linearGradient><filter id="iPcSmac" width="15.286" height="10.081" x="9.002" y="12.794" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_28477" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:soft-ice-cream" /></template>
<style>
.acwjz8lvo {
  stop-color: var(--svg-color--d89387, #D89387);
}

.bg98urbrr {
  stop-color: var(--svg-color--fed29c, #FED29C);
  stop-opacity: 0;
}

.cx2c-0bdn {
  stop-color: var(--svg-color--d2ad8c, #D2AD8C);
}

.d-eg1cc4i {
  stop-color: var(--svg-color--ffdba7, #FFDBA7);
}

.d27iilbvg {
  stop-color: var(--svg-color--c8746a, #C8746A);
  stop-opacity: 0;
}

.dfb07ngug {
  stop-color: var(--svg-color--e6be8d, #E6BE8D);
}

.e2a7rcbkj {
  stop-color: var(--svg-color--ffdea7, #FFDEA7);
}

.e77er8b8i {
  stop-color: var(--svg-color--d4a789, #D4A789);
}

.efbn9x6af {
  d: path("M15.712 22.63h-5.01l.82 6.602c.05.433.42.756.85.756h7.61c.43 0 .79-.323.85-.756l.82-6.603z");
}

.enu6wibfc {
  stop-color: var(--svg-color--fad8a6, #FAD8A6);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g3z18qbut {
  stop-color: var(--svg-color--ffd59b, #FFD59B);
}

.hbqctvbfk {
  stop-color: var(--svg-color--db9176, #DB9176);
  stop-opacity: 0;
}

.jg9ct6bqn {
  stop-color: var(--svg-color--eaa26b, #EAA26B);
}

.jiq6nebbu {
  stop-color: var(--svg-color--ffe1a8, #FFE1A8);
}

.jiw0bfxjb {
  stop-color: var(--svg-color--fff8bd, #FFF8BD);
}

.jj6qprbvt {
  stop-color: var(--svg-color--f8c589, #F8C589);
}

.jx3fnpbms {
  d: path("M19.842 22.63h-1.4l-2.21 2.227l-2.21-2.228h-1.4l-1.72 1.734l.32 2.61l1.45 1.463l-1.08 1.088a.86.86 0 0 0 .76.464h.07l.89-.897l.89.897h1.29l-1.51-1.552l2.26-2.279l2.26 2.279l-1.54 1.552h1.29l.89-.897l.89.897c.34-.02.62-.242.74-.555l-.99-.997l1.3-1.31l.18-1.483l-2.13 2.147l-2.26-2.278l2.26-2.278l2.16 2.177l.14-1.159zm-6.51 5.15l-2.26-2.278l2.26-2.278l2.26 2.278z");
}

.k-o25mbus {
  stop-color: var(--svg-color--fcbd73, #FCBD73);
}

.kmubh8kzn {
  stop-color: var(--svg-color--c5987c, #C5987C);
}

.kogi9ibcq {
  stop-color: var(--svg-color--fdd594, #FDD594);
}

.kp6avnb4k {
  stop-color: var(--svg-color--f9cf9a, #F9CF9A);
}

.kup0_557w {
  stop-color: var(--svg-color--fff0c9, #FFF0C9);
}

.lbt0xbcfr {
  stop-color: var(--svg-color--ffd4a8, #FFD4A8);
}

.lfhi7188t {
  stop-color: var(--svg-color--d19870, #D19870);
}

.lo4ldxbms {
  stop-color: var(--svg-color--f8c6a3, #F8C6A3);
}

.m-zder2uu {
  stop-color: var(--svg-color--ffeeb6, #FFEEB6);
  stop-opacity: 0;
}

.m2mxadbbx {
  stop-color: var(--svg-color--e19978, #E19978);
}

.mc2zb0bvp {
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mi9qai-vj {
  stop-color: var(--svg-color--ffe5b1, #FFE5B1);
  stop-opacity: 0;
}

.mm0998f9n {
  stop-color: var(--svg-color--e1ae83, #E1AE83);
  stop-opacity: 0;
}

.n03tmgbfr {
  stop-color: var(--svg-color--ffe0af, #FFE0AF);
}

.n3xfxob9x {
  stop-color: var(--svg-color--e09a80, #E09A80);
  stop-opacity: 0;
}

.nk8h5wixq {
  stop-color: var(--svg-color--fff6ba, #FFF6BA);
}

.nvl2p-5ya {
  stop-color: var(--svg-color--ffe4a8, #FFE4A8);
}

.pquvpov8y {
  stop-color: var(--svg-color--fff8ba, #FFF8BA);
}

.q64djcbcz {
  d: path("M25.772 15.956c-.15-1.673-1.61-2.913-3.27-2.772l-13.96 1.23a3.05 3.05 0 0 0-2.75 3.296c.15 1.673 1.61 2.913 3.27 2.772l8.04-.706c.27-.02 3.42-.302 3.66-.322l2.26-.202a3.05 3.05 0 0 0 2.75-3.296");
}

.qse4dwd9h {
  stop-color: var(--svg-color--e4b783, #E4B783);
}

.qu1wo5lbe {
  d: path("M25.772 15.956c-.15-1.673-1.61-2.913-3.27-2.772l-13.96 1.23a3.05 3.05 0 0 0-2.75 3.296c.15 1.673 1.61 2.913 3.27 2.772l2.33-.201c.22-.02.41.16.41.383l.03.191c0 .504.41.917.91.917s.91-.413.91-.917l-.03-.423c0-.202.15-.363.35-.383l3.12-.273c.27-.02 3.42-.302 3.66-.322l2.26-.202a3.05 3.05 0 0 0 2.76-3.296");
}

.qyuu4-csi {
  d: path("M21.836 7.406c0-.945-1.32-1.593-2.04-1.593h-1.124c-.17.01-.672-.118-.672-.5c0 0-.047-1.004-.047-1.532s-.274-1.315-1.164-1.234c-.75.07-1.007.768-1.067 1.07c-.06.333-.293.814-.753 1.156c-.95.706-3.805 1.82-3.805 1.82c-.841.283-1.52 1.221-1.453 2.11c0 .445.312.852.312 1.172s-.609.492-.609.492L22.016 9.36s-.461-.28-.461-.617c0-.281.28-.57.28-1.336");
}

.r67rx883r {
  fill: var(--svg-color--c67b4d, #C67B4D);
  d: path("M22.502 13.794c-3.006.265-10.098 3.63-12.393 5.643c-.468.411.703.702 1.309.964c.3.13.35.587.395.724c.133.413.5.75 1 .75s.992-.542.992-.836c0-.202-.094-.56 1.039-.638s2.008-.129 5.969-.438c3.96-.309 2.073-3.546 1.69-6.169");
}

.rogluyn_n {
  stop-color: var(--svg-color--fedcab, #FEDCAB);
}

.sy5ga3v_w {
  d: path("M22.502 13.794c-3.006.265-10.098 3.63-12.393 5.643c-.468.411.703.702 1.309.964c.3.13.35.587.395.724c.133.413.5.75 1 .75s.992-.542.992-.836c0-.202-.094-.56 1.039-.638s2.008-.129 5.969-.438c3.96-.309 2.073-3.546 1.69-6.169");
}

.tbsziibgm {
  stop-color: var(--svg-color--ffe0a6, #FFE0A6);
}

.tmy9x9yhg {
  d: path("M22.222 22.63h-11.97a.863.863 0 0 1-.86-.868v-1.501l13.68-1.059v2.56a.85.85 0 0 1-.85.867");
}

.tp9qrnbeg {
  stop-color: var(--svg-color--f9c994, #F9C994);
}

.tuintsbtg {
  stop-color: var(--svg-color--fff5d4, #FFF5D4);
}

.tyxtlj-gn {
  stop-color: var(--svg-color--fab88d, #FAB88D);
}

.ujtnbqbex {
  stop-color: var(--svg-color--ffe0a8, #FFE0A8);
}

.v3h8dvbst {
  stop-color: var(--svg-color--f8ba81, #F8BA81);
}

.vjgsribzq {
  d: path("M14.802 18.083h-3.51v2.026s.44-.07.65.182c.11.13.09.453.09.453c0 .575.46 1.029 1.02 1.029s1.02-.464 1.02-1.029c0 0-.01-.403.11-.604c.15-.263.43-.273.43-.273z");
}

.vu5nfsqka {
  stop-color: var(--svg-color--eaa36e, #EAA36E);
}

.wdkeu2b4g {
  stop-color: var(--svg-color--fbc49e, #FBC49E);
  stop-opacity: 0;
}

.wnbwqsbcb {
  stop-color: var(--svg-color--ca7d95, #CA7D95);
}

.xeoh-uoct {
  stop-color: var(--svg-color--e0bb89, #E0BB89);
  stop-opacity: 0;
}

.xg1__jbog {
  stop-color: var(--svg-color--be6d82, #BE6D82);
}

.xspqbhqhs {
  stop-color: var(--svg-color--ffdea3, #FFDEA3);
}

.y3iv3o0sd {
  stop-color: var(--svg-color--ffe7b1, #FFE7B1);
  stop-opacity: 0;
}

.ytx-8cb1b {
  stop-color: var(--svg-color--e7b286, #E7B286);
}

.zmhyvgglu {
  d: path("M21.302 9.242c-1.51.126-11.44 1.008-11.44 1.008c-1.36.121-2.268 1.297-2.268 2.398c0 .797.406.993.406 1.47c0 .476-.406.608-.406.608l16.601-1.085s-.407-.266-.407-.871c0-.372.274-.504.274-1.223c0-1.274-1.25-2.43-2.76-2.305");
}

.zmsmh186p {
  stop-color: var(--svg-color--cc8953, #CC8953);
}

.zrwi8mbyq {
  stop-color: var(--svg-color--c97758, #C97758);
}

.zx27c-avk {
  stop-color: var(--svg-color--fdc59f, #FDC59F);
}

</style>
