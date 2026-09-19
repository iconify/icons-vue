<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="dge16lbmj"/><path fill="url(#ifiCbVc)" class="c4__k7b4z"/><path fill="url(#i6QhMBd)" class="c4__k7b4z"/><path fill="url(#iERZ0Hm)" class="c4__k7b4z"/><path fill="url(#iMy6m1n)" class="x5bywsbxv"/><path fill="url(#i43NKmk)" class="x5bywsbxv"/><path fill="url(#iRnDKpk)" class="x5bywsbxv"/><path fill="url(#iR2xytc)" class="a6-k240bs"/><g filter="url(#iIqrvvd)"><path fill="url(#igaB7nc)" class="y-8-eaccr"/></g><g filter="url(#iEtomNc)"><path class="fq2u14nai"/><path class="waerimb_l"/></g><path class="ms6rbmmya"/><path fill="url(#i3E8jdd)" class="lz6ua7b1r"/><g filter="url(#iJIIyRb)"><path class="tdr9jhb-b"/><path class="ok7ku9bmj"/></g><g filter="url(#ifsEnDb)"><path stroke="url(#iZTnb0c)" class="g78__vbaj"/></g><path class="kuecjnbtw"/><path fill="url(#i5n1HCd)" class="lyi50sxgr"/><path fill="url(#igZotLd)" class="ra-bezs1z"/><path fill="url(#iHShgyc)" class="xkm965b6f"/><g filter="url(#ikImMfe)"><path fill="url(#itWDAec)" class="lh5rndbbu"/></g><path fill="url(#iKur8Tu)" class="nrqtwxhse"/><path fill="url(#iRqOwlc)" class="nrqtwxhse"/><g filter="url(#idVUUzc)"><path stroke="url(#iIO6dYc)" class="ktvk93btk"/></g><defs><linearGradient id="iMy6m1n" x1="6.875" x2="17.313" y1="8.75" y2="17.938" gradientUnits="userSpaceOnUse"><stop class="o88y2wbig"/><stop offset="1" class="tx29ghbdv"/></linearGradient><linearGradient id="i43NKmk" x1="20.625" x2="3.375" y1="3.5" y2="20.313" gradientUnits="userSpaceOnUse"><stop class="z8y8xkpvf"/><stop offset=".19" class="pzk1cqb3f"/><stop offset=".711" class="p4g_pckdc"/><stop offset="1" class="jarb8ybxi"/></linearGradient><linearGradient id="iRnDKpk" x1="6.375" x2="11.375" y1="7.875" y2="13.06" gradientUnits="userSpaceOnUse"><stop class="b1fud5a9r"/><stop offset="1" class="lk6o6qb3d"/></linearGradient><linearGradient id="iR2xytc" x1="19.313" x2="3.539" y1="3.875" y2="17" gradientUnits="userSpaceOnUse"><stop class="vt609h34t"/><stop offset=".498" class="f_jowmbud"/><stop offset="1" class="g6cvf3swx"/></linearGradient><linearGradient id="iZTnb0c" x1="20.313" x2="16.625" y1="4.594" y2="4" gradientUnits="userSpaceOnUse"><stop class="livbukvxq"/><stop offset="1" class="wr9i42bbk"/></linearGradient><linearGradient id="igZotLd" x1="11.25" x2="17.375" y1="11.313" y2="17.125" gradientUnits="userSpaceOnUse"><stop class="jkpbawiuw"/><stop offset=".263" class="omwhmkb4w"/><stop offset=".46" class="hhctjoo7s"/><stop offset=".782" class="egmlv4bso"/></linearGradient><linearGradient id="iHShgyc" x1="9.084" x2="20.402" y1="14.657" y2="14.657" gradientUnits="userSpaceOnUse"><stop offset=".65" class="e9_i-bcrx"/><stop offset=".865" class="ps81f7b8q"/></linearGradient><linearGradient id="itWDAec" x1="8.75" x2="19.188" y1="21.75" y2="8.938" gradientUnits="userSpaceOnUse"><stop class="n_au17bry"/><stop offset=".284" class="z_-kgzb-o"/><stop offset="1" class="caoykib8c"/></linearGradient><linearGradient id="iKur8Tu" x1="23.5" x2="8.444" y1="8.812" y2="22.563" gradientUnits="userSpaceOnUse"><stop offset=".011" class="ecscp6bsl"/><stop offset=".377" class="tr1cb2sfw"/><stop offset="1" class="u6wpv2lcm"/></linearGradient><linearGradient id="iIO6dYc" x1="19.813" x2="13.125" y1="9.3" y2="12.438" gradientUnits="userSpaceOnUse"><stop offset=".503" class="nv9_mfbmq"/><stop offset="1" class="cgtf_3oto"/></linearGradient><radialGradient id="ifiCbVc" cx="0" cy="0" r="1" gradientTransform="rotate(102.886 6.815 14.018)scale(26.2871)" gradientUnits="userSpaceOnUse"><stop offset=".494" class="f_-xq7bkg"/><stop offset=".809" class="pmxg51h-d"/></radialGradient><radialGradient id="i6QhMBd" cx="0" cy="0" r="1" gradientTransform="rotate(117.308 8.662 13.845)scale(12.9423)" gradientUnits="userSpaceOnUse"><stop class="xj44znbms"/><stop offset=".858" class="o6sptfbzi"/></radialGradient><radialGradient id="iERZ0Hm" cx="0" cy="0" r="1" gradientTransform="rotate(88.424 11.511 10.997)scale(13.6302)" gradientUnits="userSpaceOnUse"><stop class="bqo3hbcih"/><stop offset="1" class="iim47zbou"/></radialGradient><radialGradient id="igaB7nc" cx="0" cy="0" r="1" gradientTransform="matrix(-1.18748 9.75 -11.40105 -1.38856 8.625 11.25)" gradientUnits="userSpaceOnUse"><stop offset=".066" class="w-y0uzykl"/><stop offset=".576" class="lik4c9zrj"/></radialGradient><radialGradient id="i3E8jdd" cx="0" cy="0" r="1" gradientTransform="rotate(111.615 5.912 9.315)scale(3.56305)" gradientUnits="userSpaceOnUse"><stop offset=".213" class="haxm-blrv"/><stop offset="1" class="w15jk7bob"/></radialGradient><radialGradient id="i5n1HCd" cx="0" cy="0" r="1" gradientTransform="rotate(92.42 -2.638 11.384)scale(4.44146)" gradientUnits="userSpaceOnUse"><stop class="jzz1iz8js"/><stop offset=".506" class="ja4chs8_e"/><stop offset="1" class="dox4jvhwf"/></radialGradient><radialGradient id="iRqOwlc" cx="0" cy="0" r="1" gradientTransform="matrix(-5.18748 -5.12502 10.26744 -10.39257 14.063 12.375)" gradientUnits="userSpaceOnUse"><stop offset=".71" class="nij5yir4a"/><stop offset=".886" class="tbd_ah9qe"/></radialGradient><filter id="iIqrvvd" width="10.763" height="10.25" x="5.438" y="4.125" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33523" stdDeviation=".5"/></filter><filter id="iEtomNc" width="11.4" height="11.4" x="9.658" y="4" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33523" stdDeviation=".5"/></filter><filter id="iJIIyRb" width="11.4" height="11.4" x="3.386" y="11" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33523" stdDeviation=".5"/></filter><filter id="ifsEnDb" width="6.063" height="2.733" x="14.781" y="2.892" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33523" stdDeviation=".25"/></filter><filter id="ikImMfe" width="16.285" height="16.588" x="7.215" y="7.101" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33523" stdDeviation=".5"/></filter><filter id="idVUUzc" width="12.031" height="7.906" x="10.313" y="7.594" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_33523" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:stuffed-flatbread" /></template>
<style>
.a6-k240bs {
  d: path("M14.078 4.133c-1.01.91-2.26 1.347-3.61 1.187c-1.29-.15-2.783.393-3.773 1.383S5.14 9.116 5.29 10.406c0 1.555.36.975-1.084 3.742s-.377 5.883 1.654 7.493l16-15.953c-2.609-3.172-5.944-3.21-7.78-1.555");
}

