<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijwje2j)"><path fill="url(#i4PSoKV)" class="lq3t2ab9i"/><path fill="url(#iis3kMe)" class="lq3t2ab9i"/><path fill="url(#isoj3te)" class="lq3t2ab9i"/><path fill="url(#isvUyzk)" class="lq3t2ab9i"/></g><path fill="url(#i05rxQe)" class="iox7j9bka"/><g filter="url(#ixUpKYd)"><path fill="url(#iPzwcsc)" class="c-o5xgb3o"/><path fill="url(#idaBCVZ)" class="c-o5xgb3o"/><path fill="url(#iX6caxd)" class="c-o5xgb3o"/><path fill="url(#iEN46Rb)" class="c-o5xgb3o"/></g><path fill="url(#iLe0Dte)" class="v7vln0vqb"/><path fill="url(#iq6jFxc)" class="v7vln0vqb"/><path fill="url(#iWQSzdc)" class="s8tjgr_ft"/><circle fill="url(#i2PAwZb)" class="qv6l4db9q"/><rect fill="url(#iLgZeSd)" class="m15r3hvpf"/><rect fill="url(#iA00eFd)" class="gjqj01sqc"/><path fill="url(#ifwxase)" class="yuod84b5x"/><path fill="url(#ioCowGe)" class="gdiwky6aw"/><defs><linearGradient id="i4PSoKV" x1="16" x2="16" y1="2" y2="20" gradientUnits="userSpaceOnUse"><stop class="fm2f1_tng"/><stop offset="1" class="q2exhp7ka"/></linearGradient><linearGradient id="iPzwcsc" x1="28.125" x2="9.063" y1="21.75" y2="21.688" gradientUnits="userSpaceOnUse"><stop class="elfiln2ui"/><stop offset="1" class="jedq8v5go"/></linearGradient><linearGradient id="iX6caxd" x1="16" x2="16" y1="19" y2="20.313" gradientUnits="userSpaceOnUse"><stop class="orynsew4z"/><stop offset="1" class="cixq9ibjq"/></linearGradient><linearGradient id="iLe0Dte" x1="16" x2="16" y1="20.375" y2="25.813" gradientUnits="userSpaceOnUse"><stop class="cna33ub3j"/><stop offset="1" class="g8hnd434x"/></linearGradient><linearGradient id="iq6jFxc" x1="16" x2="16" y1="19" y2="20" gradientUnits="userSpaceOnUse"><stop class="kskur3d7r"/><stop offset="1" class="eartdbb6i"/></linearGradient><linearGradient id="iWQSzdc" x1="13.688" x2="19.156" y1="13.313" y2="13.313" gradientUnits="userSpaceOnUse"><stop class="xu0bfcbcn"/><stop offset="1" class="ulk4htbpw"/></linearGradient><linearGradient id="i2PAwZb" x1="15.438" x2="18.875" y1="6.938" y2="11.25" gradientUnits="userSpaceOnUse"><stop class="to6oyj6dn"/><stop offset="1" class="o9lbq8bus"/></linearGradient><linearGradient id="iLgZeSd" x1="14.5" x2="14.5" y1="8" y2="9.5" gradientUnits="userSpaceOnUse"><stop class="vgm43qbnm"/><stop offset="1" class="jfmgs-bpf"/></linearGradient><linearGradient id="iA00eFd" x1="17.5" x2="17.5" y1="8" y2="9.5" gradientUnits="userSpaceOnUse"><stop class="tyyf8jbta"/><stop offset="1" class="z8k4rqb5y"/></linearGradient><linearGradient id="ifwxase" x1="16.5" x2="19.75" y1="4" y2="8" gradientUnits="userSpaceOnUse"><stop class="q-dl9jw8y"/><stop offset=".245" class="ve7idvtez"/><stop offset="1" class="aw6skr89i"/></linearGradient><linearGradient id="ioCowGe" x1="15.063" x2="12" y1="4.688" y2="8" gradientUnits="userSpaceOnUse"><stop class="q-dl9jw8y"/><stop offset="1" class="ptvtsq0xf"/></linearGradient><radialGradient id="iis3kMe" cx="0" cy="0" r="1" gradientTransform="rotate(119.814 9.007 6.932)scale(6.41105 6.17038)" gradientUnits="userSpaceOnUse"><stop class="mg54mdbov"/><stop offset="1" class="hgmibiwui"/></radialGradient><radialGradient id="isoj3te" cx="0" cy="0" r="1" gradientTransform="matrix(2.24996 5.06252 -4.39563 1.95357 18.875 10.688)" gradientUnits="userSpaceOnUse"><stop class="qdi75wb-d"/><stop offset="1" class="tkrqpxcnq"/></radialGradient><radialGradient id="isvUyzk" cx="0" cy="0" r="1" gradientTransform="matrix(1.25 -8.375 10.1559 1.5158 19.563 20.438)" gradientUnits="userSpaceOnUse"><stop class="ifpym1n0n"/><stop offset="1" class="ej6-dfben"/></radialGradient><radialGradient id="i05rxQe" cx="0" cy="0" r="1" gradientTransform="matrix(4.70588 -5.64705 9.7975 8.1646 13.804 20)" gradientUnits="userSpaceOnUse"><stop offset=".115" class="l48n39b-u"/><stop offset=".768" class="wef6k_fcl"/></radialGradient><radialGradient id="idaBCVZ" cx="0" cy="0" r="1" gradientTransform="rotate(-131.112 18.835 9.085)scale(9.125 17.0154)" gradientUnits="userSpaceOnUse"><stop class="a_8dk29cd"/><stop offset="1" class="itsw89bvr"/></radialGradient><radialGradient id="iEN46Rb" cx="0" cy="0" r="1" gradientTransform="matrix(-6.625 0 0 -.5 22.469 19.656)" gradientUnits="userSpaceOnUse"><stop class="xrxo4bcsx"/><stop offset="1" class="fikm-k36t"/></radialGradient><filter id="ijwje2j" width="18.25" height="18.1" x="7" y="2" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25" dy=".1"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.8 0 0 0 0 0.447059 0 0 0 0 0.517647 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3963"/></filter><filter id="ixUpKYd" width="22" height="11.25" x="5" y="18.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="-.25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.792157 0 0 0 0 0.388235 0 0 0 0 0.639216 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_3963"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:nesting-dolls" /></template>
<style>
.a_8dk29cd {
  stop-color: var(--svg-color--e1295e, #E1295E);
}

.aw6skr89i {
  stop-color: var(--svg-color--be8b7d, #BE8B7D);
}

.c-o5xgb3o {
  d: path("M5 20a1 1 0 0 1 1-1h20a1 1 0 0 1 1 1v1a9 9 0 0 1-9 9h-4a9 9 0 0 1-9-9z");
}

.cixq9ibjq {
  stop-color: var(--svg-color--d93e70, #D93E70);
  stop-opacity: 0;
}

.cna33ub3j {
  stop-color: var(--svg-color--d4c7df, #D4C7DF);
}

.eartdbb6i {
  stop-color: var(--svg-color--e9dfdf, #E9DFDF);
  stop-opacity: 0;
}

.ej6-dfben {
  stop-color: var(--svg-color--ff7288, #FF7288);
  stop-opacity: 0;
}

.elfiln2ui {
  stop-color: var(--svg-color--fa4e95, #FA4E95);
}

.fikm-k36t {
  stop-color: var(--svg-color--ff71b0, #FF71B0);
  stop-opacity: 0;
}

.fm2f1_tng {
  stop-color: var(--svg-color--f1358c, #F1358C);
}

.ft5dv1b6b {
  fill: none;
}

.g8hnd434x {
  stop-color: var(--svg-color--b59dcd, #B59DCD);
}

.gdiwky6aw {
  d: path("M16 4a4 4 0 0 0-4 4a4 4 0 0 0 4-4");
}

.gjqj01sqc {
  width: 1px;
  height: 1.5px;
  x: 17px;
  y: 8px;
  rx: 0.5px;
}

.hgmibiwui {
  stop-color: var(--svg-color--ff59aa, #FF59AA);
  stop-opacity: 0;
}

.ifpym1n0n {
  stop-color: var(--svg-color--ff7288, #FF7288);
}

.iox7j9bka {
  d: path("M21 20c-2-.5-4.5-6-5-8c-.5 2-3 7.5-5 8z");
}

.itsw89bvr {
  stop-color: var(--svg-color--e1295e, #E1295E);
  stop-opacity: 0;
}

.jedq8v5go {
  stop-color: var(--svg-color--c02d59, #C02D59);
}

.jfmgs-bpf {
  stop-color: var(--svg-color--342f36, #342F36);
}

.kskur3d7r {
  stop-color: var(--svg-color--e9dfdf, #E9DFDF);
}

.l48n39b-u {
  stop-color: var(--svg-color--bfb4b3, #BFB4B3);
}

.lq3t2ab9i {
  d: path("M9 14.5C7.613 16.58 7 18 7 20h18c0-2-.613-3.42-2-5.5C22 13 21.5 10 21.5 9c0-2.333-.5-7-5.5-7s-5.5 4.667-5.5 7c0 1-.5 4-1.5 5.5");
}

.m15r3hvpf {
  width: 1px;
  height: 1.5px;
  x: 14px;
  y: 8px;
  rx: 0.5px;
}

.mg54mdbov {
  stop-color: var(--svg-color--ff59aa, #FF59AA);
}

.o9lbq8bus {
  stop-color: var(--svg-color--ffefbf, #FFEFBF);
}

.orynsew4z {
  stop-color: var(--svg-color--d93e70, #D93E70);
}

.ptvtsq0xf {
  stop-color: var(--svg-color--935749, #935749);
}

.q-dl9jw8y {
  stop-color: var(--svg-color--794b41, #794B41);
}

.q2exhp7ka {
  stop-color: var(--svg-color--d82e4a, #D82E4A);
}

.qdi75wb-d {
  stop-color: var(--svg-color--ff739b, #FF739B);
}

.qv6l4db9q {
  cx: 16px;
  cy: 8px;
  r: 4px;
}

.s8tjgr_ft {
  d: path("M14.318 12a1.82 1.82 0 0 0-1.818 1.818c0 .1.081.182.182.182H14c.74 0 1.654-.644 2-1.242c.155-.25-.147-.254 0 0c.346.598 1.26 1.242 2 1.242h1.318c.1 0 .182-.081.182-.182A1.82 1.82 0 0 0 17.682 12z");
}

.tkrqpxcnq {
  stop-color: var(--svg-color--ff739b, #FF739B);
  stop-opacity: 0;
}

.to6oyj6dn {
  stop-color: var(--svg-color--e7a668, #E7A668);
}

.tyyf8jbta {
  stop-color: var(--svg-color--685d73, #685D73);
}

.ulk4htbpw {
  stop-color: var(--svg-color--dd647a, #DD647A);
}

.v7vln0vqb {
  d: path("M9.227 19h13.546v1.813a5 5 0 0 1-5 5h-3.546a5 5 0 0 1-5-5z");
}

.ve7idvtez {
  stop-color: var(--svg-color--81534a, #81534A);
}

.vgm43qbnm {
  stop-color: var(--svg-color--463552, #463552);
}

.wef6k_fcl {
  stop-color: var(--svg-color--f9f1f7, #F9F1F7);
}

.xrxo4bcsx {
  stop-color: var(--svg-color--ff71b0, #FF71B0);
}

.xu0bfcbcn {
  stop-color: var(--svg-color--b42948, #B42948);
}

.yuod84b5x {
  d: path("M16 4a4 4 0 0 1 4 4a4 4 0 0 1-4-4");
}

.z8k4rqb5y {
  stop-color: var(--svg-color--5d5960, #5D5960);
}

</style>
