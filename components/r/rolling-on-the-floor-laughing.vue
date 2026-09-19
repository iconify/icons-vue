<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><path id="ik2LsAe" class="je5f-i_to"/></defs><g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g clip-path="url(#iBHkmDe)"><path fill="url(#iMxH86k)" class="hx64oibex"/><path fill="url(#isxmjEc)" class="hx64oibex"/><path fill="url(#ieLWHVE)" class="hx64oibex"/><path fill="url(#ivMiwKc)" class="l2d_x_bzb"/><path fill="url(#iXNGHqS)" class="hx64oibex"/><path fill="url(#ihpaCwd)" class="hx64oibex"/><path fill="url(#iIVNNfd)" class="hx64oibex"/><path fill="url(#iswJOce)" class="hx64oibex"/></g><g clip-path="url(#iBHkmDe)"><g filter="url(#iyK9vDi)"><path fill="url(#ix3xbDe)" class="bzcatsbda"/><path fill="url(#ix3xbDe)" class="f1s566b_b"/></g><path fill="url(#iAKueac)" class="imzqttbsq"/><path fill="url(#iqi46mc)" class="eauon0e4g"/><g filter="url(#imDFVpb)"><path fill="url(#ievwTBc)" class="h_7nyp6mh"/><path fill="url(#ievwTBc)" class="cf9l8jbao"/></g><path fill="url(#iBOigky)" class="hpc59cccp"/><path fill="url(#iYszPqc)" class="hbhtvqnfg"/></g><path fill="url(#iVYB47c)" class="g69i3v35k"/><path fill="url(#itV1Toc)" class="zvwq35ksz"/><g clip-path="url(#iBHkmDe)"><path fill="url(#imYkruO)" clip-rule="evenodd" class="p9v-fycec"/><path fill="url(#iDHR4tr)" clip-rule="evenodd" class="zvu8xrm3z"/><path fill="url(#iPNukQe)" class="ose89bctk"/><path fill="url(#islMatd)" class="k7tei3ehw"/></g></g><defs><radialGradient id="iMxH86k" cx="0" cy="0" r="1" gradientTransform="rotate(87.839 6.634 11.392)scale(37.5033)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="isxmjEc" cx="0" cy="0" r="1" gradientTransform="rotate(86.878 6.596 11.548)scale(38.9487)" gradientUnits="userSpaceOnUse"><stop class="qvxe_pbez"/><stop offset=".475" class="cjd26qb7f"/><stop offset="1" class="h13dd1l8r"/></radialGradient><radialGradient id="ieLWHVE" cx="0" cy="0" r="1" gradientTransform="matrix(9.89952 14.84926 -19.01908 12.6794 13.525 13.525)" gradientUnits="userSpaceOnUse"><stop offset=".788" class="og2_-db3e"/><stop offset=".973" class="w5xp9scuu"/></radialGradient><radialGradient id="ivMiwKc" cx="0" cy="0" r="1" gradientTransform="rotate(90 1.414 14.586)scale(41.0122)" gradientUnits="userSpaceOnUse"><stop offset=".315" class="k05n1gbkm"/><stop offset="1"/></radialGradient><radialGradient id="iXNGHqS" cx="0" cy="0" r="1" gradientTransform="rotate(32.692 -20.129 36.835)scale(28.1469)" gradientUnits="userSpaceOnUse"><stop offset=".508" class="zgcpgx8ap"/><stop offset="1" class="fqgjm_v0b"/></radialGradient><radialGradient id="ihpaCwd" cx="0" cy="0" r="1" gradientTransform="matrix(13.08145 2.47486 -1.79391 9.48212 16.707 16)" gradientUnits="userSpaceOnUse"><stop class="g4z4xncfo"/><stop offset="1" class="k7y-44b1u"/></radialGradient><radialGradient id="iIVNNfd" cx="0" cy="0" r="1" gradientTransform="rotate(-35.134 32.776 -25.412)scale(11.6726)" gradientUnits="userSpaceOnUse"><stop class="c1buurbbt"/><stop offset=".9" class="mqe6vbive"/></radialGradient><radialGradient id="iswJOce" cx="0" cy="0" r="1" gradientTransform="rotate(-1.029 800.496 -903.298)scale(59.0529)" gradientUnits="userSpaceOnUse"><stop offset=".185" class="k05n1gbkm"/><stop offset="1" class="rw5c_lizo"/></radialGradient><radialGradient id="ix3xbDe" cx="0" cy="0" r="1" gradientTransform="matrix(3.18196 6.8943 -9.01085 4.15883 6.255 15.05)" gradientUnits="userSpaceOnUse"><stop class="vn4n3no1s"/><stop offset=".889" class="ixmaddcbc"/></radialGradient><radialGradient id="ievwTBc" cx="0" cy="0" r="1" gradientTransform="matrix(-13.35769 .232 -.30321 -17.45847 23.259 7.946)" gradientUnits="userSpaceOnUse"><stop class="kb93-db6z"/><stop offset=".802" class="z-xmlwmhd"/></radialGradient><radialGradient id="iVYB47c" cx="0" cy="0" r="1" gradientTransform="rotate(-135 18.842 8.012)scale(16.9706 33.9411)" gradientUnits="userSpaceOnUse"><stop offset=".051" class="h13dd1l8r"/><stop offset="1" class="di9ro-btr"/></radialGradient><radialGradient id="imYkruO" cx="0" cy="0" r="1" gradientTransform="matrix(1.06066 -4.5962 2.98353 .6885 9.99 26.96)" gradientUnits="userSpaceOnUse"><stop class="p4vnlcfhl"/><stop offset="1" class="cr309tbhd"/></radialGradient><radialGradient id="iDHR4tr" cx="0" cy="0" r="1" gradientTransform="matrix(5.3033 -1.06067 .6885 3.44252 23.071 9.636)" gradientUnits="userSpaceOnUse"><stop class="p4vnlcfhl"/><stop offset="1" class="cr309tbhd"/></radialGradient><radialGradient id="iPNukQe" cx="0" cy="0" r="1" gradientTransform="rotate(102.529 -3.585 14.34)scale(6.5192 2.96814)" gradientUnits="userSpaceOnUse"><stop class="ex5w2u-ri"/><stop offset="1" class="uospscb_d"/></radialGradient><radialGradient id="islMatd" cx="0" cy="0" r="1" gradientTransform="matrix(4.5962 .35355 -.16097 2.0926 23.778 7.515)" gradientUnits="userSpaceOnUse"><stop class="i97_rac7h"/><stop offset="1" class="yco627brm"/></radialGradient><linearGradient id="iAKueac" x1="11.27" x2="5.668" y1="18.937" y2="16.982" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iqi46mc" x1="7.513" x2="5.889" y1="17.611" y2="12.607" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iBOigky" x1="18.926" x2="16.971" y1="11.281" y2="5.679" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="iYszPqc" x1="17.601" x2="12.596" y1="7.524" y2="5.9" gradientUnits="userSpaceOnUse"><stop offset=".25" class="ccr58nbuz"/><stop offset=".406" class="gvfj_gdms"/><stop offset=".511" class="ccr58nbuz"/></linearGradient><linearGradient id="itV1Toc" x1="16" x2="17.061" y1="16" y2="17.061" gradientUnits="userSpaceOnUse"><stop class="nvahlubfz"/><stop offset="1" class="vc--wpv5i"/></linearGradient><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath><clipPath id="iBHkmDe"><use href="#ik2LsAe"/></clipPath><filter id="iyK9vDi" width="7.24" height="7.24" x="4.91" y="13.395" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_372" stdDeviation=".25"/></filter><filter id="imDFVpb" width="7.239" height="7.24" x="12.975" y="5.33" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_23_372" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rolling-on-the-floor-laughing" /></template>
<style>
.bzcatsbda {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M10.184 19.45a1 1 0 0 1-1.897-.632l.78-2.34l2.291-2.292a1 1 0 0 1 .24 1.022z");
}

