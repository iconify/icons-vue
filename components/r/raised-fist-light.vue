<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#i93MTGS)"><path fill="url(#ioHAQUQ)" class="npysqirwv"/></g><path fill="url(#ie2Iq4B)" class="npysqirwv"/><path fill="url(#iy22sTb)" class="npysqirwv"/><g filter="url(#iZl4tje)"><rect fill="url(#iTgSIGd)" class="lj_83cc8f"/></g><g filter="url(#iGjM9xb)"><path class="nxpemhbhi"/></g><rect fill="url(#iTAiYzE)" class="urd8n0l1k"/><rect fill="url(#iaPpsZd)" class="urd8n0l1k"/><rect fill="url(#irSxHFb)" class="urd8n0l1k"/><rect fill="url(#iciHh4b)" class="urd8n0l1k"/><path fill="url(#ivLHo8b)" class="pmbdoiq2w"/><path fill="url(#i2G9IUe)" class="pmbdoiq2w"/><path fill="url(#i3jstye)" class="pmbdoiq2w"/><path fill="url(#ih6t5je)" class="pmbdoiq2w"/><path fill="url(#iAK67Ib)" class="pmbdoiq2w"/><rect class="fdj2c6beq"/><rect fill="url(#ixiFDad)" class="na6venb5y"/><rect fill="url(#iQ7dyvb)" class="na6venb5y"/><rect fill="url(#iGhq98b)" class="na6venb5y"/><rect fill="url(#iCNbSBQ)" class="na6venb5y"/><path fill="url(#iVES9Fd)" class="sju2h6bdt"/><path fill="url(#ipZtBtb)" class="sju2h6bdt"/><path fill="url(#iN5jUkd)" class="sju2h6bdt"/><path fill="url(#iJakBOc)" class="sju2h6bdt"/><path fill="url(#i6vL1Uc)" class="sju2h6bdt"/><path fill="url(#iZFdg3k)" class="fecqi6oco"/><path fill="url(#i7G6Rke)" class="fecqi6oco"/><path fill="url(#iP4DnYd)" class="fecqi6oco"/><path fill="url(#i28hF0b)" class="fecqi6oco"/><path fill="url(#i2AzTkd)" class="fecqi6oco"/><path fill="url(#iXE4v7B)" class="fecqi6oco"/><g filter="url(#i7D7L4o)"><path stroke="url(#iBtHkpd)" class="yqmci6bnk"/></g><defs><radialGradient id="ie2Iq4B" cx="0" cy="0" r="1" gradientTransform="matrix(0 13.0399 -20.6277 0 16.463 18.075)" gradientUnits="userSpaceOnUse"><stop offset=".657" class="feupohv5j"/><stop offset="1" class="m9shcub0p"/></radialGradient><radialGradient id="iy22sTb" cx="0" cy="0" r="1" gradientTransform="rotate(164.074 7.26 9.972)scale(13.9404 19.1941)" gradientUnits="userSpaceOnUse"><stop offset=".834" class="d3s1pbcgk"/><stop offset="1" class="w9vznvbzy"/></radialGradient><radialGradient id="iTAiYzE" cx="0" cy="0" r="1" gradientTransform="matrix(-3.83217 0 0 -8.73643 8.696 10.438)" gradientUnits="userSpaceOnUse"><stop class="bfut5bbsf"/><stop offset=".582" class="kd7ndgb6w"/><stop offset="1" class="m8zojnbjt"/></radialGradient><radialGradient id="iaPpsZd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.67954 0 0 -10.0187 10.126 10.126)" gradientUnits="userSpaceOnUse"><stop offset=".413" class="q1pklbbjk"/><stop offset="1" class="t8g3217lz"/></radialGradient><radialGradient id="irSxHFb" cx="0" cy="0" r="1" gradientTransform="matrix(1.22807 1.63545 -3.19277 2.39747 4.666 5.531)" gradientUnits="userSpaceOnUse"><stop class="ufnn19b7v"/><stop offset="1" class="xujtvx-rl"/></radialGradient><radialGradient id="iciHh4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 8.04945 -6.98425 0 7.348 7.064)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="c2k9je98i"/><stop offset="1" class="xw841hwrh"/></radialGradient><radialGradient id="ivLHo8b" cx="0" cy="0" r="1" gradientTransform="matrix(-3.83217 0 0 -10.0007 13.953 9.762)" gradientUnits="userSpaceOnUse"><stop class="z1p__59we"/><stop offset=".582" class="hjfyk089s"/><stop offset="1" class="qzkt2ibxe"/></radialGradient><radialGradient id="i2G9IUe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.32071 0 0 -9.01829 15.702 9.404)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="nosswebgn"/><stop offset="1" class="n-b_xc_zc"/></radialGradient><radialGradient id="i3jstye" cx="0" cy="0" r="1" gradientTransform="rotate(56.736 1.124 11.26)scale(2.23897 4.17494)" gradientUnits="userSpaceOnUse"><stop class="ufnn19b7v"/><stop offset="1" class="xujtvx-rl"/></radialGradient><radialGradient id="ih6t5je" cx="0" cy="0" r="1" gradientTransform="matrix(0 9.21429 -6.98425 0 12.605 5.9)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="c2k9je98i"/><stop offset="1" class="xw841hwrh"/></radialGradient><radialGradient id="iAK67Ib" cx="0" cy="0" r="1" gradientTransform="matrix(1.91245 2.04588 -2.5041 2.34079 9.792 3.188)" gradientUnits="userSpaceOnUse"><stop class="f-1cni8au"/><stop offset="1" class="cpnlx2bdb"/></radialGradient><radialGradient id="ixiFDad" cx="0" cy="0" r="1" gradientTransform="matrix(-4.541 0 0 -12.3464 26.574 8.128)" gradientUnits="userSpaceOnUse"><stop class="scjo-lbpq"/><stop offset=".582" class="e0-wihxvt"/><stop offset="1" class="jrsuqmz2m"/><stop offset="1" class="eh5sqzboi"/></radialGradient><radialGradient id="iQ7dyvb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.89577 0 0 -13.4868 29.189 8.77)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="vl2qxnb1v"/><stop offset="1" class="qyxgm1bls"/></radialGradient><radialGradient id="iGhq98b" cx="0" cy="0" r="1" gradientTransform="rotate(57.804 8.326 21.647)scale(2.30488 4.22527)" gradientUnits="userSpaceOnUse"><stop class="ufnn19b7v"/><stop offset="1" class="xujtvx-rl"/></radialGradient><radialGradient id="iCNbSBQ" cx="0" cy="0" r="1" gradientTransform="matrix(1.91245 2.1315 -2.59952 2.33239 22.078 2.072)" gradientUnits="userSpaceOnUse"><stop class="f-1cni8au"/><stop offset="1" class="cpnlx2bdb"/></radialGradient><radialGradient id="iVES9Fd" cx="0" cy="0" r="1" gradientTransform="matrix(-3.77598 0 0 -11.2824 19.917 9.354)" gradientUnits="userSpaceOnUse"><stop class="xubb47nuq"/><stop offset=".582" class="avz2mobff"/><stop offset="1" class="jrsuqmz2m"/></radialGradient><radialGradient id="ipZtBtb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.86797 0 0 -14.6041 22.824 9.192)" gradientUnits="userSpaceOnUse"><stop offset=".132" class="vl2qxnb1v"/><stop offset="1" class="qyxgm1bls"/></radialGradient><radialGradient id="iN5jUkd" cx="0" cy="0" r="1" gradientTransform="rotate(60.19 5.37 15.265)scale(2.43413 4.26884)" gradientUnits="userSpaceOnUse"><stop class="ufnn19b7v"/><stop offset="1" class="xujtvx-rl"/></radialGradient><radialGradient id="iJakBOc" cx="0" cy="0" r="1" gradientTransform="matrix(0 10.3952 -6.88184 0 18.589 4.997)" gradientUnits="userSpaceOnUse"><stop offset=".667" class="c2k9je98i"/><stop offset="1" class="xw841hwrh"/></radialGradient><radialGradient id="i6vL1Uc" cx="0" cy="0" r="1" gradientTransform="rotate(50.77 5.866 17.636)scale(2.97963 3.58139)" gradientUnits="userSpaceOnUse"><stop class="f-1cni8au"/><stop offset="1" class="cpnlx2bdb"/></radialGradient><radialGradient id="iZFdg3k" cx="0" cy="0" r="1" gradientTransform="matrix(-1.30518 5.45366 -11.83567 -2.83254 24.232 10.987)" gradientUnits="userSpaceOnUse"><stop class="egfjmqn-x"/><stop offset="1" class="z4t_hd8cz"/></radialGradient><radialGradient id="i7G6Rke" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.77179 -6.41638 0 20.3 17.548)" gradientUnits="userSpaceOnUse"><stop offset=".445" class="jawwspb7w"/><stop offset="1" class="kgg1_36pq"/></radialGradient><radialGradient id="iP4DnYd" cx="0" cy="0" r="1" gradientTransform="matrix(2.68404 -3.56818 5.7103 4.29537 23.793 21.525)" gradientUnits="userSpaceOnUse"><stop offset=".386" class="rj_42lbht"/><stop offset="1" class="k9v9o_bet"/></radialGradient><radialGradient id="i28hF0b" cx="0" cy="0" r="1" gradientTransform="matrix(3.74677 0 0 5.4251 14.703 13.267)" gradientUnits="userSpaceOnUse"><stop class="xe3membuy"/><stop offset="1" class="etfcrcbol"/></radialGradient><radialGradient id="i2AzTkd" cx="0" cy="0" r="1" gradientTransform="matrix(2.9832 -2.51707 2.60763 3.09052 16.634 16.72)" gradientUnits="userSpaceOnUse"><stop class="ntfthabgx"/><stop offset="1" class="rsoroc-dd"/></radialGradient><radialGradient id="iXE4v7B" cx="0" cy="0" r="1" gradientTransform="matrix(1.14015 -.98439 1.64762 1.90833 15.77 15.661)" gradientUnits="userSpaceOnUse"><stop class="qcze5vx6e"/><stop offset="1" class="mxk571bku"/></radialGradient><filter id="i93MTGS" width="25.02" height="20.828" x="3.953" y="9.479" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.862745 0 0 0 0 0.643137 0 0 0 0 0.572549 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_3176"/></filter><filter id="iZl4tje" width="18.678" height="12.194" x="7.743" y="9.903" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3176" stdDeviation="1.5"/></filter><filter id="iGjM9xb" width="24.653" height="14.935" x="3.674" y="3.065" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3176" stdDeviation="1"/></filter><filter id="i7D7L4o" width="12.76" height="8.553" x="17.929" y="9.808" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_3176" stdDeviation=".85"/></filter><linearGradient id="ioHAQUQ" x1="16.004" x2="29.818" y1="20.604" y2="20.604" gradientUnits="userSpaceOnUse"><stop class="j0dj7tbzh"/><stop offset="1" class="cp60lac7f"/></linearGradient><linearGradient id="iTgSIGd" x1="20.856" x2="9.034" y1="17.241" y2="21.196" gradientUnits="userSpaceOnUse"><stop class="i1ylugbwm"/><stop offset="1" class="z-e197bzy"/></linearGradient><linearGradient id="iBtHkpd" x1="20.629" x2="31.931" y1="12.671" y2="16.361" gradientUnits="userSpaceOnUse"><stop class="da09a-vmu"/><stop offset="1" class="ciy5vot7u"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raised-fist-light" /></template>
<style>
.avz2mobff {
  stop-color: var(--svg-color--f6c2a7, #F6C2A7);
}

.bfut5bbsf {
  stop-color: var(--svg-color--f8c7b2, #F8C7B2);
}

.c2k9je98i {
  stop-color: var(--svg-color--c38586, #C38586);
  stop-opacity: 0;
}

.ciy5vot7u {
  stop-color: var(--svg-color--ffddc2, #FFDDC2);
  stop-opacity: 0;
}

.cp60lac7f {
  stop-color: var(--svg-color--f5c1b2, #F5C1B2);
}

.cpnlx2bdb {
  stop-color: var(--svg-color--d2a68b, #D2A68B);
  stop-opacity: 0;
}

.d3s1pbcgk {
  stop-color: var(--svg-color--ecb09b, #ECB09B);
  stop-opacity: 0;
}

.da09a-vmu {
  stop-color: var(--svg-color--ffddc2, #FFDDC2);
}

.e0-wihxvt {
  stop-color: var(--svg-color--f7bb9d, #F7BB9D);
}

.egfjmqn-x {
  stop-color: var(--svg-color--ffdaba, #FFDABA);
}

.eh5sqzboi {
  stop-color: var(--svg-color--f0a47d, #F0A47D);
}

.etfcrcbol {
  stop-color: var(--svg-color--dca892, #DCA892);
  stop-opacity: 0;
}

.f-1cni8au {
  stop-color: var(--svg-color--d2a68b, #D2A68B);
}

.fdj2c6beq {
  width: 6.79px;
  height: 11.898px;
  x: 21.496px;
  y: 2.599px;
  fill: var(--svg-color--7dde5b, #7DDE5B);
  fill-opacity: var(--svg-fill-opacity--0-55, 0.55);
  rx: 3.395px;
}

.fecqi6oco {
  d: path("M18.802 9.797c-1.965 0-3.559 1.507-3.559 3.365s1.594 3.365 3.56 3.365h2.601c1.168 0 2.115.896 2.115 2v2.999h.2c3.464 0 5.254-3.022 5.254-5.766c0-3.293-2.823-5.963-6.306-5.963z");
}

.feupohv5j {
  stop-color: var(--svg-color--b67995, #B67995);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.hjfyk089s {
  stop-color: var(--svg-color--efbda3, #EFBDA3);
}

.i1ylugbwm {
  stop-color: var(--svg-color--af7068, #AF7068);
}

.j0dj7tbzh {
  stop-color: var(--svg-color--dda89a, #DDA89A);
}

.jawwspb7w {
  stop-color: var(--svg-color--bd8088, #BD8088);
}

.jrsuqmz2m {
  stop-color: var(--svg-color--dca486, #DCA486);
}

.k9v9o_bet {
  stop-color: var(--svg-color--ebb7a8, #EBB7A8);
  stop-opacity: 0;
}

.kd7ndgb6w {
  stop-color: var(--svg-color--e8b69e, #E8B69E);
}

.kgg1_36pq {
  stop-color: var(--svg-color--bd8088, #BD8088);
  stop-opacity: 0;
}

.lj_83cc8f {
  width: 12.678px;
  height: 6.195px;
  x: 10.743px;
  y: 12.903px;
  rx: 3.097px;
}

.m8zojnbjt {
  stop-color: var(--svg-color--e2ad92, #E2AD92);
}

.m9shcub0p {
  stop-color: var(--svg-color--b67995, #B67995);
}

.mxk571bku {
  stop-color: var(--svg-color--d89d90, #D89D90);
  stop-opacity: 0;
}

.n-b_xc_zc {
  stop-color: var(--svg-color--d39a76, #D39A76);
  stop-opacity: 0;
}

.na6venb5y {
  width: 6.79px;
  height: 11.898px;
  x: 21.496px;
  y: 2.599px;
  rx: 3.395px;
}

.nosswebgn {
  stop-color: var(--svg-color--d39a76, #D39A76);
}

.npysqirwv {
  d: path("M28.286 9.479H3.953v9.328c0 6.351 5.149 11.5 11.5 11.5h1.333c2.153 0 4.168-.592 5.89-1.621l.005.018c2.518-1.454 5.089-4.099 5.904-7.358c.831-3.325.134-5.707-.3-6.552z");
}

.ntfthabgx {
  stop-color: var(--svg-color--c78c90, #C78C90);
}

.nxpemhbhi {
  fill: var(--svg-color--9c5a53, #9C5A53);
  d: path("M15.487 14.283c-.504.868-1.422 1.472-2.47 1.472c-.93 0-1.756-.314-2.283-.987a2.882 2.882 0 0 1-5.06-1.886v-2.704a2.882 2.882 0 0 1 4.61-2.306c.383-1.244 1.462-1.81 2.733-1.81c.936 0 1.768.447 2.294 1.138c.26-1.272 1.408-2.135 2.785-2.135A2.84 2.84 0 0 1 20.77 6.95a2.883 2.883 0 0 1 5.556 1.074v4.335a2.882 2.882 0 0 1-5.44 1.327a2.84 2.84 0 0 1-5.399.598");
}

.pmbdoiq2w {
  d: path("M9.21 7.09c0-2.35 1.52-3.396 3.395-3.396A3.395 3.395 0 0 1 16 7.09v4.509c0 1.875-1.52 3.516-3.395 3.516S9.21 14.029 9.21 11.598z");
}

.q1pklbbjk {
  stop-color: var(--svg-color--d1a083, #D1A083);
}

.qcze5vx6e {
  stop-color: var(--svg-color--d89d90, #D89D90);
}

.qyxgm1bls {
  stop-color: var(--svg-color--e8ac88, #E8AC88);
  stop-opacity: 0;
}

.qzkt2ibxe {
  stop-color: var(--svg-color--d69f88, #D69F88);
}

.rj_42lbht {
  stop-color: var(--svg-color--ebb7a8, #EBB7A8);
}

.rsoroc-dd {
  stop-color: var(--svg-color--c78c90, #C78C90);
  stop-opacity: 0;
}

.scjo-lbpq {
  stop-color: var(--svg-color--ffe8ca, #FFE8CA);
}

.sju2h6bdt {
  d: path("M15.243 5.675c0-1.847 1.498-3.166 3.346-3.166a3.345 3.345 0 0 1 3.345 3.346v6.192a3.345 3.345 0 0 1-6.69 0z");
}

.t8g3217lz {
  stop-color: var(--svg-color--d1a083, #D1A083);
  stop-opacity: 0;
}

.ufnn19b7v {
  stop-color: var(--svg-color--d7ab93, #D7AB93);
}

.urd8n0l1k {
  width: 6.79px;
  height: 9.976px;
  x: 3.953px;
  y: 5.138px;
  rx: 3.395px;
}

.vl2qxnb1v {
  stop-color: var(--svg-color--e8ac88, #E8AC88);
}

.w9vznvbzy {
  stop-color: var(--svg-color--ecb09b, #ECB09B);
}

.xe3membuy {
  stop-color: var(--svg-color--dca892, #DCA892);
}

.xubb47nuq {
  stop-color: var(--svg-color--ffe5c7, #FFE5C7);
}

.xujtvx-rl {
  stop-color: var(--svg-color--d7ab93, #D7AB93);
  stop-opacity: 0;
}

.xw841hwrh {
  stop-color: var(--svg-color--c38586, #C38586);
}

.yqmci6bnk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20.629 12.519h2.14c3.187-.132 4.706 1.01 5.22 3.142");
}

.z-e197bzy {
  stop-color: var(--svg-color--af7068, #AF7068);
  stop-opacity: 0;
}

.z1p__59we {
  stop-color: var(--svg-color--ffd6ba, #FFD6BA);
}

.z4t_hd8cz {
  stop-color: var(--svg-color--edb8a9, #EDB8A9);
}

</style>
