<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#ir2DINc)" class="ac2g0fnpf"/><circle fill="url(#ifaGZdd)" class="ac2g0fnpf"/><circle fill="url(#i2bOMrb)" class="ac2g0fnpf"/><circle fill="url(#iavY3ob)" class="t4z2jsbwq"/><circle fill="url(#iPjZlPc)" class="t4z2jsbwq"/><circle fill="url(#ivo02je)" class="t4z2jsbwq"/><circle fill="url(#ijOu9Ae)" class="qsn6-bbkk"/><circle fill="url(#iS7x7Ac)" class="qsn6-bbkk"/><circle fill="url(#iImNOhb)" class="qsn6-bbkk"/><circle fill="url(#iBHghLb)" class="jfw9uebyz"/><circle fill="url(#iGFAaVb)" class="jfw9uebyz"/><circle fill="url(#iLqVDKS)" class="jfw9uebyz"/><circle fill="url(#irZKlzb)" class="ohts1rb2i"/><circle fill="url(#ixUWWLb)" class="ohts1rb2i"/><circle fill="url(#iSwt8Zc)" class="ohts1rb2i"/><circle fill="url(#ixygk1q)" class="rlnsib-lg"/><circle fill="url(#ig6LmJc)" class="rlnsib-lg"/><circle fill="url(#ih1a0zc)" class="rlnsib-lg"/><circle fill="url(#iFZem1c)" class="py3xc6v7u"/><circle fill="url(#ikKCQpT)" class="py3xc6v7u"/><circle fill="url(#i82UF5b)" class="py3xc6v7u"/><g filter="url(#iekNgmk)"><path fill="url(#io8Ikmd)" class="e5re9rbjq"/><path fill="url(#i4BL6jd)" class="e5re9rbjq"/><path fill="url(#iQ1ZAme)" class="e5re9rbjq"/></g><circle fill="url(#iHkwxcd)" class="oab4exbpy"/><circle fill="url(#i49c5md)" class="oab4exbpy"/><circle fill="url(#i8pviic)" class="doi-ubb3k"/><circle fill="url(#ikQqVhg)" class="doi-ubb3k"/><circle fill="url(#iStTNLy)" class="doi-ubb3k"/><circle fill="url(#ihYLf0k)" class="vgvz7rb5m"/><circle fill="url(#iBFcVyb)" class="vgvz7rb5m"/><circle fill="url(#iR15J1b)" class="vgvz7rb5m"/><circle fill="url(#iT50Kob)" class="cpd718yzr"/><circle fill="url(#imh2sBd)" class="cpd718yzr"/><g filter="url(#ix7vUkb)"><path stroke="url(#iTp1eFV)" class="e0a4qpbos"/></g><circle fill="url(#iSbeIze)" class="vevan7hzx"/><defs><radialGradient id="ir2DINc" cx="0" cy="0" r="1" gradientTransform="rotate(131.022 2.088 12.427)scale(3.95907)" gradientUnits="userSpaceOnUse"><stop class="oo-29byod"/><stop offset=".557" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="ifaGZdd" cx="0" cy="0" r="1" gradientTransform="matrix(.20805 -2.28125 4.40202 .40146 11.24 22.797)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="i2bOMrb" cx="0" cy="0" r="1" gradientTransform="matrix(-1.23934 -.4161 .79313 -2.36232 13.953 21.401)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="jq-x97b7u"/><stop offset="1" class="r1l_khbds"/></radialGradient><radialGradient id="iavY3ob" cx="0" cy="0" r="1" gradientTransform="rotate(145.768 2.538 9.706)scale(4.06814)" gradientUnits="userSpaceOnUse"><stop class="oo-29byod"/><stop offset=".557" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="iPjZlPc" cx="0" cy="0" r="1" gradientTransform="matrix(.20805 -2.28125 4.40202 .40146 8.053 19.625)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="ivo02je" cx="0" cy="0" r="1" gradientTransform="matrix(-1.00555 -.8322 1.58623 -1.91668 10.443 19.113)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="jq-x97b7u"/><stop offset="1" class="r1l_khbds"/></radialGradient><radialGradient id="ijOu9Ae" cx="0" cy="0" r="1" gradientTransform="rotate(132.797 5.275 4.993)scale(3.82771)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="oo-29byod"/><stop offset=".553" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="iS7x7Ac" cx="0" cy="0" r="1" gradientTransform="matrix(-.72817 -1.83774 3.5462 -1.40511 12.91 8.19)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="iImNOhb" cx="0" cy="0" r="1" gradientTransform="matrix(.58947 -1.7684 3.37073 1.12358 11.315 8.293)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="jq-x97b7u"/><stop offset="1" class="r1l_khbds"/></radialGradient><radialGradient id="iBHghLb" cx="0" cy="0" r="1" gradientTransform="rotate(138.734 7.71 10.34)scale(3.83801)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="oo-29byod"/><stop offset=".553" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="iGFAaVb" cx="0" cy="0" r="1" gradientTransform="matrix(.10402 -2.69614 3.32811 .1284 19.909 16.477)" gradientUnits="userSpaceOnUse"><stop class="jq-x97b7u"/><stop offset="1" class="r1l_khbds"/></radialGradient><radialGradient id="iLqVDKS" cx="0" cy="0" r="1" gradientTransform="matrix(-.72817 -1.83774 3.5462 -1.40511 20.425 16.424)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="irZKlzb" cx="0" cy="0" r="1" gradientTransform="rotate(134.31 7.759 5.335)scale(4.07036)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="p12k6ozdp"/><stop offset=".553" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="ixUWWLb" cx="0" cy="0" r="1" gradientTransform="matrix(-.72817 -1.83774 3.5462 -1.40511 17.191 7.01)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="iSwt8Zc" cx="0" cy="0" r="1" gradientTransform="rotate(-144.823 9.668 .335)scale(1.68524 2.651)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="jq-x97b7u"/><stop offset="1" class="r1l_khbds"/></radialGradient><radialGradient id="ixygk1q" cx="0" cy="0" r="1" gradientTransform="rotate(138.734 7.493 8.13)scale(3.83801)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="oo-29byod"/><stop offset=".553" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="ig6LmJc" cx="0" cy="0" r="1" gradientTransform="matrix(-.72817 -1.83774 3.5462 -1.40511 18.59 12.697)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="ih1a0zc" cx="0" cy="0" r="1" gradientTransform="rotate(107.745 6.561 10.349)scale(1.82032 2.247)" gradientUnits="userSpaceOnUse"><stop offset=".28" class="jq-x97b7u"/><stop offset="1" class="r1l_khbds"/></radialGradient><radialGradient id="iFZem1c" cx="0" cy="0" r="1" gradientTransform="rotate(132.117 6.224 14.411)scale(3.41238)" gradientUnits="userSpaceOnUse"><stop class="oo-29byod"/><stop offset=".557" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="ikKCQpT" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.70282 3.28586 0 20.234 22.792)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="i82UF5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.69348 1.14426 -2.22104 -1.34606 21.608 18.593)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="a52nh1b1f"/><stop offset="1" class="np0h8sbol"/></radialGradient><radialGradient id="iQ1ZAme" cx="0" cy="0" r="1" gradientTransform="matrix(0 .97088 -1.96846 0 15.983 23.69)" gradientUnits="userSpaceOnUse"><stop offset=".464" class="dgecsxyrw"/><stop offset="1" class="v2nb1aclh"/></radialGradient><radialGradient id="iHkwxcd" cx="0" cy="0" r="1" gradientTransform="rotate(134.31 8.392 12.938)scale(4.07036)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="p12k6ozdp"/><stop offset=".553" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="i49c5md" cx="0" cy="0" r="1" gradientTransform="rotate(-79.634 23.35 -3.422)scale(2.57227 4.96359)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="i8pviic" cx="0" cy="0" r="1" gradientTransform="rotate(137.261 3.324 5.563)scale(3.77092)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="oo-29byod"/><stop offset=".553" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="ikQqVhg" cx="0" cy="0" r="1" gradientTransform="matrix(-.72817 -1.83774 3.5462 -1.40511 9.714 11.346)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="iStTNLy" cx="0" cy="0" r="1" gradientTransform="matrix(.58947 -1.7684 3.37073 1.12358 8.12 11.45)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="jq-x97b7u"/><stop offset="1" class="r1l_khbds"/></radialGradient><radialGradient id="ihYLf0k" cx="0" cy="0" r="1" gradientTransform="rotate(148.98 2.619 7.397)scale(3.61501)" gradientUnits="userSpaceOnUse"><stop offset=".079" class="oo-29byod"/><stop offset=".557" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="iBFcVyb" cx="0" cy="0" r="1" gradientTransform="matrix(1.30816 -1.95173 3.76615 2.5243 5.796 14.952)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="iR15J1b" cx="0" cy="0" r="1" gradientTransform="rotate(-106.882 10.164 4.533)scale(1.71297 3.26509)" gradientUnits="userSpaceOnUse"><stop offset=".172" class="jq-x97b7u"/><stop offset="1" class="r1l_khbds"/></radialGradient><radialGradient id="iT50Kob" cx="0" cy="0" r="1" gradientTransform="rotate(134.31 8.981 6.953)scale(4.07036)" gradientUnits="userSpaceOnUse"><stop offset=".061" class="p12k6ozdp"/><stop offset=".553" class="s28rx442j"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><radialGradient id="imh2sBd" cx="0" cy="0" r="1" gradientTransform="rotate(-79.634 15.361 -6.747)scale(2.57227 4.96359)" gradientUnits="userSpaceOnUse"><stop class="owg-ogbih"/><stop offset="1" class="mdglmdbde"/></radialGradient><radialGradient id="iSbeIze" cx="0" cy="0" r="1" gradientTransform="rotate(145.84 5.369 13.228)scale(3.51991)" gradientUnits="userSpaceOnUse"><stop class="t0ep5_27v"/><stop offset=".557" class="a8nan7som"/><stop offset="1" class="h-l0-kb3l"/></radialGradient><linearGradient id="io8Ikmd" x1="15.983" x2="15.983" y1="26.372" y2="29.953" gradientUnits="userSpaceOnUse"><stop class="a575qwbtl"/><stop offset=".967" class="jqjt93b4y"/></linearGradient><linearGradient id="i4BL6jd" x1="13.445" x2="14.789" y1="25.5" y2="26.156" gradientUnits="userSpaceOnUse"><stop class="ysxow4pfb"/><stop offset="1" class="x6funoopb"/></linearGradient><linearGradient id="iTp1eFV" x1="17.055" x2="19.422" y1="24.063" y2="28.906" gradientUnits="userSpaceOnUse"><stop class="kxn6wwbul"/><stop offset="1" class="q3j0m9bhi"/></linearGradient><filter id="iekNgmk" width="8.604" height="7.411" x="11.681" y="22.542" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.827451 0 0 0 0 0.156863 0 0 0 0 0.6 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_17637"/></filter><filter id="ix7vUkb" width="5.031" height="7.031" x="15.516" y="22.714" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_17637" stdDeviation=".375"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:prayer-beads" /></template>
<style>
.a52nh1b1f {
  stop-color: var(--svg-color--f6a66c, #F6A66C);
}

.a575qwbtl {
  stop-color: var(--svg-color--f13a52, #F13A52);
}

.a8nan7som {
  stop-color: var(--svg-color--ffc145, #FFC145);
}

.ac2g0fnpf {
  cx: 11.672px;
  cy: 20.516px;
  r: 2.281px;
}

.cpd718yzr {
  cx: 19.234px;
  cy: 6.242px;
  r: 2.281px;
}

.dgecsxyrw {
  stop-color: var(--svg-color--d82a30, #D82A30);
}

.doi-ubb3k {
  cx: 8.523px;
  cy: 8.703px;
  r: 2.281px;
}

.e0a4qpbos {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("m16.64 23.839l2.782 4.781");
}

.e5re9rbjq {
  d: path("m15.068 22.792l.915.589l.915-.59l3.23 5.438a1.113 1.113 0 0 1-1.843 1.241l-.046-.061v.005c-.096-.146-.382-.423-.766-.363a.9.9 0 0 0-.591.337c-.237.385-.508.565-.905.565c-.404 0-.68-.207-.913-.58a.9.9 0 0 0-.58-.322c-.308-.048-.553.121-.687.265l-.117.154a1.113 1.113 0 0 1-1.843-1.24z");
}

.ft5dv1b6b {
  fill: none;
}

.h-l0-kb3l {
  stop-color: var(--svg-color--e7894a, #E7894A);
}

.jfw9uebyz {
  cx: 19.234px;
  cy: 13.781px;
  r: 2.281px;
}

.jq-x97b7u {
  stop-color: var(--svg-color--ec8c51, #EC8C51);
}

.jqjt93b4y {
  stop-color: var(--svg-color--dd238f, #DD238F);
}

.kxn6wwbul {
  stop-color: var(--svg-color--ff5d66, #FF5D66);
}

.mdglmdbde {
  stop-color: var(--svg-color--ea854f, #EA854F);
  stop-opacity: 0;
}

.np0h8sbol {
  stop-color: var(--svg-color--f6a66c, #F6A66C);
  stop-opacity: 0;
}

.oab4exbpy {
  cx: 22.516px;
  cy: 16.828px;
  r: 2.281px;
}

.ohts1rb2i {
  cx: 16px;
  cy: 4.367px;
  r: 2.281px;
}

.oo-29byod {
  stop-color: var(--svg-color--ffc69f, #FFC69F);
}

.owg-ogbih {
  stop-color: var(--svg-color--d76c85, #D76C85);
}

.p12k6ozdp {
  stop-color: var(--svg-color--ffdaa2, #FFDAA2);
}

.py3xc6v7u {
  cx: 20.234px;
  cy: 20.511px;
  r: 2.281px;
}

.q3j0m9bhi {
  stop-color: var(--svg-color--fd527d, #FD527D);
}

.qsn6-bbkk {
  cx: 11.719px;
  cy: 5.547px;
  r: 2.281px;
}

.r1l_khbds {
  stop-color: var(--svg-color--ec8c51, #EC8C51);
  stop-opacity: 0;
}

.rlnsib-lg {
  cx: 17.398px;
  cy: 10.055px;
  r: 2.281px;
}

.s28rx442j {
  stop-color: var(--svg-color--f9aa79, #F9AA79);
}

.t0ep5_27v {
  stop-color: var(--svg-color--ffe65c, #FFE65C);
}

.t4z2jsbwq {
  cx: 8.484px;
  cy: 17.344px;
  r: 2.281px;
}

.v2nb1aclh {
  stop-color: var(--svg-color--d82a30, #D82A30);
  stop-opacity: 0;
}

.vevan7hzx {
  cx: 15.977px;
  cy: 21.773px;
  r: 2.453px;
}

.vgvz7rb5m {
  cx: 7.328px;
  cy: 13px;
  r: 2.281px;
}

.x6funoopb {
  stop-color: var(--svg-color--d9363c, #D9363C);
  stop-opacity: 0;
}

.ysxow4pfb {
  stop-color: var(--svg-color--d9363c, #D9363C);
}

</style>
