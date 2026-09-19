<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iakIfNS)" class="qvxv54fcg"/><rect fill="url(#iO5HDec)" class="qvxv54fcg"/><path fill="url(#iQvhFQc)" class="dpfcflbco"/><path fill="url(#ixQBRcc)" class="dpfcflbco"/><path fill="url(#iN8goLd)" class="dpfcflbco"/><path fill="url(#iYighKb)" class="dpfcflbco"/><g filter="url(#i4uVNtc)"><path fill="url(#iMIF8Ub)" class="pr11e84cd"/></g><path class="t5myzsb3u"/><path fill="url(#ijVaqWb)" class="bmw53uijx"/><path fill="url(#iN9FuWb)" class="bmw53uijx"/><path fill="url(#iddBCDd)" class="bmw53uijx"/><path fill="url(#iv2Qhuc)" class="bmw53uijx"/><path fill="url(#ipPynab)" class="bmw53uijx"/><g filter="url(#i5QBNOb)"><path class="i4zp22uhe"/><path fill="url(#ibL0nDd)" class="aiu-8xb_b"/><path fill="url(#ikRx4sb)" class="aiu-8xb_b"/></g><path fill="url(#iljekMb)" class="aiu-8xb_b"/><rect fill="url(#iYhndQt)" class="iqaadvvob"/><rect fill="url(#iCvQ7kb)" class="iqaadvvob"/><rect fill="url(#izhGpME)" class="iqaadvvob"/><rect fill="url(#i0l6dAd)" class="iqaadvvob"/><rect fill="url(#ippk8QB)" class="ooxr-3b-k"/><rect fill="url(#iy8gVEc)" class="ooxr-3b-k"/><rect fill="url(#iKKisRd)" class="ooxr-3b-k"/><rect fill="url(#i4CrmDb)" class="hwip5eb5u"/><rect fill="url(#iONFP7c)" class="hwip5eb5u"/><rect fill="url(#iOphdAb)" class="hwip5eb5u"/><rect fill="url(#ijr84rb)" class="hwip5eb5u"/><rect fill="url(#iGZa7Qc)" class="y0tvhdc-t"/><rect fill="url(#ikYRRwb)" class="y0tvhdc-t"/><rect fill="url(#iVTYqNc)" class="y0tvhdc-t"/><rect fill="url(#i0Y2Ocz)" class="y0tvhdc-t"/><defs><radialGradient id="iQvhFQc" cx="0" cy="0" r="1" gradientTransform="rotate(97.587 8.91 11.116)scale(8.79527 10.2043)" gradientUnits="userSpaceOnUse"><stop class="i2trb--mw"/><stop offset="1" class="n2cboqbpo"/></radialGradient><radialGradient id="iYighKb" cx="0" cy="0" r="1" gradientTransform="matrix(1.94501 .78125 -.58938 1.46734 18 9.313)" gradientUnits="userSpaceOnUse"><stop class="m6s5orlpe"/><stop offset="1" class="yu5deqbhy"/></radialGradient><radialGradient id="ijVaqWb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28125 .97656 -1.0161 -3.41411 23.5 11.93)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="ov0rgnbgf"/><stop offset="1" class="f4_imgbtg"/></radialGradient><radialGradient id="iN9FuWb" cx="0" cy="0" r="1" gradientTransform="matrix(3.0968 -.55469 3.18173 17.7635 15.299 11.898)" gradientUnits="userSpaceOnUse"><stop class="ov0rgnbgf"/><stop offset="1" class="f4_imgbtg"/></radialGradient><radialGradient id="iddBCDd" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71723 3.30237 0 18.362 10.125)" gradientUnits="userSpaceOnUse"><stop class="ov0rgnbgf"/><stop offset="1" class="f4_imgbtg"/></radialGradient><radialGradient id="iv2Qhuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.80716 .88786 -.96855 -.8805 17.79 11.092)" gradientUnits="userSpaceOnUse"><stop class="wrb4o18wk"/><stop offset="1" class="z1mqxnblh"/></radialGradient><radialGradient id="ipPynab" cx="0" cy="0" r="1" gradientTransform="matrix(-.62745 .62745 -.71264 -.71264 18.89 8.31)" gradientUnits="userSpaceOnUse"><stop class="q5u40b7rv"/><stop offset="1" class="pfdmmcc2p"/></radialGradient><radialGradient id="ibL0nDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68752 2.24998 -.59132 -.70631 23.483 15.024)" gradientUnits="userSpaceOnUse"><stop class="u9h--_uhg"/><stop offset="1" class="nq5--fbox"/></radialGradient><radialGradient id="iljekMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.32813 .40625 -1.35537 4.43103 14.75 18)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="p-1r-quvn"/><stop offset="1" class="r1pk_fb-k"/></radialGradient><radialGradient id="iCvQ7kb" cx="0" cy="0" r="1" gradientTransform="matrix(-.53893 .375 -.33792 -.48564 24.181 11.32)" gradientUnits="userSpaceOnUse"><stop class="yfcig1bqm"/><stop offset="1" class="l8ohao8ua"/></radialGradient><radialGradient id="izhGpME" cx="0" cy="0" r="1" gradientTransform="matrix(.94672 0 0 1.77217 21.572 11.61)" gradientUnits="userSpaceOnUse"><stop class="ha7sfnbee"/><stop offset="1" class="ttnpq97vi"/></radialGradient><radialGradient id="iy8gVEc" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 5.313)" gradientUnits="userSpaceOnUse"><stop class="yfcig1bqm"/><stop offset="1" class="l8ohao8ua"/></radialGradient><radialGradient id="iKKisRd" cx="0" cy="0" r="1" gradientTransform="matrix(1.11163 0 0 1.77217 21.654 5.602)" gradientUnits="userSpaceOnUse"><stop class="ha7sfnbee"/><stop offset="1" class="ttnpq97vi"/></radialGradient><radialGradient id="iONFP7c" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 9.39)" gradientUnits="userSpaceOnUse"><stop class="yfcig1bqm"/><stop offset="1" class="l8ohao8ua"/></radialGradient><radialGradient id="iOphdAb" cx="0" cy="0" r="1" gradientTransform="matrix(1.11163 0 0 1.77217 21.654 9.68)" gradientUnits="userSpaceOnUse"><stop class="ha7sfnbee"/><stop offset="1" class="ttnpq97vi"/></radialGradient><radialGradient id="ikYRRwb" cx="0" cy="0" r="1" gradientTransform="matrix(-.66202 .375 -.3091 -.54569 24.694 7.406)" gradientUnits="userSpaceOnUse"><stop class="yfcig1bqm"/><stop offset="1" class="l8ohao8ua"/></radialGradient><radialGradient id="iVTYqNc" cx="0" cy="0" r="1" gradientTransform="matrix(1.16294 0 0 1.77217 21.49 7.695)" gradientUnits="userSpaceOnUse"><stop class="ha7sfnbee"/><stop offset="1" class="ttnpq97vi"/></radialGradient><linearGradient id="iakIfNS" x1="21.513" x2="24.074" y1="5.178" y2="2.469" gradientUnits="userSpaceOnUse"><stop class="fy31g80qu"/><stop offset="1" class="jcq7qbblj"/></linearGradient><linearGradient id="iO5HDec" x1="20.361" x2="20.361" y1="12.192" y2="11.411" gradientUnits="userSpaceOnUse"><stop class="b4id_clxv"/><stop offset="1" class="bxgu95jbn"/></linearGradient><linearGradient id="ixQBRcc" x1="23.17" x2="22.466" y1="7.255" y2="7.255" gradientUnits="userSpaceOnUse"><stop class="o219w69lb"/><stop offset="1" class="ofwypjbaj"/></linearGradient><linearGradient id="iN8goLd" x1="16.906" x2="17.334" y1="6.977" y2="6.977" gradientUnits="userSpaceOnUse"><stop class="bxw14_b6p"/><stop offset="1" class="l5s8r7bmx"/></linearGradient><linearGradient id="iMIF8Ub" x1="21.942" x2="21.942" y1="10.563" y2="5.65" gradientUnits="userSpaceOnUse"><stop class="kjc7f9q9w"/><stop offset="1" class="dw-6bo_en"/></linearGradient><linearGradient id="ikRx4sb" x1="11.076" x2="11.076" y1="30.773" y2="27.148" gradientUnits="userSpaceOnUse"><stop class="s-5ofoxht"/><stop offset="1" class="ab64lebgw"/></linearGradient><linearGradient id="iYhndQt" x1="23.086" x2="23.086" y1="10.563" y2="12.656" gradientUnits="userSpaceOnUse"><stop class="pbg1snbkx"/><stop offset="1" class="wf0taebat"/></linearGradient><linearGradient id="i0l6dAd" x1="23.086" x2="23.086" y1="10.414" y2="11.375" gradientUnits="userSpaceOnUse"><stop class="q2dhpsvnr"/><stop offset="1" class="yxg89zvav"/></linearGradient><linearGradient id="ippk8QB" x1="23.431" x2="23.431" y1="4.555" y2="6.648" gradientUnits="userSpaceOnUse"><stop class="pbg1snbkx"/><stop offset="1" class="wf0taebat"/></linearGradient><linearGradient id="i4CrmDb" x1="23.431" x2="23.431" y1="8.633" y2="10.727" gradientUnits="userSpaceOnUse"><stop class="pbg1snbkx"/><stop offset="1" class="wf0taebat"/></linearGradient><linearGradient id="ijr84rb" x1="23.431" x2="23.431" y1="8.633" y2="9.25" gradientUnits="userSpaceOnUse"><stop class="q2dhpsvnr"/><stop offset="1" class="yxg89zvav"/></linearGradient><linearGradient id="iGZa7Qc" x1="23.349" x2="23.349" y1="6.648" y2="8.742" gradientUnits="userSpaceOnUse"><stop class="pbg1snbkx"/><stop offset="1" class="wf0taebat"/></linearGradient><linearGradient id="i0Y2Ocz" x1="23.349" x2="23.349" y1="6.5" y2="7.125" gradientUnits="userSpaceOnUse"><stop class="q2dhpsvnr"/><stop offset="1" class="yxg89zvav"/></linearGradient><filter id="i4uVNtc" width="3.914" height="6.625" x="20.699" y="4.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5856" stdDeviation=".25"/></filter><filter id="i5QBNOb" width="22.048" height="15.844" x="1.998" y="15.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.121569 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5856"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:selfie-light" /></template>
<style>
.ab64lebgw {
  stop-color: var(--svg-color--ba2083, #BA2083);
  stop-opacity: 0;
}

.aiu-8xb_b {
  d: path("M16.778 15.023a1.2 1.2 0 0 0-1.129.794l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.321a1 1 0 0 0-.955-1.298z");
}

.b4id_clxv {
  stop-color: var(--svg-color--1b1f50, #1B1F50);
}

.bmw53uijx {
  d: path("M16.62 7.258a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.369.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.053a1.6 1.6 0 0 0-.392.047q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.bxgu95jbn {
  stop-color: var(--svg-color--1b1f50, #1B1F50);
  stop-opacity: 0;
}

.bxw14_b6p {
  stop-color: var(--svg-color--4887b6, #4887B6);
}

.dpfcflbco {
  d: path("M16.94 10.96V2.993h6.01v7.969z");
}

.dw-6bo_en {
  stop-color: var(--svg-color--3985c0, #3985C0);
}

.f4_imgbtg {
  stop-color: var(--svg-color--d79d96, #D79D96);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fy31g80qu {
  stop-color: var(--svg-color--3c4071, #3C4071);
}

.ha7sfnbee {
  stop-color: var(--svg-color--dfac95, #DFAC95);
}

.hwip5eb5u {
  width: 3.555px;
  height: 2.094px;
  x: 21.654px;
  y: 8.633px;
  rx: 1.047px;
}

.i2trb--mw {
  stop-color: var(--svg-color--4cbff1, #4CBFF1);
}

.i4zp22uhe {
  fill: var(--svg-color--e24c86, #E24C86);
  d: path("M16.778 15.023a1.2 1.2 0 0 0-1.129.794l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.321a1 1 0 0 0-.955-1.298z");
}

.iqaadvvob {
  width: 3.027px;
  height: 2.094px;
  x: 21.572px;
  y: 10.563px;
  rx: 1.047px;
}

.jcq7qbblj {
  stop-color: var(--svg-color--5c618e, #5C618E);
}

.kjc7f9q9w {
  stop-color: var(--svg-color--2967a0, #2967A0);
}

.l5s8r7bmx {
  stop-color: var(--svg-color--4887b6, #4887B6);
  stop-opacity: 0;
}

.l8ohao8ua {
  stop-color: var(--svg-color--ffdac2, #FFDAC2);
  stop-opacity: 0;
}

.m6s5orlpe {
  stop-color: var(--svg-color--267bae, #267BAE);
}

.n2cboqbpo {
  stop-color: var(--svg-color--1884d9, #1884D9);
}

.nq5--fbox {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
  stop-opacity: 0;
}

.o219w69lb {
  stop-color: var(--svg-color--68eaff, #68EAFF);
}

.ofwypjbaj {
  stop-color: var(--svg-color--68eaff, #68EAFF);
  stop-opacity: 0;
}

.ooxr-3b-k {
  width: 3.555px;
  height: 2.094px;
  x: 21.654px;
  y: 4.555px;
  rx: 1.047px;
}

.ov0rgnbgf {
  stop-color: var(--svg-color--d79d96, #D79D96);
}

.p-1r-quvn {
  stop-color: var(--svg-color--d56274, #D56274);
}

.pbg1snbkx {
  stop-color: var(--svg-color--f1c5ab, #F1C5AB);
}

.pfdmmcc2p {
  stop-color: var(--svg-color--ffd4be, #FFD4BE);
  stop-opacity: 0;
}

.pr11e84cd {
  d: path("M21.328 5.892c0-.527.427-.955.954-.955h.876a.954.954 0 1 1 0 1.909a.954.954 0 0 1 .305 1.858a.955.955 0 0 1-.305 1.858h-.876a.954.954 0 0 1-.362-1.837a.954.954 0 0 1 .233-1.88h.129a.954.954 0 0 1-.954-.953");
}

.q2dhpsvnr {
  stop-color: var(--svg-color--d79b7d, #D79B7D);
}

.q5u40b7rv {
  stop-color: var(--svg-color--ffd4be, #FFD4BE);
}

.qvxv54fcg {
  width: 6.844px;
  height: 9.938px;
  x: 16.939px;
  y: 1.992px;
  rx: 0.9px;
}

.r1pk_fb-k {
  stop-color: var(--svg-color--d56274, #D56274);
  stop-opacity: 0;
}

.s-5ofoxht {
  stop-color: var(--svg-color--ba2083, #BA2083);
}

.t5myzsb3u {
  fill: var(--svg-color--f3c1ae, #F3C1AE);
  d: path("M16.62 7.258a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.369.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.053a1.6 1.6 0 0 0-.392.047q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.ttnpq97vi {
  stop-color: var(--svg-color--dfac95, #DFAC95);
  stop-opacity: 0;
}

.u9h--_uhg {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
}

.wf0taebat {
  stop-color: var(--svg-color--e9b19d, #E9B19D);
}

.wrb4o18wk {
  stop-color: var(--svg-color--e9baa9, #E9BAA9);
}

.y0tvhdc-t {
  width: 3.719px;
  height: 2.094px;
  x: 21.49px;
  y: 6.648px;
  rx: 1.047px;
}

.yfcig1bqm {
  stop-color: var(--svg-color--ffdac2, #FFDAC2);
}

.yu5deqbhy {
  stop-color: var(--svg-color--267bae, #267BAE);
  stop-opacity: 0;
}

.yxg89zvav {
  stop-color: var(--svg-color--d79b7d, #D79B7D);
  stop-opacity: 0;
}

.z1mqxnblh {
  stop-color: var(--svg-color--e9baa9, #E9BAA9);
  stop-opacity: 0;
}

</style>
