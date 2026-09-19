<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iK5ss7b)" class="hntxvv91o"/><rect fill="url(#idE8uyb)" class="hntxvv91o"/><path fill="url(#iP4GBpc)" class="trloanblz"/><path fill="url(#i6xiCsb)" class="trloanblz"/><path fill="url(#iYxBUsc)" class="trloanblz"/><path fill="url(#ifcEvfc)" class="trloanblz"/><g filter="url(#isiMBib)"><path fill="url(#imuBpgc)" class="pr5srbcsp"/></g><path class="tyq938biw"/><path fill="url(#iJTIvNq)" class="rgekcdbdo"/><path fill="url(#iHOoz8l)" class="rgekcdbdo"/><path fill="url(#imtYChe)" class="rgekcdbdo"/><path fill="url(#ilenf6H)" class="rgekcdbdo"/><g filter="url(#iOVJCIb)"><path class="gcjx43bty"/><path fill="url(#igPDBXd)" class="sn692nu2n"/><path fill="url(#i3G4fdV)" class="sn692nu2n"/></g><rect fill="url(#iU4drDd)" class="s-pxt2b6i"/><rect fill="url(#iTfRide)" class="s-pxt2b6i"/><rect fill="url(#idrqxik)" class="s-pxt2b6i"/><rect fill="url(#iiOyUpb)" class="s-pxt2b6i"/><rect fill="url(#ibmcvVP)" class="s-pxt2b6i"/><rect fill="url(#iunHEJd)" class="ezm874s8f"/><rect fill="url(#i1w3DQd)" class="ezm874s8f"/><rect fill="url(#iKY6hjb)" class="ezm874s8f"/><rect fill="url(#izurRDe)" class="hiusohbhc"/><rect fill="url(#iA72GHE)" class="hiusohbhc"/><rect fill="url(#iiSRFMd)" class="hiusohbhc"/><rect fill="url(#iK8eNVc)" class="hiusohbhc"/><rect fill="url(#itHBTQn)" class="s6j8ehboa"/><rect fill="url(#i9sslnX)" class="s6j8ehboa"/><rect fill="url(#iUOA9ve)" class="s6j8ehboa"/><rect fill="url(#iC6mQlZ)" class="s6j8ehboa"/><defs><radialGradient id="iP4GBpc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.45239 7.41865 -5.95467 -1.16578 21.398 4.787)" gradientUnits="userSpaceOnUse"><stop class="gs3347o9z"/><stop offset="1" class="lo_kwkn1k"/></radialGradient><radialGradient id="ifcEvfc" cx="0" cy="0" r="1" gradientTransform="matrix(1.94501 .78125 -.58938 1.46734 18 9.352)" gradientUnits="userSpaceOnUse"><stop class="m6s5orlpe"/><stop offset="1" class="yu5deqbhy"/></radialGradient><radialGradient id="iJTIvNq" cx="0" cy="0" r="1" gradientTransform="matrix(-3.19961 0 0 -3.32917 23.639 12.406)" gradientUnits="userSpaceOnUse"><stop offset=".425" class="wwgqfmb9p"/><stop offset="1" class="mqtz8ts8k"/></radialGradient><radialGradient id="iHOoz8l" cx="0" cy="0" r="1" gradientTransform="matrix(2.14654 -.49853 2.8596 12.3127 16.25 11.882)" gradientUnits="userSpaceOnUse"><stop class="wwgqfmb9p"/><stop offset="1" class="mqtz8ts8k"/></radialGradient><radialGradient id="imtYChe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71723 3.30237 0 18.361 10.166)" gradientUnits="userSpaceOnUse"><stop class="wwgqfmb9p"/><stop offset="1" class="mqtz8ts8k"/></radialGradient><radialGradient id="ilenf6H" cx="0" cy="0" r="1" gradientTransform="matrix(-.62745 .62745 -.71264 -.71264 18.89 8.348)" gradientUnits="userSpaceOnUse"><stop class="q-hxnzcmp"/><stop offset="1" class="lehv35frp"/></radialGradient><radialGradient id="igPDBXd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68752 2.24998 -.59132 -.70631 23.483 15.062)" gradientUnits="userSpaceOnUse"><stop class="u9h--_uhg"/><stop offset="1" class="nq5--fbox"/></radialGradient><radialGradient id="iU4drDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.29687 0 0 -1.47398 24.263 11.648)" gradientUnits="userSpaceOnUse"><stop class="segmrjbcd"/><stop offset="1" class="xly5tmb_h"/></radialGradient><radialGradient id="iTfRide" cx="0" cy="0" r="1" gradientTransform="matrix(-.53893 .375 -.33792 -.48564 24.18 11.36)" gradientUnits="userSpaceOnUse"><stop class="dj5ag1bkk"/><stop offset="1" class="ale66yetj"/></radialGradient><radialGradient id="idrqxik" cx="0" cy="0" r="1" gradientTransform="matrix(.91818 0 0 1.71875 21.16 11.648)" gradientUnits="userSpaceOnUse"><stop class="rb9iwvb-r"/><stop offset="1" class="xmej9sbic"/></radialGradient><radialGradient id="i1w3DQd" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 5.352)" gradientUnits="userSpaceOnUse"><stop class="f5i6p7kyc"/><stop offset="1" class="xtgjebbxe"/></radialGradient><radialGradient id="iKY6hjb" cx="0" cy="0" r="1" gradientTransform="matrix(1.07813 0 0 1.71875 21.17 5.64)" gradientUnits="userSpaceOnUse"><stop class="rb9iwvb-r"/><stop offset="1" class="xmej9sbic"/></radialGradient><radialGradient id="izurRDe" cx="0" cy="0" r="1" gradientTransform="matrix(-2.69698 0 0 -1.47398 24.814 9.719)" gradientUnits="userSpaceOnUse"><stop class="segmrjbcd"/><stop offset="1" class="xly5tmb_h"/></radialGradient><radialGradient id="iA72GHE" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 9.43)" gradientUnits="userSpaceOnUse"><stop class="dj5ag1bkk"/><stop offset="1" class="ale66yetj"/></radialGradient><radialGradient id="iiSRFMd" cx="0" cy="0" r="1" gradientTransform="matrix(1.07813 0 0 1.71875 21.17 9.719)" gradientUnits="userSpaceOnUse"><stop class="rb9iwvb-r"/><stop offset="1" class="xmej9sbic"/></radialGradient><radialGradient id="i9sslnX" cx="0" cy="0" r="1" gradientTransform="matrix(-.66202 .375 -.3091 -.54569 24.694 7.445)" gradientUnits="userSpaceOnUse"><stop class="f5i6p7kyc"/><stop offset="1" class="xtgjebbxe"/></radialGradient><radialGradient id="iUOA9ve" cx="0" cy="0" r="1" gradientTransform="matrix(1.12788 0 0 1.71875 20.983 7.734)" gradientUnits="userSpaceOnUse"><stop class="rb9iwvb-r"/><stop offset="1" class="xmej9sbic"/></radialGradient><linearGradient id="iK5ss7b" x1="20.724" x2="24.074" y1="5.663" y2="2.508" gradientUnits="userSpaceOnUse"><stop class="w_89m814e"/><stop offset="1" class="serw5ewgc"/></linearGradient><linearGradient id="idE8uyb" x1="20.361" x2="20.361" y1="12.231" y2="11.45" gradientUnits="userSpaceOnUse"><stop class="fpvpr7bey"/><stop offset="1" class="e-cgqu93z"/></linearGradient><linearGradient id="i6xiCsb" x1="23.17" x2="22.466" y1="7.294" y2="7.294" gradientUnits="userSpaceOnUse"><stop class="pg9s5fb7y"/><stop offset="1" class="bt51ccc1c"/></linearGradient><linearGradient id="iYxBUsc" x1="16.906" x2="17.334" y1="7.016" y2="7.016" gradientUnits="userSpaceOnUse"><stop class="p4jue8bcy"/><stop offset="1" class="hylr8nchj"/></linearGradient><linearGradient id="imuBpgc" x1="21.942" x2="21.942" y1="10.602" y2="5.689" gradientUnits="userSpaceOnUse"><stop class="miuihyw-g"/><stop offset="1" class="g7p_djyaq"/></linearGradient><linearGradient id="i3G4fdV" x1="11.076" x2="11.076" y1="30.813" y2="27.188" gradientUnits="userSpaceOnUse"><stop class="mghv6db2o"/><stop offset="1" class="ehq-2ui4p"/></linearGradient><linearGradient id="iiOyUpb" x1="23.086" x2="23.086" y1="10.602" y2="10.883" gradientUnits="userSpaceOnUse"><stop class="k_q5q1btb"/><stop offset="1" class="ppovehb_c"/></linearGradient><linearGradient id="ibmcvVP" x1="23.086" x2="23.086" y1="12.261" y2="12.822" gradientUnits="userSpaceOnUse"><stop class="zr3etrbqa"/><stop offset="1" class="fexno0grb"/></linearGradient><linearGradient id="iunHEJd" x1="23.431" x2="23.431" y1="4.594" y2="6.688" gradientUnits="userSpaceOnUse"><stop class="unwf03xqx"/><stop offset="1" class="rf04682gx"/></linearGradient><linearGradient id="iK8eNVc" x1="23.431" x2="23.431" y1="8.625" y2="8.922" gradientUnits="userSpaceOnUse"><stop class="k_q5q1btb"/><stop offset="1" class="ppovehb_c"/></linearGradient><linearGradient id="itHBTQn" x1="23.349" x2="23.349" y1="6.688" y2="8.781" gradientUnits="userSpaceOnUse"><stop class="dfiwqc1cf"/><stop offset="1" class="rf04682gx"/></linearGradient><linearGradient id="iC6mQlZ" x1="23.349" x2="23.349" y1="6.563" y2="6.938" gradientUnits="userSpaceOnUse"><stop class="k_q5q1btb"/><stop offset="1" class="ppovehb_c"/></linearGradient><filter id="isiMBib" width="3.914" height="6.625" x="20.699" y="4.477" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5804" stdDeviation=".25"/></filter><filter id="iOVJCIb" width="22.048" height="15.844" x="1.998" y="15.063" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.839216 0 0 0 0 0.215686 0 0 0 0 0.380392 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5804"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:selfie" /></template>
<style>
.ale66yetj {
  stop-color: var(--svg-color--ffd666, #FFD666);
  stop-opacity: 0;
}

.bt51ccc1c {
  stop-color: var(--svg-color--6cedff, #6CEDFF);
  stop-opacity: 0;
}

.dfiwqc1cf {
  stop-color: var(--svg-color--f9bf3e, #F9BF3E);
}

.dj5ag1bkk {
  stop-color: var(--svg-color--ffd666, #FFD666);
}

.e-cgqu93z {
  stop-color: var(--svg-color--312d58, #312D58);
  stop-opacity: 0;
}

.ehq-2ui4p {
  stop-color: var(--svg-color--df42c3, #DF42C3);
  stop-opacity: 0;
}

.ezm874s8f {
  width: 3.555px;
  height: 2.094px;
  x: 21.654px;
  y: 4.594px;
  rx: 1.047px;
}

.f5i6p7kyc {
  stop-color: var(--svg-color--ffe064, #FFE064);
}

.fexno0grb {
  stop-color: var(--svg-color--eb8f72, #EB8F72);
}

.fpvpr7bey {
  stop-color: var(--svg-color--312d58, #312D58);
}

.ft5dv1b6b {
  fill: none;
}

.g7p_djyaq {
  stop-color: var(--svg-color--5192b4, #5192B4);
}

.gcjx43bty {
  fill: var(--svg-color--e83896, #E83896);
  d: path("M16.778 15.063a1.2 1.2 0 0 0-1.129.793l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.36a1 1 0 0 0-.955-1.297z");
}

.gs3347o9z {
  stop-color: var(--svg-color--54c4ff, #54C4FF);
}

.hiusohbhc {
  width: 3.555px;
  height: 2.094px;
  x: 21.654px;
  y: 8.672px;
  rx: 1.047px;
}

.hntxvv91o {
  width: 6.844px;
  height: 9.938px;
  x: 16.939px;
  y: 2.031px;
  rx: 0.9px;
}

.hylr8nchj {
  stop-color: var(--svg-color--5e98c5, #5E98C5);
  stop-opacity: 0;
}

.k_q5q1btb {
  stop-color: var(--svg-color--d68c02, #D68C02);
}

.lehv35frp {
  stop-color: var(--svg-color--ffdc62, #FFDC62);
  stop-opacity: 0;
}

.lo_kwkn1k {
  stop-color: var(--svg-color--2e8de8, #2E8DE8);
}

.m6s5orlpe {
  stop-color: var(--svg-color--267bae, #267BAE);
}

.mghv6db2o {
  stop-color: var(--svg-color--df42c3, #DF42C3);
}

.miuihyw-g {
  stop-color: var(--svg-color--2e74a1, #2E74A1);
}

.mqtz8ts8k {
  stop-color: var(--svg-color--f09b4c, #F09B4C);
  stop-opacity: 0;
}

.nq5--fbox {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
  stop-opacity: 0;
}

.p4jue8bcy {
  stop-color: var(--svg-color--5e98c5, #5E98C5);
}

.pg9s5fb7y {
  stop-color: var(--svg-color--6cedff, #6CEDFF);
}

.ppovehb_c {
  stop-color: var(--svg-color--d68c02, #D68C02);
  stop-opacity: 0;
}

.pr5srbcsp {
  d: path("M21.328 5.93c0-.526.427-.953.954-.953h.876a.954.954 0 1 1 0 1.908a.954.954 0 0 1 .305 1.858a.955.955 0 0 1-.305 1.859h-.876a.954.954 0 0 1-.362-1.838a.954.954 0 0 1 .233-1.88h.129a.954.954 0 0 1-.954-.953");
}

.q-hxnzcmp {
  stop-color: var(--svg-color--ffdc62, #FFDC62);
}

.rb9iwvb-r {
  stop-color: var(--svg-color--dd9d52, #DD9D52);
}

.rf04682gx {
  stop-color: var(--svg-color--f4af24, #F4AF24);
}

.rgekcdbdo {
  d: path("M16.62 7.297a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.368.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.054c-.132-.006-.262.02-.392.046q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.s-pxt2b6i {
  width: 3.027px;
  height: 2.094px;
  x: 21.572px;
  y: 10.602px;
  rx: 1.047px;
}

.s6j8ehboa {
  width: 3.719px;
  height: 2.094px;
  x: 21.49px;
  y: 6.688px;
  rx: 1.047px;
}

.segmrjbcd {
  stop-color: var(--svg-color--fbbe3e, #FBBE3E);
}

.serw5ewgc {
  stop-color: var(--svg-color--5c6193, #5C6193);
}

.sn692nu2n {
  d: path("M16.778 15.063a1.2 1.2 0 0 0-1.129.793l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.36a1 1 0 0 0-.955-1.297z");
}

.trloanblz {
  d: path("M16.94 11V3.031h6.01V11z");
}

.tyq938biw {
  fill: var(--svg-color--f6c32f, #F6C32F);
  d: path("M16.62 7.297a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.368.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.054c-.132-.006-.262.02-.392.046q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.u9h--_uhg {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
}

.unwf03xqx {
  stop-color: var(--svg-color--f1c438, #F1C438);
}

.w_89m814e {
  stop-color: var(--svg-color--48427d, #48427D);
}

.wwgqfmb9p {
  stop-color: var(--svg-color--f09b4c, #F09B4C);
}

.xly5tmb_h {
  stop-color: var(--svg-color--eaa504, #EAA504);
}

.xmej9sbic {
  stop-color: var(--svg-color--dd9d52, #DD9D52);
  stop-opacity: 0;
}

.xtgjebbxe {
  stop-color: var(--svg-color--ffe064, #FFE064);
  stop-opacity: 0;
}

.yu5deqbhy {
  stop-color: var(--svg-color--267bae, #267BAE);
  stop-opacity: 0;
}

.zr3etrbqa {
  stop-color: var(--svg-color--eb8f72, #EB8F72);
  stop-opacity: 0;
}

</style>
