<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path stroke="url(#i5LbC1d)" class="suerd1_kx"/><path stroke="url(#i8Ebklc)" class="suerd1_kx"/><path stroke="url(#i7eXmMy)" class="suerd1_kx"/><path stroke="url(#iQTE2lm)" class="v1h6hrbca"/><path stroke="url(#i3tVm5b)" class="v1h6hrbca"/><path fill="url(#iplGREc)" class="oyit3b00e"/><path fill="url(#imeyCQd)" class="oyit3b00e"/><path fill="url(#iQulj5b)" class="oyit3b00e"/><path fill="url(#izXTnBe)" class="iq5vvtbml"/><path fill="url(#iN0CZoo)" class="iq5vvtbml"/><path fill="url(#i4lhLhc)" class="iq5vvtbml"/><path fill="url(#ipbqFSd)" class="iq5vvtbml"/><path fill="url(#iT8ck7b)" clip-rule="evenodd" class="dt734sbtw"/><g filter="url(#ilLusNe)"><path stroke="url(#ijXNF8b)" class="qxrihksyo"/></g><defs><linearGradient id="i5LbC1d" x1="4.234" x2="5.5" y1="17.125" y2="18.813" gradientUnits="userSpaceOnUse"><stop class="s-2n9fptn"/><stop offset=".091" class="q0ij9lset"/><stop offset=".363" class="w-uwm6bst"/><stop offset=".575" class="w-uwm6bst"/><stop offset=".788" class="xr2obybsq"/><stop offset="1" class="hy6ixtb9r"/></linearGradient><linearGradient id="i8Ebklc" x1="7" x2="6.031" y1="16.531" y2="16.5" gradientUnits="userSpaceOnUse"><stop class="ago74-alx"/><stop offset="1" class="rmczwab8c"/></linearGradient><linearGradient id="iQTE2lm" x1="27.779" x2="26.513" y1="17.156" y2="18.906" gradientUnits="userSpaceOnUse"><stop class="o-dmxomfq"/><stop offset=".09" class="u3e2ijtef"/><stop offset=".294" class="u3e2ijtef"/><stop offset=".5" class="gb3h6t4sp"/><stop offset="1" class="r1nqmfbmu"/></linearGradient><linearGradient id="iQulj5b" x1="16" x2="16" y1="6" y2="25.031" gradientUnits="userSpaceOnUse"><stop offset=".466" class="lu2n6cbnj"/><stop offset=".578" class="xt9ggsumx"/></linearGradient><linearGradient id="izXTnBe" x1="9.938" x2="24.125" y1="28.188" y2="16.563" gradientUnits="userSpaceOnUse"><stop class="pjlzf8b3t"/><stop offset=".484" class="m7_jnybzz"/><stop offset="1" class="fv-oo0zlz"/></linearGradient><linearGradient id="iN0CZoo" x1="7" x2="9.063" y1="22.406" y2="22" gradientUnits="userSpaceOnUse"><stop offset=".367" class="zf6i6o5eg"/><stop offset="1" class="g6c2po32r"/></linearGradient><linearGradient id="i4lhLhc" x1="16" x2="16" y1="15.5" y2="30" gradientUnits="userSpaceOnUse"><stop offset=".905" class="f8v_2acyb"/><stop offset="1" class="cba0b7bhl"/></linearGradient><linearGradient id="ipbqFSd" x1="25.094" x2="23.938" y1="21.719" y2="21.531" gradientUnits="userSpaceOnUse"><stop offset=".548" class="s5rdp96je"/><stop offset=".891" class="cwvq7rrgw"/></linearGradient><linearGradient id="iT8ck7b" x1="13.188" x2="19.602" y1="20.106" y2="24.825" gradientUnits="userSpaceOnUse"><stop class="dja5ambxs"/><stop offset="1" class="uuqlxib6n"/></linearGradient><linearGradient id="ijXNF8b" x1="7.281" x2="7.464" y1="16.188" y2="17.939" gradientUnits="userSpaceOnUse"><stop class="af9vyt46t"/><stop offset="1" class="v48nkzbpu"/></linearGradient><radialGradient id="i7eXmMy" cx="0" cy="0" r="1" gradientTransform="matrix(2.14063 3.51562 -4.83398 2.94336 5.875 17.094)" gradientUnits="userSpaceOnUse"><stop offset=".631" class="a8te_xhtq"/><stop offset="1" class="vy2v4kpsl"/></radialGradient><radialGradient id="i3tVm5b" cx="0" cy="0" r="1" gradientTransform="rotate(122.674 8.401 15.795)scale(3.78674 6.94571)" gradientUnits="userSpaceOnUse"><stop offset=".482" class="hg8mbjbqr"/><stop offset="1" class="hemcwsbaf"/></radialGradient><radialGradient id="iplGREc" cx="0" cy="0" r="1" gradientTransform="matrix(-14.62498 6.5626 -7.1812 -16.00355 21.625 10.438)" gradientUnits="userSpaceOnUse"><stop class="amcu5f51g"/><stop offset=".529" class="af9vyt46t"/><stop offset="1" class="q2u5i95so"/></radialGradient><radialGradient id="imeyCQd" cx="0" cy="0" r="1" gradientTransform="rotate(91.965 .723 15.261)scale(12.7575 13.0095)" gradientUnits="userSpaceOnUse"><stop offset=".69" class="xp31vug9r"/><stop offset=".752" class="xt9ggsumx"/></radialGradient><filter id="ilLusNe" width="18.75" height=".75" x="6.656" y="15.531" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_27694" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:takeout-box" /></template>
<style>
.a8te_xhtq {
  stop-color: var(--svg-color--a298ad, #A298AD);
  stop-opacity: 0;
}

.af9vyt46t {
  stop-color: var(--svg-color--d6d6d6, #D6D6D6);
}

.ago74-alx {
  stop-color: var(--svg-color--96929a, #96929A);
}

.amcu5f51g {
  stop-color: var(--svg-color--f1f1f1, #F1F1F1);
}

.cba0b7bhl {
  stop-color: var(--svg-color--a583c4, #A583C4);
}

.cwvq7rrgw {
  stop-color: var(--svg-color--d5d1db, #D5D1DB);
  stop-opacity: 0;
}

.dja5ambxs {
  stop-color: var(--svg-color--e53469, #E53469);
}

.dt734sbtw {
  fill-rule: evenodd;
  d: path("M16.25 17.288a.25.25 0 1 0-.5 0v.768h-1.69c-.08 0-.125.11-.125.11l-.429 1.236c-.027.068 0 .192.156.192h.588v1.025h-1.361c-.13 0-.2.147-.2.147L12 22.413c-.044.09 0 .256.25.256h1v2.319h-.75a.5.5 0 0 0 0 1h7a.5.5 0 0 0 0-1h-.75v-2.32h1c.25 0 .286-.16.25-.255l-.689-1.647s-.054-.147-.193-.147H17.75v-1.025h.587c.156 0 .178-.12.156-.192l-.43-1.236s-.034-.11-.12-.11H16.25zm2 7.7v-2.32h-4.5v2.32zm-3.5-4.37v-1.024h2.5v1.025z");
}

.f8v_2acyb {
  stop-color: var(--svg-color--c5b5d7, #C5B5D7);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fv-oo0zlz {
  stop-color: var(--svg-color--e5e3e7, #E5E3E7);
}

.g6c2po32r {
  stop-color: var(--svg-color--b2adb7, #B2ADB7);
  stop-opacity: 0;
}

.gb3h6t4sp {
  stop-color: var(--svg-color--dad9dc, #DAD9DC);
}

.hemcwsbaf {
  stop-color: var(--svg-color--b3aabb, #B3AABB);
}

.hg8mbjbqr {
  stop-color: var(--svg-color--b2aaba, #B2AABA);
  stop-opacity: 0;
}

.hy6ixtb9r {
  stop-color: var(--svg-color--a599b0, #A599B0);
}

.iq5vvtbml {
  d: path("M25.148 15.5H6.854a.296.296 0 0 0-.297.343c.309 1.849 1.767 10.589 1.99 12.11C8.797 29.656 9.875 30 10.828 30h10.14c1.173 0 2.235-.656 2.438-1.703c.183-.94 1.726-10.513 2.039-12.455a.296.296 0 0 0-.297-.342");
}

.lu2n6cbnj {
  stop-color: var(--svg-color--b5b5b5, #B5B5B5);
  stop-opacity: 0;
}

.m7_jnybzz {
  stop-color: var(--svg-color--d7d2dc, #D7D2DC);
}

.o-dmxomfq {
  stop-color: var(--svg-color--d4d4d4, #D4D4D4);
}

.oyit3b00e {
  d: path("M25.5 15.5s-1.937 9.531-9.5 9.531c-8.031 0-9.5-9.531-9.5-9.531a9.5 9.5 0 0 1 19 0");
}

.pjlzf8b3t {
  stop-color: var(--svg-color--c0b9c8, #C0B9C8);
}

.q0ij9lset {
  stop-color: var(--svg-color--bfbfbf, #BFBFBF);
}

.q2u5i95so {
  stop-color: var(--svg-color--a6a6a6, #A6A6A6);
}

.qxrihksyo {
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M25.156 15.906H6.906");
}

.r1nqmfbmu {
  stop-color: var(--svg-color--a59baf, #A59BAF);
}

.rmczwab8c {
  stop-color: var(--svg-color--9b999d, #9B999D);
  stop-opacity: 0;
}

.s-2n9fptn {
  stop-color: var(--svg-color--b7b7b7, #B7B7B7);
}

.s5rdp96je {
  stop-color: var(--svg-color--cac6cf, #CAC6CF);
}

.suerd1_kx {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m3.016 19.25l5.5-4");
}

.u3e2ijtef {
  stop-color: var(--svg-color--ededed, #EDEDED);
}

.uuqlxib6n {
  stop-color: var(--svg-color--f44564, #F44564);
}

.v1h6hrbca {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m28.982 19.25l-5.5-4");
}

.v48nkzbpu {
  stop-color: var(--svg-color--f1f1f2, #F1F1F2);
}

.vy2v4kpsl {
  stop-color: var(--svg-color--ada7b3, #ADA7B3);
}

.w-uwm6bst {
  stop-color: var(--svg-color--ceccd0, #CECCD0);
}

.xp31vug9r {
  stop-color: var(--svg-color--b8b8b8, #B8B8B8);
  stop-opacity: 0;
}

.xr2obybsq {
  stop-color: var(--svg-color--b7b2bc, #B7B2BC);
}

.xt9ggsumx {
  stop-color: var(--svg-color--b5b5b5, #B5B5B5);
}

.zf6i6o5eg {
  stop-color: var(--svg-color--b1acb6, #B1ACB6);
}

</style>