.c1buurbbt {
  stop-color: var(--svg-color--ffa64b, #FFA64B);
}

.ccr58nbuz {
  stop-color: var(--svg-color--482641, #482641);
}

.cf9l8jbao {
  d: path("M14.94 6.514a1 1 0 0 1 1.898.632l-.78 2.34l-2.291 2.292a1 1 0 0 1-.24-1.022z");
}

.cjd26qb7f {
  stop-color: var(--svg-color--ffb02e, #FFB02E);
}

.cr309tbhd {
  stop-color: var(--svg-color--ff822d, #FF822D);
  stop-opacity: 0;
}

.di9ro-btr {
  stop-color: var(--svg-color--89029c, #89029C);
}

.eauon0e4g {
  d: path("M5.784 15.051a1 1 0 0 0 .633 1.898l2.34-.78l2.292-2.292a1 1 0 0 0-1.022-.24z");
}

.ex5w2u-ri {
  stop-color: var(--svg-color--508fff, #508FFF);
}

.f1s566b_b {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M6.094 15.36a1 1 0 0 0 .632 1.898l2.34-.78l2.292-2.292a1 1 0 0 0-1.021-.24z");
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

.g69i3v35k {
  d: path("M23.071 23.071c-7.071 7.071-14.142 0-14.142 0L23.071 8.929s7.071 7.071 0 14.142");
}

.gvfj_gdms {
  stop-color: var(--svg-color--503a4a, #503A4A);
}

.h_7nyp6mh {
  d: path("M19.03 10.604a1 1 0 0 0-.632-1.898l-2.34.78l-2.291 2.292a1 1 0 0 0 1.021.24z");
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hbhtvqnfg {
  d: path("M15.04 5.795a1 1 0 0 1 1.898.633l-.78 2.34l-2.292 2.292a1 1 0 0 1-.24-1.022z");
}

.hpc59cccp {
  d: path("M19.13 9.885a1 1 0 0 0-.632-1.897l-2.34.78l-2.292 2.292a1 1 0 0 0 1.022.24z");
}

.hx64oibex {
  d: path("M25.897 25.899c6.6-6.6 5.467-14.33 0-19.798S12.7-.499 6.1 6.101S.633 20.431 6.1 25.9s13.197 6.6 19.797 0");
}

.i97_rac7h {
  stop-color: var(--svg-color--5092ff, #5092FF);
}

.imzqttbsq {
  d: path("M9.875 19.141a1 1 0 0 1-1.898-.632l.78-2.34l2.292-2.292a1 1 0 0 1 .24 1.022z");
}

.ixmaddcbc {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
  stop-opacity: 0;
}

.je5f-i_to {
  fill: var(--svg-color--fff, #fff);
  d: path("M-6.627 16L16-6.627L38.627 16L16 38.627z");
}

.k05n1gbkm {
  stop-opacity: 0;
}

.k7tei3ehw {
  d: path("M22.54 10.874h4.766a2.121 2.121 0 0 0 0-4.243h-4.765a2.121 2.121 0 1 0 0 4.243");
}

.k7y-44b1u {
  stop-color: var(--svg-color--ffb847, #FFB847);
  stop-opacity: 0;
}

.kb93-db6z {
  stop-color: var(--svg-color--e9830a, #E9830A);
}

.l2d_x_bzb {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M25.897 25.899c6.6-6.6 5.467-14.33 0-19.798S12.7-.499 6.1 6.101S.633 20.431 6.1 25.9s13.197 6.6 19.797 0");
}

.mqe6vbive {
  stop-color: var(--svg-color--ffae46, #FFAE46);
  stop-opacity: 0;
}

.nvahlubfz {
  stop-color: var(--svg-color--eccdff, #ECCDFF);
}

.og2_-db3e {
  stop-color: var(--svg-color--f59639, #F59639);
  stop-opacity: 0;
}

.ose89bctk {
  d: path("M11.05 22.364v4.766a2.121 2.121 0 1 1-4.242 0v-4.766a2.121 2.121 0 1 1 4.242 0");
}

.p4vnlcfhl {
  stop-color: var(--svg-color--6d4534, #6D4534);
}

.p9v-fycec {
  fill-rule: evenodd;
  d: path("M10.741 29.214a2.12 2.12 0 0 0 1.723-2.084v-4.766a2.121 2.121 0 1 0-4.242 0v4.766q.001.35.107.666q1.166.834 2.412 1.418");
}

.qvxe_pbez {
  stop-color: var(--svg-color--fff478, #FFF478);
}

.rw5c_lizo {
  stop-opacity: 0.4;
}

.uospscb_d {
  stop-color: var(--svg-color--3d5bf1, #3D5BF1);
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vn4n3no1s {
  stop-color: var(--svg-color--9f5e0f, #9F5E0F);
}

.w5xp9scuu {
  stop-color: var(--svg-color--ff7dce, #FF7DCE);
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.yco627brm {
  stop-color: var(--svg-color--3f5fff, #3F5FFF);
}

.z-xmlwmhd {
  stop-color: var(--svg-color--f08b13, #F08B13);
  stop-opacity: 0;
}

.zgcpgx8ap {
  stop-color: var(--svg-color--7d6133, #7D6133);
  stop-opacity: 0;
}

.zvu8xrm3z {
  fill-rule: evenodd;
  d: path("M27.314 7.692h-4.42a2.121 2.121 0 1 0 0 4.242h4.766c.701 0 1.318-.339 1.703-.857a15.4 15.4 0 0 0-2.049-3.385");
}

.zvwq35ksz {
  d: path("M22.364 11.757L11.757 22.364a1.5 1.5 0 0 1-2.121 0L22.364 9.636a1.5 1.5 0 0 1 0 2.121");
}

</style>
