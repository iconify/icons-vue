<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iNV3NFc)" class="jvw-1qblv"/><path fill="url(#i99q9Ub)" class="jvw-1qblv"/><path fill="url(#ighox5d)" class="bg-pd2krb"/><path fill="url(#ib10yFg)" class="bg-pd2krb"/><path fill="url(#irLQzKX)" class="bg-pd2krb"/><path fill="url(#i04Q1Rb)" class="bg-pd2krb"/><path fill="url(#i3u8MTb)" class="bg-pd2krb"/><path fill="url(#iaLvfae)" class="bg-pd2krb"/><g filter="url(#iF1kckd)"><path fill="url(#iJHWcuV)" class="i_2zapzfh"/></g><path class="c-z0mfodv"/><path fill="url(#iLaLRqa)" class="jkkv4ibns"/><path fill="url(#idBz6Oe)" class="jkkv4ibns"/><path fill="url(#ikQhO3b)" class="jkkv4ibns"/><path fill="url(#iEyWyFe)" class="jkkv4ibns"/><path fill="url(#ic51eGc)" class="jkkv4ibns"/><path fill="url(#irvZWie)" class="c7s4zwb_l"/><path fill="url(#iQErRbd)" class="c7s4zwb_l"/><path fill="url(#iqTVxqK)" class="c7s4zwb_l"/><path fill="url(#ifv8cUd)" class="c7s4zwb_l"/><path fill="url(#iIP5NSe)" class="c7s4zwb_l"/><g filter="url(#iKuU1MO)"><rect class="qv9fxobnd"/></g><rect fill="url(#iqQ6uDb)" class="cq940ddph"/><rect fill="url(#ipS5IUd)" class="cq940ddph"/><rect fill="url(#iY8gWWd)" class="cq940ddph"/><g filter="url(#i0vhvDv)"><path stroke="url(#iLWC1Hd)" class="p2zn2ibqm"/></g><g filter="url(#iYeabvO)"><path fill="url(#iz7BXHe)" class="vk7dlg74d"/></g><g filter="url(#iVeBUse)"><path stroke="url(#irA4Xtd)" class="haw36mbql"/></g><defs><radialGradient id="i99q9Ub" cx="0" cy="0" r="1" gradientTransform="rotate(154.861 1.253 14.288)scale(3.08953 4.78447)" gradientUnits="userSpaceOnUse"><stop offset=".867" class="fpzvpy79j"/><stop offset="1" class="ndq92sv4k"/></radialGradient><radialGradient id="ighox5d" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1875 11.25 -10.91257 -1.15189 17.644 14.221)" gradientUnits="userSpaceOnUse"><stop class="i6oghfssh"/><stop offset="1" class="tfs4fjbwc"/></radialGradient><radialGradient id="ib10yFg" cx="0" cy="0" r="1" gradientTransform="matrix(4.62497 3.4834 -4.4591 5.92044 2.644 12.346)" gradientUnits="userSpaceOnUse"><stop class="ulnkzdbpe"/><stop offset="1" class="ktrgqcb9u"/></radialGradient><radialGradient id="irLQzKX" cx="0" cy="0" r="1" gradientTransform="matrix(3.3125 -4.0625 2.88203 2.34997 5.144 17.659)" gradientUnits="userSpaceOnUse"><stop class="x44ouzbvi"/><stop offset="1" class="ibx_o7b9e"/></radialGradient><radialGradient id="i04Q1Rb" cx="0" cy="0" r="1" gradientTransform="rotate(62.053 1.909 12.882)scale(26.0718 24.6351)" gradientUnits="userSpaceOnUse"><stop offset=".9" class="d_gt2esig"/><stop offset="1" class="zrdem_b0x"/></radialGradient><radialGradient id="iaLvfae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.1875 5.09576 -4.81497 -1.12207 24.706 1.688)" gradientUnits="userSpaceOnUse"><stop class="yav9du_ob"/><stop offset="1" class="ro5nhcbei"/></radialGradient><radialGradient id="iLaLRqa" cx="0" cy="0" r="1" gradientTransform="matrix(6 0 0 11.6635 6.831 25.034)" gradientUnits="userSpaceOnUse"><stop class="mxktzyb0d"/><stop offset="1" class="psli_vbil"/></radialGradient><radialGradient id="idBz6Oe" cx="0" cy="0" r="1" gradientTransform="matrix(.00597 16.06 -22.7917 .00847 17.326 14.474)" gradientUnits="userSpaceOnUse"><stop offset=".662" class="y6csecs4r"/><stop offset="1" class="h70c5nb_w"/></radialGradient><radialGradient id="ikQhO3b" cx="0" cy="0" r="1" gradientTransform="rotate(87.907 1.157 16.222)scale(15.5645 22.0885)" gradientUnits="userSpaceOnUse"><stop offset=".91" class="kfdmknbsr"/><stop offset="1" class="e654dtble"/></radialGradient><radialGradient id="iEyWyFe" cx="0" cy="0" r="1" gradientTransform="matrix(-10.06249 -2.83564 1.3523 -4.79876 17.394 23.057)" gradientUnits="userSpaceOnUse"><stop class="jet8r83fx"/><stop offset="1" class="j4b19lvft"/></radialGradient><radialGradient id="ic51eGc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.12504 5.49997 -12.46294 -11.61334 11.832 21.284)" gradientUnits="userSpaceOnUse"><stop offset=".819" class="xpc618j5a"/><stop offset="1" class="b9b1o2bpb"/></radialGradient><radialGradient id="iqTVxqK" cx="0" cy="0" r="1" gradientTransform="rotate(167.935 8.979 13.653)scale(4.18622 9.4331)" gradientUnits="userSpaceOnUse"><stop offset=".682" class="yawit-ovz"/><stop offset="1" class="evnkl3i-h"/></radialGradient><radialGradient id="ifv8cUd" cx="0" cy="0" r="1" gradientTransform="rotate(-88.877 25.235 5.41)scale(1.59406 3.592)" gradientUnits="userSpaceOnUse"><stop offset=".001" class="evnkl3i-h"/><stop offset="1" class="yawit-ovz"/></radialGradient><radialGradient id="iIP5NSe" cx="0" cy="0" r="1" gradientTransform="matrix(1.375 5.64052 -2.16764 .52841 17.081 19.362)" gradientUnits="userSpaceOnUse"><stop class="q93sycacm"/><stop offset="1" class="us95m639l"/></radialGradient><radialGradient id="iY8gWWd" cx="0" cy="0" r="1" gradientTransform="rotate(-104.953 13.338 1.047)scale(1.14848 1.24581)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><linearGradient id="iNV3NFc" x1="9.956" x2="5.519" y1="28.096" y2="28.096" gradientUnits="userSpaceOnUse"><stop offset=".082" class="jtowu-dcx"/><stop offset="1" class="frna1k7ds"/></linearGradient><linearGradient id="i3u8MTb" x1="1.05" x2="3.191" y1="14.409" y2="14.409" gradientUnits="userSpaceOnUse"><stop class="m_wy0iq8m"/><stop offset="1" class="fnx1-gbkc"/></linearGradient><linearGradient id="iJHWcuV" x1="18.3" x2="29.113" y1="18.659" y2="21.846" gradientUnits="userSpaceOnUse"><stop class="z7ec53bvc"/><stop offset="1" class="azf-0824f"/></linearGradient><linearGradient id="irvZWie" x1="20.331" x2="20.331" y1="20.315" y2="29.096" gradientUnits="userSpaceOnUse"><stop class="f0nkvsxaw"/><stop offset="1" class="wf8aq4z8y"/></linearGradient><linearGradient id="iQErRbd" x1="21.238" x2="20.175" y1="25.002" y2="25.002" gradientUnits="userSpaceOnUse"><stop class="crza0pbem"/><stop offset="1" class="duukm51hf"/></linearGradient><linearGradient id="iqQ6uDb" x1="16.157" x2="15.583" y1="13.926" y2="13.926" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="ipS5IUd" x1="16.312" x2="16.312" y1="14.937" y2="14.003" gradientUnits="userSpaceOnUse"><stop class="vh3k8hojv"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iLWC1Hd" x1="25.161" x2="26.891" y1="6.814" y2="25.277" gradientUnits="userSpaceOnUse"><stop class="aho0t9bks"/><stop offset="1" class="gw4rabc8u"/></linearGradient><linearGradient id="iz7BXHe" x1="24.222" x2="20.394" y1="-1.341" y2="9.877" gradientUnits="userSpaceOnUse"><stop class="c_hcupbhl"/><stop offset="1" class="do65xhrna"/></linearGradient><linearGradient id="irA4Xtd" x1="23.827" x2="23.827" y1="2.284" y2="5.518" gradientUnits="userSpaceOnUse"><stop class="dfl2lab_p"/><stop offset="1" class="lgu5i2bpv"/></linearGradient><filter id="iF1kckd" width="14.305" height="15.71" x="15.652" y="14.284" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5847" stdDeviation="1"/></filter><filter id="iKuU1MO" width="1.992" height="2.961" x="14.224" y="12.744" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5847" stdDeviation=".25"/></filter><filter id="i0vhvDv" width="7.375" height="17.406" x="21.8" y="5.521" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5847" stdDeviation=".5"/></filter><filter id="iYeabvO" width="4.425" height="6.498" x="20.797" y="1.223" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5847" stdDeviation=".5"/></filter><filter id="iVeBUse" width="1.541" height="4.284" x="23.056" y="1.759" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5847" stdDeviation=".2"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:whale" /></template>
<style>
.aho0t9bks {
  stop-color: var(--svg-color--6ad3ff, #6AD3FF);
}

.azf-0824f {
  stop-color: var(--svg-color--63d2ff, #63D2FF);
  stop-opacity: 0;
}

.b9b1o2bpb {
  stop-color: var(--svg-color--b0cfff, #B0CFFF);
}

.bg-pd2krb {
  d: path("M29 16.936c0-3.985-1.89-7.579-4.82-10.344c-.113-.106-.314-.36-.149-.68c.383-.742.831-1.326.453-3.062c-.092-.426-.148-1.235-.953-1.157s-1.586 1.211-1.586 1.211c-.503.705-.687 1.156-.687 2.516c.022.38-.056.58-.445.625c-.54.062-1.68.21-2.454 1.117c0 0-1.16 1.166-1.203 1.719s.408.666.727.726c1.648.313 2.61.024 3.742-1.047c.169-.159.322-.087.438.04c1.875 2.039 2.843 5.539 2.547 8.226c-.283 2.561-3.735 2.14-4.047-.442c-.172-3.605-2.204-6.37-6.07-6.37l-6.55-.085c-2.35 0-5.194 1.593-5.6 5.163c-.839 7.39 6.173 15.094 13.735 14.875C23.87 29.74 29 25.717 29 16.936");
}

.c_hcupbhl {
  stop-color: var(--svg-color--53beff, #53BEFF);
}

.c-z0mfodv {
  fill: var(--svg-color--7dd7ff, #7DD7FF);
  d: path("M22.285 28.778c-5.285-1.604-5.366-3.05-5.625-7.688l-.016-.28c-.164-2.912-2.813-4.72-5.625-4.72c-1.86 0-8.173-.01-8.74 0c-.18 7.088 6.557 14.143 13.8 13.933c2.328-.067 4.418-.474 6.206-1.245");
}

.c7s4zwb_l {
  d: path("M19.207 29.784c-1.112-.633-2.657-1.936-2.657-6.157c0-1.265.563-3.484 1.14-4.015c.239-.219 1.048-.672 2.391.703c1.076 1.1.938 3.146.86 3.656l-.11 5.11c-.104.562-.484 1.352-1.625.703");
}

.cq940ddph {
  width: 0.992px;
  height: 1.961px;
  x: 15.165px;
  y: 13.068px;
  rx: 0.496px;
}

.crza0pbem {
  stop-color: var(--svg-color--65c9ff, #65C9FF);
}

.d_gt2esig {
  stop-color: var(--svg-color--7c88ff, #7C88FF);
  stop-opacity: 0;
}

.dfl2lab_p {
  stop-color: var(--svg-color--6ccfff, #6CCFFF);
}

.do65xhrna {
  stop-color: var(--svg-color--53beff, #53BEFF);
  stop-opacity: 0;
}

.duukm51hf {
  stop-color: var(--svg-color--65c9ff, #65C9FF);
  stop-opacity: 0;
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e654dtble {
  stop-color: var(--svg-color--d09bff, #D09BFF);
}

.evnkl3i-h {
  stop-color: var(--svg-color--3782ff, #3782FF);
}

.f0nkvsxaw {
  stop-color: var(--svg-color--5dc8fc, #5DC8FC);
}

.fnx1-gbkc {
  stop-color: var(--svg-color--addbfd, #ADDBFD);
  stop-opacity: 0;
}

.fpzvpy79j {
  stop-color: var(--svg-color--7babff, #7BABFF);
  stop-opacity: 0;
}

.frna1k7ds {
  stop-color: var(--svg-color--3f8bff, #3F8BFF);
}

.ft5dv1b6b {
  fill: none;
}

.gw4rabc8u {
  stop-color: var(--svg-color--6ad3ff, #6AD3FF);
  stop-opacity: 0;
}

.h70c5nb_w {
  stop-color: var(--svg-color--ca99ff, #CA99FF);
}

.haw36mbql {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M23.769 2.284c.266.552.6 1.972-.187 3.234");
}

.i_2zapzfh {
  d: path("M19.589 27.993c-2.909-4.544-2.234-8.68 0-11.71c0 .947.805 3.493 2.802 3.493c2.72 0 5.245-2.069 5.566-3.055c0 9.438-6.313 10.875-8.368 11.272");
}

.i6oghfssh {
  stop-color: var(--svg-color--6bdcff, #6BDCFF);
}

.ibx_o7b9e {
  stop-color: var(--svg-color--3b9af0, #3B9AF0);
  stop-opacity: 0;
}

.j4b19lvft {
  stop-color: var(--svg-color--b0d8ff, #B0D8FF);
  stop-opacity: 0;
}

.jet8r83fx {
  stop-color: var(--svg-color--b0d8ff, #B0D8FF);
}

.jkkv4ibns {
  d: path("M22.285 28.778c-5.285-1.604-5.366-3.05-5.625-7.688l-.016-.28c-.164-2.912-2.813-4.72-5.625-4.72c-1.86 0-8.173-.01-8.74 0c-.18 7.088 6.557 14.143 13.8 13.933c2.328-.067 4.418-.474 6.206-1.245");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.jtowu-dcx {
  stop-color: var(--svg-color--296dfd, #296DFD);
}

.jvw-1qblv {
  d: path("M8.363 29.971c-1.735 0-3.64-2.437-3.11-5.922c.313.2 2.615 2.052 3.75 3.14c.328.845.11 2.782-.64 2.782");
}

.kfdmknbsr {
  stop-color: var(--svg-color--d09bff, #D09BFF);
  stop-opacity: 0;
}

.ktrgqcb9u {
  stop-color: var(--svg-color--7cbce7, #7CBCE7);
  stop-opacity: 0;
}

.lgu5i2bpv {
  stop-color: var(--svg-color--6ccfff, #6CCFFF);
  stop-opacity: 0;
}

.m_wy0iq8m {
  stop-color: var(--svg-color--addbfd, #ADDBFD);
}

.mxktzyb0d {
  stop-color: var(--svg-color--6dacff, #6DACFF);
}

.ndq92sv4k {
  stop-color: var(--svg-color--7babff, #7BABFF);
}

.p2zn2ibqm {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-75px, 0.75px);
  d: path("M23.175 6.896c1.01.844 2.953 3.239 3.938 5.719c.843 2.125 1.062 5.344-.219 8.937");
}

.psli_vbil {
  stop-color: var(--svg-color--6dacff, #6DACFF);
  stop-opacity: 0;
}

.q93sycacm {
  stop-color: var(--svg-color--53bbf8, #53BBF8);
}

.qv9fxobnd {
  width: 0.992px;
  height: 1.961px;
  x: 14.724px;
  y: 13.244px;
  fill: var(--svg-color--33a8ff, #33A8FF);
  rx: 0.496px;
}

.ro5nhcbei {
  stop-color: var(--svg-color--4bbff9, #4BBFF9);
  stop-opacity: 0;
}

.tfs4fjbwc {
  stop-color: var(--svg-color--3c99ef, #3C99EF);
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ulnkzdbpe {
  stop-color: var(--svg-color--7cbce7, #7CBCE7);
}

.us95m639l {
  stop-color: var(--svg-color--53bbf8, #53BBF8);
  stop-opacity: 0;
}

.vh3k8hojv {
  stop-color: var(--svg-color--492847, #492847);
}

.vk7dlg74d {
  d: path("M22.05 3.877c-.525 1.175-.114 2.386.156 2.844c.573-.364 1.532-.64 1.922-1.969c.23-.778-.008-1.769-.23-2.309a.336.336 0 0 0-.485-.174c-.4.228-.965.72-1.363 1.608");
}

.wf8aq4z8y {
  stop-color: var(--svg-color--4d99ff, #4D99FF);
}

.x44ouzbvi {
  stop-color: var(--svg-color--3b9af0, #3B9AF0);
}

.xpc618j5a {
  stop-color: var(--svg-color--b0cfff, #B0CFFF);
  stop-opacity: 0;
}

.y6csecs4r {
  stop-color: var(--svg-color--ca99ff, #CA99FF);
  stop-opacity: 0;
}

.yav9du_ob {
  stop-color: var(--svg-color--4bbff9, #4BBFF9);
}

.yawit-ovz {
  stop-color: var(--svg-color--3782ff, #3782FF);
  stop-opacity: 0;
}

.z7ec53bvc {
  stop-color: var(--svg-color--63d2ff, #63D2FF);
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

.zrdem_b0x {
  stop-color: var(--svg-color--7c88ff, #7C88FF);
}

</style>
