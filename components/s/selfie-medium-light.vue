<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><rect fill="url(#iakIfNS)" class="qvxv54fcg"/><rect fill="url(#iO5HDec)" class="qvxv54fcg"/><path fill="url(#iQvhFQc)" class="dpfcflbco"/><path fill="url(#ixQBRcc)" class="dpfcflbco"/><path fill="url(#iN8goLd)" class="dpfcflbco"/><path fill="url(#iYighKb)" class="dpfcflbco"/><g filter="url(#ibevrLq)"><path fill="url(#iMIF8Ub)" class="pr11e84cd"/></g><path class="f0hxsfpke"/><path fill="url(#itTeFTb)" class="bmw53uijx"/><path fill="url(#iwSa5Dp)" class="bmw53uijx"/><path fill="url(#iSlMK7c)" class="bmw53uijx"/><path fill="url(#i7lwb8d)" class="bmw53uijx"/><path fill="url(#i13V3gb)" class="bmw53uijx"/><g filter="url(#it79HKd)"><path class="i4zp22uhe"/><path fill="url(#ibL0nDd)" class="aiu-8xb_b"/><path fill="url(#ikRx4sb)" class="aiu-8xb_b"/></g><path fill="url(#iljekMb)" class="aiu-8xb_b"/><rect fill="url(#iEd274c)" class="iqaadvvob"/><rect fill="url(#i7nqE5b)" class="iqaadvvob"/><rect fill="url(#iMkbIwd)" class="iqaadvvob"/><rect fill="url(#iggetyd)" class="iqaadvvob"/><rect fill="url(#i2dyuJc)" class="ooxr-3b-k"/><rect fill="url(#i30ztTI)" class="ooxr-3b-k"/><rect fill="url(#idIDVVd)" class="ooxr-3b-k"/><rect fill="url(#iWUTWHe)" class="hwip5eb5u"/><rect fill="url(#iXQkUqd)" class="hwip5eb5u"/><rect fill="url(#iBscEPb)" class="hwip5eb5u"/><rect fill="url(#i4gTnON)" class="hwip5eb5u"/><rect fill="url(#ilk2CQn)" class="y0tvhdc-t"/><rect fill="url(#iep92qe)" class="y0tvhdc-t"/><rect fill="url(#iQHHbxc)" class="y0tvhdc-t"/><rect fill="url(#iOFyare)" class="y0tvhdc-t"/><defs><radialGradient id="iQvhFQc" cx="0" cy="0" r="1" gradientTransform="rotate(97.587 8.91 11.116)scale(8.79527 10.2043)" gradientUnits="userSpaceOnUse"><stop class="i2trb--mw"/><stop offset="1" class="n2cboqbpo"/></radialGradient><radialGradient id="iYighKb" cx="0" cy="0" r="1" gradientTransform="matrix(1.94501 .78125 -.58938 1.46734 18 9.313)" gradientUnits="userSpaceOnUse"><stop class="m6s5orlpe"/><stop offset="1" class="yu5deqbhy"/></radialGradient><radialGradient id="itTeFTb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.28125 .97656 -1.0161 -3.41411 23.5 11.93)" gradientUnits="userSpaceOnUse"><stop offset=".168" class="chm9jrc5b"/><stop offset="1" class="nolhsib7e"/></radialGradient><radialGradient id="iwSa5Dp" cx="0" cy="0" r="1" gradientTransform="matrix(3.0968 -.55469 3.18173 17.7635 15.299 11.898)" gradientUnits="userSpaceOnUse"><stop class="chm9jrc5b"/><stop offset="1" class="nolhsib7e"/></radialGradient><radialGradient id="iSlMK7c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -1.71723 3.30237 0 18.362 10.125)" gradientUnits="userSpaceOnUse"><stop class="chm9jrc5b"/><stop offset="1" class="nolhsib7e"/></radialGradient><radialGradient id="i7lwb8d" cx="0" cy="0" r="1" gradientTransform="matrix(-.80716 .88786 -.96855 -.8805 17.79 11.092)" gradientUnits="userSpaceOnUse"><stop class="d154ezdcq"/><stop offset="1" class="bpksruhej"/></radialGradient><radialGradient id="i13V3gb" cx="0" cy="0" r="1" gradientTransform="matrix(-.62745 .62745 -.71264 -.71264 18.89 8.31)" gradientUnits="userSpaceOnUse"><stop class="kbagffbbn"/><stop offset="1" class="ryzapbcga"/></radialGradient><radialGradient id="ibL0nDd" cx="0" cy="0" r="1" gradientTransform="matrix(-2.68752 2.24998 -.59132 -.70631 23.483 15.024)" gradientUnits="userSpaceOnUse"><stop class="u9h--_uhg"/><stop offset="1" class="nq5--fbox"/></radialGradient><radialGradient id="iljekMb" cx="0" cy="0" r="1" gradientTransform="matrix(1.32813 .40625 -1.35537 4.43103 14.75 18)" gradientUnits="userSpaceOnUse"><stop offset=".25" class="p-1r-quvn"/><stop offset="1" class="r1pk_fb-k"/></radialGradient><radialGradient id="i7nqE5b" cx="0" cy="0" r="1" gradientTransform="matrix(-.53893 .375 -.33792 -.48564 24.181 11.32)" gradientUnits="userSpaceOnUse"><stop class="aodzo-bwr"/><stop offset="1" class="rymzi8b9f"/></radialGradient><radialGradient id="iMkbIwd" cx="0" cy="0" r="1" gradientTransform="matrix(.94672 0 0 1.77217 21.572 11.61)" gradientUnits="userSpaceOnUse"><stop class="kpf1j6ctg"/><stop offset="1" class="gb1a3rsyy"/></radialGradient><radialGradient id="i30ztTI" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 5.313)" gradientUnits="userSpaceOnUse"><stop class="aodzo-bwr"/><stop offset="1" class="rymzi8b9f"/></radialGradient><radialGradient id="idIDVVd" cx="0" cy="0" r="1" gradientTransform="matrix(1.11163 0 0 1.77217 21.654 5.602)" gradientUnits="userSpaceOnUse"><stop class="kpf1j6ctg"/><stop offset="1" class="gb1a3rsyy"/></radialGradient><radialGradient id="iXQkUqd" cx="0" cy="0" r="1" gradientTransform="matrix(-.63281 .375 -.31612 -.53345 24.716 9.39)" gradientUnits="userSpaceOnUse"><stop class="aodzo-bwr"/><stop offset="1" class="rymzi8b9f"/></radialGradient><radialGradient id="iBscEPb" cx="0" cy="0" r="1" gradientTransform="matrix(1.11163 0 0 1.77217 21.654 9.68)" gradientUnits="userSpaceOnUse"><stop class="kpf1j6ctg"/><stop offset="1" class="gb1a3rsyy"/></radialGradient><radialGradient id="iep92qe" cx="0" cy="0" r="1" gradientTransform="matrix(-.66202 .375 -.3091 -.54569 24.694 7.406)" gradientUnits="userSpaceOnUse"><stop class="aodzo-bwr"/><stop offset="1" class="rymzi8b9f"/></radialGradient><radialGradient id="iQHHbxc" cx="0" cy="0" r="1" gradientTransform="matrix(1.16294 0 0 1.77217 21.49 7.695)" gradientUnits="userSpaceOnUse"><stop class="kpf1j6ctg"/><stop offset="1" class="gb1a3rsyy"/></radialGradient><linearGradient id="iakIfNS" x1="21.513" x2="24.074" y1="5.178" y2="2.469" gradientUnits="userSpaceOnUse"><stop class="fy31g80qu"/><stop offset="1" class="jcq7qbblj"/></linearGradient><linearGradient id="iO5HDec" x1="20.361" x2="20.361" y1="12.192" y2="11.411" gradientUnits="userSpaceOnUse"><stop class="b4id_clxv"/><stop offset="1" class="bxgu95jbn"/></linearGradient><linearGradient id="ixQBRcc" x1="23.17" x2="22.466" y1="7.255" y2="7.255" gradientUnits="userSpaceOnUse"><stop class="o219w69lb"/><stop offset="1" class="ofwypjbaj"/></linearGradient><linearGradient id="iN8goLd" x1="16.906" x2="17.334" y1="6.977" y2="6.977" gradientUnits="userSpaceOnUse"><stop class="bxw14_b6p"/><stop offset="1" class="l5s8r7bmx"/></linearGradient><linearGradient id="iMIF8Ub" x1="21.942" x2="21.942" y1="10.563" y2="5.65" gradientUnits="userSpaceOnUse"><stop class="kjc7f9q9w"/><stop offset="1" class="dw-6bo_en"/></linearGradient><linearGradient id="ikRx4sb" x1="11.076" x2="11.076" y1="30.773" y2="27.148" gradientUnits="userSpaceOnUse"><stop class="s-5ofoxht"/><stop offset="1" class="ab64lebgw"/></linearGradient><linearGradient id="iEd274c" x1="23.086" x2="23.086" y1="10.563" y2="12.656" gradientUnits="userSpaceOnUse"><stop class="j6cnq9xtk"/><stop offset="1" class="k62-1d0-l"/></linearGradient><linearGradient id="iggetyd" x1="23.086" x2="23.086" y1="10.391" y2="11.609" gradientUnits="userSpaceOnUse"><stop class="dkivpmowt"/><stop offset="1" class="njkbebbbp"/></linearGradient><linearGradient id="i2dyuJc" x1="23.431" x2="23.431" y1="4.555" y2="6.648" gradientUnits="userSpaceOnUse"><stop class="j6cnq9xtk"/><stop offset="1" class="k62-1d0-l"/></linearGradient><linearGradient id="iWUTWHe" x1="23.431" x2="23.431" y1="8.633" y2="10.727" gradientUnits="userSpaceOnUse"><stop class="j6cnq9xtk"/><stop offset="1" class="k62-1d0-l"/></linearGradient><linearGradient id="i4gTnON" x1="23.431" x2="23.431" y1="8.461" y2="9.422" gradientUnits="userSpaceOnUse"><stop class="dkivpmowt"/><stop offset="1" class="njkbebbbp"/></linearGradient><linearGradient id="ilk2CQn" x1="23.349" x2="23.349" y1="6.648" y2="8.742" gradientUnits="userSpaceOnUse"><stop class="j6cnq9xtk"/><stop offset="1" class="k62-1d0-l"/></linearGradient><linearGradient id="iOFyare" x1="23.349" x2="23.349" y1="6.477" y2="7.188" gradientUnits="userSpaceOnUse"><stop class="dkivpmowt"/><stop offset="1" class="njkbebbbp"/></linearGradient><filter id="ibevrLq" width="3.914" height="6.625" x="20.699" y="4.438" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_20020_5845" stdDeviation=".25"/></filter><filter id="it79HKd" width="22.048" height="15.844" x="1.998" y="15.023" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="1" dy="1"/><feGaussianBlur stdDeviation="1.5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.713726 0 0 0 0 0.121569 0 0 0 0 0.254902 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_20020_5845"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:selfie-medium-light" /></template>
<style>
.ab64lebgw {
  stop-color: var(--svg-color--ba2083, #BA2083);
  stop-opacity: 0;
}

.aiu-8xb_b {
  d: path("M16.778 15.023a1.2 1.2 0 0 0-1.129.794l-2.023 5.617a.75.75 0 0 1-.706.496H2.598a.6.6 0 0 0-.6.6v6.737a.6.6 0 0 0 .6.6h13.238a4 4 0 0 0 3.819-2.81L23 16.321a1 1 0 0 0-.955-1.298z");
}

.aodzo-bwr {
  stop-color: var(--svg-color--f2c6a6, #F2C6A6);
}

.b4id_clxv {
  stop-color: var(--svg-color--1b1f50, #1B1F50);
}

.bmw53uijx {
  d: path("M16.62 7.258a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.369.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.053a1.6 1.6 0 0 0-.392.047q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.bpksruhej {
  stop-color: var(--svg-color--d9ab93, #D9AB93);
  stop-opacity: 0;
}

.bxgu95jbn {
  stop-color: var(--svg-color--1b1f50, #1B1F50);
  stop-opacity: 0;
}

.bxw14_b6p {
  stop-color: var(--svg-color--4887b6, #4887B6);
}

.chm9jrc5b {
  stop-color: var(--svg-color--ca8577, #CA8577);
}

.d154ezdcq {
  stop-color: var(--svg-color--d9ab93, #D9AB93);
}

.dkivpmowt {
  stop-color: var(--svg-color--c68962, #C68962);
}

.dpfcflbco {
  d: path("M16.94 10.96V2.993h6.01v7.969z");
}

.dw-6bo_en {
  stop-color: var(--svg-color--3985c0, #3985C0);
}

.f0hxsfpke {
  fill: var(--svg-color--dcab91, #DCAB91);
  d: path("M16.62 7.258a1.32 1.32 0 0 0-1.321 1.336v2.684a2.3 2.3 0 0 0 1.28 2.06c.237.118.401.369.349.628l-.296 1.464h5.364l.375-1.422a.75.75 0 0 1 .44-.502l.703-.244c.442-.132.852-.62.999-1.184l.067-.289l-.948.053a1.6 1.6 0 0 0-.392.047q-.073.015-.147.028a1 1 0 0 1-.15.013H17.88a.9.9 0 0 1-.903-.9v-.89a.25.25 0 0 1 .25-.25h.844c.73 0 1.321-.589 1.321-1.316s-.591-1.316-1.321-1.316z");
}

.ft5dv1b6b {
  fill: none;
}

.fy31g80qu {
  stop-color: var(--svg-color--3c4071, #3C4071);
}

.gb1a3rsyy {
  stop-color: var(--svg-color--c9987d, #C9987D);
  stop-opacity: 0;
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

.j6cnq9xtk {
  stop-color: var(--svg-color--e0b28f, #E0B28F);
}

.jcq7qbblj {
  stop-color: var(--svg-color--5c618e, #5C618E);
}

.k62-1d0-l {
  stop-color: var(--svg-color--d49877, #D49877);
}

.kbagffbbn {
  stop-color: var(--svg-color--f0c6a6, #F0C6A6);
}

.kjc7f9q9w {
  stop-color: var(--svg-color--2967a0, #2967A0);
}

.kpf1j6ctg {
  stop-color: var(--svg-color--c9987d, #C9987D);
}

.l5s8r7bmx {
  stop-color: var(--svg-color--4887b6, #4887B6);
  stop-opacity: 0;
}

.m6s5orlpe {
  stop-color: var(--svg-color--267bae, #267BAE);
}

.n2cboqbpo {
  stop-color: var(--svg-color--1884d9, #1884D9);
}

.njkbebbbp {
  stop-color: var(--svg-color--c68962, #C68962);
  stop-opacity: 0;
}

.nolhsib7e {
  stop-color: var(--svg-color--ca8577, #CA8577);
  stop-opacity: 0;
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

.p-1r-quvn {
  stop-color: var(--svg-color--d56274, #D56274);
}

.pr11e84cd {
  d: path("M21.328 5.892c0-.527.427-.955.954-.955h.876a.954.954 0 1 1 0 1.909a.954.954 0 0 1 .305 1.858a.955.955 0 0 1-.305 1.858h-.876a.954.954 0 0 1-.362-1.837a.954.954 0 0 1 .233-1.88h.129a.954.954 0 0 1-.954-.953");
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

.rymzi8b9f {
  stop-color: var(--svg-color--f2c6a6, #F2C6A6);
  stop-opacity: 0;
}

.ryzapbcga {
  stop-color: var(--svg-color--f0c6a6, #F0C6A6);
  stop-opacity: 0;
}

.s-5ofoxht {
  stop-color: var(--svg-color--ba2083, #BA2083);
}

.u9h--_uhg {
  stop-color: var(--svg-color--ff99b6, #FF99B6);
}

.y0tvhdc-t {
  width: 3.719px;
  height: 2.094px;
  x: 21.49px;
  y: 6.648px;
  rx: 1.047px;
}

.yu5deqbhy {
  stop-color: var(--svg-color--267bae, #267BAE);
  stop-opacity: 0;
}

</style>
