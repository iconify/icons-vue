<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="kuvxqkbib"/><path fill="url(#iTr6Orc)" clip-rule="evenodd" class="t772t0b3t"/><path fill="url(#iwWKY5d)" clip-rule="evenodd" class="t772t0b3t"/><path fill="url(#i2YL03b)" clip-rule="evenodd" class="t772t0b3t"/><path fill="url(#iIGTShd)" clip-rule="evenodd" class="t772t0b3t"/><path fill="url(#imnHr2b)" clip-rule="evenodd" class="t772t0b3t"/><path fill="url(#i2wakob)" clip-rule="evenodd" class="t772t0b3t"/><path fill="url(#idyzY9d)" clip-rule="evenodd" class="t772t0b3t"/><path fill="url(#ifoy9Eg)" class="z-en13bqq"/><path fill="url(#iFubjLe)" class="gkez0i-rr"/><path fill="url(#iuWyOwJ)" class="qxfvirbev"/><path fill="url(#ihhTadc)" class="a3ie-8bzh"/><path fill="url(#i6w4Qzd)" class="a3ie-8bzh"/><path fill="url(#iZtIrGc)" clip-rule="evenodd" class="q1mewdlte"/><path fill="url(#i4LrO5c)" clip-rule="evenodd" class="q1mewdlte"/><path fill="url(#iFE6C3b)" clip-rule="evenodd" class="q1mewdlte"/><path fill="url(#iyB1Wje)" clip-rule="evenodd" class="q1mewdlte"/><path fill="url(#i9Wr2td)" clip-rule="evenodd" class="q1mewdlte"/><path fill="url(#iLg6BVt)" clip-rule="evenodd" class="q1mewdlte"/><path fill="url(#iF0WfOb)" clip-rule="evenodd" class="q1mewdlte"/><path fill="url(#i87HXcb)" clip-rule="evenodd" class="q1mewdlte"/><path fill="url(#ijm7eid)" class="n3bqtvr0y"/><path fill="url(#ivhmB5C)" class="qhd_qnaag"/><path fill="url(#icR303W)" class="hp3aorb3c"/><path fill="url(#ia1uead)" class="e7treob1b"/><defs><radialGradient id="iTr6Orc" cx="0" cy="0" r="1" gradientTransform="matrix(-3.35157 10.49996 -5.39117 -1.72085 16.766 17.063)" gradientUnits="userSpaceOnUse"><stop offset=".422" class="qgi1acchh"/><stop offset=".855" class="bccvfklli"/></radialGradient><radialGradient id="iwWKY5d" cx="0" cy="0" r="1" gradientTransform="rotate(119.241 2.184 13.877)scale(8.38042 3.56235)" gradientUnits="userSpaceOnUse"><stop offset=".646" class="ye9q01rod"/><stop offset=".907" class="lbrgarbbk"/></radialGradient><radialGradient id="i2YL03b" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 10.99999 -4.10356 -.04663 16.578 11.063)" gradientUnits="userSpaceOnUse"><stop offset=".354" class="ye9q01rod"/><stop offset=".907" class="p7d4sc1hc"/></radialGradient><radialGradient id="iIGTShd" cx="0" cy="0" r="1" gradientTransform="matrix(8.5 2.5625 -3.37797 11.205 22.465 3.906)" gradientUnits="userSpaceOnUse"><stop offset=".219" class="xin8r0bta"/><stop offset="1" class="rkqt8gbwi"/></radialGradient><radialGradient id="idyzY9d" cx="0" cy="0" r="1" gradientTransform="rotate(52.725 6.159 28.91)scale(1.76723 2.37608)" gradientUnits="userSpaceOnUse"><stop offset=".062" class="gekbmyb8x"/><stop offset="1" class="hr6ocbbvn"/></radialGradient><radialGradient id="ifoy9Eg" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.78125 -7.1875 0 24.121 9.63)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="yoozydbbj"/><stop offset=".969" class="ddkp9hbxh"/></radialGradient><radialGradient id="iFubjLe" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.78125 -7.1875 0 24.121 7.624)" gradientUnits="userSpaceOnUse"><stop offset=".355" class="yoozydbbj"/><stop offset=".969" class="ddkp9hbxh"/></radialGradient><radialGradient id="iuWyOwJ" cx="0" cy="0" r="1" gradientTransform="rotate(54.417 -8.847 31.383)scale(6.92886 6.86112)" gradientUnits="userSpaceOnUse"><stop class="fxfn5wbni"/><stop offset=".524" class="hv0domwll"/><stop offset=".727" class="y8ejde2uj"/></radialGradient><radialGradient id="ihhTadc" cx="0" cy="0" r="1" gradientTransform="rotate(131.749 2.969 16.43)scale(12.3882 10.9947)" gradientUnits="userSpaceOnUse"><stop class="fzyyubc4i"/><stop offset=".364" class="zbj_02bwe"/><stop offset=".397" class="jsi3b7brr"/></radialGradient><radialGradient id="i6w4Qzd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.87498 4.12502 -.87311 -.60853 14.703 22.28)" gradientUnits="userSpaceOnUse"><stop offset=".375" class="vbtjx1b1n"/><stop offset="1" class="irbpgda-a"/></radialGradient><radialGradient id="iZtIrGc" cx="0" cy="0" r="1" gradientTransform="matrix(.50002 19.31253 -13.93333 .36074 7.64 11.875)" gradientUnits="userSpaceOnUse"><stop offset=".041" class="e9rbpxgxo"/><stop offset=".542" class="wyiwufb2p"/><stop offset="1" class="j0ogj4baj"/></radialGradient><radialGradient id="i4LrO5c" cx="0" cy="0" r="1" gradientTransform="matrix(1.125 17.62503 -9.88201 .63076 21.39 .938)" gradientUnits="userSpaceOnUse"><stop offset=".179" class="x3nn1sbzk"/><stop offset="1" class="uobv5pyzn"/></radialGradient><radialGradient id="iFE6C3b" cx="0" cy="0" r="1" gradientTransform="rotate(85.309 .654 8.13)scale(12.2285 3.0587)" gradientUnits="userSpaceOnUse"><stop offset=".541" class="em7qdxb-c"/><stop offset=".947" class="aoow5ybre"/></radialGradient><radialGradient id="iyB1Wje" cx="0" cy="0" r="1" gradientTransform="rotate(138.93 -1.035 10.178)scale(8.70463 2.35468)" gradientUnits="userSpaceOnUse"><stop offset=".656" class="em7qdxb-c"/><stop offset=".947" class="aoow5ybre"/></radialGradient><radialGradient id="i9Wr2td" cx="0" cy="0" r="1" gradientTransform="matrix(-1.53126 3.03125 -1.57755 -.79691 9.246 14.469)" gradientUnits="userSpaceOnUse"><stop offset=".469" class="em7qdxb-c"/><stop offset=".947" class="aoow5ybre"/></radialGradient><radialGradient id="iF0WfOb" cx="0" cy="0" r="1" gradientTransform="rotate(101.689 2.885 14.77)scale(27.7633 15.5664)" gradientUnits="userSpaceOnUse"><stop offset=".664" class="rh8h2dekt"/><stop offset=".731" class="x7znz0jyx"/></radialGradient><radialGradient id="i87HXcb" cx="0" cy="0" r="1" gradientTransform="matrix(1.19531 1.625 -1.0642 .7828 17.996 3)" gradientUnits="userSpaceOnUse"><stop class="ezdebjx2x"/><stop offset="1" class="zhao5abqf"/></radialGradient><radialGradient id="ijm7eid" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.91211 -9.43856 0 15.602 6.155)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="hx2wufbgx"/><stop offset=".629" class="qbqmcqbgr"/></radialGradient><radialGradient id="ivhmB5C" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.66211 -9.25 0 15.746 4.15)" gradientUnits="userSpaceOnUse"><stop offset=".264" class="hx2wufbgx"/><stop offset=".593" class="qbqmcqbgr"/></radialGradient><radialGradient id="icR303W" cx="0" cy="0" r="1" gradientTransform="rotate(53.549 -9.34 22.759)scale(6.83768)" gradientUnits="userSpaceOnUse"><stop class="nuag0fkew"/><stop offset=".525" class="ir1tflbef"/><stop offset=".727" class="ak22o7n2q"/></radialGradient><radialGradient id="ia1uead" cx="0" cy="0" r="1" gradientTransform="matrix(-9.4999 9.12505 -8.09932 -8.43204 10.89 21.75)" gradientUnits="userSpaceOnUse"><stop class="wj_5kwb2m"/><stop offset=".377" class="d5rtl1vdo"/><stop offset=".491" class="vdv6v5bzl"/></radialGradient><linearGradient id="imnHr2b" x1="22.828" x2="21.609" y1="25.875" y2="24.656" gradientUnits="userSpaceOnUse"><stop class="g_zm2dndm"/><stop offset=".333" class="qnw63gbtm"/><stop offset="1" class="xrsyvib1k"/></linearGradient><linearGradient id="i2wakob" x1="26.871" x2="25.621" y1="14.438" y2="14.438" gradientUnits="userSpaceOnUse"><stop class="kl1tbinvr"/><stop offset="1" class="fn4qmpbkm"/></linearGradient><linearGradient id="iLg6BVt" x1="15.703" x2="13.797" y1="22.063" y2="20.219" gradientUnits="userSpaceOnUse"><stop class="n_lrelb3e"/><stop offset=".169" class="xt35vz-tz"/><stop offset="1" class="bhkkopb-q"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:socks" /></template>
<style>
.a3ie-8bzh {
  d: path("M13.347 23.577c-.817 1.577-.984 3.54.396 4.924c1.952 1.96 4.898 1.435 5.85.498c.1-1.849-1.304-4.117-3.023-4.872c-1.175-.462-2.09-.802-3.223-.55");
}

