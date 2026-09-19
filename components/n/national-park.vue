<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iOVQjJd)"><path class="vdeummbun"/></g><path fill="url(#iLq5hyc)" class="ytx-iabmk"/><g filter="url(#iM9qGbe)"><path stroke="url(#icLWopc)" class="itin8ac0p"/></g><path fill="url(#iRI2yrb)" class="c9d0mab7o"/><path fill="url(#iM4jvGe)" class="c9d0mab7o"/><path class="n4mgrtbix"/><path fill="url(#irub5LH)" class="m9w05rbgg"/><path fill="url(#igvxfCb)" class="m9w05rbgg"/><path fill="url(#iNuWEXc)" class="m9w05rbgg"/><path fill="url(#ium4leb)" class="m9w05rbgg"/><path fill="url(#isTA1wd)" class="m9w05rbgg"/><path fill="url(#iNjkfEe)" class="m9w05rbgg"/><path fill="url(#ig8yd6l)" class="i0bzq-b9x"/><path fill="url(#ivWGrxq)" class="w_ih7__gd"/><path fill="url(#iN6CHzd)" class="w_ih7__gd"/><path fill="url(#ioTdLtd)" class="w_ih7__gd"/><path fill="url(#iE6tP8Q)" class="w_ih7__gd"/><path fill="url(#ipP2Bic)" class="nurc88b5l"/><path fill="url(#iriaJ3m)" class="nurc88b5l"/><path fill="url(#iGa5wqb)" class="nurc88b5l"/><path fill="url(#i04juOb)" class="u6kp-_bcs"/><path fill="url(#imxuSwc)" class="u6kp-_bcs"/><path fill="url(#iZFFrFb)" class="u6kp-_bcs"/><g filter="url(#iuOw31b)"><path fill="url(#iExjQid)" class="voh26_b_y"/><path fill="url(#i7UiWQc)" class="voh26_b_y"/><path fill="url(#i4J0sIb)" class="voh26_b_y"/></g><g filter="url(#iqXM2sd)"><path fill="url(#i3S1fLr)" class="vqtqx7jzg"/><path fill="url(#io4wSMd)" class="vqtqx7jzg"/><path fill="url(#iVkRGOc)" class="vqtqx7jzg"/></g><g filter="url(#i8lk1nd)"><path fill="url(#iZFyg9b)" class="nhe0gbc5t"/><path fill="url(#i0oZnzc)" class="nhe0gbc5t"/><path fill="url(#isWPcWc)" class="nhe0gbc5t"/></g><path fill="url(#idiU6Hc)" class="te1ydsvnl"/><path fill="url(#i1xGGac)" class="te1ydsvnl"/><path fill="url(#ivuDZac)" class="pazw3tbxj"/><path fill="url(#ic4a52b)" class="pazw3tbxj"/><path fill="url(#i4C3cOb)" class="pazw3tbxj"/><defs><radialGradient id="iLq5hyc" cx="0" cy="0" r="1" gradientTransform="matrix(-6.16673 6.59498 -4.8832 -4.5661 30.93 1.412)" gradientUnits="userSpaceOnUse"><stop class="op4bu0ias"/><stop offset="1" class="l2-c3ac4j"/></radialGradient><radialGradient id="iRI2yrb" cx="0" cy="0" r="1" gradientTransform="rotate(-140.739 7.094 3.598)scale(2.95281)" gradientUnits="userSpaceOnUse"><stop class="unozt67tp"/><stop offset="1" class="qck58yj_e"/></radialGradient><radialGradient id="iM4jvGe" cx="0" cy="0" r="1" gradientTransform="rotate(102.875 -.07 5.97)scale(3.25397)" gradientUnits="userSpaceOnUse"><stop class="wu09j_h4w"/><stop offset="1" class="vc3no7b9m"/></radialGradient><radialGradient id="irub5LH" cx="0" cy="0" r="1" gradientTransform="rotate(122.998 8.15 8.684)scale(8.321 8.34371)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="stui2mbih"/></radialGradient><radialGradient id="igvxfCb" cx="0" cy="0" r="1" gradientTransform="rotate(149.534 2.162 6.7)scale(3.33901 6.28154)" gradientUnits="userSpaceOnUse"><stop class="ydvfhj7hu"/><stop offset="1" class="xpsmgxbnm"/></radialGradient><radialGradient id="iNuWEXc" cx="0" cy="0" r="1" gradientTransform="rotate(-110.556 11.73 4.804)scale(6.94297 4.20819)" gradientUnits="userSpaceOnUse"><stop class="xl530bbnr"/><stop offset="1" class="omo778w_z"/></radialGradient><radialGradient id="isTA1wd" cx="0" cy="0" r="1" gradientTransform="matrix(5.75958 -8.38274 3.03555 2.08565 11.253 17.428)" gradientUnits="userSpaceOnUse"><stop class="i4e748brb"/><stop offset="1" class="h3w7dfsnl"/></radialGradient><radialGradient id="iNjkfEe" cx="0" cy="0" r="1" gradientTransform="matrix(1.36865 6.0732 -1.41115 .31802 8.316 7.762)" gradientUnits="userSpaceOnUse"><stop class="wu_z-4plc"/><stop offset="1" class="hv7u9il5p"/></radialGradient><radialGradient id="ig8yd6l" cx="0" cy="0" r="1" gradientTransform="matrix(2.22688 -.47107 .63816 3.01673 28.531 11.861)" gradientUnits="userSpaceOnUse"><stop offset=".187" class="mwe-g-bgi"/><stop offset="1" class="vc--wpv5i"/></radialGradient><radialGradient id="iN6CHzd" cx="0" cy="0" r="1" gradientTransform="rotate(124.992 6.243 11.515)scale(2.77135 3.67213)" gradientUnits="userSpaceOnUse"><stop class="aqa_0yb-u"/><stop offset="1" class="mk14htbpa"/></radialGradient><radialGradient id="iriaJ3m" cx="0" cy="0" r="1" gradientTransform="matrix(0 -13.5429 10.8186 0 22.667 18.4)" gradientUnits="userSpaceOnUse"><stop offset=".935" class="zjs31ypvf"/><stop offset=".983" class="sly-dz45s"/></radialGradient><radialGradient id="i04juOb" cx="0" cy="0" r="1" gradientTransform="rotate(125.218 .334 8.475)scale(6.59755 6.71878)" gradientUnits="userSpaceOnUse"><stop class="g3-hl9baw"/><stop offset="1" class="b72c0r8rh"/></radialGradient><radialGradient id="imxuSwc" cx="0" cy="0" r="1" gradientTransform="rotate(-146.826 4.574 7.627)scale(1.42328 3.00313)" gradientUnits="userSpaceOnUse"><stop class="yt-mor8uo"/><stop offset="1" class="b7f4t1e9s"/></radialGradient><radialGradient id="iZFFrFb" cx="0" cy="0" r="1" gradientTransform="matrix(-.67743 2.63955 -2.38806 -.61288 5.313 11.768)" gradientUnits="userSpaceOnUse"><stop class="ok2nx7d1j"/><stop offset="1" class="gbhvvccyg"/></radialGradient><radialGradient id="idiU6Hc" cx="0" cy="0" r="1" gradientTransform="matrix(-.625 -7.125 22.18451 -1.946 23.412 23.063)" gradientUnits="userSpaceOnUse"><stop offset=".117" class="o2v7z39is"/><stop offset="1" class="f13009bzb"/></radialGradient><radialGradient id="ivuDZac" cx="0" cy="0" r="1" gradientTransform="rotate(-168.326 15.24 11.563)scale(33.5657 36.6658)" gradientUnits="userSpaceOnUse"><stop class="mu0u9h1ki"/><stop offset=".889" class="anireu70x"/></radialGradient><radialGradient id="ic4a52b" cx="0" cy="0" r="1" gradientTransform="matrix(-1.375 -13.81253 38.67733 -3.85022 13.787 33)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="j9xad3h0x"/><stop offset="1" class="e65orac_t"/></radialGradient><radialGradient id="i4C3cOb" cx="0" cy="0" r="1" gradientTransform="matrix(.32776 -15.12505 42.35246 .91777 15.662 34.375)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="v-6tln6vc"/><stop offset="1" class="oaahmhb5n"/></radialGradient><linearGradient id="icLWopc" x1="27.875" x2="27.875" y1="3.239" y2="11.219" gradientUnits="userSpaceOnUse"><stop class="dtcillbkx"/><stop offset="1" class="r7zpd2bof"/></linearGradient><linearGradient id="ium4leb" x1="1.395" x2="4.341" y1="16.323" y2="13.005" gradientUnits="userSpaceOnUse"><stop class="pnblhpyhv"/><stop offset="1" class="ejfuvybdn"/></linearGradient><linearGradient id="ivWGrxq" x1="18.652" x2="18.652" y1="10.125" y2="20" gradientUnits="userSpaceOnUse"><stop class="ektzoybcg"/><stop offset="1" class="b-a0vzvon"/></linearGradient><linearGradient id="ioTdLtd" x1="12.453" x2="13.132" y1="18.472" y2="16.123" gradientUnits="userSpaceOnUse"><stop class="lrc_bdcqz"/><stop offset="1" class="ze6nsgpdk"/></linearGradient><linearGradient id="iE6tP8Q" x1="12.892" x2="14.688" y1="12.115" y2="13.541" gradientUnits="userSpaceOnUse"><stop class="bl2y8ab2q"/><stop offset="1" class="qu-2jdbmq"/></linearGradient><linearGradient id="ipP2Bic" x1="20.37" x2="25.145" y1="13.531" y2="7.993" gradientUnits="userSpaceOnUse"><stop class="q7nmfpb5b"/><stop offset="1" class="hz5-rt4ii"/></linearGradient><linearGradient id="iGa5wqb" x1="26.616" x2="24.326" y1="5.093" y2="7.664" gradientUnits="userSpaceOnUse"><stop offset=".302" class="wpm4nlbcf"/><stop offset="1" class="gj43hfbvt"/></linearGradient><linearGradient id="iExjQid" x1="14.527" x2="15.393" y1="16.994" y2="15.591" gradientUnits="userSpaceOnUse"><stop class="xf3pbcqxp"/><stop offset="1" class="l_zh3t9mv"/></linearGradient><linearGradient id="i7UiWQc" x1="14.992" x2="14.992" y1="17.136" y2="16.447" gradientUnits="userSpaceOnUse"><stop class="m5hlz1bdl"/><stop offset="1" class="zx2gikkbc"/></linearGradient><linearGradient id="i4J0sIb" x1="15.743" x2="15.4" y1="15.835" y2="15.989" gradientUnits="userSpaceOnUse"><stop offset=".122" class="zpyyuab6y"/><stop offset="1" class="yuopjrpfs"/></linearGradient><linearGradient id="i3S1fLr" x1="4.25" x2="5.663" y1="17.274" y2="14.987" gradientUnits="userSpaceOnUse"><stop class="d99l0db0d"/><stop offset="1" class="bl3fwn4nb"/></linearGradient><linearGradient id="io4wSMd" x1="5.007" x2="5.007" y1="17.506" y2="16.382" gradientUnits="userSpaceOnUse"><stop class="wbo7tnv5l"/><stop offset="1" class="ilgukwf8h"/></linearGradient><linearGradient id="iVkRGOc" x1="6.231" x2="5.672" y1="15.383" y2="15.634" gradientUnits="userSpaceOnUse"><stop offset=".122" class="zl0kuhcak"/><stop offset="1" class="hwpy38kye"/></linearGradient><linearGradient id="iZFyg9b" x1="26.324" x2="27.556" y1="17.144" y2="15.154" gradientUnits="userSpaceOnUse"><stop class="xf3pbcqxp"/><stop offset="1" class="l_zh3t9mv"/></linearGradient><linearGradient id="i0oZnzc" x1="26.983" x2="26.983" y1="17.346" y2="16.367" gradientUnits="userSpaceOnUse"><stop class="m5hlz1bdl"/><stop offset="1" class="zx2gikkbc"/></linearGradient><linearGradient id="isWPcWc" x1="28.047" x2="27.561" y1="15.498" y2="15.715" gradientUnits="userSpaceOnUse"><stop offset=".122" class="zpyyuab6y"/><stop offset="1" class="yuopjrpfs"/></linearGradient><linearGradient id="i1xGGac" x1="15.989" x2="15.989" y1="16.797" y2="17.547" gradientUnits="userSpaceOnUse"><stop class="z--kb1lam"/><stop offset="1" class="uhmffv60y"/></linearGradient><filter id="iOVQjJd" width="28.03" height="28.51" x="1.974" y="1.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".5"/><feGaussianBlur stdDeviation="2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.27451 0 0 0 0 0.588235 0 0 0 0 0.741176 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5296"/></filter><filter id="iM9qGbe" width="6" height="14.865" x="24.675" y=".939" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_5296" stdDeviation="1"/></filter><filter id="iuOw31b" width="2.266" height="2.01" x="13.984" y="14.984" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.517647 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5296"/></filter><filter id="iqXM2sd" width="3.534" height="3.28" x="3.365" y="13.994" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.156863 0 0 0 0 0.419608 0 0 0 0 0.329412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5296"/></filter><filter id="i8lk1nd" width="3.105" height="2.856" x="25.555" y="14.287" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".25"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.137255 0 0 0 0 0.517647 0 0 0 0 0.333333 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_5296"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:national-park" /></template>
<style>
.anireu70x {
  stop-color: var(--svg-color--3974ff, #3974FF);
}

.aqa_0yb-u {
  stop-color: var(--svg-color--50457d, #50457D);
}

.b-a0vzvon {
  stop-color: var(--svg-color--3f3a60, #3F3A60);
}

.b72c0r8rh {
  stop-color: var(--svg-color--423c69, #423C69);
}

.b7f4t1e9s {
  stop-color: var(--svg-color--21233c, #21233C);
  stop-opacity: 0;
}

.bl2y8ab2q {
  stop-color: var(--svg-color--39325b, #39325B);
}

.bl3fwn4nb {
  stop-color: var(--svg-color--58be94, #58BE94);
}

.c9d0mab7o {
  d: path("M8.785 13.754a2.88 2.88 0 1 0 0-5.76a2.88 2.88 0 0 0 0 5.76");
}

.d99l0db0d {
  stop-color: var(--svg-color--269b69, #269B69);
}

.dtcillbkx {
  stop-color: var(--svg-color--5ddbff, #5DDBFF);
}

.e65orac_t {
  stop-color: var(--svg-color--287cd6, #287CD6);
}

.ejfuvybdn {
  stop-color: var(--svg-color--b6abc0, #B6ABC0);
  stop-opacity: 0;
}

.ektzoybcg {
  stop-color: var(--svg-color--504681, #504681);
}

.f13009bzb {
  stop-color: var(--svg-color--3b9f86, #3B9F86);
}

.ft5dv1b6b {
  fill: none;
}

.g3-hl9baw {
  stop-color: var(--svg-color--716aa3, #716AA3);
}

.gbhvvccyg {
  stop-color: var(--svg-color--68667c, #68667C);
  stop-opacity: 0;
}

.gj43hfbvt {
  stop-color: var(--svg-color--a7a7d7, #A7A7D7);
  stop-opacity: 0;
}

.h3w7dfsnl {
  stop-color: var(--svg-color--a19fa5, #A19FA5);
  stop-opacity: 0;
}

.hv7u9il5p {
  stop-color: var(--svg-color--b4b4b5, #B4B4B5);
  stop-opacity: 0;
}

.hwpy38kye {
  stop-color: var(--svg-color--65d1a1, #65D1A1);
  stop-opacity: 0;
}

.hz5-rt4ii {
  stop-color: var(--svg-color--62568f, #62568F);
}

.i0bzq-b9x {
  d: path("M30.005 9.056a5 5 0 0 0-.325-.012c-2.278 0-4.125 1.725-4.125 3.852c0 2.128 1.847 3.852 4.125 3.852q.165 0 .325-.011z");
}

.i4e748brb {
  stop-color: var(--svg-color--a19fa5, #A19FA5);
}

.ilgukwf8h {
  stop-color: var(--svg-color--01542b, #01542B);
  stop-opacity: 0;
}

.itin8ac0p {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M27.675 12.803V3.94");
}

.j9xad3h0x {
  stop-color: var(--svg-color--287cd6, #287CD6);
  stop-opacity: 0;
}

.l_zh3t9mv {
  stop-color: var(--svg-color--4fcf84, #4FCF84);
}

.l2-c3ac4j {
  stop-color: var(--svg-color--60deff, #60DEFF);
  stop-opacity: 0;
}

.lrc_bdcqz {
  stop-color: var(--svg-color--21183b, #21183B);
}

.m5hlz1bdl {
  stop-color: var(--svg-color--01a13e, #01A13E);
}

.m9w05rbgg {
  d: path("M9.473 9.545c.997-1.925 3.437-3.557 5.541-3.557c3.454-.34 7.805 3.15 7.805 7.316c0 3.29-4.514 5.96-7.804 5.96h-9.03a4.63 4.63 0 0 1-4.01-2.312v-4.636a4.625 4.625 0 0 1 6.262-1.725c.768.43.753-.296 1.236-1.046");
}

.mk14htbpa {
  stop-color: var(--svg-color--50457d, #50457D);
  stop-opacity: 0;
}

.mu0u9h1ki {
  stop-color: var(--svg-color--60dcff, #60DCFF);
}

.mwe-g-bgi {
  stop-color: var(--svg-color--eaeff3, #EAEFF3);
}

.n4mgrtbix {
  fill: var(--svg-color--d1d0d2, #D1D0D2);
  d: path("M9.473 9.545c.997-1.925 3.437-3.557 5.541-3.557c3.454-.34 7.805 3.15 7.805 7.316c0 3.29-4.514 5.96-7.804 5.96h-9.03a4.63 4.63 0 0 1-4.01-2.312v-4.636a4.625 4.625 0 0 1 6.262-1.725c.768.43.753-.296 1.236-1.046");
}

.nhe0gbc5t {
  d: path("m26.425 14.624l-.81 1.68c-.19.39.1.84.53.84h1.68c.44 0 .72-.47.52-.86l-.87-1.68a.586.586 0 0 0-1.05.02");
}

.nurc88b5l {
  d: path("m25.411 18.4l-4.556-4.556c-.6-.6-1.42-.94-2.27-.94c-.93 0-1.68-.75-1.68-1.68v-2.23h.18a2.2 2.2 0 0 0 1.53-.63l2.35-2.35c.78-.78 2.06-.78 2.84 0l6.2 6.2v4.806h-.047z");
}

.o2v7z39is {
  stop-color: var(--svg-color--33ce7a, #33CE7A);
}

.oaahmhb5n {
  stop-color: var(--svg-color--51ebff, #51EBFF);
}

.ok2nx7d1j {
  stop-color: var(--svg-color--68667c, #68667C);
}

.omo778w_z {
  stop-color: var(--svg-color--b2a1c5, #B2A1C5);
  stop-opacity: 0;
}

.op4bu0ias {
  stop-color: var(--svg-color--60deff, #60DEFF);
}

.pazw3tbxj {
  d: path("M30.005 21.09a90 90 0 0 0-14.02-1.096a90 90 0 0 0-14.01 1.096v5.754a3.16 3.16 0 0 0 3.16 3.16h21.71a3.16 3.16 0 0 0 3.16-3.16z");
}

.pnblhpyhv {
  stop-color: var(--svg-color--b6abc0, #B6ABC0);
}

.q7nmfpb5b {
  stop-color: var(--svg-color--473862, #473862);
}

.qck58yj_e {
  stop-color: var(--svg-color--d6dde2, #D6DDE2);
}

.qu-2jdbmq {
  stop-color: var(--svg-color--39325b, #39325B);
  stop-opacity: 0;
}

.r7zpd2bof {
  stop-color: var(--svg-color--5ddbff, #5DDBFF);
  stop-opacity: 0;
}

.sly-dz45s {
  stop-color: var(--svg-color--a49ec8, #A49EC8);
}

.stui2mbih {
  stop-color: var(--svg-color--fff, #fff);
  stop-opacity: 0;
}

.te1ydsvnl {
  d: path("M30.005 16.994H1.974v4.58h28.03z");
}

.u6kp-_bcs {
  d: path("m1.974 17.008l5.34 4.02h8.534l-8.444-8.444c-.78-.78-2.06-.78-2.84 0l-2.35 2.35a2 2 0 0 1-.24.203z");
}

.uhmffv60y {
  stop-color: var(--svg-color--45c978, #45C978);
  stop-opacity: 0;
}

.unozt67tp {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
}

.v-6tln6vc {
  stop-color: var(--svg-color--51ebff, #51EBFF);
  stop-opacity: 0;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vc3no7b9m {
  stop-color: var(--svg-color--acb2b6, #ACB2B6);
  stop-opacity: 0;
}

.vdeummbun {
  fill: var(--svg-color--4fd3ff, #4FD3FF);
  d: path("M26.845 1.994H5.134a3.16 3.16 0 0 0-3.16 3.16v21.69a3.16 3.16 0 0 0 3.16 3.16h21.71a3.16 3.16 0 0 0 3.16-3.16v-21.7c0-1.74-1.42-3.15-3.16-3.15");
}

.voh26_b_y {
  d: path("m14.595 15.214l-.57 1.19c-.13.27.07.59.37.59h1.19c.31 0 .51-.33.37-.6l-.61-1.19c-.17-.3-.6-.29-.75.01");
}

.vqtqx7jzg {
  d: path("m4.365 14.374l-.93 1.93c-.22.45.11.97.61.97h1.93c.5 0 .83-.53.6-.98l-1-1.93a.676.676 0 0 0-1.21.01");
}

.w_ih7__gd {
  d: path("m30.005 12.214l-6.2-6.2c-.78-.78-2.06-.78-2.84 0l-2.35 2.35c-.41.4-.96.63-1.53.63h-.12c-.64 0-1.25.29-1.66.78l-4.35 5.22l-5.64 6.67c-.78.78-.78 2.06 0 2.84l24.643-7.485h.047z");
}

.wbo7tnv5l {
  stop-color: var(--svg-color--01542b, #01542B);
}

.wpm4nlbcf {
  stop-color: var(--svg-color--a7a7d7, #A7A7D7);
}

.wu_z-4plc {
  stop-color: var(--svg-color--b4b4b5, #B4B4B5);
}

.wu09j_h4w {
  stop-color: var(--svg-color--acb2b6, #ACB2B6);
}

.xf3pbcqxp {
  stop-color: var(--svg-color--29b465, #29B465);
}

.xl530bbnr {
  stop-color: var(--svg-color--b2a1c5, #B2A1C5);
}

.xpsmgxbnm {
  stop-color: var(--svg-color--e1e0e2, #E1E0E2);
  stop-opacity: 0;
}

.ydvfhj7hu {
  stop-color: var(--svg-color--ebebeb, #EBEBEB);
}

.yt-mor8uo {
  stop-color: var(--svg-color--21233c, #21233C);
}

.ytx-iabmk {
  d: path("M26.845 1.994H5.134a3.16 3.16 0 0 0-3.16 3.16v21.69a3.16 3.16 0 0 0 3.16 3.16h21.71a3.16 3.16 0 0 0 3.16-3.16v-21.7c0-1.74-1.42-3.15-3.16-3.15");
}

.yuopjrpfs {
  stop-color: var(--svg-color--5fda8d, #5FDA8D);
  stop-opacity: 0;
}

.z--kb1lam {
  stop-color: var(--svg-color--45c978, #45C978);
}

.ze6nsgpdk {
  stop-color: var(--svg-color--21183b, #21183B);
  stop-opacity: 0;
}

.zjs31ypvf {
  stop-color: var(--svg-color--a49ec8, #A49EC8);
  stop-opacity: 0;
}

.zl0kuhcak {
  stop-color: var(--svg-color--65d1a1, #65D1A1);
}

.zpyyuab6y {
  stop-color: var(--svg-color--5fda8d, #5FDA8D);
}

.zx2gikkbc {
  stop-color: var(--svg-color--01a13e, #01A13E);
  stop-opacity: 0;
}

</style>
