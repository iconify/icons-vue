<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iQt2LtV)" class="n6a42cqnz"/><path class="v5-mdkdsq"/><path fill="url(#ihdqpvd)" class="k6519wr5u"/><path fill="url(#iMBlyVZ)" class="k6519wr5u"/><path fill="url(#iUWRFRc)" class="li72-rcrt"/><path fill="url(#iPgs4Ab)" class="li72-rcrt"/><path fill="url(#iFxB39b)" class="tqi4qlghe"/><path class="jnkr0qo7b"/><path fill="url(#iVtLSPa)" class="hfrtxt8ef"/><path fill="url(#ilX1BEc)" class="hfrtxt8ef"/><path fill="url(#imBfJle)" class="era9-1bhl"/><g filter="url(#i8U7YBc)"><path class="dbl31bbhu"/></g><path fill="url(#iaAsodx)" class="lsu5chbki"/><g filter="url(#ita13wd)"><path class="l805eptdl"/></g><path class="joqgpvb1y"/><path fill="url(#im3sFQd)" class="d4821ubvc"/><path fill="url(#inu4POc)" class="d4821ubvc"/><path fill="url(#i3hB4fc)" class="d4821ubvc"/><path fill="url(#iDPBOjd)" class="o6ccvrsng"/><g filter="url(#i11SzHO)"><path fill="url(#iXeZd1C)" class="o6ccvrsng"/><path fill="url(#iFZyUXb)" class="o6ccvrsng"/><path fill="url(#iYk8Bxi)" class="o6ccvrsng"/><path fill="url(#iRLdLmb)" class="o6ccvrsng"/></g><g filter="url(#iy46sld)"><path fill="url(#iPYDt6d)" class="cu9x5cbub"/></g><defs><linearGradient id="iQt2LtV" x1="24.25" x2="21.75" y1="8" y2="8.5" gradientUnits="userSpaceOnUse"><stop class="x_88-xlmf"/><stop offset="1" class="khzos7q9w"/></linearGradient><linearGradient id="ihdqpvd" x1="20.751" x2="20.946" y1="9.642" y2="9.739" gradientUnits="userSpaceOnUse"><stop class="qp2tn2b6x"/><stop offset="1" class="rrukusfrw"/></linearGradient><linearGradient id="iMBlyVZ" x1="23.99" x2="23.49" y1="10.356" y2="10.356" gradientUnits="userSpaceOnUse"><stop class="v394bvbpq"/><stop offset="1" class="o1w3elkxp"/></linearGradient><linearGradient id="iUWRFRc" x1="26" x2="12.875" y1="12" y2="12" gradientUnits="userSpaceOnUse"><stop class="gz5w19p9v"/><stop offset="1" class="q3584xbhy"/></linearGradient><linearGradient id="iPgs4Ab" x1="12.173" x2="12.916" y1="12" y2="12.325" gradientUnits="userSpaceOnUse"><stop offset=".4" class="z7s57vb0s"/><stop offset="1" class="ohzsaxbhx"/></linearGradient><linearGradient id="iFxB39b" x1="28.5" x2="9.5" y1="28.5" y2="11.5" gradientUnits="userSpaceOnUse"><stop class="wr7rxybje"/><stop offset=".084" class="vc--wpv5i"/><stop offset=".856" class="vc--wpv5i"/><stop offset=".998" class="zaeth0b6d"/></linearGradient><linearGradient id="iVtLSPa" x1="26" x2="24.586" y1="15.109" y2="15.109" gradientUnits="userSpaceOnUse"><stop class="x-3a2m5wk"/><stop offset="1" class="w9kbsjy1v"/></linearGradient><linearGradient id="ilX1BEc" x1="10.247" x2="10.854" y1="13.781" y2="14.376" gradientUnits="userSpaceOnUse"><stop class="fxahkdbbc"/><stop offset="1" class="zpg-d_pwd"/></linearGradient><linearGradient id="imBfJle" x1="20" x2="25" y1="15" y2="15" gradientUnits="userSpaceOnUse"><stop offset=".595" class="cp65m-qgt"/><stop offset="1" class="gds77obnh"/></linearGradient><linearGradient id="iaAsodx" x1="8.025" x2="18.5" y1="15" y2="15" gradientUnits="userSpaceOnUse"><stop offset=".741" class="cp65m-qgt"/><stop offset=".937" class="gds77obnh"/></linearGradient><linearGradient id="im3sFQd" x1="28.002" x2="2.003" y1="18.003" y2="18.003" gradientUnits="userSpaceOnUse"><stop offset=".895" class="h13dd1l8r"/><stop offset="1" class="j10nr2byz"/></linearGradient><linearGradient id="inu4POc" x1="7.75" x2="24.375" y1="18.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="rcc-4sbff"/><stop offset="1" class="lcp-ucb6o"/></linearGradient><linearGradient id="i3hB4fc" x1="2" x2="2.892" y1="19" y2="19" gradientUnits="userSpaceOnUse"><stop offset=".214" class="t3pn_7b7m"/><stop offset="1" class="x52ht31vm"/></linearGradient><linearGradient id="iXeZd1C" x1="15" x2="15" y1="20" y2="25.063" gradientUnits="userSpaceOnUse"><stop class="tngp1cche"/><stop offset="1" class="fp-1xclza"/></linearGradient><linearGradient id="iFZyUXb" x1="2.941" x2="9.656" y1="24.106" y2="22.411" gradientUnits="userSpaceOnUse"><stop class="p6t2fbkqw"/><stop offset="1" class="jkt-3hb8i"/></linearGradient><linearGradient id="iYk8Bxi" x1="28" x2="22.563" y1="21.438" y2="21.438" gradientUnits="userSpaceOnUse"><stop class="hft7hibkm"/><stop offset="1" class="md6w2ee8p"/></linearGradient><linearGradient id="iRLdLmb" x1="28" x2="26.938" y1="22.563" y2="23" gradientUnits="userSpaceOnUse"><stop class="oa8zkfbgo"/><stop offset="1" class="agcv0443p"/></linearGradient><linearGradient id="iPYDt6d" x1="18.843" x2="18.843" y1="30.875" y2="24.343" gradientUnits="userSpaceOnUse"><stop class="mtztso4yr"/><stop offset="1" class="l2tc1xykf"/></linearGradient><filter id="i8U7YBc" width="4.5" height="3.4" x="19.49" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.5" dy=".4"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.733333 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12403"/></filter><filter id="ita13wd" width="10.75" height="3.6" x="7.25" y="13" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.75" dy=".6"/><feGaussianBlur stdDeviation=".5"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.266667 0 0 0 0 0.733333 0 0 0 0 0.945098 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12403"/></filter><filter id="i11SzHO" width="26.4" height="8.2" x="2" y="18.8" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".4" dy="-.2"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.513726 0 0 0 0 0.52549 0 0 0 0 0.615686 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12403"/></filter><filter id="iy46sld" width="28.6" height="7.6" x="1.4" y="23" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx="-.6" dy=".6"/><feGaussianBlur stdDeviation=".3"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.384314 0 0 0 0 0.67451 0 0 0 0 0.996078 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_18_12403"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dy=".4"/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.305882 0 0 0 0 0.556863 0 0 0 0 0.882353 0 0 0 1 0"/><feBlend in2="effect1_innerShadow_18_12403" result="effect2_innerShadow_18_12403"/></filter><radialGradient id="iDPBOjd" cx="0" cy="0" r="1" gradientTransform="matrix(-15.40745 10.2856 -7.0964 -10.63015 21.26 16.714)" gradientUnits="userSpaceOnUse"><stop class="wr7rxybje"/><stop offset=".084" class="vc--wpv5i"/><stop offset=".884" class="vc--wpv5i"/><stop offset=".998" class="zaeth0b6d"/></radialGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:motor-boat" /></template>
<style>
.agcv0443p {
  stop-color: var(--svg-color--dadbed, #DADBED);
  stop-opacity: 0;
}

.cp65m-qgt {
  stop-color: var(--svg-color--4cf0f8, #4CF0F8);
}

.cu9x5cbub {
  d: path("M30 23c-1.406 0-1.616.969-3.375.969c-1.75 0-1.756-.969-3.516-.969c-1.749 0-1.876.969-3.625.969S17.515 23 15.766 23c-1.438 0-1.53.969-3.28.969S10.343 23 8.594 23s-2.042.969-3.781.969C3.516 23.969 2.906 23 2 23v7h27.99z");
}

.d4821ubvc {
  d: path("M28 18.04c0-.57-.461-1.04-1.042-1.04H3.042A1.04 1.04 0 0 0 2 18.04V19h26z");
}

.dbl31bbhu {
  fill: var(--svg-color--60ffff, #60FFFF);
  d: path("M23.022 13h-2.064a.97.97 0 0 0-.968.967v1.066c0 .529.429.967.968.967h2.064a.97.97 0 0 0 .968-.967v-1.066a.97.97 0 0 0-.968-.967");
}

.era9-1bhl {
  d: path("M23.022 13h-2.064a.97.97 0 0 0-.968.967v1.066c0 .529.429.967.968.967h2.064a.97.97 0 0 0 .968-.967v-1.066a.97.97 0 0 0-.968-.967");
}

.fp-1xclza {
  stop-color: var(--svg-color--d2d6e6, #D2D6E6);
}

.ft5dv1b6b {
  fill: none;
}

.fxahkdbbc {
  stop-color: var(--svg-color--b2afb0, #B2AFB0);
}

.gds77obnh {
  stop-color: var(--svg-color--00a6ed, #00A6ED);
}

.gz5w19p9v {
  stop-color: var(--svg-color--ff4964, #FF4964);
}

.h13dd1l8r {
  stop-color: var(--svg-color--f70a8d, #F70A8D);
}

.hfrtxt8ef {
  d: path("M26 17H7l5.004-5H25.98c.01.027.019.046.019.073z");
}

.hft7hibkm {
  stop-color: var(--svg-color--c9cee1, #C9CEE1);
}

.j10nr2byz {
  stop-color: var(--svg-color--cc0649, #CC0649);
}

.jkt-3hb8i {
  stop-color: var(--svg-color--c7cbdd, #C7CBDD);
  stop-opacity: 0;
}

.jnkr0qo7b {
  fill: var(--svg-color--e6deec, #E6DEEC);
  d: path("M26 17H7l5.004-5H25.98c.01.027.019.046.019.073z");
}

.joqgpvb1y {
  fill: var(--svg-color--c0bfd4, #C0BFD4);
  d: path("M29.055 25H27v-4h2.055c.52 0 .945.424.945.945v2.11a.94.94 0 0 1-.945.945");
}

.k6519wr5u {
  d: path("M23.99 11h-4l.99-2h3.01z");
}

.khzos7q9w {
  stop-color: var(--svg-color--ec3e4e, #EC3E4E);
}

.l2tc1xykf {
  stop-color: var(--svg-color--539dfa, #539DFA);
}

.l805eptdl {
  fill: var(--svg-color--60ffff, #60FFFF);
  d: path("M18 14.99V14c0-.55-.452-1-1.004-1h-5.984L8 16h8.996A1.02 1.02 0 0 0 18 14.99");
}

.lcp-ucb6o {
  stop-color: var(--svg-color--ff4153, #FF4153);
}

.li72-rcrt {
  d: path("M24.936 11h-11.48c-.292 0-.563.11-.763.31L12 12h14c-.04-.55-.502-1-1.064-1");
}

.lsu5chbki {
  d: path("M18 14.99V14c0-.55-.452-1-1.004-1h-5.984L8 16h8.996A1.02 1.02 0 0 0 18 14.99");
}

.md6w2ee8p {
  stop-color: var(--svg-color--c9cee1, #C9CEE1);
  stop-opacity: 0;
}

.mtztso4yr {
  stop-color: var(--svg-color--51adff, #51ADFF);
}

.n6a42cqnz {
  d: path("M22.49 8h.5c.606 0 1 .5 1 1h-3s.5-1 1.5-1");
}

.o1w3elkxp {
  stop-color: var(--svg-color--fcf0fd, #FCF0FD);
  stop-opacity: 0;
}

.o6ccvrsng {
  d: path("M2 19v.076C2.522 23.535 6.49 27 11.323 27h15.632c.573 0 1.045-.44 1.045-.993V19z");
}

.oa8zkfbgo {
  stop-color: var(--svg-color--dadbed, #DADBED);
}

.ohzsaxbhx {
  stop-color: var(--svg-color--c45d6a, #C45D6A);
  stop-opacity: 0;
}

.p6t2fbkqw {
  stop-color: var(--svg-color--c7cbdd, #C7CBDD);
}

.q3584xbhy {
  stop-color: var(--svg-color--ff4a66, #FF4A66);
}

.qp2tn2b6x {
  stop-color: var(--svg-color--d5cbd4, #D5CBD4);
}

.rcc-4sbff {
  stop-color: var(--svg-color--ff496b, #FF496B);
}

.rrukusfrw {
  stop-color: var(--svg-color--d5cbd4, #D5CBD4);
  stop-opacity: 0;
}

.t3pn_7b7m {
  stop-color: var(--svg-color--b04659, #B04659);
}

.tngp1cche {
  stop-color: var(--svg-color--e6e5f5, #E6E5F5);
}

.tqi4qlghe {
  d: path("M26 17H7l5-4.99L25.98 12c.01.027.02.046.02.073z");
}

.v394bvbpq {
  stop-color: var(--svg-color--fcf0fd, #FCF0FD);
}

.v5-mdkdsq {
  fill: var(--svg-color--f2e2ef, #F2E2EF);
  d: path("M23.99 11h-4l.99-2h3.01z");
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.w9kbsjy1v {
  stop-color: var(--svg-color--fbf4ff, #FBF4FF);
  stop-opacity: 0;
}

.wr7rxybje {
  stop-color: var(--svg-color--d3d2d2, #D3D2D2);
}

.x_88-xlmf {
  stop-color: var(--svg-color--f87b86, #F87B86);
}

.x-3a2m5wk {
  stop-color: var(--svg-color--fbf4ff, #FBF4FF);
}

.x52ht31vm {
  stop-color: var(--svg-color--b04659, #B04659);
  stop-opacity: 0;
}

.z7s57vb0s {
  stop-color: var(--svg-color--c45d6a, #C45D6A);
}

.zaeth0b6d {
  stop-color: var(--svg-color--636363, #636363);
}

.zpg-d_pwd {
  stop-color: var(--svg-color--b2afb0, #B2AFB0);
  stop-opacity: 0;
}

</style>
