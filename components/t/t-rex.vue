<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="rvfe1cczh"/><path fill="url(#imV6med)" class="od7u76g1q"/><path fill="url(#iOsHwae)" class="od7u76g1q"/><path fill="url(#iHPs4yd)" class="od7u76g1q"/><path fill="url(#i5QiI1F)" class="od7u76g1q"/><path class="ztow04bsq"/><path fill="url(#iWnRm8d)" class="tzsqzub9w"/><path fill="url(#irTweYd)" class="tzsqzub9w"/><path fill="url(#ivnfqde)" class="tzsqzub9w"/><path fill="url(#ioWgwEb)" class="tzsqzub9w"/><path fill="url(#iHatWRc)" class="tzsqzub9w"/><path fill="url(#iuRivhd)" class="tzsqzub9w"/><path fill="url(#iaGTi4b)" class="tzsqzub9w"/><path class="k75dufpfi"/><path fill="url(#iHw5A9d)" class="wzuq7c62u"/><path fill="url(#iAArNic)" class="wzuq7c62u"/><path fill="url(#ik74yfP)" class="wzuq7c62u"/><path fill="url(#ichTwWd)" class="wzuq7c62u"/><path fill="url(#ibs77od)" class="wzuq7c62u"/><path fill="url(#iCJdgxd)" class="q8wz9rrne"/><path fill="url(#i80UkSA)" class="q8wz9rrne"/><path fill="url(#istA74d)" class="q8wz9rrne"/><path fill="url(#if0qaec)" class="q8wz9rrne"/><path fill="url(#iqYWDVd)" class="q8wz9rrne"/><path fill="url(#ix8u6pc)" class="q8wz9rrne"/><path fill="url(#iKDMuGe)" class="ro_gwf7cc"/><path fill="url(#ic2mHNb)" class="ro_gwf7cc"/><path fill="url(#ifwYHac)" class="ro_gwf7cc"/><path fill="url(#ixtgImd)" class="ro_gwf7cc"/><path fill="url(#iJZ3M5b)" class="zb3x01b2s"/><path fill="url(#igOexoe)" class="zb3x01b2s"/><path fill="url(#iArbKZc)" class="zb3x01b2s"/><path fill="url(#iOT6BKc)" class="zb3x01b2s"/><path fill="url(#i14hZmd)" class="zb3x01b2s"/><path fill="url(#ikvm7Ee)" class="zb3x01b2s"/><path class="zmv1trbmg"/><path fill="url(#i1hZ4lh)" class="u-frw-bzk"/><path fill="url(#iaXLYHd)" class="u-frw-bzk"/><path fill="url(#i4mj7WW)" class="u-frw-bzk"/><path fill="url(#i1W38Db)" class="u-frw-bzk"/><path fill="url(#iDf2L8c)" class="u-frw-bzk"/><g filter="url(#iA5lyDl)"><rect transform="rotate(45.994 9.115 5.066)" class="lr2r0bcao"/></g><rect fill="url(#ir9aNHd)" transform="rotate(45.994 9.388 4.996)" class="effua5baj"/><rect fill="url(#iiBz49b)" transform="rotate(45.994 9.388 4.996)" class="effua5baj"/><rect fill="url(#iT08sRb)" transform="rotate(45.994 9.388 4.996)" class="effua5baj"/><g filter="url(#imycjxd)"><path fill="url(#iU8Qrxd)" class="cxcirnzkd"/></g><g filter="url(#ib7C3qd)"><path stroke="url(#iHakaZq)" class="ra1nwe49a"/></g><path fill="url(#ij2qqUb)" clip-rule="evenodd" class="j477ljb4v"/><path fill="url(#imEp2ud)" clip-rule="evenodd" class="j477ljb4v"/><path fill="url(#i6I0lsb)" clip-rule="evenodd" class="j477ljb4v"/><path fill="url(#iPwZosd)" class="wf1bjvb8a"/><path fill="url(#ikQdc8d)" class="wf1bjvb8a"/><path fill="url(#iLVVivb)" class="wf1bjvb8a"/><path fill="url(#i0c3pyd)" class="wf1bjvb8a"/><path fill="url(#iH10RCV)" class="wf1bjvb8a"/><g filter="url(#iyqXhac)"><path fill="url(#i24fGqe)" class="vs-nlk-et"/></g><g filter="url(#icWSked)"><path fill="url(#iU4zite)" class="i88qe339c"/></g><defs><radialGradient id="i5QiI1F" cx="0" cy="0" r="1" gradientTransform="rotate(142.745 .981 8.672)scale(1.90417 1.91676)" gradientUnits="userSpaceOnUse"><stop class="jsgegie7e"/><stop offset="1" class="kej9dq11p"/></radialGradient><radialGradient id="iWnRm8d" cx="0" cy="0" r="1" gradientTransform="rotate(52.185 -18.008 21.572)scale(3.59971 5.14449)" gradientUnits="userSpaceOnUse"><stop class="betrmabbr"/><stop offset="1" class="z2_n35b3r"/></radialGradient><radialGradient id="irTweYd" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 1 -2.70096 3.71382 11.09 28.228)" gradientUnits="userSpaceOnUse"><stop class="e1baekg7j"/><stop offset="1" class="v3q76dbxz"/></radialGradient><radialGradient id="ivnfqde" cx="0" cy="0" r="1" gradientTransform="matrix(5.07812 -3.9375 1.7956 2.31575 6.762 31.416)" gradientUnits="userSpaceOnUse"><stop class="o9purgbcw"/><stop offset="1" class="jxc-4jbsm"/></radialGradient><radialGradient id="iHatWRc" cx="0" cy="0" r="1" gradientTransform="rotate(-29.389 55.79 -11.726)scale(.78008 .42898)" gradientUnits="userSpaceOnUse"><stop class="qgt4s4rhl"/><stop offset="1" class="w7_3ovb5b"/></radialGradient><radialGradient id="iuRivhd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.09375 -.40624 .6111 -1.64529 15.434 28.65)" gradientUnits="userSpaceOnUse"><stop class="fiaw7_bfe"/><stop offset="1" class="n4leswb_y"/></radialGradient><radialGradient id="iaGTi4b" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.07813 -.60167 0 14.7 23.712)" gradientUnits="userSpaceOnUse"><stop class="y7nltdc7n"/><stop offset="1" class="fm6vwccdx"/></radialGradient><radialGradient id="iHw5A9d" cx="0" cy="0" r="1" gradientTransform="matrix(3.4375 3.4375 -5.92188 5.92188 25.86 15.06)" gradientUnits="userSpaceOnUse"><stop class="me07zll6w"/><stop offset=".752" class="im9jpjbvo"/></radialGradient><radialGradient id="iAArNic" cx="0" cy="0" r="1" gradientTransform="matrix(.90627 3.40625 -1.98902 .5292 27.235 9.811)" gradientUnits="userSpaceOnUse"><stop class="me07zll6w"/><stop offset="1" class="im9jpjbvo"/></radialGradient><radialGradient id="ik74yfP" cx="0" cy="0" r="1" gradientTransform="matrix(2.125 9.19795 -9.93793 2.29596 22.328 14.843)" gradientUnits="userSpaceOnUse"><stop offset=".569" class="jo0ijhxev"/><stop offset="1" class="sjpkpq2jr"/></radialGradient><radialGradient id="ichTwWd" cx="0" cy="0" r="1" gradientTransform="matrix(2.24991 9.56252 -10.33187 2.43093 22.328 14.843)" gradientUnits="userSpaceOnUse"><stop offset=".756" class="j505_3btl"/><stop offset="1" class="w53f9uiby"/></radialGradient><radialGradient id="ibs77od" cx="0" cy="0" r="1" gradientTransform="matrix(.6875 0 0 7.50139 20.903 19.806)" gradientUnits="userSpaceOnUse"><stop class="e0fq8xasw"/><stop offset=".489" class="x6vtrhbuh"/></radialGradient><radialGradient id="iCJdgxd" cx="0" cy="0" r="1" gradientTransform="matrix(12.12503 -8.6874 14.95197 20.86853 4.559 20.384)" gradientUnits="userSpaceOnUse"><stop class="uex1-wbrj"/><stop offset="1" class="fx3xxpb8n"/></radialGradient><radialGradient id="i80UkSA" cx="0" cy="0" r="1" gradientTransform="matrix(-3.18749 3.12501 -2.98932 -3.04908 15.059 4.572)" gradientUnits="userSpaceOnUse"><stop class="z111n_bsf"/><stop offset="1" class="p8x5gbb2r"/></radialGradient><radialGradient id="istA74d" cx="0" cy="0" r="1" gradientTransform="matrix(-3.62487 14.81251 -24.38437 -5.96727 15.559 8.822)" gradientUnits="userSpaceOnUse"><stop offset=".589" class="t4tfx5p2a"/><stop offset="1" class="u9apd0jqf"/></radialGradient><radialGradient id="if0qaec" cx="0" cy="0" r="1" gradientTransform="matrix(-3.56262 15.81243 -19.91675 -4.48734 15.559 8.822)" gradientUnits="userSpaceOnUse"><stop offset=".76" class="j505_3btl"/><stop offset=".955" class="w53f9uiby"/></radialGradient><radialGradient id="iqYWDVd" cx="0" cy="0" r="1" gradientTransform="matrix(.17187 -.57812 4.13415 1.22907 12.529 23.915)" gradientUnits="userSpaceOnUse"><stop class="pl91yo24y"/><stop offset="1" class="nmpdn4bsm"/></radialGradient><radialGradient id="ix8u6pc" cx="0" cy="0" r="1" gradientTransform="matrix(-2.65623 2.34376 -2.21062 -2.50534 18.559 16.697)" gradientUnits="userSpaceOnUse"><stop class="ltt1sabpu"/><stop offset="1" class="xvs0e7e4e"/></radialGradient><radialGradient id="ifwYHac" cx="0" cy="0" r="1" gradientTransform="matrix(3.5625 3.71875 -3.3718 3.23013 5.403 12.478)" gradientUnits="userSpaceOnUse"><stop offset=".212" class="xi5bumbka"/><stop offset="1" class="nk9c0ciek"/></radialGradient><radialGradient id="ixtgImd" cx="0" cy="0" r="1" gradientTransform="matrix(2.03125 0 0 5.82736 5.653 14.197)" gradientUnits="userSpaceOnUse"><stop class="ezhihj7sk"/><stop offset="1" class="qwjc5fb0j"/></radialGradient><radialGradient id="iJZ3M5b" cx="0" cy="0" r="1" gradientTransform="rotate(130.342 6.134 5.803)scale(2.99299 3.00973)" gradientUnits="userSpaceOnUse"><stop class="z111n_bsf"/><stop offset="1" class="p8x5gbb2r"/></radialGradient><radialGradient id="igOexoe" cx="0" cy="0" r="1" gradientTransform="rotate(-49.173 15.392 .233)scale(5.16232 9.38254)" gradientUnits="userSpaceOnUse"><stop class="h8f7hac-n"/><stop offset="1" class="k0jwap-ew"/></radialGradient><radialGradient id="i14hZmd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -.39063 6.10938 0 5.309 11.197)" gradientUnits="userSpaceOnUse"><stop class="aqmfao_eg"/><stop offset="1" class="tbug5uboa"/></radialGradient><radialGradient id="iaXLYHd" cx="0" cy="0" r="1" gradientTransform="matrix(0 .95313 -3.87954 0 11.543 14.712)" gradientUnits="userSpaceOnUse"><stop class="imzs8n2wh"/><stop offset="1" class="e0ucubc-x"/></radialGradient><radialGradient id="i4mj7WW" cx="0" cy="0" r="1" gradientTransform="matrix(1.28443 -1.375 1.3841 1.29292 9.715 19.353)" gradientUnits="userSpaceOnUse"><stop class="uvnvqebkz"/><stop offset="1" class="wkiv05b5f"/></radialGradient><radialGradient id="i1W38Db" cx="0" cy="0" r="1" gradientTransform="rotate(148.808 4.51 9.39)scale(1.34252 1.0993)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="s65c0y1nr"/><stop offset="1" class="wdgu8y-wl"/></radialGradient><radialGradient id="iT08sRb" cx="0" cy="0" r="1" gradientTransform="matrix(-.29308 -1.10872 1.19205 -.3151 9.984 6.13)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="ij2qqUb" cx="0" cy="0" r="1" gradientTransform="rotate(141.421 5.632 16.464)scale(10.1643 19.8308)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="b0mib2b3v"/><stop offset="1" class="wmomqqbok"/></radialGradient><radialGradient id="iPwZosd" cx="0" cy="0" r="1" gradientTransform="rotate(124.931 5.428 14.361)scale(14.4083 27.0692)" gradientUnits="userSpaceOnUse"><stop offset=".091" class="b0mib2b3v"/><stop offset="1" class="wmomqqbok"/></radialGradient><radialGradient id="ikQdc8d" cx="0" cy="0" r="1" gradientTransform="matrix(-8 .5938 -.64653 -8.71045 24.184 21.978)" gradientUnits="userSpaceOnUse"><stop offset=".718" class="zw7jmqy8g"/><stop offset="1" class="oxg3qbmcf"/></radialGradient><radialGradient id="iLVVivb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.125 5.37501 -6.07543 -5.79284 22.684 20.134)" gradientUnits="userSpaceOnUse"><stop offset=".739" class="h-6xnacrc"/><stop offset="1" class="zwxd2kbvf"/></radialGradient><radialGradient id="i0c3pyd" cx="0" cy="0" r="1" gradientTransform="rotate(4.6 -260.013 203.666)scale(2.72754 4.70263)" gradientUnits="userSpaceOnUse"><stop class="sbhdi7b6h"/><stop offset=".447" class="rv686_bte"/></radialGradient><radialGradient id="iH10RCV" cx="0" cy="0" r="1" gradientTransform="matrix(-.1328 -.61719 3.40653 -.73303 19.926 25.892)" gradientUnits="userSpaceOnUse"><stop class="gc78ugb4i"/><stop offset=".724" class="v5n1olc0u"/></radialGradient><linearGradient id="imV6med" x1="3.653" x2="4.684" y1="17.415" y2="17.415" gradientUnits="userSpaceOnUse"><stop class="mc2srbbew"/><stop offset="1" class="pc5_5bymf"/></linearGradient><linearGradient id="iOsHwae" x1="6.18" x2="5.539" y1="18.044" y2="17.404" gradientUnits="userSpaceOnUse"><stop class="wr08xfb7f"/><stop offset="1" class="xfgjfy-2l"/></linearGradient><linearGradient id="iHPs4yd" x1="6.04" x2="6.04" y1="14.681" y2="15.587" gradientUnits="userSpaceOnUse"><stop class="jsgegie7e"/><stop offset="1" class="kej9dq11p"/></linearGradient><linearGradient id="ioWgwEb" x1="12.282" x2="12.282" y1="30.588" y2="29.291" gradientUnits="userSpaceOnUse"><stop class="fslidslty"/><stop offset="1" class="haf_tmgcg"/></linearGradient><linearGradient id="iKDMuGe" x1="16.809" x2="9.997" y1="13.322" y2="13.322" gradientUnits="userSpaceOnUse"><stop class="don7qdnhj"/><stop offset="1" class="rhwpoiofa"/></linearGradient><linearGradient id="ic2mHNb" x1="14.971" x2="14.106" y1="10.822" y2="10.822" gradientUnits="userSpaceOnUse"><stop class="ufluz7bgs"/><stop offset="1" class="qv__kqhdl"/></linearGradient><linearGradient id="iArbKZc" x1="2.278" x2="6.997" y1="11.033" y2="11.033" gradientUnits="userSpaceOnUse"><stop class="qb4_hnb6a"/><stop offset="1" class="u7koeubmc"/></linearGradient><linearGradient id="iOT6BKc" x1="8.528" x2="8.528" y1="2.947" y2="7.529" gradientUnits="userSpaceOnUse"><stop class="mibdd-4ex"/><stop offset="1" class="wacxuubhr"/></linearGradient><linearGradient id="ikvm7Ee" x1="1.653" x2="2.762" y1="8.384" y2="8.384" gradientUnits="userSpaceOnUse"><stop class="p-u3s3esv"/><stop offset="1" class="o2rnbwbel"/></linearGradient><linearGradient id="i1hZ4lh" x1="8.988" x2="10.45" y1="17.494" y2="17.494" gradientUnits="userSpaceOnUse"><stop class="jlaup-u-q"/><stop offset="1" class="wrxiqmrgy"/></linearGradient><linearGradient id="iDf2L8c" x1="8.988" x2="9.063" y1="17.181" y2="17.181" gradientUnits="userSpaceOnUse"><stop class="jw9fppb5n"/><stop offset="1" class="v295_wbqj"/></linearGradient><linearGradient id="ir9aNHd" x1="10.37" x2="9.802" y1="5.853" y2="5.853" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iiBz49b" x1="10.523" x2="10.523" y1="6.863" y2="5.93" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iU8Qrxd" x1="29.622" x2="20.622" y1="13.915" y2="25.416" gradientUnits="userSpaceOnUse"><stop class="qebyhcbhk"/><stop offset="1" class="otq0vgbty"/></linearGradient><linearGradient id="iHakaZq" x1="12.559" x2="9.598" y1="15.556" y2="18.642" gradientUnits="userSpaceOnUse"><stop class="kqxpdn6tv"/><stop offset="1" class="n-7_15g-w"/></linearGradient><linearGradient id="imEp2ud" x1="16.465" x2="18.458" y1="28.509" y2="29.572" gradientUnits="userSpaceOnUse"><stop class="evr8nucpq"/><stop offset="1" class="euntlmbva"/></linearGradient><linearGradient id="i6I0lsb" x1="18.458" x2="18.458" y1="30.291" y2="29.228" gradientUnits="userSpaceOnUse"><stop class="w53f9uiby"/><stop offset="1" class="j505_3btl"/></linearGradient><linearGradient id="i24fGqe" x1="19.762" x2="20.309" y1="29.267" y2="26.377" gradientUnits="userSpaceOnUse"><stop class="i_wy89vui"/><stop offset="1" class="ns1qw3bga"/></linearGradient><linearGradient id="iU4zite" x1="18.773" x2="21.07" y1="25.08" y2="20.274" gradientUnits="userSpaceOnUse"><stop class="i_wy89vui"/><stop offset="1" class="ns1qw3bga"/></linearGradient><filter id="iA5lyDl" width="2.685" height="2.661" x="7.409" y="4.769" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5761" stdDeviation=".25"/></filter><filter id="imycjxd" width="10.161" height="13.844" x="19.965" y="10.103" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5761" stdDeviation=".5"/></filter><filter id="ib7C3qd" width="4.797" height="4.891" x="8.762" y="14.556" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5761" stdDeviation=".375"/></filter><filter id="iyqXhac" width="4.547" height="4.766" x="16.762" y="25.502" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5761" stdDeviation=".5"/></filter><filter id="icWSked" width="3.988" height="7.453" x="16.212" y="18.627" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5761" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:t-rex" /></template>
<style>
.aqmfao_eg {
  stop-color: var(--svg-color--2d9b83, #2D9B83);
}

.b0mib2b3v {
  stop-color: var(--svg-color--49ea8c, #49EA8C);
}

.betrmabbr {
  stop-color: var(--svg-color--57b397, #57B397);
}

.cxcirnzkd {
  d: path("M20.965 19.884c7.844.313 7.847-7.126 7.25-8.781c3.188 7.094-2.656 11.844-7.25 11.844z");
}

.don7qdnhj {
  stop-color: var(--svg-color--5bf593, #5BF593);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e0fq8xasw {
  stop-color: var(--svg-color--56ef95, #56EF95);
}

.e0ucubc-x {
  stop-color: var(--svg-color--1ec26c, #1EC26C);
  stop-opacity: 0;
}

.e1baekg7j {
  stop-color: var(--svg-color--64b484, #64B484);
}

.effua5baj {
  width: 0.981px;
  height: 1.959px;
  x: 9.388px;
  y: 4.996px;
  rx: 0.491px;
}

.euntlmbva {
  stop-color: var(--svg-color--23b666, #23B666);
  stop-opacity: 0;
}

.evr8nucpq {
  stop-color: var(--svg-color--23b666, #23B666);
}

.ezhihj7sk {
  stop-color: var(--svg-color--7ece9c, #7ECE9C);
}

.fiaw7_bfe {
  stop-color: var(--svg-color--4c9193, #4C9193);
}

.fm6vwccdx {
  stop-color: var(--svg-color--46679e, #46679E);
  stop-opacity: 0;
}

.fslidslty {
  stop-color: var(--svg-color--8779e0, #8779E0);
}

.ft5dv1b6b {
  fill: none;
}

.fx3xxpb8n {
  stop-color: var(--svg-color--40e288, #40E288);
}

.gc78ugb4i {
  stop-color: var(--svg-color--63e9b1, #63E9B1);
}

.h-6xnacrc {
  stop-color: var(--svg-color--49adab, #49ADAB);
  stop-opacity: 0;
}

.h8f7hac-n {
  stop-color: var(--svg-color--40c992, #40C992);
}

.haf_tmgcg {
  stop-color: var(--svg-color--8779e0, #8779E0);
  stop-opacity: 0;
}

.i_wy89vui {
  stop-color: var(--svg-color--61ebac, #61EBAC);
}

.i88qe339c {
  d: path("M17.997 19.627c-.802 1.036-1.685 3.578 1.203 5.453z");
}

.im9jpjbvo {
  stop-color: var(--svg-color--56c173, #56C173);
  stop-opacity: 0;
}

.imzs8n2wh {
  stop-color: var(--svg-color--1ec26c, #1EC26C);
}

.j477ljb4v {
  fill-rule: evenodd;
  d: path("M20.934 25.822v3.195c0 .485-.195.93-.867.93h-3.602c-.273 0-.765-.352-.273-.89c.462-.507 2.086-2.126 2.93-2.907l.038-.045c.074-.083.177-.198.06-.283z");
}

.j505_3btl {
  stop-color: var(--svg-color--8295d7, #8295D7);
  stop-opacity: 0;
}

.jlaup-u-q {
  stop-color: var(--svg-color--2c807d, #2C807D);
}

.jo0ijhxev {
  stop-color: var(--svg-color--4db7af, #4DB7AF);
  stop-opacity: 0;
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jsgegie7e {
  stop-color: var(--svg-color--4ead6a, #4EAD6A);
}

.jw9fppb5n {
  stop-color: var(--svg-color--66a287, #66A287);
}

.jxc-4jbsm {
  stop-color: var(--svg-color--70c992, #70C992);
  stop-opacity: 0;
}

.k0jwap-ew {
  stop-color: var(--svg-color--40c992, #40C992);
  stop-opacity: 0;
}

.k75dufpfi {
  fill: var(--svg-color--40e288, #40E288);
  d: path("M27.763 10.643c.74 5.24-3.255 7.82-7.581 7.325v6.062c6.89.25 9.49-4.035 9.703-7.562c.208-3.451-.938-5.114-1.775-6.008c-.134-.144-.375-.012-.347.183");
}

.kej9dq11p {
  stop-color: var(--svg-color--4ead6a, #4EAD6A);
  stop-opacity: 0;
}

.kqxpdn6tv {
  stop-color: var(--svg-color--4acea4, #4ACEA4);
}

.lr2r0bcao {
  width: 0.981px;
  height: 1.959px;
  x: 9.115px;
  y: 5.066px;
  fill: var(--svg-color--1eb564, #1EB564);
  rx: 0.491px;
}

.ltt1sabpu {
  stop-color: var(--svg-color--52f591, #52F591);
}

.mc2srbbew {
  stop-color: var(--svg-color--69a08e, #69A08E);
}

.me07zll6w {
  stop-color: var(--svg-color--56c173, #56C173);
}

.mibdd-4ex {
  stop-color: var(--svg-color--38d875, #38D875);
}

.n-7_15g-w {
  stop-color: var(--svg-color--4aaece, #4AAECE);
}

.n4leswb_y {
  stop-color: var(--svg-color--4c9193, #4C9193);
  stop-opacity: 0;
}

.nk9c0ciek {
  stop-color: var(--svg-color--2aa677, #2AA677);
  stop-opacity: 0;
}

.nmpdn4bsm {
  stop-color: var(--svg-color--9fb6ee, #9FB6EE);
  stop-opacity: 0;
}

.ns1qw3bga {
  stop-color: var(--svg-color--61ebac, #61EBAC);
  stop-opacity: 0;
}

.o2rnbwbel {
  stop-color: var(--svg-color--8ed9a5, #8ED9A5);
  stop-opacity: 0;
}

.o9purgbcw {
  stop-color: var(--svg-color--70c992, #70C992);
}

.od7u76g1q {
  d: path("M4.028 15.781a.8.8 0 0 1 .8-.8H7.4c.58 0 .87.704.457 1.112L5.135 18.79a.65.65 0 0 1-1.107-.462z");
}

.otq0vgbty {
  stop-color: var(--svg-color--60ee9e, #60EE9E);
  stop-opacity: 0;
}

.oxg3qbmcf {
  stop-color: var(--svg-color--1cc172, #1CC172);
}

.p-u3s3esv {
  stop-color: var(--svg-color--8ed9a5, #8ED9A5);
}

.p8x5gbb2r {
  stop-color: var(--svg-color--59f695, #59F695);
  stop-opacity: 0;
}

.pc5_5bymf {
  stop-color: var(--svg-color--69a08e, #69A08E);
  stop-opacity: 0;
}

.pl91yo24y {
  stop-color: var(--svg-color--9fb6ee, #9FB6EE);
}

.q8wz9rrne {
  d: path("M5.59 4.025a3.5 3.5 0 0 0-3.5 3.5v2a1.5 1.5 0 0 0 1.5 1.5h2.32a.5.5 0 0 1 .5.5v5.406c0 2.618 1.637 4.502 3.399 5.672c1.66 1.103 5.117 1.484 6.625 1.344c.617 1.11 2.313 1.703 2.688 1.828c.257.086.127.23.038.33l-.038.045c-.844.781-2.468 2.4-2.93 2.906c-.492.54 0 .89.273.89h3.602c.672 0 .867-.445.867-.929V24.01h.01c0-.303.007-2.142.013-3.708v-.024L20.965 18s-.463-4.9-5.897-4.96a.1.1 0 0 1-.103-.1V7.525a3.5 3.5 0 0 0-3.5-3.5z");
}

.qb4_hnb6a {
  stop-color: var(--svg-color--2baf76, #2BAF76);
}

.qebyhcbhk {
  stop-color: var(--svg-color--60ee9e, #60EE9E);
}

.qgt4s4rhl {
  stop-color: var(--svg-color--60a0a5, #60A0A5);
}

.qv__kqhdl {
  stop-color: var(--svg-color--51e689, #51E689);
  stop-opacity: 0;
}

.qwjc5fb0j {
  stop-color: var(--svg-color--7ece9c, #7ECE9C);
  stop-opacity: 0;
}

.ra1nwe49a {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m9.762 18.447l2.797-2.89");
}

.rhwpoiofa {
  stop-color: var(--svg-color--5bf593, #5BF593);
  stop-opacity: 0;
}

.ro_gwf7cc {
  d: path("M14.971 12.974a.1.1 0 0 1-.006-.033V7.525a3.5 3.5 0 0 0-3.5-3.5H5.59a3.5 3.5 0 0 0-3.5 3.5v2a1.5 1.5 0 0 0 1.5 1.5h2.32a.5.5 0 0 1 .5.5v5.406c0 .456.05.889.141 1.3z");
}

.rv686_bte {
  stop-color: var(--svg-color--1fab7a, #1FAB7A);
  stop-opacity: 0;
}

.rvfe1cczh {
  fill: var(--svg-color--378b74, #378B74);
  d: path("M4.028 15.781a.8.8 0 0 1 .8-.8H7.4c.58 0 .87.704.457 1.112L5.135 18.79a.65.65 0 0 1-1.107-.462z");
}

.s65c0y1nr {
  stop-color: var(--svg-color--57ec97, #57EC97);
}

.sbhdi7b6h {
  stop-color: var(--svg-color--1fab7a, #1FAB7A);
}

.sjpkpq2jr {
  stop-color: var(--svg-color--4db7af, #4DB7AF);
}

.t4tfx5p2a {
  stop-color: var(--svg-color--44a6a5, #44A6A5);
  stop-opacity: 0;
}

.tbug5uboa {
  stop-color: var(--svg-color--2d9b83, #2D9B83);
  stop-opacity: 0;
}

.tzsqzub9w {
  d: path("M13.153 25.681c-1.966-.368-3.305-2.219-3.555-3.328l5.367 1.11v5.21c0 .985-.638 1.25-.96 1.282h-3.446c-.605 0-.656-.532-.437-.774l3.03-3.062c.157-.157.292-.383 0-.438");
}

.u-frw-bzk {
  d: path("M8.988 15.781a.8.8 0 0 1 .8-.8h2.573c.58 0 .87.704.457 1.112l-2.723 2.697a.65.65 0 0 1-1.107-.462z");
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.u7koeubmc {
  stop-color: var(--svg-color--2baf76, #2BAF76);
  stop-opacity: 0;
}

.u9apd0jqf {
  stop-color: var(--svg-color--44a6a5, #44A6A5);
}

.uex1-wbrj {
  stop-color: var(--svg-color--31aa78, #31AA78);
}

.ufluz7bgs {
  stop-color: var(--svg-color--51e689, #51E689);
}

.uvnvqebkz {
  stop-color: var(--svg-color--526bb1, #526BB1);
}

.v295_wbqj {
  stop-color: var(--svg-color--66a287, #66A287);
  stop-opacity: 0;
}

.v3q76dbxz {
  stop-color: var(--svg-color--64b484, #64B484);
  stop-opacity: 0;
}

.v5n1olc0u {
  stop-color: var(--svg-color--63e9b1, #63E9B1);
  stop-opacity: 0;
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vs-nlk-et {
  d: path("m20.309 26.502l-2.547 2.765h2.469z");
}

.w53f9uiby {
  stop-color: var(--svg-color--8295d7, #8295D7);
}

.w7_3ovb5b {
  stop-color: var(--svg-color--588e92, #588E92);
  stop-opacity: 0;
}

.wacxuubhr {
  stop-color: var(--svg-color--38d875, #38D875);
  stop-opacity: 0;
}

.wdgu8y-wl {
  stop-color: var(--svg-color--40b294, #40B294);
  stop-opacity: 0;
}

.wf1bjvb8a {
  d: path("m20.957 20.288l.008-2.154h-1.581a3.5 3.5 0 0 0-3.443 2.871l-.03.164c-.179.976-.114 2.022.487 2.81a4.74 4.74 0 0 0 2.604 1.76l.12.036a.4.4 0 0 1 .097.047h1.715v-1.813h.01c0-.304.007-2.147.013-3.714z");
}

.wkiv05b5f {
  stop-color: var(--svg-color--526bb1, #526BB1);
  stop-opacity: 0;
}

.wmomqqbok {
  stop-color: var(--svg-color--18c06b, #18C06B);
}

.wr08xfb7f {
  stop-color: var(--svg-color--6a6bbe, #6A6BBE);
}

.wrxiqmrgy {
  stop-color: var(--svg-color--2c807d, #2C807D);
  stop-opacity: 0;
}

.wzuq7c62u {
  d: path("M27.763 10.643c.74 5.24-3.255 7.82-7.581 7.325v6.062c6.89.25 9.49-4.035 9.703-7.562c.208-3.451-.938-5.114-1.775-6.008c-.134-.144-.375-.012-.347.183");
}

.x6vtrhbuh {
  stop-color: var(--svg-color--56ef95, #56EF95);
  stop-opacity: 0;
}

.xfgjfy-2l {
  stop-color: var(--svg-color--6a6bbe, #6A6BBE);
  stop-opacity: 0;
}

.xi5bumbka {
  stop-color: var(--svg-color--2aa677, #2AA677);
}

.xvs0e7e4e {
  stop-color: var(--svg-color--52f591, #52F591);
  stop-opacity: 0;
}

.y7nltdc7n {
  stop-color: var(--svg-color--46679e, #46679E);
}

.z111n_bsf {
  stop-color: var(--svg-color--59f695, #59F695);
}

.z2_n35b3r {
  stop-color: var(--svg-color--57b397, #57B397);
  stop-opacity: 0;
}

.zb3x01b2s {
  d: path("M14.965 11.033H6l-.088-.008H3.59a1.5 1.5 0 0 1-1.5-1.5v-2a3.5 3.5 0 0 1 3.5-3.5h5.874a3.5 3.5 0 0 1 3.5 3.5z");
}

.zmv1trbmg {
  fill: var(--svg-color--3fb193, #3FB193);
  d: path("M8.988 15.781a.8.8 0 0 1 .8-.8h2.573c.58 0 .87.704.457 1.112l-2.723 2.697a.65.65 0 0 1-1.107-.462z");
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.ztow04bsq {
  fill: var(--svg-color--437599, #437599);
  d: path("M13.153 25.681c-1.966-.368-3.305-2.219-3.555-3.328l5.367 1.11v5.21c0 .985-.638 1.25-.96 1.282h-3.446c-.605 0-.656-.532-.437-.774l3.03-3.062c.157-.157.292-.383 0-.438");
}

.zw7jmqy8g {
  stop-color: var(--svg-color--1cc172, #1CC172);
  stop-opacity: 0;
}

.zwxd2kbvf {
  stop-color: var(--svg-color--49adab, #49ADAB);
}

</style>
