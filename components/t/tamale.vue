<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iJxF6Ob)" class="eig77jbcm"/><path fill="url(#iOx0NNb)" class="eig77jbcm"/><path fill="url(#ifgCiGd)" class="jgrbqebxa"/><path fill="url(#iC6JxQd)" class="l0ljahbhp"/><path fill="url(#iP2OFeb)" class="o170ijbze"/><path fill="url(#iGvpkNe)" class="necv2_48b"/><path fill="url(#iJZl1Fd)" class="necv2_48b"/><path fill="url(#iLIqvac)" class="necv2_48b"/><path fill="url(#iGSyWyc)" class="necv2_48b"/><path fill="url(#iSxpOEe)" clip-rule="evenodd" class="bgq6aj_4s"/><path fill="url(#iPOiyqe)" clip-rule="evenodd" class="b0mry9tfx"/><path fill="url(#iBFTnyb)" clip-rule="evenodd" class="a-aa7nbsd"/><g filter="url(#i2ANBWc)"><path fill="url(#iTUBPvd)" class="lba83p9rh"/></g><path fill="url(#iXJgpxd)" class="z0-iiusxq"/><path fill="url(#iXPFaTb)" class="plkbk5b7r"/><g filter="url(#iJvDrcd)"><path class="dhuu8_b0b"/></g><path class="ph_1mabbq"/><path fill="url(#ikhTWFG)" class="zpe3u2bhn"/><path fill="url(#icu34gc)" class="zpe3u2bhn"/><path fill="url(#ioctqOc)" class="zpe3u2bhn"/><path fill="url(#iWhZ1od)" class="zpe3u2bhn"/><path fill="url(#i9Csa0d)" class="zpe3u2bhn"/><path fill="url(#iBNgRob)" class="zpe3u2bhn"/><path fill="url(#ip5bjMe)" class="z0q7_o35m"/><path class="plyhzac2k"/><path class="ysggr_bxn"/><path fill="url(#i3Y32pe)" class="kxnxcebwv"/><path fill="url(#iF2h4tc)" class="kxnxcebwv"/><path fill="url(#ibpRfBb)" class="kxnxcebwv"/><g filter="url(#ix295Md)"><path class="pfp91fbzi"/></g><path class="sc4cvmb3p"/><path fill="url(#i2zYLgd)" class="al7vm2bwt"/><path fill="url(#idExIIe)" class="al7vm2bwt"/><path fill="url(#iH5Wgqc)" class="al7vm2bwt"/><defs><radialGradient id="iOx0NNb" cx="0" cy="0" r="1" gradientTransform="rotate(55.647 4.436 17.155)scale(5.14795)" gradientUnits="userSpaceOnUse"><stop class="vwo-mqbha"/><stop offset="1" class="bv18juxno"/></radialGradient><radialGradient id="iJZl1Fd" cx="0" cy="0" r="1" gradientTransform="matrix(4.84174 7.5625 -5.29362 3.38914 15.25 26.813)" gradientUnits="userSpaceOnUse"><stop class="hqtatmbff"/><stop offset="1" class="fz3hhke7j"/></radialGradient><radialGradient id="iLIqvac" cx="0" cy="0" r="1" gradientTransform="matrix(8.6875 1.0625 -.32731 2.67628 18.563 30.438)" gradientUnits="userSpaceOnUse"><stop class="qc9bc0b9d"/><stop offset="1" class="dgjfklbjc"/></radialGradient><radialGradient id="iGSyWyc" cx="0" cy="0" r="1" gradientTransform="rotate(111.125 8.775 16.951)scale(8.84436 9.43161)" gradientUnits="userSpaceOnUse"><stop class="bmg61vi_y"/><stop offset="1" class="nsd1debzl"/></radialGradient><radialGradient id="ikhTWFG" cx="0" cy="0" r="1" gradientTransform="matrix(0 11.7187 -1.09521 0 18.594 20.188)" gradientUnits="userSpaceOnUse"><stop class="jtsdatbij"/><stop offset="1" class="c0e-deccw"/></radialGradient><radialGradient id="icu34gc" cx="0" cy="0" r="1" gradientTransform="rotate(-178.963 11.1 9.307)scale(6.90738 1.75426)" gradientUnits="userSpaceOnUse"><stop class="qlwn_9byo"/><stop offset="1" class="hf-nf8b3h"/></radialGradient><radialGradient id="ioctqOc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.90625 0 0 -1.15625 22.531 17.344)" gradientUnits="userSpaceOnUse"><stop class="jtsdatbij"/><stop offset="1" class="c0e-deccw"/></radialGradient><radialGradient id="iWhZ1od" cx="0" cy="0" r="1" gradientTransform="rotate(126.342 4.395 13.172)scale(2.71574)" gradientUnits="userSpaceOnUse"><stop class="syw780osw"/><stop offset="1" class="swlfs_e5j"/></radialGradient><radialGradient id="i9Csa0d" cx="0" cy="0" r="1" gradientTransform="rotate(119.055 6.567 15.633)scale(.96521)" gradientUnits="userSpaceOnUse"><stop class="espza03mm"/><stop offset="1" class="s-r-xtbzf"/></radialGradient><radialGradient id="iBNgRob" cx="0" cy="0" r="1" gradientTransform="matrix(3.695 0 0 .6457 16.813 24.012)" gradientUnits="userSpaceOnUse"><stop class="bnofscb8l"/><stop offset="1" class="v0t8b4b7b"/></radialGradient><radialGradient id="i3Y32pe" cx="0" cy="0" r="1" gradientTransform="rotate(49.129 1.019 16.902)scale(2.82653 2.59386)" gradientUnits="userSpaceOnUse"><stop class="qkcrwomld"/><stop offset="1" class="sfi-skqqe"/></radialGradient><radialGradient id="iF2h4tc" cx="0" cy="0" r="1" gradientTransform="matrix(2.10343 2.05282 -1.574 1.61281 9.47 8.779)" gradientUnits="userSpaceOnUse"><stop class="qkcrwomld"/><stop offset="1" class="sfi-skqqe"/></radialGradient><radialGradient id="ibpRfBb" cx="0" cy="0" r="1" gradientTransform="matrix(2.0309 1.95624 -1.4705 1.52662 5.989 12.28)" gradientUnits="userSpaceOnUse"><stop class="qkcrwomld"/><stop offset="1" class="sfi-skqqe"/></radialGradient><radialGradient id="i2zYLgd" cx="0" cy="0" r="1" gradientTransform="matrix(1.59375 1.84375 -1.69172 1.46233 13.313 6.375)" gradientUnits="userSpaceOnUse"><stop class="qkcrwomld"/><stop offset="1" class="sfi-skqqe"/></radialGradient><radialGradient id="idExIIe" cx="0" cy="0" r="1" gradientTransform="matrix(1.8125 1.77082 -1.35782 1.38977 10.156 9.573)" gradientUnits="userSpaceOnUse"><stop class="qkcrwomld"/><stop offset="1" class="sfi-skqqe"/></radialGradient><radialGradient id="iH5Wgqc" cx="0" cy="0" r="1" gradientTransform="matrix(1.75 1.6875 -1.26853 1.31551 7.156 12.594)" gradientUnits="userSpaceOnUse"><stop class="qkcrwomld"/><stop offset="1" class="sfi-skqqe"/></radialGradient><linearGradient id="iJxF6Ob" x1="18.125" x2="7.844" y1="7.5" y2="17.781" gradientUnits="userSpaceOnUse"><stop class="gf9772b9k"/><stop offset=".365" class="kv0boctso"/><stop offset=".657" class="ikzs_bb0t"/><stop offset="1" class="ov83gbc7x"/></linearGradient><linearGradient id="ifgCiGd" x1="9.5" x2="12.125" y1="14.938" y2="17.688" gradientUnits="userSpaceOnUse"><stop class="vm1-qxbpw"/><stop offset="1" class="r6e6vtgbc"/></linearGradient><linearGradient id="iC6JxQd" x1="12.313" x2="14.188" y1="12.375" y2="14.188" gradientUnits="userSpaceOnUse"><stop class="f040o76il"/><stop offset="1" class="ha422_b7r"/></linearGradient><linearGradient id="iP2OFeb" x1="17.438" x2="15.656" y1="12.125" y2="8.813" gradientUnits="userSpaceOnUse"><stop class="n3-gtqbbh"/><stop offset="1" class="vhj80z11k"/></linearGradient><linearGradient id="iGvpkNe" x1="14.313" x2="26.063" y1="13.813" y2="25.563" gradientUnits="userSpaceOnUse"><stop class="g5ductsmf"/><stop offset=".146" class="yey3afpok"/><stop offset=".316" class="xsh3nbw2i"/><stop offset=".678" class="c6-m7wpzn"/><stop offset=".952" class="w_yqusins"/><stop offset="1" class="vu7d7dbce"/></linearGradient><linearGradient id="iSxpOEe" x1="12.063" x2="23" y1="18" y2="28.688" gradientUnits="userSpaceOnUse"><stop class="t-b49b_hv"/><stop offset=".131" class="qo5ispbqc"/><stop offset=".412" class="i887_ymff"/><stop offset=".693" class="t1582obpp"/><stop offset=".925" class="q7kg38bqv"/><stop offset="1" class="zvv865g2l"/></linearGradient><linearGradient id="iPOiyqe" x1="14.5" x2="26.207" y1="14.5" y2="25.813" gradientUnits="userSpaceOnUse"><stop class="l9aa6cc7i"/><stop offset=".177" class="c3kj4k6is"/><stop offset=".413" class="d4bixbblv"/><stop offset=".609" class="ifk8w9b8d"/><stop offset=".934" class="x67sgdbfb"/><stop offset="1" class="vfxx8ibbb"/></linearGradient><linearGradient id="iBFTnyb" x1="17.625" x2="28.563" y1="11.727" y2="22.875" gradientUnits="userSpaceOnUse"><stop class="jned40ltp"/><stop offset=".736" class="eo_s4b-tz"/><stop offset=".951" class="b6l3u5bmy"/><stop offset="1" class="b7ahy7dol"/></linearGradient><linearGradient id="iTUBPvd" x1="21.75" x2="11.594" y1="12" y2="22.188" gradientUnits="userSpaceOnUse"><stop class="en4t4v8bg"/><stop offset="1" class="ztwekymcg"/></linearGradient><linearGradient id="iXJgpxd" x1="20.656" x2="22.313" y1="13.734" y2="15.406" gradientUnits="userSpaceOnUse"><stop offset=".058" class="fl8y1mblg"/><stop offset=".193" class="p0v9nkb8p"/><stop offset=".364" class="c1oja26oq"/><stop offset=".666" class="lfq-6jbps"/><stop offset=".975" class="o_ox4zblj"/></linearGradient><linearGradient id="iXPFaTb" x1="13.75" x2="15.422" y1="20.844" y2="22.578" gradientUnits="userSpaceOnUse"><stop class="ny-9pid5x"/><stop offset=".098" class="pk7ax14rz"/><stop offset=".519" class="epe1zobdj"/><stop offset=".917" class="jvoivyowm"/></linearGradient><linearGradient id="ip5bjMe" x1="5.438" x2="12.125" y1="4.938" y2="11.875" gradientUnits="userSpaceOnUse"><stop class="uytr56imj"/><stop offset="1" class="nqyk4rvge"/></linearGradient><filter id="i2ANBWc" width="18.398" height="18.358" x="8.676" y="8.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33464" stdDeviation="1.5"/></filter><filter id="iJvDrcd" width="11.01" height="11.01" x="14.587" y="15.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33464" stdDeviation="1"/></filter><filter id="ix295Md" width="11.259" height="10.972" x="3.398" y="4.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33464" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:tamale" /></template>
<style>
.a-aa7nbsd {
  fill-rule: evenodd;
  d: path("m28.318 23.378l.71-.71l-10.94-10.94l-.988.432z");
}

.al7vm2bwt {
  d: path("M4.872 13.933c1.55.97 3.61.79 4.96-.56l3.55-3.55a4.004 4.004 0 0 0 .56-4.96c-.86-.45-1.94-.32-2.65.4c-.6.6-.79 1.44-.58 2.2c.04.14-.09.27-.23.23c-.76-.21-1.61-.02-2.2.58c-.6.6-.79 1.44-.58 2.2c.04.14-.09.26-.23.23c-.75-.21-1.6-.02-2.2.58c-.72.71-.85 1.79-.4 2.65");
}

.b0mry9tfx {
  fill-rule: evenodd;
  d: path("M26.208 25.488L14.305 13.585q-.392.317-.714.706l11.907 11.907l.334-.335z");
}

.b6l3u5bmy {
  stop-color: var(--svg-color--f5b937, #F5B937);
}

.b7ahy7dol {
  stop-color: var(--svg-color--dca656, #DCA656);
}

.bgq6aj_4s {
  fill-rule: evenodd;
  d: path("M23.368 28.328L12.141 17.102l-.43.98l10.95 10.95h.001z");
}

.bmg61vi_y {
  stop-color: var(--svg-color--fff94d, #FFF94D);
}

.bnofscb8l {
  stop-color: var(--svg-color--d39b7d, #D39B7D);
}

.bv18juxno {
  stop-color: var(--svg-color--f9da4a, #F9DA4A);
  stop-opacity: 0;
}

.c0e-deccw {
  stop-color: var(--svg-color--ffebb3, #FFEBB3);
  stop-opacity: 0;
}

.c1oja26oq {
  stop-color: var(--svg-color--fff0ae, #FFF0AE);
}

.c3kj4k6is {
  stop-color: var(--svg-color--e2b131, #E2B131);
}

.c6-m7wpzn {
  stop-color: var(--svg-color--ffda4a, #FFDA4A);
}

.d4bixbblv {
  stop-color: var(--svg-color--e5a529, #E5A529);
}

.dgjfklbjc {
  stop-color: var(--svg-color--c3826a, #C3826A);
  stop-opacity: 0;
}

.dhuu8_b0b {
  fill: var(--svg-color--d39976, #D39976);
  d: path("M22.597 17.288h-5c-.28 0-.53.11-.71.3c-.18.18-.3.43-.3.71v5c0 .55.45 1 1 1s1-.45 1-1v-4.01h4.01c.55 0 1-.45 1-1c0-.56-.45-1-1-1");
}

.eig77jbcm {
  d: path("m27.903 21.243l-6.65 6.65c-1.1 1.1-2.88 1.1-3.98 0l-13.81-13.81l10.63-10.63l13.81 13.82a2.8 2.8 0 0 1 0 3.97");
}

.en4t4v8bg {
  stop-color: var(--svg-color--f4cf2e, #F4CF2E);
}

.eo_s4b-tz {
  stop-color: var(--svg-color--ffce4c, #FFCE4C);
}

.epe1zobdj {
  stop-color: var(--svg-color--e4b49b, #E4B49B);
}

.espza03mm {
  stop-color: var(--svg-color--fea, #FEA);
}

.f040o76il {
  stop-color: var(--svg-color--d9a63f, #D9A63F);
}

.fl8y1mblg {
  stop-color: var(--svg-color--e1b971, #E1B971);
}

.ft5dv1b6b {
  fill: none;
}

.fz3hhke7j {
  stop-color: var(--svg-color--d09942, #D09942);
  stop-opacity: 0;
}

.g5ductsmf {
  stop-color: var(--svg-color--e4cb21, #E4CB21);
}

.gf9772b9k {
  stop-color: var(--svg-color--f9d44b, #F9D44B);
}

.ha422_b7r {
  stop-color: var(--svg-color--d99928, #D99928);
}

.hf-nf8b3h {
  stop-color: var(--svg-color--e6b2a6, #E6B2A6);
  stop-opacity: 0;
}

.hqtatmbff {
  stop-color: var(--svg-color--d09943, #D09943);
}

.i887_ymff {
  stop-color: var(--svg-color--d69436, #D69436);
}

.ifk8w9b8d {
  stop-color: var(--svg-color--fec34a, #FEC34A);
}

.ikzs_bb0t {
  stop-color: var(--svg-color--deab43, #DEAB43);
}

.jgrbqebxa {
  d: path("m23.373 28.333l-13.86-13.86l-.7.71l13.85 13.85z");
}

.jned40ltp {
  stop-color: var(--svg-color--e8ba20, #E8BA20);
}

.jtsdatbij {
  stop-color: var(--svg-color--ffe9b3, #FFE9B3);
}

.jvoivyowm {
  stop-color: var(--svg-color--d9a39f, #D9A39F);
}

.kv0boctso {
  stop-color: var(--svg-color--e5b142, #E5B142);
}

.kxnxcebwv {
  d: path("M11.223 3.043c-.59-.1-1.2.08-1.63.5l-.01.01c-.6.6-.79 1.45-.58 2.21c.04.13-.09.26-.23.22c-.76-.21-1.61-.02-2.2.58c-.6.6-.79 1.44-.58 2.2c.04.14-.09.27-.22.23c-.76-.21-1.61-.02-2.2.58l-.01.01c-.42.43-.6 1.04-.5 1.63c.13.79.5 1.55 1.12 2.16a4.005 4.005 0 0 0 5.51.14l.08-.63c-.03-.07-.05-.15-.09-.22c.07.03.14.06.22.09l2.88-2.88c-.03-.07-.05-.15-.09-.22c.07.03.14.06.22.09l.77-.24a4.004 4.004 0 0 0-.28-5.35c-.63-.6-1.39-.97-2.18-1.11");
}

.l0ljahbhp {
  d: path("m26.213 25.493l-13.86-13.86l-.71.71l13.86 13.86z");
}

.l9aa6cc7i {
  stop-color: var(--svg-color--d9ad24, #D9AD24);
}

.lba83p9rh {
  d: path("M23.781 13.39L13.38 23.755a.996.996 0 1 1-1.41-1.41l10.4-10.365a.996.996 0 1 1 1.41 1.41");
}

.lfq-6jbps {
  stop-color: var(--svg-color--fff1ae, #FFF1AE);
}

.n3-gtqbbh {
  stop-color: var(--svg-color--f2b644, #F2B644);
}

.necv2_48b {
  d: path("M30.003 19.613c0-1.01-.4-1.98-1.12-2.69l-6.46-6.43a.95.95 0 0 0-1.06-.2l-5.89 2.58a5.12 5.12 0 0 0-2.63 2.63l-2.58 5.89c-.16.36-.08.78.2 1.06l6.34 6.41c.71.72 1.69 1.13 2.7 1.13h.13c1.22 0 2.24-.2 2.89-.82l3.31-3.31l3.33-3.33c.81-.81.84-1.89.84-2.92");
}

.nqyk4rvge {
  stop-color: var(--svg-color--f5d7b0, #F5D7B0);
}

.nsd1debzl {
  stop-color: var(--svg-color--fff94d, #FFF94D);
  stop-opacity: 0;
}

.ny-9pid5x {
  stop-color: var(--svg-color--dcb27f, #DCB27F);
}

.o_ox4zblj {
  stop-color: var(--svg-color--ffd595, #FFD595);
}

.o170ijbze {
  d: path("m29.033 22.673l-13.86-13.86l-.71.71l13.86 13.86z");
}

.ov83gbc7x {
  stop-color: var(--svg-color--b68749, #B68749);
}

.p0v9nkb8p {
  stop-color: var(--svg-color--ffd793, #FFD793);
}

.pfp91fbzi {
  fill: var(--svg-color--442622, #442622);
  d: path("M4.64 13.406c1.404.934 3.22.896 4.499-.314l3.363-3.18a3.69 3.69 0 0 0 .644-4.557a2.08 2.08 0 0 0-2.452.3a2.07 2.07 0 0 0-.592 2.013a.172.172 0 0 1-.218.206a2.07 2.07 0 0 0-2.042.478a2.07 2.07 0 0 0-.592 2.012c.034.13-.09.238-.218.206a2.08 2.08 0 0 0-2.042.478c-.682.636-.742 1.554-.35 2.358");
}

.ph_1mabbq {
  fill: var(--svg-color--deb089, #DEB089);
  d: path("M23.013 17.003h-5c-.28 0-.53.11-.71.3c-.18.18-.3.43-.3.71v5c0 .55.45 1 1 1s1-.45 1-1v-4.01h4.01c.55 0 1-.45 1-1c0-.56-.45-1-1-1");
}

.pk7ax14rz {
  stop-color: var(--svg-color--e1b391, #E1B391);
}

.plkbk5b7r {
  d: path("m18.708 18.698l-6.015 6.014a.996.996 0 1 1-1.41-1.41l6.015-6.014z");
}

.plyhzac2k {
  fill: var(--svg-color--d3b731, #D3B731);
  d: path("m13.383 9.823l-3.55 3.55a4.01 4.01 0 0 1-5.66 0a4.01 4.01 0 0 1 0-5.66l3.55-3.55a4.01 4.01 0 0 1 5.66 0a4.01 4.01 0 0 1 0 5.66");
}

.q7kg38bqv {
  stop-color: var(--svg-color--e8aa43, #E8AA43);
}

.qc9bc0b9d {
  stop-color: var(--svg-color--c2816e, #C2816E);
}

.qkcrwomld {
  stop-color: var(--svg-color--744a47, #744A47);
}

.qlwn_9byo {
  stop-color: var(--svg-color--d59e9b, #D59E9B);
}

.qo5ispbqc {
  stop-color: var(--svg-color--d5a62b, #D5A62B);
}

.r6e6vtgbc {
  stop-color: var(--svg-color--c88b2e, #C88B2E);
}

.s-r-xtbzf {
  stop-color: var(--svg-color--fff2af, #FFF2AF);
  stop-opacity: 0;
}

.sc4cvmb3p {
  fill: var(--svg-color--582f32, #582F32);
  d: path("M4.872 13.933c1.55.97 3.61.79 4.96-.56l3.55-3.55a4.004 4.004 0 0 0 .56-4.96c-.86-.45-1.94-.32-2.65.4c-.6.6-.79 1.44-.58 2.2c.04.14-.09.27-.23.23c-.76-.21-1.61-.02-2.2.58c-.6.6-.79 1.44-.58 2.2c.04.14-.09.26-.23.23c-.75-.21-1.6-.02-2.2.58c-.72.71-.85 1.79-.4 2.65");
}

.sfi-skqqe {
  stop-color: var(--svg-color--744a48, #744A48);
  stop-opacity: 0;
}

.swlfs_e5j {
  stop-color: var(--svg-color--ffd99b, #FFD99B);
  stop-opacity: 0;
}

.syw780osw {
  stop-color: var(--svg-color--ffda9b, #FFDA9B);
}

.t-b49b_hv {
  stop-color: var(--svg-color--cfa229, #CFA229);
}

.t1582obpp {
  stop-color: var(--svg-color--efb348, #EFB348);
}

.uytr56imj {
  stop-color: var(--svg-color--f2d4a9, #F2D4A9);
}

.v0t8b4b7b {
  stop-color: var(--svg-color--d8a2a5, #D8A2A5);
  stop-opacity: 0;
}

.vfxx8ibbb {
  stop-color: var(--svg-color--d89f54, #D89F54);
}

.vhj80z11k {
  stop-color: var(--svg-color--e5ba48, #E5BA48);
}

.vm1-qxbpw {
  stop-color: var(--svg-color--c89c38, #C89C38);
}

.vu7d7dbce {
  stop-color: var(--svg-color--e4af55, #E4AF55);
}

.vwo-mqbha {
  stop-color: var(--svg-color--f7d94b, #F7D94B);
}

.w_yqusins {
  stop-color: var(--svg-color--ffc83c, #FFC83C);
}

.x67sgdbfb {
  stop-color: var(--svg-color--f0b33d, #F0B33D);
}

.xsh3nbw2i {
  stop-color: var(--svg-color--ffd243, #FFD243);
}

.yey3afpok {
  stop-color: var(--svg-color--f0d82e, #F0D82E);
}

.ysggr_bxn {
  fill: var(--svg-color--5d3630, #5D3630);
  d: path("M11.223 3.043c-.59-.1-1.2.08-1.63.5l-.01.01c-.6.6-.79 1.45-.58 2.21c.04.13-.09.26-.23.22c-.76-.21-1.61-.02-2.2.58c-.6.6-.79 1.44-.58 2.2c.04.14-.09.27-.22.23c-.76-.21-1.61-.02-2.2.58l-.01.01c-.42.43-.6 1.04-.5 1.63c.13.79.5 1.55 1.12 2.16a4.005 4.005 0 0 0 5.51.14l.08-.63c-.03-.07-.05-.15-.09-.22c.07.03.14.06.22.09l2.88-2.88c-.03-.07-.05-.15-.09-.22c.07.03.14.06.22.09l.77-.24a4.004 4.004 0 0 0-.28-5.35c-.63-.6-1.39-.97-2.18-1.11");
}

.z0-iiusxq {
  d: path("m24.723 12.683l-12.03 12.03a.996.996 0 1 1-1.41-1.41l12.03-12.03a.996.996 0 1 1 1.41 1.41");
}

.z0q7_o35m {
  d: path("M10.533 14.083a5.003 5.003 0 0 1-7.07 0a5.003 5.003 0 0 1 0-7.07l3.55-3.55a5.003 5.003 0 0 1 7.07 0a5.003 5.003 0 0 1 0 7.07z");
}

.zpe3u2bhn {
  d: path("M23.013 17.003h-5c-.28 0-.53.11-.71.3c-.18.18-.3.43-.3.71v5c0 .55.45 1 1 1s1-.45 1-1v-4.01h4.01c.55 0 1-.45 1-1c0-.56-.45-1-1-1");
}

.ztwekymcg {
  stop-color: var(--svg-color--d6aa26, #D6AA26);
}

.zvv865g2l {
  stop-color: var(--svg-color--cc9261, #CC9261);
}

</style>