.b1fud5a9r {
  stop-color: var(--svg-color--be9b72, #BE9B72);
}

.bqo3hbcih {
  stop-color: var(--svg-color--e1b78e, #E1B78E);
}

.c4__k7b4z {
  d: path("M25.898 6.09a13.95 13.95 0 0 0-7.01-3.8L2.267 18.91a14 14 0 0 0 3.8 7.01c5.48 5.48 14.35 5.48 19.83 0s5.48-14.36 0-19.83");
}

.caoykib8c {
  stop-color: var(--svg-color--a29614, #A29614);
  stop-opacity: 0;
}

.cgtf_3oto {
  stop-color: var(--svg-color--9adf7b, #9ADF7B);
  stop-opacity: 0;
}

.dge16lbmj {
  fill: var(--svg-color--e6b595, #E6B595);
  d: path("M25.898 6.09a13.95 13.95 0 0 0-7.01-3.8L2.267 18.91a14 14 0 0 0 3.8 7.01c5.48 5.48 14.35 5.48 19.83 0s5.48-14.36 0-19.83");
}

.dox4jvhwf {
  stop-color: var(--svg-color--c23d65, #C23D65);
  stop-opacity: 0;
}

.e9_i-bcrx {
  stop-color: var(--svg-color--fffa59, #FFFA59);
}

.ecscp6bsl {
  stop-color: var(--svg-color--a6ef67, #A6EF67);
}

.egmlv4bso {
  stop-color: var(--svg-color--4e251c, #4E251C);
}

.f_-xq7bkg {
  stop-color: var(--svg-color--ab6277, #AB6277);
  stop-opacity: 0;
}

.f_jowmbud {
  stop-color: var(--svg-color--5b8d40, #5B8D40);
}

.fq2u14nai {
  fill: var(--svg-color--bf285b, #BF285B);
  d: path("M15.358 14.4a4.7 4.7 0 1 0 0-9.4a4.7 4.7 0 0 0 0 9.4");
}

.ft5dv1b6b {
  fill: none;
}

.g6cvf3swx {
  stop-color: var(--svg-color--527c37, #527C37);
}

.g78__vbaj {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M20.094 4.875c-1.235-1.172-3.125-1.563-4.563-.937");
}

.haxm-blrv {
  stop-color: var(--svg-color--e5657d, #E5657D);
}

.hhctjoo7s {
  stop-color: var(--svg-color--815e58, #815E58);
}

.iim47zbou {
  stop-color: var(--svg-color--deb48c, #DEB48C);
  stop-opacity: 0;
}

.ja4chs8_e {
  stop-color: var(--svg-color--c23c66, #C23C66);
}

.jarb8ybxi {
  stop-color: var(--svg-color--b68665, #B68665);
}

.jkpbawiuw {
  stop-color: var(--svg-color--763837, #763837);
}

.jzz1iz8js {
  stop-color: var(--svg-color--ae1137, #AE1137);
}

.ktvk93btk {
  stroke-linecap: round;
  d: path("M20.844 9.094c-.4 1.012-2.407 2.875-5.094 2.406c-3.017-.526-3.937 1.656-3.937 2.5");
}

.kuecjnbtw {
  fill: var(--svg-color--b92a64, #B92A64);
  d: path("M9.474 20.594a4.7 4.7 0 1 0 0-9.4a4.7 4.7 0 0 0 0 9.4");
}

.lh5rndbbu {
  d: path("M18.594 9.153c-.02.02-.04.04-.06.05c-.99.89-2.32 1.28-3.65 1.13c-1.27-.14-2.58.27-3.55 1.24S9.78 13.875 9.78 15.156v3.594c-1.469.469-1.75 2.25-1.468 3.875c1.874.313 4.11-.57 5.009-1.469c2.953-2.953 4.515-4.578 6.969-7.078c2.174-2.216 2.28-4.656 2.187-5.89c-1.274-.26-2.845.066-3.884.965");
}

.lik4c9zrj {
  stop-color: var(--svg-color--7db061, #7DB061);
}

.livbukvxq {
  stop-color: var(--svg-color--739d59, #739D59);
}

.lk6o6qb3d {
  stop-color: var(--svg-color--c09c72, #C09C72);
  stop-opacity: 0;
}

.lyi50sxgr {
  d: path("M9.474 20.594a4.7 4.7 0 1 0 0-9.4a4.7 4.7 0 0 0 0 9.4");
}

.lz6ua7b1r {
  d: path("M16.137 14a4.7 4.7 0 1 0 0-9.4a4.7 4.7 0 0 0 0 9.4");
}

.ms6rbmmya {
  fill: var(--svg-color--bf285b, #BF285B);
  d: path("M16.137 14a4.7 4.7 0 1 0 0-9.4a4.7 4.7 0 0 0 0 9.4");
}

.n_au17bry {
  stop-color: var(--svg-color--582e32, #582E32);
}

.nij5yir4a {
  stop-color: var(--svg-color--607727, #607727);
  stop-opacity: 0;
}

.nrqtwxhse {
  d: path("M19.038 9.152c-.02.02-.04.04-.06.05c-.99.89-2.32 1.28-3.65 1.13c-1.27-.14-2.58.27-3.55 1.24s-1.38 2.28-1.24 3.55c.15 1.33-.257 3.029-1.147 4.019c-.95.95-1.095 2.466-.828 3.75c1.874.312 4.304-.836 5.203-1.735c2.953-2.953 4.515-4.578 6.968-7.078c2.175-2.216 2.282-4.656 2.188-5.89c-1.274-.26-2.845.066-3.884.964");
}

.nv9_mfbmq {
  stop-color: var(--svg-color--aeef90, #AEEF90);
}

.o6sptfbzi {
  stop-color: var(--svg-color--fdd5ac, #FDD5AC);
  stop-opacity: 0;
}

.o88y2wbig {
  stop-color: var(--svg-color--c09d73, #C09D73);
}

.ok7ku9bmj {
  fill: var(--svg-color--3c4f0f, #3C4F0F);
  d: path("M9.086 21.4a4.7 4.7 0 1 0 0-9.4a4.7 4.7 0 0 0 0 9.4");
}

.omwhmkb4w {
  stop-color: var(--svg-color--7a544e, #7A544E);
}

.p4g_pckdc {
  stop-color: var(--svg-color--d1a574, #D1A574);
}

.pmxg51h-d {
  stop-color: var(--svg-color--ad657e, #AD657E);
}

.ps81f7b8q {
  stop-color: var(--svg-color--e4ca49, #E4CA49);
}

.pzk1cqb3f {
  stop-color: var(--svg-color--e2b984, #E2B984);
}

.ra-bezs1z {
  d: path("M21.78 5.598a3.4 3.4 0 0 0-4.81 0L5.878 16.846a3.4 3.4 0 0 0 0 4.81c1.33 1.33 3.855 1.799 5.185.469l11.03-11.484c1.31-1.33 1.007-3.713-.313-5.043");
}

.tbd_ah9qe {
  stop-color: var(--svg-color--467725, #467725);
}

.tdr9jhb-b {
  fill: var(--svg-color--b92a64, #B92A64);
  d: path("M9.086 21.4a4.7 4.7 0 1 0 0-9.4a4.7 4.7 0 0 0 0 9.4");
}

.tr1cb2sfw {
  stop-color: var(--svg-color--80c95e, #80C95E);
}

.tx29ghbdv {
  stop-color: var(--svg-color--d7ab7e, #D7AB7E);
}

.u6wpv2lcm {
  stop-color: var(--svg-color--3d775a, #3D775A);
}

.vt609h34t {
  stop-color: var(--svg-color--4a7615, #4A7615);
}

.w-y0uzykl {
  stop-color: var(--svg-color--507a1d, #507A1D);
}

.w15jk7bob {
  stop-color: var(--svg-color--e5647d, #E5647D);
  stop-opacity: 0;
}

.waerimb_l {
  fill: var(--svg-color--374906, #374906);
  d: path("M15.358 14.4a4.7 4.7 0 1 0 0-9.4a4.7 4.7 0 0 0 0 9.4");
}

.wr9i42bbk {
  stop-color: var(--svg-color--76a05b, #76A05B);
  stop-opacity: 0;
}

.x5bywsbxv {
  d: path("M21.188 4.953c3.078 2.688 1.546 6.953-.344 8.985l-7.094 7.234c-2.453 2.062-6.203 2.64-8.547-.188c-2.15-2.15-2.136-5.744.014-7.894l7.86-7.86c1.97-1.97 6.037-2.331 8.11-.277m-9.516-.719l-7.25 7.672C1.782 14.796.89 18.61 4.078 22a7.07 7.07 0 0 0 5.03 2.08c1.9 0 3.69-.74 5.03-2.08l7.86-7.86a7.07 7.07 0 0 0 2.08-5.03c0-1.9-.74-3.69-2.08-5.03c-2.838-2.838-7.523-2.649-10.326.154");
}

.xj44znbms {
  stop-color: var(--svg-color--fcd3a8, #FCD3A8);
}

.xkm965b6f {
  d: path("M19.781 9h-9.505c-.66 0-1.19.53-1.19 1.19v9.591c0 .66.53.529 1.19.529l10.12-10.12c.01-.66.045-1.19-.615-1.19");
}

.y-8-eaccr {
  d: path("M6.438 10.375c0-1.75.812-4.375 4.312-4.125c2.517.18 3.784-.2 4.243-.63l.194-.495c.041.152-.014.327-.194.495l-1.743 4.443l-6.812 3.312z");
}

.z_-kgzb-o {
  stop-color: var(--svg-color--9a8f10, #9A8F10);
}

.z8y8xkpvf {
  stop-color: var(--svg-color--d8b07d, #D8B07D);
}

</style>
