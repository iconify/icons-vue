<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#ik9o6Ph)"><g filter="url(#iYqgDTb)"><path fill="url(#if3IMze)" class="q-k57ac5p"/><path fill="url(#iAKb1Bp)" class="q-k57ac5p"/></g><path class="gplvp_-3q"/><path stroke="url(#ibGfzpX)" class="ae06482jq"/><path stroke="url(#ioDQMVb)" class="ae06482jq"/><g filter="url(#ibzEEnz)"><path stroke="url(#iVB8ErH)" class="xb4d-vbry"/></g><g filter="url(#iUOnI2b)"><path stroke="url(#iYsLl2g)" class="zawxpd_iz"/></g><g filter="url(#i19YnVb)"><path fill="url(#iJpHVpa)" class="pwu16bcri"/></g><path class="f69ya9jtw"/><path stroke="url(#i90y27d)" class="wnsgh692y"/><path stroke="url(#iKYibSc)" class="wnsgh692y"/><path stroke="url(#iRbxUiw)" class="wnsgh692y"/><g filter="url(#i0ISE1b)"><path stroke="url(#ima7Y0d)" class="k69kcjbtt"/></g><g filter="url(#iF8l89e)"><path stroke="url(#ilglQXd)" class="ub9dwaccr"/></g><path fill="url(#iolQEEe)" class="wgrefs-2j"/><path fill="url(#ihm3qsc)" class="wgrefs-2j"/><path fill="url(#iQQIHQe)" class="wgrefs-2j"/><path fill="url(#iZY421b)" class="wgrefs-2j"/><path fill="url(#ie8LC8b)" class="wgrefs-2j"/><path fill="url(#idzi0Gc)" class="wgrefs-2j"/><path fill="url(#ioLV6ud)" class="wgrefs-2j"/><path fill="url(#i2UY91b)" class="wgrefs-2j"/><path fill="url(#iFRtIXb)" class="kv_wwab2a"/><path fill="url(#iim2bSc)" class="zqsee0cdr"/><path fill="url(#iEmec2c)" class="i7uducb-u"/><path fill="url(#iKF3jec)" class="i7uducb-u"/><path fill="url(#i4jp5Rd)" class="swrhspbnz"/><path fill="url(#irL3Brd)" class="swrhspbnz"/><g filter="url(#igEWZZo)"><path class="ou6wuob1r"/></g><g filter="url(#imYjRCd)"><path class="ea2_h6iqi"/></g><path fill="url(#ikIOKxc)" class="mhbwcearh"/><path fill="url(#itB0kPb)" class="mhbwcearh"/><path fill="url(#iAVBYle)" class="d16cszb4e"/><path fill="url(#iL4Z1QQ)" class="d16cszb4e"/><path fill="url(#iFLgDiG)" class="xhm-z6bls"/><path fill="url(#iDp16Ae)" class="xhm-z6bls"/><path fill="url(#i9RJhmd)" class="xhm-z6bls"/><path fill="url(#iYnRFcd)" class="xhm-z6bls"/><path fill="url(#i2sGmzd)" class="xhm-z6bls"/><path fill="url(#iltPT4i)" class="cmvoh8b3p"/><path fill="url(#iGJlCxd)" class="cmvoh8b3p"/><path fill="url(#ijLNWjb)" class="cmvoh8b3p"/><path fill="url(#if1DeRd)" class="cmvoh8b3p"/><path fill="url(#idQpUte)" class="cmvoh8b3p"/><g filter="url(#iJczQwd)"><ellipse class="ryut2ac8z"/></g><g filter="url(#ibeUcId)"><path class="gzpiht87f"/></g><path stroke="url(#iNcV9EB)" class="yrzumdtui"/><path stroke="url(#iMjD8rc)" class="yrzumdtui"/><path stroke="url(#iTp3ICd)" class="yrzumdtui"/><path stroke="url(#iXzu1KE)" class="munfs_wsm"/><path stroke="url(#ieseVPD)" class="munfs_wsm"/></g><defs><radialGradient id="ioDQMVb" cx="0" cy="0" r="1" gradientTransform="rotate(166.185 4.19 5.339)scale(4.95587 10.6481)" gradientUnits="userSpaceOnUse"><stop offset=".784" class="k5a4uxbmh"/><stop offset="1" class="x2h0o8bwl"/></radialGradient><radialGradient id="iKYibSc" cx="0" cy="0" r="1" gradientTransform="matrix(4.8125 1.1834 -2.54264 10.34007 23.046 9.522)" gradientUnits="userSpaceOnUse"><stop offset=".784" class="k5a4uxbmh"/><stop offset="1" class="x2h0o8bwl"/></radialGradient><radialGradient id="iRbxUiw" cx="0" cy="0" r="1" gradientTransform="matrix(-.40624 1.75 -2.84634 -.66074 28.503 7.257)" gradientUnits="userSpaceOnUse"><stop class="v03uahbxj"/><stop offset="1" class="ajjn3272v"/></radialGradient><radialGradient id="iolQEEe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25006 17.49996 -32.96335 -6.1219 20.128 11.46)" gradientUnits="userSpaceOnUse"><stop class="o2llgzb9s"/><stop offset="1" class="n8yhwobbb"/></radialGradient><radialGradient id="ihm3qsc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.25004 -5.56245 19.5327 -18.43567 28.94 26.898)" gradientUnits="userSpaceOnUse"><stop offset=".094" class="en2bkeb1v"/><stop offset=".647" class="pw3o6ibhn"/></radialGradient><radialGradient id="iQQIHQe" cx="0" cy="0" r="1" gradientTransform="matrix(0 4.375 -6.91532 0 9.065 20.398)" gradientUnits="userSpaceOnUse"><stop offset=".479" class="aa8xlfbom"/><stop offset="1" class="s_irdnbpj"/></radialGradient><radialGradient id="iZY421b" cx="0" cy="0" r="1" gradientTransform="scale(5.53226 3.5)rotate(90 -.895 5.2)" gradientUnits="userSpaceOnUse"><stop offset=".278" class="dmksxt5pw"/><stop offset="1" class="s_irdnbpj"/></radialGradient><radialGradient id="idzi0Gc" cx="0" cy="0" r="1" gradientTransform="matrix(-16.81257 11.37484 -12.34415 -18.24527 17.503 13.835)" gradientUnits="userSpaceOnUse"><stop offset=".731" class="ltk6nsb0j"/><stop offset="1" class="bjl0fzwmc"/></radialGradient><radialGradient id="ioLV6ud" cx="0" cy="0" r="1" gradientTransform="matrix(0 -20.375 19.4539 0 16.006 25.71)" gradientUnits="userSpaceOnUse"><stop offset=".868" class="daora8b7o"/><stop offset="1" class="jxrnq5byv"/></radialGradient><radialGradient id="i2UY91b" cx="0" cy="0" r="1" gradientTransform="matrix(3.6875 5.3125 -5.8664 4.07198 11.565 10.773)" gradientUnits="userSpaceOnUse"><stop class="wn1ake54r"/><stop offset="1" class="x4xw3-lqg"/></radialGradient><radialGradient id="iKF3jec" cx="0" cy="0" r="1" gradientTransform="rotate(109.567 -3.027 13.706)scale(7.89334 19.6076)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="swdq_6bjc"/><stop offset="1" class="lnp5ixqgv"/></radialGradient><radialGradient id="irL3Brd" cx="0" cy="0" r="1" gradientTransform="matrix(1.9965 8.4125 -20.89725 4.95947 20.819 21.147)" gradientUnits="userSpaceOnUse"><stop offset=".652" class="swdq_6bjc"/><stop offset="1" class="lnp5ixqgv"/></radialGradient><radialGradient id="iFLgDiG" cx="0" cy="0" r="1" gradientTransform="matrix(-3.37763 8.72384 -8.64277 -3.34624 19.378 22.736)" gradientUnits="userSpaceOnUse"><stop class="wks2v-oxj"/><stop offset="1" class="ier_gdbyu"/></radialGradient><radialGradient id="iDp16Ae" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.09375 14.8776 0 16 31.741)" gradientUnits="userSpaceOnUse"><stop class="lnp5ixqgv"/><stop offset="1" class="swdq_6bjc"/></radialGradient><radialGradient id="i9RJhmd" cx="0" cy="0" r="1" gradientTransform="rotate(145.763 4.427 14.959)scale(7.10955 6.98471)" gradientUnits="userSpaceOnUse"><stop offset=".678" class="ltk6nsb0j"/><stop offset="1" class="bjl0fzwmc"/></radialGradient><radialGradient id="iYnRFcd" cx="0" cy="0" r="1" gradientTransform="matrix(5.5 -6.35 6.2385 5.40342 15.44 27.46)" gradientUnits="userSpaceOnUse"><stop offset=".61" class="eoegembrw"/><stop offset="1" class="z-p8e951b"/></radialGradient><radialGradient id="i2sGmzd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -6.0375 9.5625 0 15.44 27.148)" gradientUnits="userSpaceOnUse"><stop offset=".561" class="eoegembrw"/><stop offset="1" class="z-p8e951b"/></radialGradient><radialGradient id="iGJlCxd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.3423 1.48858 -2.72652 -2.4586 16.324 21.725)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="ueu24dben"/><stop offset=".956" class="vylhu7i4w"/></radialGradient><radialGradient id="idQpUte" cx="0" cy="0" r="1" gradientTransform="rotate(-161.02 11.35 10.144)scale(5.71706 2.5936)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="lm-pdjb-m"/><stop offset=".935" class="z17z3-a-u"/></radialGradient><radialGradient id="iNcV9EB" cx="0" cy="0" r="1" gradientTransform="matrix(-.62502 3.26563 -2.81412 -.5386 14.706 24.82)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset=".589" class="ajx6-mbfo"/><stop offset=".747" class="z6-ovubwn"/></radialGradient><radialGradient id="iMjD8rc" cx="0" cy="0" r="1" gradientTransform="matrix(-.60937 .53125 -.6777 -.77736 15.534 25.913)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset="1" class="yx-bms0gr"/></radialGradient><radialGradient id="iTp3ICd" cx="0" cy="0" r="1" gradientTransform="matrix(.875 1.04687 -.78497 .6561 12.737 24.523)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset="1" class="yx-bms0gr"/></radialGradient><radialGradient id="iXzu1KE" cx="0" cy="0" r="1" gradientTransform="rotate(81.355 -5.885 22.951)scale(2.70258 2.8068)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset=".589" class="ajx6-mbfo"/><stop offset=".747" class="z6-ovubwn"/></radialGradient><radialGradient id="ieseVPD" cx="0" cy="0" r="1" gradientTransform="matrix(.92187 .875 -.96783 1.01968 15.706 25.038)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset="1" class="yx-bms0gr"/></radialGradient><linearGradient id="if3IMze" x1="8.575" x2="8.206" y1="8.33" y2="11.351" gradientUnits="userSpaceOnUse"><stop class="gibikcbgp"/><stop offset="1" class="fof9vp_uc"/></linearGradient><linearGradient id="iAKb1Bp" x1="8.721" x2="7.753" y1="11.194" y2="10.288" gradientUnits="userSpaceOnUse"><stop class="xogze0mqi"/><stop offset=".738" class="m6xzd0bxb"/></linearGradient><linearGradient id="ibGfzpX" x1="9.69" x2="7.128" y1="12.023" y2="9.272" gradientUnits="userSpaceOnUse"><stop class="ozvikqbix"/><stop offset="1" class="gitsnfbpu"/></linearGradient><linearGradient id="iVB8ErH" x1="11.049" x2="6.331" y1="8.866" y2="8.007" gradientUnits="userSpaceOnUse"><stop class="p03wo6b8c"/><stop offset="1" class="umn9y9bop"/></linearGradient><linearGradient id="iYsLl2g" x1="10.475" x2="5.756" y1="10.62" y2="9.761" gradientUnits="userSpaceOnUse"><stop class="p03wo6b8c"/><stop offset="1" class="umn9y9bop"/></linearGradient><linearGradient id="iJpHVpa" x1="24.006" x2="24.534" y1="7.772" y2="10.706" gradientUnits="userSpaceOnUse"><stop class="gibikcbgp"/><stop offset="1" class="fof9vp_uc"/></linearGradient><linearGradient id="i90y27d" x1="24.006" x2="25.453" y1="6.429" y2="9.272" gradientUnits="userSpaceOnUse"><stop class="ozvikqbix"/><stop offset="1" class="gitsnfbpu"/></linearGradient><linearGradient id="ima7Y0d" x1="21.531" x2="26.25" y1="8.866" y2="8.007" gradientUnits="userSpaceOnUse"><stop class="p03wo6b8c"/><stop offset="1" class="umn9y9bop"/></linearGradient><linearGradient id="ilglQXd" x1="22.106" x2="26.825" y1="10.62" y2="9.761" gradientUnits="userSpaceOnUse"><stop class="p03wo6b8c"/><stop offset="1" class="umn9y9bop"/></linearGradient><linearGradient id="ie8LC8b" x1="3.378" x2="7.253" y1="12.898" y2="16.46" gradientUnits="userSpaceOnUse"><stop class="bjl0fzwmc"/><stop offset=".708" class="ltk6nsb0j"/></linearGradient><linearGradient id="iFRtIXb" x1="13.878" x2="11.377" y1="15.96" y2="28.898" gradientUnits="userSpaceOnUse"><stop class="vn7ncpb8d"/><stop offset="1" class="fjauwqy9p"/></linearGradient><linearGradient id="iim2bSc" x1="21.951" x2="26.628" y1="17.835" y2="28.335" gradientUnits="userSpaceOnUse"><stop class="k72yrvb2q"/><stop offset="1" class="fjauwqy9p"/></linearGradient><linearGradient id="iEmec2c" x1="13.436" x2="13.436" y1="16.82" y2="31.085" gradientUnits="userSpaceOnUse"><stop class="xmfqxbb8v"/><stop offset="1" class="w6na61tgg"/></linearGradient><linearGradient id="i4jp5Rd" x1="25.381" x2="25.381" y1="16.82" y2="31.772" gradientUnits="userSpaceOnUse"><stop class="c-06avbju"/><stop offset="1" class="w6na61tgg"/></linearGradient><linearGradient id="ikIOKxc" x1="20.715" x2="19.89" y1="19.5" y2="19.5" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="itB0kPb" x1="21.037" x2="21.037" y1="21.525" y2="19.935" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iAVBYle" x1="12.668" x2="11.842" y1="19.5" y2="19.5" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iL4Z1QQ" x1="12.989" x2="12.989" y1="21.525" y2="19.935" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iltPT4i" x1="17.228" x2="14.397" y1="20.844" y2="23.321" gradientUnits="userSpaceOnUse"><stop offset=".191" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="ijLNWjb" x1="16.359" x2="16.359" y1="21.979" y2="20.425" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="if1DeRd" x1="17.127" x2="17.127" y1="24.584" y2="22.235" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><filter id="iYqgDTb" width="9.166" height="9.264" x="4.646" y="6.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.26434 0 0 0 0 0.25276 0 0 0 0 0.2875 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_1998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.26434 0 0 0 0 0.25276 0 0 0 0 0.2875 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_1998" result="effect2_innerShadow_28327_1998"/></filter><filter id="ibzEEnz" width="5.922" height="2.266" x="5.94" y="6.882" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1998" stdDeviation=".15"/></filter><filter id="iUOnI2b" width="1.713" height="3.872" x="6.295" y="8.776" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1998" stdDeviation=".125"/></filter><filter id="i19YnVb" width="9.166" height="9.264" x="19.268" y="6.743" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.26434 0 0 0 0 0.25276 0 0 0 0 0.2875 0 0 0 0.5 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_1998"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy="2"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.26434 0 0 0 0 0.25276 0 0 0 0 0.2875 0 0 0 0.5 0"/><feBlend in2="effect1_innerShadow_28327_1998" result="effect2_innerShadow_28327_1998"/></filter><filter id="i0ISE1b" width="1.922" height="5.687" x="25.69" y="7.554" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1998" stdDeviation=".15"/></filter><filter id="iF8l89e" width="4.181" height="1.962" x="21.74" y="8.416" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1998" stdDeviation=".125"/></filter><filter id="igEWZZo" width="2.5" height="4" x="18.624" y="17.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1998" stdDeviation=".25"/></filter><filter id="imYjRCd" width="2.5" height="4" x="10.505" y="17.734" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1998" stdDeviation=".25"/></filter><filter id="iJczQwd" width="10.953" height="5.839" x="20.144" y="16.371" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1998" stdDeviation="1"/></filter><filter id="ibeUcId" width="16.438" height="16.25" x="13.925" y="5.621" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1998" stdDeviation="1.5"/></filter><clipPath id="ik9o6Ph"><path class="wycjhibbk"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:raccoon" /></template>
<style>
.aa8xlfbom {
  stop-color: var(--svg-color--9c93a7, #9C93A7);
}

.ae06482jq {
  stroke-width: var(--svg-stroke-width--1-6px, 1.6px);
  d: path("m7.194 13.592l.581.702l.621-.667l3.11-3.344l.61-.656l-.721-.533C9.973 8.045 8.085 7.632 6.97 7.548c-.915-.07-1.58.695-1.521 1.533c.137 1.998.985 3.594 1.744 4.51Z");
}

.ajjn3272v {
  stop-color: var(--svg-color--bfbdc2, #BFBDC2);
  stop-opacity: 0;
}

.ajx6-mbfo {
  stop-color: var(--svg-color--4e4647, #4E4647);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.bjl0fzwmc {
  stop-color: var(--svg-color--e1dde6, #E1DDE6);
}

.c-06avbju {
  stop-color: var(--svg-color--868488, #868488);
}

.cmvoh8b3p {
  d: path("m14.075 22.77l1.25 1.26c.38.38.99.38 1.36 0l1.25-1.26c.61-.61.18-1.66-.68-1.66h-2.5c-.86 0-1.29 1.05-.68 1.66");
}

.d16cszb4e {
  d: path("M12.005 21c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.daora8b7o {
  stop-color: var(--svg-color--b0a9b8, #B0A9B8);
  stop-opacity: 0;
}

.dmksxt5pw {
  stop-color: var(--svg-color--a99eb6, #A99EB6);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.ea2_h6iqi {
  fill: var(--svg-color--574f5e, #574F5E);
  d: path("M11.755 21.234c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.en2bkeb1v {
  stop-color: var(--svg-color--978ea0, #978EA0);
}

.eoegembrw {
  stop-color: var(--svg-color--aba5b1, #ABA5B1);
  stop-opacity: 0;
}

.ew8h6t88b {
  stop-color: var(--svg-color--261317, #261317);
}

.f69ya9jtw {
  stroke: var(--svg-color--aeaab3, #AEAAB3);
  stroke-width: var(--svg-stroke-width--1-6px, 1.6px);
  d: path("m25.387 13.592l-.582.702l-.62-.667l-3.11-3.344l-.61-.656l.72-.533c1.423-1.049 3.312-1.462 4.425-1.546c.915-.07 1.579.695 1.521 1.533c-.137 1.998-.985 3.594-1.744 4.51Z");
}

.fjauwqy9p {
  stop-color: var(--svg-color--b7a8c7, #B7A8C7);
}

.fof9vp_uc {
  stop-color: var(--svg-color--77747c, #77747C);
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.gibikcbgp {
  stop-color: var(--svg-color--656169, #656169);
}

.gitsnfbpu {
  stop-color: var(--svg-color--a19ea5, #A19EA5);
  stop-opacity: 0;
}

.gplvp_-3q {
  stroke: var(--svg-color--aeaab3, #AEAAB3);
  stroke-width: var(--svg-stroke-width--1-6px, 1.6px);
  d: path("m7.194 13.592l.581.702l.621-.667l3.11-3.344l.61-.656l-.721-.533C9.973 8.045 8.085 7.632 6.97 7.548c-.915-.07-1.58.695-1.521 1.533c.137 1.998.985 3.594 1.744 4.51Z");
}

.gzpiht87f {
  stroke: var(--svg-color--e1dde6, #E1DDE6);
  stroke-linecap: round;
  d: path("M17.425 9.121c.625.021 2.175.425 3.375 1.875s4.542 5.521 6.063 7.375");
}

.i7uducb-u {
  d: path("M11.689 16.82a2.15 2.15 0 0 0-1.69.77l-2.6 2.99c-1.97 2.27-1.38 5.79 1.25 7.25c1.56.87 3.3 1.47 5.14 1.73V19.01c0-1.18-.93-2.17-2.1-2.19");
}

.ier_gdbyu {
  stop-color: var(--svg-color--978ea2, #978EA2);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jxrnq5byv {
  stop-color: var(--svg-color--b0a9b8, #B0A9B8);
}

.k5a4uxbmh {
  stop-color: var(--svg-color--bdbac0, #BDBAC0);
  stop-opacity: 0;
}

.k69kcjbtt {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M27.018 7.929c.438.515.266 3.031-.953 4.937");
}

.k72yrvb2q {
  stop-color: var(--svg-color--e6e1ed, #E6E1ED);
}

.kv_wwab2a {
  d: path("M11.785 15.21h-.08c-1.11 0-2.15.49-2.87 1.33l-2.59 2.98a6.35 6.35 0 0 0-1.49 5.13c2.64 2.98 6.45 4.9 10.72 5.05V19.01c-.01-2.06-1.66-3.76-3.69-3.8");
}

.lm-pdjb-m {
  stop-color: var(--svg-color--5c5458, #5C5458);
  stop-opacity: 0;
}

.lnp5ixqgv {
  stop-color: var(--svg-color--8664a8, #8664A8);
}

.ltk6nsb0j {
  stop-color: var(--svg-color--e1dde6, #E1DDE6);
  stop-opacity: 0;
}

.m6xzd0bxb {
  stop-color: var(--svg-color--5a585d, #5A585D);
  stop-opacity: 0;
}

.mhbwcearh {
  d: path("M20.053 21c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.munfs_wsm {
  stroke-linecap: round;
  d: path("M19.102 25.398c0 .53-.329 1.507-1.516 1.507S16.052 25.978 16 25.5");
}

.n8yhwobbb {
  stop-color: var(--svg-color--b0a7b9, #B0A7B9);
}

.o2llgzb9s {
  stop-color: var(--svg-color--c6c5c7, #C6C5C7);
}

.ou6wuob1r {
  fill: var(--svg-color--574f5e, #574F5E);
  d: path("M19.874 21.234c-.41 0-.75-.34-.75-.75v-1.5c0-.41.34-.75.75-.75s.75.34.75.75v1.5c0 .42-.34.75-.75.75");
}

.ozvikqbix {
  stop-color: var(--svg-color--a19ea5, #A19EA5);
}

.p03wo6b8c {
  stop-color: var(--svg-color--cbc7ce, #CBC7CE);
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.pw3o6ibhn {
  stop-color: var(--svg-color--978ea0, #978EA0);
  stop-opacity: 0;
}

.pwu16bcri {
  d: path("M26.333 9.026c-.124 1.808-.894 3.248-1.563 4.056l-3.11-3.344c1.257-.927 2.98-1.315 4.01-1.393c.391-.03.69.29.663.681");
}

.q-k57ac5p {
  d: path("M6.248 9.026c.124 1.808.894 3.248 1.563 4.056l3.109-3.344c-1.257-.927-2.98-1.315-4.01-1.393c-.39-.03-.69.29-.662.681");
}

.ryut2ac8z {
  cx: 25.62px;
  cy: 19.291px;
  fill: var(--svg-color--e1dde6, #E1DDE6);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  rx: 3.476px;
  ry: 0.919px;
}

.s_irdnbpj {
  stop-color: var(--svg-color--a098a9, #A098A9);
  stop-opacity: 0;
}

.swdq_6bjc {
  stop-color: var(--svg-color--8664a8, #8664A8);
  stop-opacity: 0;
}

.swrhspbnz {
  d: path("M20.275 16.82c.68-.01 1.29.29 1.69.77l2.6 2.99c1.97 2.27 1.38 5.79-1.25 7.25c-1.56.87-3.3 1.47-5.14 1.73V19.01c0-1.18.93-2.17 2.1-2.19");
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ub9dwaccr {
  stroke-linecap: round;
  stroke-opacity: 0.3;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M25.596 8.741c-1.114 0-3.078.73-3.53 1.313");
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.umn9y9bop {
  stop-color: var(--svg-color--cbc7ce, #CBC7CE);
  stop-opacity: 0;
}

.v03uahbxj {
  stop-color: var(--svg-color--bfbdc2, #BFBDC2);
}

.vn7ncpb8d {
  stop-color: var(--svg-color--e1daea, #E1DAEA);
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.w6na61tgg {
  stop-color: var(--svg-color--574f60, #574F60);
}

.wgrefs-2j {
  d: path("M23.505 10.72c-.06-.08-.13-.16-.2-.23a9.6 9.6 0 0 0-7.3-3.34c-2.92 0-5.53 1.29-7.31 3.33c-.06.08-.13.16-.19.24l-5.8 6.92c-.74.89-.91 2.12-.44 3.17c2.35 5.24 7.62 8.9 13.74 8.9s11.39-3.66 13.74-8.91a3 3 0 0 0-.44-3.17z");
}

.wks2v-oxj {
  stop-color: var(--svg-color--dfdbe4, #DFDBE4);
}

.wn1ake54r {
  stop-color: var(--svg-color--b6b2b9, #B6B2B9);
}

.wnsgh692y {
  stroke-width: var(--svg-stroke-width--1-6px, 1.6px);
  d: path("m25.387 13.592l-.582.702l-.62-.667l-3.11-3.344l-.61-.656l.72-.533c1.423-1.049 3.312-1.462 4.425-1.546c.915-.07 1.579.695 1.521 1.533c-.137 1.998-.985 3.594-1.744 4.51Z");
}

.wycjhibbk {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h32v32H0z");
}

.x2h0o8bwl {
  stop-color: var(--svg-color--bdbac0, #BDBAC0);
}

.x4xw3-lqg {
  stop-color: var(--svg-color--b6b2b9, #B6B2B9);
  stop-opacity: 0;
}

.xb4d-vbry {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M6.315 7.257c.906.01 3.578.469 5.172 1.515");
}

.xhm-z6bls {
  d: path("M21.375 24.911c0-2.094-1.67-3.801-3.74-3.801h-3.27c-2.06 0-3.74 1.697-3.74 3.801c0 2.612 2.01 4.777 4.58 4.92c.27.01.54.02.8.02s.53-.01.79-.02c2.57-.133 4.58-2.298 4.58-4.92");
}

.xmfqxbb8v {
  stop-color: var(--svg-color--6f6c72, #6F6C72);
}

.xogze0mqi {
  stop-color: var(--svg-color--5a585d, #5A585D);
}

.yrzumdtui {
  stroke-linecap: round;
  d: path("M12.898 25.398c0 .53.329 1.507 1.516 1.507S15.948 25.978 16 25.5");
}

.yx-bms0gr {
  stop-color: var(--svg-color--261317, #261317);
  stop-opacity: 0;
}

.z-p8e951b {
  stop-color: var(--svg-color--aba5b1, #ABA5B1);
}

.z17z3-a-u {
  stop-color: var(--svg-color--5c5458, #5C5458);
}

.z6-ovubwn {
  stop-color: var(--svg-color--2f172a, #2F172A);
}

.zawxpd_iz {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-15px, 0.15px);
  d: path("M6.62 9.1c.086 1.04.61 2.641 1.062 3.223");
}

.zqsee0cdr {
  d: path("M20.245 15.21h.08c1.11 0 2.15.49 2.87 1.33l2.59 2.98a6.35 6.35 0 0 1 1.49 5.13c-2.64 2.98-6.45 4.9-10.72 5.05V19.01c.01-2.06 1.66-3.76 3.69-3.8");
}

</style>