.ak22o7n2q {
  stop-color: var(--svg-color--4553ff, #4553FF);
}

.aoow5ybre {
  stop-color: var(--svg-color--f1c34d, #F1C34D);
  stop-opacity: 0;
}

.bccvfklli {
  stop-color: var(--svg-color--5ca9ff, #5CA9FF);
  stop-opacity: 0;
}

.bhkkopb-q {
  stop-color: var(--svg-color--febf5c, #FEBF5C);
  stop-opacity: 0;
}

.d5rtl1vdo {
  stop-color: var(--svg-color--5754ff, #5754FF);
}

.ddkp9hbxh {
  stop-color: var(--svg-color--2f55da, #2F55DA);
}

.e7treob1b {
  d: path("M6.07 20.088c-.817 1.577-.86 3.62.52 5.003c1.952 1.96 5.32 1.25 6.405-.172c.099-1.848-1.659-3.856-3.378-4.611c-1.175-.463-2.414-.473-3.547-.22");
}

.e9rbpxgxo {
  stop-color: var(--svg-color--e0b248, #E0B248);
}

.em7qdxb-c {
  stop-color: var(--svg-color--b8943e, #B8943E);
}

.ezdebjx2x {
  stop-color: var(--svg-color--fff958, #FFF958);
}

.fn4qmpbkm {
  stop-color: var(--svg-color--5cb5ff, #5CB5FF);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fxfn5wbni {
  stop-color: var(--svg-color--3e5dff, #3E5DFF);
}

.fzyyubc4i {
  stop-color: var(--svg-color--407aff, #407AFF);
}

.g_zm2dndm {
  stop-color: var(--svg-color--5c6eff, #5C6EFF);
}

.gekbmyb8x {
  stop-color: var(--svg-color--86d6ff, #86D6FF);
}

.gkez0i-rr {
  d: path("M26.427 7.267q.076.264.077.551v.526h-8.652v-.526q0-.287.076-.551z");
}

.hp3aorb3c {
  d: path("M19.231 15.952h-4.985a.276.276 0 0 0-.281.272a4.1 4.1 0 0 0 3.353 4.03l.532-.559a5 5 0 0 0 1.381-3.45z");
}

.hr6ocbbvn {
  stop-color: var(--svg-color--6ecdff, #6ECDFF);
  stop-opacity: 0;
}

.hv0domwll {
  stop-color: var(--svg-color--3454ff, #3454FF);
}

.hx2wufbgx {
  stop-color: var(--svg-color--5872ff, #5872FF);
}

.ir1tflbef {
  stop-color: var(--svg-color--575aff, #575AFF);
}

.irbpgda-a {
  stop-color: var(--svg-color--2b50ff, #2B50FF);
  stop-opacity: 0;
}

.j0ogj4baj {
  stop-color: var(--svg-color--fdea49, #FDEA49);
}

.jsi3b7brr {
  stop-color: var(--svg-color--3859ff, #3859FF);
}

.kl1tbinvr {
  stop-color: var(--svg-color--54a3e6, #54A3E6);
}

.kuvxqkbib {
  fill: var(--svg-color--64b2ff, #64B2FF);
  fill-rule: evenodd;
  d: path("M26.505 7.82a2 2 0 0 0-2-2h-4.69a2 2 0 0 0-1.924 1.448l4.192.355l4.344-.355a2 2 0 0 1 .078.551v.526L22.082 8l-4.269.346v.927l4.269.383l4.421-.383v1.078l-4.421-.288l-4.269.288v6.596c0 1.011-.337 2.017-1.025 2.757l-2.61 2.899c-.264.295-.58.705-.765 1.062c.167 1.401 4.968 6.59 6.086 5.43l5.623-5.743a5 5 0 0 0 1.382-3.45zm0 11.788l-4.678.39c-1.406 0 1.517 3.683 2.764 3.911l.532-.558a5 5 0 0 0 1.382-3.45z");
}

.lbrgarbbk {
  stop-color: var(--svg-color--5aa7ff, #5AA7FF);
  stop-opacity: 0;
}

.n_lrelb3e {
  stop-color: var(--svg-color--e59b64, #E59B64);
}

.n3bqtvr0y {
  d: path("M19.191 5.616H10.5v1.078h8.691z");
}

.nuag0fkew {
  stop-color: var(--svg-color--5a61ff, #5A61FF);
}

.p7d4sc1hc {
  stop-color: var(--svg-color--4886d8, #4886D8);
  stop-opacity: 0;
}

.q1mewdlte {
  fill-rule: evenodd;
  d: path("M19.192 4.163a2 2 0 0 0-2-2h-4.69a2 2 0 0 0-1.923 1.449l4.191.355l4.345-.355a2 2 0 0 1 .077.551v.526l-4.422-.346l-4.268.346v.927L14.77 6l4.422-.383v1.078l-4.422-.289l-4.268.289v6.596c0 1.01-.337 2.017-1.025 2.757l-2.61 2.898c-.265.296-.58.706-.765 1.063c.199 1.676 4.804 5.187 5.785 5.304c-.139-.051.248.143.248.156v.043c.221-.146.503-.267.685-.456l4.99-5.36a5 5 0 0 0 1.382-3.45zm0 11.789l-4.678.389c-1.405 0 1.517 3.683 2.764 3.912l.533-.558a5 5 0 0 0 1.381-3.45z");
}

.qbqmcqbgr {
  stop-color: var(--svg-color--4154e6, #4154E6);
}

.qgi1acchh {
  stop-color: var(--svg-color--509bff, #509BFF);
}

.qhd_qnaag {
  d: path("M19.114 3.61q.076.264.077.552v.526H10.5v-.526q.001-.287.077-.552z");
}

.qnw63gbtm {
  stop-color: var(--svg-color--6099ff, #6099FF);
}

.qxfvirbev {
  d: path("M26.504 19.499h-4.945c-.154 0-.282.228-.282.381c.13 1.775 1.489 3.635 3.285 4.026c1.016-1 1.942-2.353 1.942-4.006z");
}

.rh8h2dekt {
  stop-color: var(--svg-color--ad9a37, #AD9A37);
  stop-opacity: 0;
}

.rkqt8gbwi {
  stop-color: var(--svg-color--62c3ff, #62C3FF);
  stop-opacity: 0;
}

.t772t0b3t {
  fill-rule: evenodd;
  d: path("M26.505 7.82a2 2 0 0 0-2-2h-4.69a2 2 0 0 0-1.924 1.448l4.192.355l4.344-.355a2 2 0 0 1 .078.551v.526L22.082 8l-4.269.346v.927l4.269.383l4.421-.383v1.078l-4.421-.288l-4.269.288v6.596c0 1.011-.337 2.017-1.025 2.757l-2.61 2.899c-.264.295-.58.705-.765 1.062c.167 1.401 4.968 6.59 6.086 5.43l5.623-5.743a5 5 0 0 0 1.382-3.45zm0 11.788l-4.678.39c-1.406 0 1.517 3.683 2.764 3.911l.532-.558a5 5 0 0 0 1.382-3.45z");
}

.uobv5pyzn {
  stop-color: var(--svg-color--fdec4b, #FDEC4B);
  stop-opacity: 0;
}

.vbtjx1b1n {
  stop-color: var(--svg-color--2542e3, #2542E3);
}

.vdv6v5bzl {
  stop-color: var(--svg-color--3f48c1, #3F48C1);
}

.wj_5kwb2m {
  stop-color: var(--svg-color--5b61ff, #5B61FF);
}

.wyiwufb2p {
  stop-color: var(--svg-color--fbcd56, #FBCD56);
}

.x3nn1sbzk {
  stop-color: var(--svg-color--fdec4b, #FDEC4B);
}

.x7znz0jyx {
  stop-color: var(--svg-color--ad9a37, #AD9A37);
}

.xin8r0bta {
  stop-color: var(--svg-color--69cbff, #69CBFF);
}

.xrsyvib1k {
  stop-color: var(--svg-color--65a9ff, #65A9FF);
  stop-opacity: 0;
}

.xt35vz-tz {
  stop-color: var(--svg-color--fdbb5c, #FDBB5C);
}

.y8ejde2uj {
  stop-color: var(--svg-color--3842ff, #3842FF);
}

.ye9q01rod {
  stop-color: var(--svg-color--4886d8, #4886D8);
}

.yoozydbbj {
  stop-color: var(--svg-color--4669ff, #4669FF);
}

.z-en13bqq {
  d: path("M26.504 9.272h-8.652v1.078h8.652z");
}

.zbj_02bwe {
  stop-color: var(--svg-color--3c6eff, #3C6EFF);
}

.zhao5abqf {
  stop-color: var(--svg-color--feec50, #FEEC50);
  stop-opacity: 0;
}

</style>
