<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#ijd33ve)"><path fill="url(#i14XBub)" class="jr2d789cx"/><path fill="url(#iyPpxKd)" class="jr2d789cx"/></g><path fill="url(#ibW2hGP)" class="vxssozeuk"/><path fill="url(#iXqE1mE)" class="fo0m2ac2h"/><path fill="url(#iIGPiOE)" class="mkxdstb0o"/><path fill="url(#i1PNf1c)" class="mkxdstb0o"/><path fill="url(#iLlkeze)" class="rpf14bbch"/><path fill="url(#i8rNyOd)" class="rpf14bbch"/><path fill="url(#iLlkeze)" class="rqg3yrb_h"/><path fill="url(#i8rNyOd)" class="rqg3yrb_h"/><path fill="url(#iBvc5qS)" class="z2ju28b2w"/><path fill="url(#iOwQVQd)" class="z2ju28b2w"/><path fill="url(#i4zmKbd)" class="hwvrs7get"/><path fill="url(#i6uMJne)" class="hwvrs7get"/><path fill="url(#iVxITXp)" class="zlyhblbcu"/><path fill="url(#iQxC6Md)" class="zlyhblbcu"/><path fill="url(#inbdSYL)" class="zlyhblbcu"/><path fill="url(#iCfVF4d)" class="pzx6u9quy"/><g filter="url(#ipFi5Jc)"><path fill="url(#iXTAySk)" class="o_bck1q9b"/><path fill="url(#irfZpvd)" class="o_bck1q9b"/></g><defs><linearGradient id="ibW2hGP" x1="11.324" x2="16.381" y1="2.15" y2="9.804" gradientUnits="userSpaceOnUse"><stop class="rh0gq5pwj"/><stop offset="1" class="zekj6cvfw"/></linearGradient><linearGradient id="iXqE1mE" x1="25.661" x2="25.148" y1="3.874" y2="10.387" gradientUnits="userSpaceOnUse"><stop class="oatnu8y2b"/><stop offset="1" class="okw-x7bxv"/></linearGradient><linearGradient id="iIGPiOE" x1="13.307" x2="7.764" y1="2.996" y2="11.7" gradientUnits="userSpaceOnUse"><stop class="a5enribkz"/><stop offset="1" class="egdc97b3d"/></linearGradient><linearGradient id="i1PNf1c" x1="13.91" x2="13.91" y1="1.811" y2="3.47" gradientUnits="userSpaceOnUse"><stop class="fx4yhfbnd"/><stop offset="1" class="e-bc9obwn"/></linearGradient><linearGradient id="iLlkeze" x1="23.49" x2="17.766" y1="3.005" y2="11.255" gradientUnits="userSpaceOnUse"><stop class="a5enribkz"/><stop offset="1" class="egdc97b3d"/></linearGradient><linearGradient id="i8rNyOd" x1="24.042" x2="24.042" y1="1.821" y2="3.479" gradientUnits="userSpaceOnUse"><stop class="fx4yhfbnd"/><stop offset="1" class="e-bc9obwn"/></linearGradient><linearGradient id="iBvc5qS" x1="20.93" x2="16.305" y1="2.713" y2="10.838" gradientUnits="userSpaceOnUse"><stop class="ly4-dcb0m"/><stop offset="1" class="zf_fasugz"/></linearGradient><linearGradient id="iOwQVQd" x1="15.093" x2="16.047" y1="7.318" y2="7.954" gradientUnits="userSpaceOnUse"><stop class="wwi-hljxf"/><stop offset="1" class="zp3822ego"/></linearGradient><linearGradient id="i4zmKbd" x1="21.404" x2="13.341" y1="16.157" y2="29.782" gradientUnits="userSpaceOnUse"><stop class="zyy2sebfb"/><stop offset="1" class="a3ao8sbxc"/></linearGradient><linearGradient id="i6uMJne" x1="12.529" x2="14.904" y1="30.594" y2="17.157" gradientUnits="userSpaceOnUse"><stop class="noy6u8_5o"/><stop offset="1" class="k_q28_b4b"/></linearGradient><linearGradient id="iVxITXp" x1="12.232" x2="24.509" y1="18.734" y2="18.734" gradientUnits="userSpaceOnUse"><stop class="ehyg8wqsg"/><stop offset="1" class="vqbzr5d3f"/></linearGradient><linearGradient id="iCfVF4d" x1="24.092" x2="16.047" y1="18.224" y2="18.224" gradientUnits="userSpaceOnUse"><stop class="u3fznriir"/><stop offset="1" class="ep_ctkm6f"/><stop offset="1" class="ep_ctkm6f"/></linearGradient><linearGradient id="iXTAySk" x1="15.082" x2="18.4" y1="19.075" y2="24.242" gradientUnits="userSpaceOnUse"><stop class="y09wzybtv"/><stop offset="1" class="hgk_o0bxr"/></linearGradient><radialGradient id="i14XBub" cx="0" cy="0" r="1" gradientTransform="rotate(124.323 3.672 5.69)scale(6.48778 12.8773)" gradientUnits="userSpaceOnUse"><stop offset=".361" class="b9u2kqbwd"/><stop offset="1" class="sn0p2-y-g"/></radialGradient><radialGradient id="iyPpxKd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -3.22394 3.90129 0 10.734 12.268)" gradientUnits="userSpaceOnUse"><stop class="nr-25yb-y"/><stop offset="1" class="p4hp88g5x"/></radialGradient><radialGradient id="iQxC6Md" cx="0" cy="0" r="1" gradientTransform="matrix(-10.9797 0 0 -9.59463 19.228 19.804)" gradientUnits="userSpaceOnUse"><stop offset=".844" class="g23k9-bem"/><stop offset="1" class="nvqwiabcw"/></radialGradient><radialGradient id="inbdSYL" cx="0" cy="0" r="1" gradientTransform="matrix(10.3667 0 0 9.34393 13.9 19.804)" gradientUnits="userSpaceOnUse"><stop offset=".826" class="p8rhe369k"/><stop offset="1" class="feq4hk7pc"/></radialGradient><radialGradient id="irfZpvd" cx="0" cy="0" r="1" gradientTransform="rotate(130.746 5.327 12.672)scale(2.68113 3.65655)" gradientUnits="userSpaceOnUse"><stop offset=".201" class="vv5ow_bjb"/><stop offset="1" class="td3nbtbdl"/></radialGradient><filter id="ijd33ve" width="14.016" height="11.609" x="3.509" y="2.01" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".15" dy="-.15"/><feGaussianBlur stdDeviation=".25"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.254902 0 0 0 0 0.329412 0 0 0 0 0.729412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1461"/></filter><filter id="ipFi5Jc" width="9.224" height="8.899" x="11.342" y="15.064" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.3" dy="-.3"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.290196 0 0 0 0 0.14902 0 0 0 0 0.14902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_1461"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".2" dy="-.2"/><feGaussianBlur stdDeviation=".075"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.517647 0 0 0 0 0.372549 0 0 0 0 0.34902 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_1461" result="effect2_innerShadow_18_1461"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:sports-medal" /></template>
<style>
.a3ao8sbxc {
  stop-color: var(--svg-color--dc9729, #DC9729);
}

.a5enribkz {
  stop-color: var(--svg-color--e3d4f3, #E3D4F3);
}

.b9u2kqbwd {
  stop-color: var(--svg-color--3fa0f7, #3FA0F7);
}

.e-bc9obwn {
  stop-color: var(--svg-color--d3ccd9, #D3CCD9);
  stop-opacity: 0;
}

.egdc97b3d {
  stop-color: var(--svg-color--e3c2f5, #E3C2F5);
}

.ehyg8wqsg {
  stop-color: var(--svg-color--faa945, #FAA945);
}

.ep_ctkm6f {
  stop-color: var(--svg-color--faa742, #FAA742);
}

.feq4hk7pc {
  stop-color: var(--svg-color--d2801f, #D2801F);
}

.fo0m2ac2h {
  d: path("m19.282 8.656l-1.67 3.014h2.643c.97 0-.76 1.226 0 .636c2.457-1.03 6.77-4.986 8.08-7.316c.72-1.27-.2-2.83-1.64-2.83h-.35c-2.192 2.29-4.725 4.585-7.063 6.496");
}

.ft5dv1b6b {
  fill: none;
}

.fx4yhfbnd {
  stop-color: var(--svg-color--d3ccd9, #D3CCD9);
}

.g23k9-bem {
  stop-color: var(--svg-color--f7b44d, #F7B44D);
  stop-opacity: 0;
}

.hgk_o0bxr {
  stop-color: var(--svg-color--5d3247, #5D3247);
}

.hwvrs7get {
  d: path("M16.037 30.094c5.545 0 10.04-4.607 10.04-10.29s-4.495-10.29-10.04-10.29s-10.04 4.607-10.04 10.29s4.495 10.29 10.04 10.29");
}

.jr2d789cx {
  d: path("M17.375 11.66c-.2-.02-.4-.04-.6-.08c-1.24-.22-2.4-.78-3.34-1.64c-2.74-2.11-6.01-4.77-7.68-7.78h-.35c-1.45 0-2.36 1.56-1.65 2.82c1.32 2.33 3.18 4.31 5.42 5.77c.76.59 4.546 2.869 5.506 2.869z");
}

.k_q28_b4b {
  stop-color: var(--svg-color--fa8547, #FA8547);
  stop-opacity: 0;
}

.ly4-dcb0m {
  stop-color: var(--svg-color--3ea0f4, #3EA0F4);
}

.mkxdstb0o {
  d: path("M16.015 11.629q-.146.017-.29.031l-.2.24l.21-.327a6.66 6.66 0 0 1-3.3-1.633c-2.74-2.11-5.218-4.78-6.888-7.79h4.388z");
}

.noy6u8_5o {
  stop-color: var(--svg-color--fa8547, #FA8547);
}

.nr-25yb-y {
  stop-color: var(--svg-color--3258bf, #3258BF);
}

.nvqwiabcw {
  stop-color: var(--svg-color--f7b44d, #F7B44D);
}

.o_bck1q9b {
  d: path("m16.647 15.754l.83 1.72c.1.2.29.35.51.38l1.85.28c.55.08.78.78.37 1.18l-1.28 1.28c-.19.19-.25.47-.17.73l.59 1.71c.2.57-.36 1.11-.91.87l-2.14-.96a.64.64 0 0 0-.54 0l-2.14.96c-.54.24-1.11-.3-.91-.87l.59-1.71c.09-.26.02-.54-.17-.73l-1.28-1.28c-.4-.4-.18-1.1.37-1.18l1.85-.28c.22-.03.41-.17.51-.38l.83-1.72c.27-.52.99-.52 1.24 0");
}

.oatnu8y2b {
  stop-color: var(--svg-color--fd4058, #FD4058);
}

.okw-x7bxv {
  stop-color: var(--svg-color--f62e9e, #F62E9E);
}

.p4hp88g5x {
  stop-color: var(--svg-color--3258bf, #3258BF);
  stop-opacity: 0;
}

.p8rhe369k {
  stop-color: var(--svg-color--d2801f, #D2801F);
  stop-opacity: 0;
}

.pzx6u9quy {
  d: path("M16.047 28.854c-2.36 0-4.58-.94-6.24-2.65a9.1 9.1 0 0 1-2.59-6.4c0-2.42.92-4.69 2.59-6.4a8.69 8.69 0 0 1 12.49 0c3.44 3.53 3.44 9.27 0 12.8c-1.68 1.71-3.9 2.65-6.25 2.65m-.01-16.87c-1.95 0-3.91.76-5.39 2.29a7.87 7.87 0 0 0-2.23 5.53c0 2.09.79 4.05 2.23 5.53a7.48 7.48 0 0 0 5.39 2.29c2.04 0 3.95-.81 5.39-2.29c2.97-3.05 2.97-8.01 0-11.06a7.46 7.46 0 0 0-5.39-2.29");
}

.rh0gq5pwj {
  stop-color: var(--svg-color--f53f56, #F53F56);
}

.rpf14bbch {
  d: path("m16.609 10.211l.18 1.27a6.65 6.65 0 0 0 2.876-1.54c2.74-2.11 5.01-4.77 6.68-7.78h-4.57z");
}

.rqg3yrb_h {
  d: path("M16.421 11.66h-.046l.2.24z");
}

.sn0p2-y-g {
  stop-color: var(--svg-color--2f60c2, #2F60C2);
}

.td3nbtbdl {
  stop-color: var(--svg-color--602543, #602543);
  stop-opacity: 0;
}

.u3fznriir {
  stop-color: var(--svg-color--f9a842, #F9A842);
}

.vqbzr5d3f {
  stop-color: var(--svg-color--ec9936, #EC9936);
}

.vv5ow_bjb {
  stop-color: var(--svg-color--602543, #602543);
}

.vxssozeuk {
  d: path("m16.205 7.37l.176 1.239l-1.563 1.195L9.797 2.15h2.178c.67 0 1.29.35 1.62.93z");
}

.wwi-hljxf {
  stop-color: var(--svg-color--6c65c0, #6C65C0);
}

.y09wzybtv {
  stop-color: var(--svg-color--864b60, #864B60);
}

.z2ju28b2w {
  d: path("M22.155 2.16h-2.04c-.67 0-1.28.35-1.62.93l-5.22 8.58h2.78z");
}

.zekj6cvfw {
  stop-color: var(--svg-color--ea3586, #EA3586);
}

.zf_fasugz {
  stop-color: var(--svg-color--437ee0, #437EE0);
}

.zlyhblbcu {
  d: path("M16.037 28.244c4.545 0 8.23-3.779 8.23-8.44s-3.685-8.44-8.23-8.44s-8.23 3.779-8.23 8.44c0 4.662 3.685 8.44 8.23 8.44");
}

.zp3822ego {
  stop-color: var(--svg-color--6c65c0, #6C65C0);
  stop-opacity: 0;
}

.zyy2sebfb {
  stop-color: var(--svg-color--f4c654, #F4C654);
}

</style>
