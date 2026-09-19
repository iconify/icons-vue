<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iFfx0Mb)" clip-rule="evenodd" class="g9x01ib7p"/><path fill="url(#iupwKMM)" clip-rule="evenodd" class="pveg-8y5i"/><g filter="url(#ijHSigC)"><path fill="url(#iM0nHJb)" clip-rule="evenodd" class="t6bcwzzow"/></g><g filter="url(#iQqvTec)"><path fill="url(#iaYIcAb)" clip-rule="evenodd" class="jkw_mbm3d"/></g><path fill="url(#iW4wGod)" class="hn0ng8cpy"/><ellipse fill="url(#i4wQS8d)" class="x3dykpbsd"/><ellipse fill="url(#ixL9lFd)" class="d8-0_5ymy"/><ellipse fill="url(#iLfZqed)" class="wpr6c48vv"/><g filter="url(#iHWi9uS)"><path class="ot6trphul"/></g><g filter="url(#if8SPHc)"><path class="rgld9vb4t"/></g><path fill="url(#ihqLmKe)" class="ctfivzboc"/><g filter="url(#iFxR3Md)"><path clip-rule="evenodd" class="ub_m3bb1r"/></g><path fill="url(#i3nJbbc)" class="hbcyo782k"/><path fill="url(#ilFniib)" class="ntp0yqb3v"/><g filter="url(#iSFhRVc)"><path class="nnherwbkt"/></g><path fill="url(#i31s9Qw)" class="ksnwnjavd"/><path fill="url(#iOtUwVb)" class="csidl6fpm"/><g filter="url(#iCXZvmd)"><circle class="pbdsl_bog"/></g><g filter="url(#icgTwOb)"><circle class="ewceivbzr"/></g><circle fill="url(#icdThZc)" class="najsiob_s"/><g filter="url(#i0sDZjb)"><circle class="f-z5q0bdp"/></g><circle fill="url(#ihIvPTd)" class="ab61nhbej"/><circle fill="url(#icJrSsd)" class="l69ejpbrz"/><g filter="url(#i9PKXrw)"><path clip-rule="evenodd" class="fwrer1bxc"/></g><path fill="url(#iVxJ8wb)" clip-rule="evenodd" class="kwak3bbla"/><g filter="url(#iBLDHBp)"><path stroke="url(#iDv746d)" class="yb4hz-lhk"/></g><g filter="url(#ibMQvkb)"><path stroke="url(#iJUO7Ob)" class="shtuqsgkl"/></g><g filter="url(#ii4pGzc)"><path stroke="url(#iqnzu6d)" class="x1okj2bkw"/></g><defs><filter id="ijHSigC" width="6.672" height="7.883" x="1.969" y="13.086" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="iQqvTec" width="6.86" height="8.438" x="23.422" y="12.781" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".25"/></filter><filter id="iHWi9uS" width="4.453" height="2.563" x="17.772" y="15.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="if8SPHc" width="4.453" height="2.563" x="13.772" y="18.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="iFxR3Md" width="6.399" height="2.469" x="15.781" y="9.938" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="iSFhRVc" width="2.351" height="1.5" x="10.821" y="17.922" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="iCXZvmd" width="2" height="2" x="8.836" y="15.117" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="icgTwOb" width="2" height="2" x="19.864" y="13.098" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="i0sDZjb" width="2" height="2" x="13.906" y="8.094" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="i9PKXrw" width="6.745" height="6.745" x="10.422" y="10.878" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="iBLDHBp" width="5.313" height="5.063" x="11.844" y="11.031" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".375"/></filter><filter id="ibMQvkb" width="2.188" height="5.047" x="2.891" y="14.344" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><filter id="ii4pGzc" width="2.438" height="5.797" x="27.5" y="13.875" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_29109" stdDeviation=".125"/></filter><radialGradient id="iLfZqed" cx="0" cy="0" r="1" gradientTransform="matrix(13.90623 2.71874 -2.04323 10.45104 10.688 13.625)" gradientUnits="userSpaceOnUse"><stop class="a8fw0nb2c"/><stop offset=".902" class="psp4ckbvi"/><stop offset=".96" class="n1sj6tbzb"/></radialGradient><radialGradient id="ihqLmKe" cx="0" cy="0" r="1" gradientTransform="matrix(4.03125 -1 1 4.03125 17.813 18)" gradientUnits="userSpaceOnUse"><stop class="y_yy7prrh"/><stop offset=".509" class="x71--4-vz"/><stop offset="1" class="uqnfbvo9p"/></radialGradient><radialGradient id="i3nJbbc" cx="0" cy="0" r="1" gradientTransform="matrix(-.0625 1.78125 -2.58838 -.09082 20.781 11)" gradientUnits="userSpaceOnUse"><stop class="qvijrsbto"/><stop offset=".469" class="jo5g62czr"/><stop offset="1" class="cmihwwbci"/></radialGradient><radialGradient id="ilFniib" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.85938 -2.99899 0 17.453 11.313)" gradientUnits="userSpaceOnUse"><stop class="ayvx88mfb"/><stop offset=".193" class="acp-y5oyt"/><stop offset=".63" class="flfi7cbwp"/></radialGradient><radialGradient id="i31s9Qw" cx="0" cy="0" r="1" gradientTransform="matrix(2.01562 -.5 .5 2.01562 10.906 19)" gradientUnits="userSpaceOnUse"><stop class="y_yy7prrh"/><stop offset=".605" class="x71--4-vz"/><stop offset="1" class="uqnfbvo9p"/></radialGradient><radialGradient id="iOtUwVb" cx="0" cy="0" r="1" gradientTransform="matrix(-.125 2.03125 -2.95166 -.18164 16.781 20)" gradientUnits="userSpaceOnUse"><stop class="qvijrsbto"/><stop offset=".329" class="jo5g62czr"/><stop offset=".851" class="ubwf1pp0w"/></radialGradient><radialGradient id="icdThZc" cx="0" cy="0" r="1" gradientTransform="rotate(110.76 -.314 11.504)scale(.93578)" gradientUnits="userSpaceOnUse"><stop class="khozd346p"/><stop offset=".472" class="sdcw15t3w"/><stop offset="1" class="n8n9qib_p"/></radialGradient><radialGradient id="ihIvPTd" cx="0" cy="0" r="1" gradientTransform="rotate(110.76 4.602 9.73)scale(.93578)" gradientUnits="userSpaceOnUse"><stop class="khozd346p"/><stop offset=".472" class="sdcw15t3w"/><stop offset="1" class="n8n9qib_p"/></radialGradient><radialGradient id="icJrSsd" cx="0" cy="0" r="1" gradientTransform="rotate(110.76 5.876 14.3)scale(.93578)" gradientUnits="userSpaceOnUse"><stop class="khozd346p"/><stop offset=".472" class="sdcw15t3w"/><stop offset="1" class="n8n9qib_p"/></radialGradient><radialGradient id="iVxJ8wb" cx="0" cy="0" r="1" gradientTransform="rotate(101.107 2.001 12.6)scale(4.23763)" gradientUnits="userSpaceOnUse"><stop class="rp-81-kjx"/><stop offset=".465" class="izxovzzds"/><stop offset=".773" class="l_64srbse"/><stop offset=".969" class="lmts1yblo"/></radialGradient><radialGradient id="iJUO7Ob" cx="0" cy="0" r="1" gradientTransform="matrix(3.07813 0 0 2.75 3.266 17.094)" gradientUnits="userSpaceOnUse"><stop class="xgvx0f9mh"/><stop offset="1" class="mv0kd8bdz"/></radialGradient><radialGradient id="iqnzu6d" cx="0" cy="0" r="1" gradientTransform="rotate(171.408 13.99 9.349)scale(4.20342 4.17384)" gradientUnits="userSpaceOnUse"><stop class="wddr4l2ef"/><stop offset="1" class="r-sgj4b1d"/></radialGradient><linearGradient id="iFfx0Mb" x1="7" x2="1.781" y1="16.25" y2="16.25" gradientUnits="userSpaceOnUse"><stop class="qe_nrwybn"/><stop offset="1" class="j_t5bccir"/></linearGradient><linearGradient id="iupwKMM" x1="25" x2="32.875" y1="17" y2="17" gradientUnits="userSpaceOnUse"><stop class="t4eog8bhk"/><stop offset=".397" class="w89uifo7x"/><stop offset="1" class="vtak2cs-n"/></linearGradient><linearGradient id="iM0nHJb" x1="6.781" x2="1.813" y1="16.188" y2="16.188" gradientUnits="userSpaceOnUse"><stop class="gpyvasdyu"/><stop offset=".237" class="zrfojabsg"/><stop offset=".748" class="nohmnpv1c"/></linearGradient><linearGradient id="iaYIcAb" x1="25.505" x2="25.505" y1="20.438" y2="13.5" gradientUnits="userSpaceOnUse"><stop class="pinc10x1d"/><stop offset=".739" class="mza5rab2f"/><stop offset="1" class="tvp-_cbsm"/></linearGradient><linearGradient id="iW4wGod" x1="7" x2="25" y1="21.25" y2="21.25" gradientUnits="userSpaceOnUse"><stop class="w81dqbg_p"/><stop offset=".139" class="sfp530a7b"/><stop offset=".528" class="yyut8i0qw"/><stop offset="1" class="zo13vrb2o"/></linearGradient><linearGradient id="i4wQS8d" x1="16" x2="16" y1="5" y2="23.531" gradientUnits="userSpaceOnUse"><stop class="gc649hati"/><stop offset="1" class="ov-osoa9s"/></linearGradient><linearGradient id="ixL9lFd" x1="7.766" x2="24.219" y1="11.188" y2="11.188" gradientUnits="userSpaceOnUse"><stop class="iwxsfzlsa"/><stop offset=".508" class="jzo4vklkj"/><stop offset="1" class="i8v188uje"/></linearGradient><linearGradient id="iDv746d" x1="12.781" x2="15.875" y1="12.156" y2="14.969" gradientUnits="userSpaceOnUse"><stop class="aj3n42brb"/><stop offset=".721" class="gc_3sccxq"/><stop offset="1" class="cryv69bud"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pot-of-food" /></template>
<style>
.a8fw0nb2c {
  stop-color: var(--svg-color--ff8b45, #FF8B45);
}

.ab61nhbej {
  cx: 15px;
  cy: 9px;
  r: 0.75px;
}

.acp-y5oyt {
  stop-color: var(--svg-color--7ad263, #7AD263);
}

.aj3n42brb {
  stop-color: var(--svg-color--f1a78f, #F1A78F);
}

.ayvx88mfb {
  stop-color: var(--svg-color--82e270, #82E270);
}

.cmihwwbci {
  stop-color: var(--svg-color--55a649, #55A649);
}

.cryv69bud {
  stop-color: var(--svg-color--d99a87, #D99A87);
}

.csidl6fpm {
  d: path("M16 19a2 2 0 0 0-1.985 1.75c-.017.137.097.25.235.25h3.5c.138 0 .252-.113.235-.25A2 2 0 0 0 16 19");
}

.ctfivzboc {
  d: path("M20 16a2 2 0 0 0-1.985 1.75c-.017.137.097.25.235.25h3.5c.138 0 .252-.113.235-.25A2 2 0 0 0 20 16");
}

.d8-0_5ymy {
  cx: 15.992px;
  cy: 14.25px;
  rx: 8.227px;
  ry: 8.25px;
}

.ewceivbzr {
  cx: 20.864px;
  cy: 14.098px;
  r: 0.75px;
  fill: var(--svg-color--e44f2e, #E44F2E);
}

.f-z5q0bdp {
  cx: 14.906px;
  cy: 9.094px;
  r: 0.75px;
  fill: var(--svg-color--e44f2e, #E44F2E);
}

.flfi7cbwp {
  stop-color: var(--svg-color--619f39, #619F39);
}

.ft5dv1b6b {
  fill: none;
}

.fwrer1bxc {
  fill: var(--svg-color--d95b39, #D95B39);
  fill-rule: evenodd;
  d: path("M12.422 11.128c.966 0 1.75.783 1.75 1.75c0 .549.445.994.995.994a1.75 1.75 0 1 1 0 3.5a4.495 4.495 0 0 1-4.495-4.494c0-.967.783-1.75 1.75-1.75");
}

.g9x01ib7p {
  fill-rule: evenodd;
  d: path("M2 17a4 4 0 0 1 4-4h6v8H6a4 4 0 0 1-4-4m4-2a2 2 0 1 0 0 4h4v-4z");
}

.gc_3sccxq {
  stop-color: var(--svg-color--cf8b73, #CF8B73);
}

.gc649hati {
  stop-color: var(--svg-color--d0cbd8, #D0CBD8);
}

.gpyvasdyu {
  stop-color: var(--svg-color--7b6999, #7B6999);
}

.hbcyo782k {
  d: path("M20 10a2 2 0 0 0-2 2h3.75c.138 0 .252-.113.235-.25A2 2 0 0 0 20 10");
}

.hn0ng8cpy {
  d: path("M7 14h18v7a9 9 0 1 1-18 0z");
}

.i8v188uje {
  stop-color: var(--svg-color--9a7079, #9A7079);
}

.iwxsfzlsa {
  stop-color: var(--svg-color--ecc1bc, #ECC1BC);
}

.izxovzzds {
  stop-color: var(--svg-color--b06446, #B06446);
}

.j_t5bccir {
  stop-color: var(--svg-color--939099, #939099);
}

.jkw_mbm3d {
  fill-rule: evenodd;
  d: path("M27.91 15.26c.397.344.793.909.793 1.834c0 .895-.357 1.4-.712 1.695c-.386.32-1.245.43-1.493.43h-1.554a.75.75 0 1 0 0 1.5h1.554c.57 0 1.377-.215 2.053-.776c.706-.586 1.23-1.518 1.23-2.85c0-1.394-.588-2.361-1.287-2.967c-.515-.446-1.235-.845-1.935-.845h-1.887v1.371h1.789c.492 0 1.155.354 1.448.607m-3.988-1.229c0 .414.335.621.75.621v-1.37a.75.75 0 0 0-.75.75");
}

.jo5g62czr {
  stop-color: var(--svg-color--64bf6c, #64BF6C);
}

.jzo4vklkj {
  stop-color: var(--svg-color--a788a2, #A788A2);
}

.khozd346p {
  stop-color: var(--svg-color--ff877f, #FF877F);
}

.ksnwnjavd {
  d: path("M12 18a1 1 0 0 0-.97.753c-.033.133.082.247.22.247h1.5c.138 0 .253-.114.22-.247A1 1 0 0 0 12 18");
}

.kwak3bbla {
  fill-rule: evenodd;
  d: path("M12.561 10.976c.967 0 1.75.783 1.75 1.75c0 .55.446.995.995.995a1.75 1.75 0 1 1 0 3.5a4.495 4.495 0 0 1-4.495-4.495c0-.967.784-1.75 1.75-1.75");
}

.l_64srbse {
  stop-color: var(--svg-color--8b543e, #8B543E);
}

.l69ejpbrz {
  cx: 21px;
  cy: 14px;
  r: 0.75px;
}

.lmts1yblo {
  stop-color: var(--svg-color--8d482d, #8D482D);
}

.mv0kd8bdz {
  stop-color: var(--svg-color--aca5bb, #ACA5BB);
  stop-opacity: 0;
}

.mza5rab2f {
  stop-color: var(--svg-color--d3d3d8, #D3D3D8);
}

.n1sj6tbzb {
  stop-color: var(--svg-color--b9462d, #B9462D);
}

.n8n9qib_p {
  stop-color: var(--svg-color--bd3f25, #BD3F25);
}

.najsiob_s {
  cx: 10px;
  cy: 16px;
  r: 0.75px;
}

.nnherwbkt {
  fill: var(--svg-color--f1512a, #F1512A);
  d: path("M11.996 18.172c-.443 0-.815.32-.92.752c-.032.134.083.248.22.248h1.4c.137 0 .252-.114.22-.248c-.105-.432-.477-.752-.92-.752");
}

.nohmnpv1c {
  stop-color: var(--svg-color--a59db4, #A59DB4);
}

.ntp0yqb3v {
  d: path("M17 11a1 1 0 0 0-.97.752c-.033.134.082.248.22.248H18a1 1 0 0 0-1-1");
}

.ot6trphul {
  fill: var(--svg-color--eb502e, #EB502E);
  d: path("M20 16.11c-.643 0-1.782.933-1.973 1.768c-.029.128.074.238.206.245c.339.019 1.011.049 1.767.049s1.428-.03 1.767-.049c.132-.007.234-.117.203-.245c-.191-.778-1.254-1.769-1.97-1.769");
}

.ov-osoa9s {
  stop-color: var(--svg-color--cbc4d5, #CBC4D5);
}

.pbdsl_bog {
  cx: 9.836px;
  cy: 16.117px;
  r: 0.75px;
  fill: var(--svg-color--e44f2e, #E44F2E);
}

.pinc10x1d {
  stop-color: var(--svg-color--bab4c6, #BAB4C6);
}

.psp4ckbvi {
  stop-color: var(--svg-color--ff8144, #FF8144);
}

.pveg-8y5i {
  fill-rule: evenodd;
  d: path("M20 13h6a4 4 0 0 1 0 8h-6zm2 2v4h4a2 2 0 1 0 0-4z");
}

.qe_nrwybn {
  stop-color: var(--svg-color--8e8d8f, #8E8D8F);
}

.qvijrsbto {
  stop-color: var(--svg-color--63be6c, #63BE6C);
}

.r-sgj4b1d {
  stop-color: var(--svg-color--e1e0e7, #E1E0E7);
  stop-opacity: 0;
}

.rgld9vb4t {
  fill: var(--svg-color--eb502e, #EB502E);
  d: path("M16 19.172c-.643 0-1.782.934-1.973 1.769c-.029.128.074.238.206.245c.339.018 1.011.048 1.767.048s1.428-.03 1.767-.048c.132-.007.234-.117.203-.245c-.191-.779-1.254-1.77-1.97-1.77");
}

.rp-81-kjx {
  stop-color: var(--svg-color--c86d42, #C86D42);
}

.sdcw15t3w {
  stop-color: var(--svg-color--f1412e, #F1412E);
}

.sfp530a7b {
  stop-color: var(--svg-color--87799a, #87799A);
}

.shtuqsgkl {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M4.297 19.016c-.339-.266-1.031-1.163-1.031-2.063c0-1.781 1.437-2.234 1.437-2.234");
}

.t4eog8bhk {
  stop-color: var(--svg-color--898391, #898391);
}

.t6bcwzzow {
  fill-rule: evenodd;
  d: path("M4.535 15.198c-.398.266-.816.766-.816 1.833c0 .787.352 1.317.795 1.67c.474.378 1.01.518 1.244.518h1.601a.75.75 0 1 1 0 1.5H5.758c-.61 0-1.47-.28-2.179-.845a3.54 3.54 0 0 1-1.36-2.843c0-1.558.66-2.53 1.482-3.08a3.8 3.8 0 0 1 1.994-.615H7.64v1.5H5.696a2.3 2.3 0 0 0-1.16.362m3.856-1.112a.75.75 0 0 1-.75.75v-.75l-.001-.75a.75.75 0 0 1 .75.75");
}

.tvp-_cbsm {
  stop-color: var(--svg-color--b6b6bc, #B6B6BC);
}

.ub_m3bb1r {
  fill: var(--svg-color--f15c31, #F15C31);
  fill-rule: evenodd;
  d: path("M17.985 12.156c0-1.087.886-1.969 1.98-1.969c1.008 0 1.84.75 1.963 1.72c.017.137-.096.25-.234.25zm-1.948-.247a.99.99 0 0 1 .959-.737c.546 0 .99.44.99.984h-1.73c-.138 0-.253-.114-.219-.247");
}

.ubwf1pp0w {
  stop-color: var(--svg-color--4c9840, #4C9840);
}

.uqnfbvo9p {
  stop-color: var(--svg-color--fff15a, #FFF15A);
}

.vtak2cs-n {
  stop-color: var(--svg-color--898391, #898391);
  stop-opacity: 0;
}

.w81dqbg_p {
  stop-color: var(--svg-color--837c8b, #837C8B);
}

.w89uifo7x {
  stop-color: var(--svg-color--8c8695, #8C8695);
}

.wddr4l2ef {
  stop-color: var(--svg-color--e3e2e9, #E3E2E9);
}

.wpr6c48vv {
  cx: 15.992px;
  cy: 14.563px;
  rx: 8.227px;
  ry: 7.938px;
}

.x1okj2bkw {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M28.406 19.172c.339-.297 1.032-1.298 1.032-2.303c0-1.988-1.438-2.494-1.438-2.494");
}

.x3dykpbsd {
  cx: 16px;
  cy: 14.266px;
  rx: 9px;
  ry: 9.266px;
}

.x71--4-vz {
  stop-color: var(--svg-color--ffd53c, #FFD53C);
}

.xgvx0f9mh {
  stop-color: var(--svg-color--aea6bc, #AEA6BC);
}

.y_yy7prrh {
  stop-color: var(--svg-color--de9a2b, #DE9A2B);
}

.yb4hz-lhk {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M12.969 12.156c.057.453.225 1.397.937 2.11s2.125.703 2.125.703");
}

.yyut8i0qw {
  stop-color: var(--svg-color--9280ad, #9280AD);
}

.zo13vrb2o {
  stop-color: var(--svg-color--cac7cf, #CAC7CF);
}

.zrfojabsg {
  stop-color: var(--svg-color--7f7098, #7F7098);
}

</style>
