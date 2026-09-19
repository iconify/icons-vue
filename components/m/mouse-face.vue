<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iUMurSc)"><circle fill="url(#invurWd)" class="kg45wyk6j"/><circle fill="url(#iWn86hb)" class="kg45wyk6j"/><circle fill="url(#iKSAtcc)" class="kg45wyk6j"/></g><circle fill="url(#i4dHIFb)" class="ux4-ddb8p"/><circle fill="url(#iIyQlCq)" class="ux4-ddb8p"/><g filter="url(#iqwoVjv)"><circle fill="url(#i0LDVCd)" class="eq7ufac8k"/><circle fill="url(#iqP0r2c)" class="eq7ufac8k"/><circle fill="url(#i5MZGTf)" class="eq7ufac8k"/><circle fill="url(#iaEqeAb)" class="eq7ufac8k"/></g><g filter="url(#i9A2rvb)"><circle fill="url(#i8qjjwd)" class="jqbdobboe"/><circle fill="url(#iN04Q7d)" class="jqbdobboe"/></g><path fill="url(#ioPMXWc)" class="xb5brmbrs"/><path fill="url(#iQKGCLe)" class="xb5brmbrs"/><path fill="url(#irCKzHI)" class="xb5brmbrs"/><path fill="url(#i9i2CAe)" class="xb5brmbrs"/><path fill="url(#ivp39ge)" class="xb5brmbrs"/><g filter="url(#iSkSkHb)"><rect class="fidygcb-u"/></g><rect fill="url(#iNzlZuL)" class="oumf9jbjk"/><rect fill="url(#irQju9b)" class="oumf9jbjk"/><rect fill="url(#iPKkzDb)" class="oumf9jbjk"/><rect fill="url(#iHEQsFc)" class="c9wvq0bqi"/><rect fill="url(#iBYHaBe)" class="c9wvq0bqi"/><rect fill="url(#iFe0xEb)" class="c9wvq0bqi"/><path class="fmwskobwx"/><path fill="url(#i1Z0gcc)" class="c8s1n2ucj"/><path stroke="url(#iQVPGme)" class="qg2nbzbyw"/><path stroke="url(#iiJclrT)" class="qg2nbzbyw"/><path stroke="url(#ib8twOz)" class="qg2nbzbyw"/><path stroke="url(#ijWtwLn)" class="qg2nbzbyw"/><path stroke="url(#iNvbxte)" class="ky1zsvuzv"/><path stroke="url(#igi6ged)" class="ky1zsvuzv"/><path stroke="url(#ierb15b)" class="ky1zsvuzv"/><path stroke="url(#iYsbs6d)" class="ky1zsvuzv"/><path stroke="url(#i9rVMte)" class="h4a5fobog"/><path stroke="url(#iGAQxne)" class="h4a5fobog"/><path stroke="url(#ikTmS3d)" class="h4a5fobog"/><path stroke="url(#iMY5oUb)" class="h4a5fobog"/><path fill="url(#iLNaVAe)" class="v-1kmjp2e"/><path fill="url(#ikwDPId)" class="v-1kmjp2e"/><path fill="url(#iXtB2mc)" class="v-1kmjp2e"/><path fill="url(#isozSCc)" class="v-1kmjp2e"/><defs><radialGradient id="iWn86hb" cx="0" cy="0" r="1" gradientTransform="matrix(2.6692 3.39717 -4.70995 3.70067 2.858 4.9)" gradientUnits="userSpaceOnUse"><stop class="jxtzo3inq"/><stop offset="1" class="y5fzhvznw"/></radialGradient><radialGradient id="iKSAtcc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.48723 2.66919 -4.65946 -4.34182 13.778 5.932)" gradientUnits="userSpaceOnUse"><stop class="we8c91axu"/><stop offset="1" class="nm9d7koaa"/></radialGradient><radialGradient id="i4dHIFb" cx="0" cy="0" r="1" gradientTransform="rotate(13.291 -49.459 18.846)scale(8.15595)" gradientUnits="userSpaceOnUse"><stop class="drq5zvi8q"/><stop offset="1" class="mz4-ifjmd"/></radialGradient><radialGradient id="iIyQlCq" cx="0" cy="0" r="1" gradientTransform="matrix(3.31248 -2.87503 4.01415 4.62493 5.258 13.25)" gradientUnits="userSpaceOnUse"><stop class="i-4ookbmm"/><stop offset=".829" class="pzjy4_9tr"/></radialGradient><radialGradient id="i0LDVCd" cx="0" cy="0" r="1" gradientTransform="rotate(52.431 1.354 22.447)scale(10.2508)" gradientUnits="userSpaceOnUse"><stop class="sgmf-dbip"/><stop offset="1" class="y-pqn9bsb"/></radialGradient><radialGradient id="iqP0r2c" cx="0" cy="0" r="1" gradientTransform="rotate(-110.395 19.506 -.951)scale(5.20104 12.8911)" gradientUnits="userSpaceOnUse"><stop class="oa_cylbch"/><stop offset="1" class="xrfecibzc"/></radialGradient><radialGradient id="i5MZGTf" cx="0" cy="0" r="1" gradientTransform="rotate(-165.838 15.902 3.832)scale(13.7942 9.0204)" gradientUnits="userSpaceOnUse"><stop offset=".85" class="g6pczxb7u"/><stop offset="1" class="j7x7e5rkz"/></radialGradient><radialGradient id="iaEqeAb" cx="0" cy="0" r="1" gradientTransform="rotate(147.095 13.615 8.098)scale(3.79659 5.45721)" gradientUnits="userSpaceOnUse"><stop class="s8bsd4tep"/><stop offset=".941" class="evcjge_9e"/></radialGradient><radialGradient id="i8qjjwd" cx="0" cy="0" r="1" gradientTransform="matrix(4.15625 -4.53125 6.04757 5.54707 22.852 13.031)" gradientUnits="userSpaceOnUse"><stop class="emo073bhj"/><stop offset="1" class="h4vl3orxo"/></radialGradient><radialGradient id="iN04Q7d" cx="0" cy="0" r="1" gradientTransform="matrix(3.625 -2.4375 2.4859 3.69698 24.008 11.438)" gradientUnits="userSpaceOnUse"><stop class="fqnjxtbuj"/><stop offset="1" class="o_xbv9k2j"/><stop offset="1" class="o_xbv9k2j"/></radialGradient><radialGradient id="iQKGCLe" cx="0" cy="0" r="1" gradientTransform="matrix(5.125 -8 13.25738 8.493 12.133 28.25)" gradientUnits="userSpaceOnUse"><stop class="pw87mwr4z"/><stop offset="1" class="jkw663bwv"/></radialGradient><radialGradient id="irCKzHI" cx="0" cy="0" r="1" gradientTransform="matrix(10.625 4.69527 -5.40278 12.22604 3.695 14.125)" gradientUnits="userSpaceOnUse"><stop offset=".121" class="jrqc5fbmv"/><stop offset="1" class="bny7ph15t"/></radialGradient><radialGradient id="i9i2CAe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.18753 5.81246 -7.45756 -9.22182 20.445 15.563)" gradientUnits="userSpaceOnUse"><stop class="w8u_w_x2y"/><stop offset=".573" class="vp_kamblu"/></radialGradient><radialGradient id="ivp39ge" cx="0" cy="0" r="1" gradientTransform="matrix(0 -18.9219 13.4687 0 16.04 27.61)" gradientUnits="userSpaceOnUse"><stop offset=".878" class="a_4dnbb0f"/><stop offset="1" class="s4tprbc2t"/></radialGradient><radialGradient id="iPKkzDb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5726 -1.63534 1.57679 -.5521 20.258 20.68)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iFe0xEb" cx="0" cy="0" r="1" gradientTransform="matrix(-.5726 -1.63534 1.57679 -.5521 12.32 20.68)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="i1Z0gcc" cx="0" cy="0" r="1" gradientTransform="rotate(143.673 5.174 14.574)scale(3.95643 4.4258)" gradientUnits="userSpaceOnUse"><stop offset=".727" class="n62cq4b6v"/><stop offset="1" class="wi8u8sbjh"/></radialGradient><radialGradient id="ijWtwLn" cx="0" cy="0" r="1" gradientTransform="matrix(-.40625 -.20312 .35074 -.70148 24.695 27.438)" gradientUnits="userSpaceOnUse"><stop class="oal005brz"/><stop offset="1" class="hv9l74odo"/></radialGradient><radialGradient id="iYsbs6d" cx="0" cy="0" r="1" gradientTransform="matrix(-.41016 0 0 -.32487 25.559 24.313)" gradientUnits="userSpaceOnUse"><stop class="oal005brz"/><stop offset="1" class="hv9l74odo"/></radialGradient><radialGradient id="iMY5oUb" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 .125 -.21584 -.68799 12.656 25.25)" gradientUnits="userSpaceOnUse"><stop class="oal005brz"/><stop offset="1" class="hv9l74odo"/></radialGradient><radialGradient id="isozSCc" cx="0" cy="0" r="1" gradientTransform="rotate(178.916 5.694 12.262)scale(.41023 .32493)" gradientUnits="userSpaceOnUse"><stop class="oal005brz"/><stop offset="1" class="hv9l74odo"/></radialGradient><linearGradient id="invurWd" x1="7.383" x2="5.57" y1="6.625" y2="17" gradientUnits="userSpaceOnUse"><stop class="p9ics4otx"/><stop offset="1" class="pollb6zeo"/></linearGradient><linearGradient id="ioPMXWc" x1="20.07" x2="5.82" y1="14.25" y2="36.5" gradientUnits="userSpaceOnUse"><stop offset=".237" class="ca_0kqwgk"/><stop offset="1" class="tqk772bft"/></linearGradient><linearGradient id="iNzlZuL" x1="20.711" x2="19.852" y1="20.5" y2="20.5" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="irQju9b" x1="20.943" x2="20.943" y1="22.257" y2="21.183" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iHEQsFc" x1="12.773" x2="11.914" y1="20.5" y2="20.5" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iBYHaBe" x1="13.005" x2="13.005" y1="22.257" y2="21.183" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iQVPGme" x1="22.414" x2="21.883" y1="26.078" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="ztpzabcoe"/><stop offset=".343" class="rwaxafcsx"/><stop offset=".833" class="cwe7z0wxy"/></linearGradient><linearGradient id="iiJclrT" x1="25.117" x2="24.711" y1="27.797" y2="27.555" gradientUnits="userSpaceOnUse"><stop class="rwaxafcsx"/><stop offset="1" class="hv9l74odo"/></linearGradient><linearGradient id="ib8twOz" x1="19.023" x2="19.961" y1="25.297" y2="25.813" gradientUnits="userSpaceOnUse"><stop class="sydmm01uo"/><stop offset="1" class="bsno5ccwx"/></linearGradient><linearGradient id="iNvbxte" x1="22.969" x2="22.969" y1="23.961" y2="25.281" gradientUnits="userSpaceOnUse"><stop class="ztpzabcoe"/><stop offset=".343" class="rwaxafcsx"/><stop offset=".833" class="cwe7z0wxy"/></linearGradient><linearGradient id="igi6ged" x1="26.148" x2="25.559" y1="24.781" y2="24.781" gradientUnits="userSpaceOnUse"><stop class="rwaxafcsx"/><stop offset="1" class="hv9l74odo"/></linearGradient><linearGradient id="ierb15b" x1="20.102" x2="20.727" y1="24.859" y2="24.859" gradientUnits="userSpaceOnUse"><stop class="sydmm01uo"/><stop offset="1" class="bsno5ccwx"/></linearGradient><linearGradient id="i9rVMte" x1="9.586" x2="10.117" y1="26.078" y2="27.375" gradientUnits="userSpaceOnUse"><stop class="ztpzabcoe"/><stop offset=".343" class="rwaxafcsx"/><stop offset=".833" class="cwe7z0wxy"/></linearGradient><linearGradient id="iGAQxne" x1="13.102" x2="12.563" y1="25.57" y2="25.828" gradientUnits="userSpaceOnUse"><stop class="rwaxafcsx"/><stop offset="1" class="hv9l74odo"/></linearGradient><linearGradient id="ikTmS3d" x1="6.961" x2="7.711" y1="27.453" y2="27.07" gradientUnits="userSpaceOnUse"><stop class="sydmm01uo"/><stop offset="1" class="bsno5ccwx"/></linearGradient><linearGradient id="iLNaVAe" x1="9.031" x2="9.031" y1="23.961" y2="25.281" gradientUnits="userSpaceOnUse"><stop class="ztpzabcoe"/><stop offset=".343" class="rwaxafcsx"/><stop offset=".833" class="cwe7z0wxy"/></linearGradient><linearGradient id="ikwDPId" x1="11.93" x2="11.109" y1="24.781" y2="24.781" gradientUnits="userSpaceOnUse"><stop class="rwaxafcsx"/><stop offset="1" class="hv9l74odo"/></linearGradient><linearGradient id="iXtB2mc" x1="5.891" x2="6.727" y1="24.75" y2="24.75" gradientUnits="userSpaceOnUse"><stop class="sydmm01uo"/><stop offset="1" class="bsno5ccwx"/></linearGradient><filter id="iUMurSc" width="13.1" height="13.1" x="1.908" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.639216 0 0 0 0 0.662745 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3650"/></filter><filter id="iqwoVjv" width="13.1" height="13.1" x="17.008" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1" dy=".1"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.647059 0 0 0 0 0.639216 0 0 0 0 0.662745 0 0 0 0.75 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3650"/></filter><filter id="i9A2rvb" width="10.1" height="10.1" x="18.908" y="6" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.898039 0 0 0 0 0.470588 0 0 0 0 0.580392 0 0 0 0.75 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_3650"/></filter><filter id="iSkSkHb" width="2.484" height="4" x="18.302" y="18.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3650" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:mouse-face" /></template>
<style>
.a_4dnbb0f {
  stop-color: var(--svg-color--c1c0c3, #C1C0C3);
  stop-opacity: 0;
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bny7ph15t {
  stop-color: var(--svg-color--9b90a2, #9B90A2);
  stop-opacity: 0;
}

.bsno5ccwx {
  stop-color: var(--svg-color--a18bba, #A18BBA);
  stop-opacity: 0;
}

.c8s1n2ucj {
  d: path("M17.977 23.86c0 .374-.743 2.109-1.938 2.109s-2.016-1.79-2.016-2.11c0-.437.188-.859 2.016-.859c1.613 0 1.938.484 1.938.86");
}

.c9wvq0bqi {
  width: 1.484px;
  height: 3px;
  x: 11.289px;
  y: 19px;
  rx: 0.742px;
}

.ca_0kqwgk {
  stop-color: var(--svg-color--d4cce2, #D4CCE2);
}

.cwe7z0wxy {
  stop-color: var(--svg-color--9877ba, #9877BA);
}

.drq5zvi8q {
  stop-color: var(--svg-color--f3758e, #F3758E);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.emo073bhj {
  stop-color: var(--svg-color--ffabb3, #FFABB3);
}

.eq7ufac8k {
  cx: 23.508px;
  cy: 10.5px;
  r: 6.5px;
}

.evcjge_9e {
  stop-color: var(--svg-color--e7e1ed, #E7E1ED);
  stop-opacity: 0;
}

.fidygcb-u {
  width: 1.484px;
  height: 3px;
  x: 18.802px;
  y: 19.188px;
  fill: var(--svg-color--b9a8ce, #B9A8CE);
  rx: 0.742px;
}

.fmwskobwx {
  fill: var(--svg-color--ff80b1, #FF80B1);
  d: path("M17.977 23.86c0 .374-.743 2.109-1.938 2.109s-2.016-1.79-2.016-2.11c0-.437.188-.859 2.016-.859c1.613 0 1.938.484 1.938.86");
}

.fqnjxtbuj {
  stop-color: var(--svg-color--f5bbd5, #F5BBD5);
}

.ft5dv1b6b {
  fill: none;
}

.g6pczxb7u {
  stop-color: var(--svg-color--a4a2a9, #A4A2A9);
  stop-opacity: 0;
}

.h4a5fobog {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m12.606 25.375l-5.172 2.18");
}

.h4vl3orxo {
  stop-color: var(--svg-color--fa91af, #FA91AF);
}

.hv9l74odo {
  stop-color: var(--svg-color--b5a8c7, #B5A8C7);
  stop-opacity: 0;
}

.i-4ookbmm {
  stop-color: var(--svg-color--ff9ca9, #FF9CA9);
}

.j7x7e5rkz {
  stop-color: var(--svg-color--a4a2a9, #A4A2A9);
}

.jkw663bwv {
  stop-color: var(--svg-color--b583e3, #B583E3);
  stop-opacity: 0;
}

.jqbdobboe {
  cx: 24.008px;
  cy: 11px;
  r: 5px;
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jrqc5fbmv {
  stop-color: var(--svg-color--9b90a2, #9B90A2);
}

.jxtzo3inq {
  stop-color: var(--svg-color--a9a4ae, #A9A4AE);
}

.kg45wyk6j {
  cx: 8.508px;
  cy: 10.5px;
  r: 6.5px;
}

.ky1zsvuzv {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("M20.379 24.477h5.18");
}

.mz4-ifjmd {
  stop-color: var(--svg-color--e7626e, #E7626E);
}

.n62cq4b6v {
  stop-color: var(--svg-color--e1589f, #E1589F);
  stop-opacity: 0;
}

.nm9d7koaa {
  stop-color: var(--svg-color--e3e0e7, #E3E0E7);
  stop-opacity: 0;
}

.o_xbv9k2j {
  stop-color: var(--svg-color--f5bbd5, #F5BBD5);
  stop-opacity: 0;
}

.oa_cylbch {
  stop-color: var(--svg-color--c5aed9, #C5AED9);
}

.oal005brz {
  stop-color: var(--svg-color--c1b1d8, #C1B1D8);
}

.oumf9jbjk {
  width: 1.484px;
  height: 3px;
  x: 19.227px;
  y: 19px;
  rx: 0.742px;
}

.p9ics4otx {
  stop-color: var(--svg-color--c1b8c6, #C1B8C6);
}

.pollb6zeo {
  stop-color: var(--svg-color--a183b2, #A183B2);
}

.pw87mwr4z {
  stop-color: var(--svg-color--b583e3, #B583E3);
}

.pzjy4_9tr {
  stop-color: var(--svg-color--ff9ca9, #FF9CA9);
  stop-opacity: 0;
}

.qg2nbzbyw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
  d: path("m19.395 25.375l5.171 2.18");
}

.rwaxafcsx {
  stop-color: var(--svg-color--b5a8c7, #B5A8C7);
}

.s4tprbc2t {
  stop-color: var(--svg-color--c1c0c3, #C1C0C3);
}

.s8bsd4tep {
  stop-color: var(--svg-color--e7e1ed, #E7E1ED);
}

.sgmf-dbip {
  stop-color: var(--svg-color--a6a2ac, #A6A2AC);
}

.sydmm01uo {
  stop-color: var(--svg-color--a18bba, #A18BBA);
}

.tqk772bft {
  stop-color: var(--svg-color--bb8ae9, #BB8AE9);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ux4-ddb8p {
  cx: 8.008px;
  cy: 11px;
  r: 5px;
}

.v-1kmjp2e {
  d: path("M11.621 24.077a.4.4 0 1 1 0 .8zm-5.18.8a.4.4 0 0 1 0-.8zm5.18 0h-5.18v-.8h5.18z");
}

.vp_kamblu {
  stop-color: var(--svg-color--f6f1fe, #F6F1FE);
  stop-opacity: 0;
}

.w8u_w_x2y {
  stop-color: var(--svg-color--f6f1fe, #F6F1FE);
}

.we8c91axu {
  stop-color: var(--svg-color--e3e0e7, #E3E0E7);
}

.wi8u8sbjh {
  stop-color: var(--svg-color--e1589f, #E1589F);
}

.xb5brmbrs {
  d: path("M24.977 18c0 4.823-4.428 8.241-7.802 9.322a4 4 0 0 1-2.338.009C11.27 26.28 7.102 23.226 7.102 18c0-3.975 3.718-7.969 8.906-7.969c6.425 0 8.969 5.344 8.969 7.969");
}

.xrfecibzc {
  stop-color: var(--svg-color--c5aed9, #C5AED9);
  stop-opacity: 0;
}

.y-pqn9bsb {
  stop-color: var(--svg-color--d3cbda, #D3CBDA);
}

.y5fzhvznw {
  stop-color: var(--svg-color--a9a4ae, #A9A4AE);
  stop-opacity: 0;
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.ztpzabcoe {
  stop-color: var(--svg-color--978ba4, #978BA4);
}

</style>
