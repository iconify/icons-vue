<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iyFwuAd)" class="ntnu75b5y"/><rect fill="url(#ipZicTc)" class="qq4vu6iur"/><rect fill="url(#i5fQAlb)" class="uvf6-ab5k"/><path class="ucmbxvbbr"/><rect fill="url(#ih4qyhd)" class="iw2w0skhw"/><rect class="rhhf6ebly"/><rect class="bpnfe4d0e"/><rect fill="url(#iDSXDfc)" class="x0d9zuzeb"/><rect class="io96qobjj"/><rect class="mj4rxac8m"/><rect fill="url(#iDrIXNc)" class="j4ouccbdu"/><path fill="url(#i0GpcVI)" class="hg-vfybfg"/><path fill="url(#imkxWqe)" class="hg-vfybfg"/><g filter="url(#i9774zd)"><path fill="url(#iEVrvpb)" class="z3s67om1o"/><path fill="url(#ihDpVqd)" class="z3s67om1o"/></g><g filter="url(#iUQzHEe)"><path fill="url(#iWnZDRl)" class="x-br_iq5a"/><path fill="url(#iebayKW)" class="x-br_iq5a"/></g><path fill="url(#inz3Q4d)" class="kwxrv67un"/><path fill="url(#ivt2RZb)" class="kwxrv67un"/><path fill="url(#ieJGzae)" class="kwxrv67un"/><path fill="url(#iYEqcmG)" class="h3e9mkrrg"/><path fill="url(#iPgOqrP)" class="h3e9mkrrg"/><path fill="url(#ieqe3Fe)" class="h3e9mkrrg"/><path fill="url(#iosl3sc)" class="q4-klcbam"/><path fill="url(#imoFrkb)" class="y6_e-1d9s"/><g filter="url(#iHYxewd)"><path class="s52oknx6i"/></g><g filter="url(#ioa4bvG)"><path class="teii_mb6c"/><path fill="url(#ivbIfed)" class="nqufpjbik"/></g><path fill="url(#iadD5Pc)" class="i-dyvh7zb"/><path fill="url(#iQQk1xd)" class="qw5fznszv"/><g filter="url(#iCmAMMe)"><path class="y8b_e0bdx"/></g><path stroke="url(#itEXGPe)" class="w3asi5b6v"/><defs><linearGradient id="iyFwuAd" x1="16" x2="16" y1="26.813" y2="29.953" gradientUnits="userSpaceOnUse"><stop class="iv_nq2ufi"/><stop offset="1" class="bprpz-bjh"/></linearGradient><linearGradient id="ipZicTc" x1="16" x2="16" y1="9.969" y2="26.875" gradientUnits="userSpaceOnUse"><stop class="l0qosebyr"/><stop offset=".974" class="rp3tnx-rk"/></linearGradient><linearGradient id="i5fQAlb" x1="16" x2="16" y1="16.156" y2="23.063" gradientUnits="userSpaceOnUse"><stop class="ra6s8sbtd"/><stop offset="1" class="l0-hodb4m"/></linearGradient><linearGradient id="ih4qyhd" x1="15.656" x2="18.555" y1="18.52" y2="18.52" gradientUnits="userSpaceOnUse"><stop class="u9zke6frd"/><stop offset="1" class="p7ijjw5um"/></linearGradient><linearGradient id="iDSXDfc" x1="15.656" x2="18.555" y1="20.48" y2="20.48" gradientUnits="userSpaceOnUse"><stop class="u9zke6frd"/><stop offset="1" class="p7ijjw5um"/></linearGradient><linearGradient id="ihDpVqd" x1="23.946" x2="23.946" y1="14.734" y2="15.828" gradientUnits="userSpaceOnUse"><stop offset=".13" class="h6qb-acao"/><stop offset="1" class="ipy9z1xka"/></linearGradient><linearGradient id="iebayKW" x1="8.054" x2="8.054" y1="14.734" y2="15.828" gradientUnits="userSpaceOnUse"><stop offset=".13" class="h6qb-acao"/><stop offset="1" class="ipy9z1xka"/></linearGradient><linearGradient id="inz3Q4d" x1="22.312" x2="20.547" y1="18.984" y2="18.984" gradientUnits="userSpaceOnUse"><stop class="xngk7ubvt"/><stop offset="1" class="vmgkxd-4j"/></linearGradient><linearGradient id="iYEqcmG" x1="8.865" x2="12.419" y1="18.984" y2="18.984" gradientUnits="userSpaceOnUse"><stop class="xngk7ubvt"/><stop offset="1" class="vmgkxd-4j"/></linearGradient><linearGradient id="iosl3sc" x1="21.016" x2="22.301" y1="20.77" y2="20.77" gradientUnits="userSpaceOnUse"><stop class="psk8nz33r"/><stop offset="1" class="g5r8wob6f"/></linearGradient><linearGradient id="imoFrkb" x1="10.984" x2="8.474" y1="20.77" y2="19.009" gradientUnits="userSpaceOnUse"><stop class="psk8nz33r"/><stop offset="1" class="g5r8wob6f"/></linearGradient><linearGradient id="ivbIfed" x1="10.984" x2="10.139" y1="19.71" y2="19.726" gradientUnits="userSpaceOnUse"><stop class="myv2fl82b"/><stop offset="1" class="xfumukc6e"/></linearGradient><linearGradient id="iadD5Pc" x1="25.406" x2="26.877" y1="23.063" y2="20.063" gradientUnits="userSpaceOnUse"><stop class="l7xjay12g"/><stop offset="1" class="zidmhrv-p"/></linearGradient><linearGradient id="iQQk1xd" x1="6.08" x2="6.08" y1="19.203" y2="23.063" gradientUnits="userSpaceOnUse"><stop class="hua2lnehr"/><stop offset="1" class="lvnnfumft"/></linearGradient><linearGradient id="itEXGPe" x1="14.734" x2="15.906" y1="12.56" y2="13.516" gradientUnits="userSpaceOnUse"><stop class="iil8700cg"/><stop offset="1" class="q10y4dook"/></linearGradient><radialGradient id="iDrIXNc" cx="0" cy="0" r="1" gradientTransform="matrix(4.4375 0 0 6.69528 24.594 19.906)" gradientUnits="userSpaceOnUse"><stop offset=".651" class="xho_ammof"/><stop offset="1" class="u6fz54byr"/></radialGradient><radialGradient id="i0GpcVI" cx="0" cy="0" r="1" gradientTransform="matrix(.3912 -8.44331 12.73923 .59023 5.312 22.856)" gradientUnits="userSpaceOnUse"><stop class="xho_ammof"/><stop offset=".688" class="fkyt2hbes"/><stop offset="1" class="u6fz54byr"/></radialGradient><radialGradient id="imkxWqe" cx="0" cy="0" r="1" gradientTransform="matrix(-3.25996 2.02118 -2.44735 -3.94733 8.148 20.346)" gradientUnits="userSpaceOnUse"><stop offset=".52" class="vhbnimgce"/><stop offset="1" class="p-3dgve4x"/></radialGradient><radialGradient id="iEVrvpb" cx="0" cy="0" r="1" gradientTransform="rotate(119.946 8.122 16.242)scale(6.6359 4.76876)" gradientUnits="userSpaceOnUse"><stop class="vfns8r-gi"/><stop offset="1" class="bbovrin-y"/></radialGradient><radialGradient id="iWnZDRl" cx="0" cy="0" r="1" gradientTransform="matrix(3.3125 5.75 -4.13213 2.38046 5.75 17.313)" gradientUnits="userSpaceOnUse"><stop class="vfns8r-gi"/><stop offset="1" class="bbovrin-y"/></radialGradient><radialGradient id="ivt2RZb" cx="0" cy="0" r="1" gradientTransform="matrix(2.51795 -4.54111 3.8475 2.13336 20.334 20.215)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="p4bgt82xa"/><stop offset=".977" class="vwivanb9h"/></radialGradient><radialGradient id="ieJGzae" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.27139 -1.45069 0 21.302 19.792)" gradientUnits="userSpaceOnUse"><stop class="wvi-2vwjy"/><stop offset="1" class="if645ybcn"/></radialGradient><radialGradient id="iPgOqrP" cx="0" cy="0" r="1" gradientTransform="rotate(-119.007 11.786 6.672)scale(5.19247 4.39938)" gradientUnits="userSpaceOnUse"><stop offset=".825" class="p4bgt82xa"/><stop offset=".977" class="vwivanb9h"/></radialGradient><radialGradient id="ieqe3Fe" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.82558 -1.98125 0 10.772 19.384)" gradientUnits="userSpaceOnUse"><stop offset=".46" class="xljz0nryf"/><stop offset="1" class="j59vwv55s"/></radialGradient><filter id="i9774zd" width="5.861" height="8.156" x="21.016" y="14.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.02"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.854902 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20365"/></filter><filter id="iUQzHEe" width="5.861" height="8.156" x="5.123" y="14.906" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.866667 0 0 0 0 0.854902 0 0 0 0 0.886275 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20365"/></filter><filter id="iHYxewd" width="1.691" height="3.133" x="21.016" y="17.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.02" dy="-.02"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.66741 0 0 0 0 0.636158 0 0 0 0 0.69085 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20365"/></filter><filter id="ioa4bvG" width="1.691" height="3.133" x="9.293" y="17.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".02" dy="-.02"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.66741 0 0 0 0 0.636158 0 0 0 0 0.69085 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20365"/></filter><filter id="iCmAMMe" width="3.399" height="2.426" x="14.305" y="11.347" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.152941 0 0 0 0 0.117647 0 0 0 0 0.196078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_20365"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".1"/><feGaussianBlur stdDeviation=".05"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.262745 0 0 0 0 0.211765 0 0 0 0 0.321569 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_20365" result="effect2_innerShadow_18_20365"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:videocassette" /></template>
<style>
.bbovrin-y {
  stop-color: var(--svg-color--d6d2da, #D6D2DA);
}

.bpnfe4d0e {
  width: 5.109px;
  height: 0.93px;
  x: 13.445px;
  y: 20.016px;
  fill: var(--svg-color--b0adb4, #B0ADB4);
  rx: 0.465px;
}

.bprpz-bjh {
  stop-color: var(--svg-color--2f2243, #2F2243);
}

.fkyt2hbes {
  stop-color: var(--svg-color--38294f, #38294F);
}

.ft5dv1b6b {
  fill: none;
}

.g5r8wob6f {
  stop-color: var(--svg-color--8f8996, #8F8996);
}

.h3e9mkrrg {
  d: path("M10.813 15.346c.108.16.171.353.171.56v6.156c0 .208-.063.4-.17.56a3.64 3.64 0 0 1 0-7.276");
}

.h6qb-acao {
  stop-color: var(--svg-color--746882, #746882);
}

.hg-vfybfg {
  d: path("M10.984 15.906a1 1 0 0 0-1-1H5.031a1 1 0 0 0-1 1v6.156a1 1 0 0 0 1 1h4.953a1 1 0 0 0 1-1z");
}

.hua2lnehr {
  stop-color: var(--svg-color--544d61, #544D61);
}

.i-dyvh7zb {
  d: path("M25.43 23.063h-.466a5.3 5.3 0 0 0 1.909-3.86q.004.11.004.219c0 1.41-.55 2.69-1.447 3.64");
}

.if645ybcn {
  stop-color: var(--svg-color--493466, #493466);
  stop-opacity: 0;
}

.iil8700cg {
  stop-color: var(--svg-color--676198, #676198);
}

.io96qobjj {
  width: 6.953px;
  height: 8.156px;
  x: 21.016px;
  y: 14.852px;
  fill: var(--svg-color--473a5a, #473A5A);
  rx: 1px;
}

.ipy9z1xka {
  stop-color: var(--svg-color--d7d3db, #D7D3DB);
  stop-opacity: 0;
}

.iv_nq2ufi {
  stop-color: var(--svg-color--302243, #302243);
}

.iw2w0skhw {
  width: 5.109px;
  height: 0.93px;
  x: 13.445px;
  y: 18.055px;
  rx: 0.465px;
}

.j4ouccbdu {
  width: 6.953px;
  height: 8.156px;
  x: 21.016px;
  y: 14.906px;
  rx: 1px;
}

.j59vwv55s {
  stop-color: var(--svg-color--4a3666, #4A3666);
  stop-opacity: 0;
}

.kwxrv67un {
  d: path("M21.187 15.346a1 1 0 0 0-.171.56v6.156c0 .208.063.4.17.56a3.64 3.64 0 0 0 0-7.276");
}

.l0-hodb4m {
  stop-color: var(--svg-color--dfdbe5, #DFDBE5);
}

.l0qosebyr {
  stop-color: var(--svg-color--635ea6, #635EA6);
}

.l7xjay12g {
  stop-color: var(--svg-color--a9a6ae, #A9A6AE);
}

.lvnnfumft {
  stop-color: var(--svg-color--67626e, #67626E);
}

.mj4rxac8m {
  width: 6.953px;
  height: 8.156px;
  x: 4.031px;
  y: 14.852px;
  fill: var(--svg-color--473a5a, #473A5A);
  rx: 1px;
}

.myv2fl82b {
  stop-color: var(--svg-color--67636c, #67636C);
}

.nqufpjbik {
  d: path("M10.984 20.565v-3.123a1.568 1.568 0 1 0 0 3.123");
}

.ntnu75b5y {
  width: 28.125px;
  height: 16.906px;
  x: 1.938px;
  y: 13.047px;
  rx: 3px;
}

.p-3dgve4x {
  stop-color: var(--svg-color--1a0f2a, #1A0F2A);
  stop-opacity: 0;
}

.p4bgt82xa {
  stop-color: var(--svg-color--4d3968, #4D3968);
  stop-opacity: 0;
}

.p7ijjw5um {
  stop-color: var(--svg-color--b0adb4, #B0ADB4);
}

.psk8nz33r {
  stop-color: var(--svg-color--676072, #676072);
}

.q10y4dook {
  stop-color: var(--svg-color--676198, #676198);
  stop-opacity: 0;
}

.q4-klcbam {
  d: path("M21.016 20.765v-3.123q.061-.006.125-.005a1.566 1.566 0 1 1-.125 3.128");
}

.qq4vu6iur {
  width: 28.125px;
  height: 16.906px;
  x: 1.938px;
  y: 9.969px;
  rx: 3px;
}

.qw5fznszv {
  d: path("M6.57 23.063h.466a5.3 5.3 0 0 1-1.909-3.86a5.3 5.3 0 0 0 1.443 3.86");
}

.ra6s8sbtd {
  stop-color: var(--svg-color--dfdbe3, #DFDBE3);
}

.rhhf6ebly {
  width: 5.109px;
  height: 0.93px;
  x: 13.445px;
  y: 20.016px;
  fill: var(--svg-color--58bad0, #58BAD0);
  fill-opacity: var(--svg-fill-opacity--0-55, 0.55);
  rx: 0.465px;
}

.rp3tnx-rk {
  stop-color: var(--svg-color--553e71, #553E71);
}

.s52oknx6i {
  fill: var(--svg-color--9a989e, #9A989E);
  d: path("M21.016 20.565v-3.123a1.568 1.568 0 1 1 0 3.123");
}

.teii_mb6c {
  fill: var(--svg-color--9a989e, #9A989E);
  d: path("M10.984 20.565v-3.123a1.568 1.568 0 1 0 0 3.123");
}

.u6fz54byr {
  stop-color: var(--svg-color--100523, #100523);
}

.u9zke6frd {
  stop-color: var(--svg-color--b1aeb4, #B1AEB4);
}

.ucmbxvbbr {
  fill: var(--svg-color--f13861, #F13861);
  d: path("M20.094 16.469h-8.188v-.563a1 1 0 0 1 1-1h6.188a1 1 0 0 1 1 1z");
}

.uvf6-ab5k {
  width: 8.188px;
  height: 8.156px;
  x: 11.906px;
  y: 14.906px;
  rx: 1px;
}

.vfns8r-gi {
  stop-color: var(--svg-color--d4d0d8, #D4D0D8);
}

.vhbnimgce {
  stop-color: var(--svg-color--1a0f2a, #1A0F2A);
}

.vmgkxd-4j {
  stop-color: var(--svg-color--402b5d, #402B5D);
}

.vwivanb9h {
  stop-color: var(--svg-color--291745, #291745);
}

.w3asi5b6v {
  stroke-width: var(--svg-stroke-width--0-05px, 0.05px);
  d: path("m15.74 11.463l-1.311 1.905a.275.275 0 0 0 .226.43h2.699a.275.275 0 0 0 .227-.43l-1.305-1.905a.325.325 0 0 0-.536 0Z");
}

.wvi-2vwjy {
  stop-color: var(--svg-color--493466, #493466);
}

.x-br_iq5a {
  d: path("M7.036 23.063a5.3 5.3 0 0 1-1.913-4.079c0-1.64.744-3.105 1.913-4.078h2.948a1 1 0 0 1 1 1v6.156a1 1 0 0 1-1 1z");
}

.x0d9zuzeb {
  width: 5.109px;
  height: 0.93px;
  x: 13.445px;
  y: 20.016px;
  rx: 0.465px;
}

.xfumukc6e {
  stop-color: var(--svg-color--9b999f, #9B999F);
  stop-opacity: 0;
}

.xho_ammof {
  stop-color: var(--svg-color--3b2b52, #3B2B52);
}

.xljz0nryf {
  stop-color: var(--svg-color--2e2043, #2E2043);
}

.xngk7ubvt {
  stop-color: var(--svg-color--53416e, #53416E);
}

.y6_e-1d9s {
  d: path("M10.984 20.765v-3.123a1.566 1.566 0 1 0 0 3.123");
}

.y8b_e0bdx {
  fill: var(--svg-color--504060, #504060);
  d: path("m15.76 11.477l-1.31 1.905a.25.25 0 0 0 .205.392h2.699a.25.25 0 0 0 .206-.392l-1.305-1.904a.3.3 0 0 0-.495 0");
}

.z3s67om1o {
  d: path("M24.964 23.063a5.3 5.3 0 0 0 1.913-4.079c0-1.64-.744-3.105-1.913-4.078h-2.948a1 1 0 0 0-1 1v6.156a1 1 0 0 0 1 1z");
}

.zidmhrv-p {
  stop-color: var(--svg-color--8d8a92, #8D8A92);
}

</style>
