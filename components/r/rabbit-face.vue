<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iCCwr7c)" class="by_-0rbfc"/><path fill="url(#iAYNegY)" class="by_-0rbfc"/><path fill="url(#iA7yyle)" class="by_-0rbfc"/><path fill="url(#i8HRy4c)" class="by_-0rbfc"/><path fill="url(#itWCkwd)" class="by_-0rbfc"/><path fill="url(#imyDTMe)" class="by_-0rbfc"/><path fill="url(#iXfT5fb)" class="by_-0rbfc"/><path fill="url(#iCKZgnt)" class="by_-0rbfc"/><path fill="url(#iQQYuBf)" class="awumhdbng"/><path fill="url(#ihVQygc)" class="awumhdbng"/><path fill="url(#iXFLBOf)" class="s7it3sb6i"/><path fill="url(#iLB15Oc)" class="u7lun2dqp"/><path fill="url(#iQVFHSb)" class="vq66a8bxb"/><path fill="url(#ioI2YIc)" class="vq66a8bxb"/><path fill="url(#icXsIFc)" class="vq66a8bxb"/><path fill="url(#iwB4AZb)" class="vq66a8bxb"/><path fill="url(#i4Bq0ae)" class="vq66a8bxb"/><path fill="url(#i57puHe)" class="q2svbf0eq"/><path fill="url(#iF9pXje)" class="luub8kboe"/><path fill="url(#iTnrGTd)" class="luub8kboe"/><path fill="url(#ifzcRie)" class="luub8kboe"/><path fill="url(#iJHqwSj)" class="hy9qwtbux"/><path fill="url(#iTWGhCb)" class="hy9qwtbux"/><path fill="url(#i6NDzpb)" class="hy9qwtbux"/><path fill="url(#iqsDGqb)" class="uic2pcc2q"/><path fill="url(#iaXGNCe)" class="uxnopcb-v"/><path fill="url(#iXjcIGc)" class="tpmq194au"/><path fill="url(#iCt0fXb)" class="vpfx82b4o"/><path stroke="url(#iDh9JYb)" class="i8a8jkfur"/><path stroke="url(#ieKHZEb)" class="u6qr1_bpf"/><path fill="url(#ihqnkEc)" class="vc5x1qbcn"/><path fill="url(#iJa1eIq)" class="vc5x1qbcn"/><path fill="url(#iqQqqId)" class="vc5x1qbcn"/><path fill="url(#i14UbIB)" class="omd6tjb1d"/><path fill="url(#iqZVc3d)" class="omd6tjb1d"/><path fill="url(#iv3CTqe)" class="omd6tjb1d"/><path fill="url(#ipsMohd)" class="lnifzvjin"/><path fill="url(#i7AgGxe)" class="lnifzvjin"/><path fill="url(#ieYdPuc)" class="lnifzvjin"/><g filter="url(#iHHPiSb)"><circle class="ky_u7idhy"/></g><g filter="url(#il70Bce)"><circle class="v_0oehbjr"/></g><g filter="url(#i4jeT3b)"><circle class="toq7bodik"/></g><g filter="url(#ieBiEgc)"><circle class="nmc8i3f6w"/></g><g filter="url(#i7IckGc)"><path stroke="url(#idBuoCc)" class="cddw6q-wp"/></g><defs><radialGradient id="iCCwr7c" cx="0" cy="0" r="1" gradientTransform="rotate(132.256 9.53 11.51)scale(14.7823)" gradientUnits="userSpaceOnUse"><stop class="h_j9u0wvt"/><stop offset="1" class="wae-w0imf"/></radialGradient><radialGradient id="iAYNegY" cx="0" cy="0" r="1" gradientTransform="matrix(-14.54362 15.01047 -17.58502 -17.0381 21.855 12.664)" gradientUnits="userSpaceOnUse"><stop offset=".621" class="nd9mpknek"/><stop offset="1" class="yxjp_acss"/></radialGradient><radialGradient id="iA7yyle" cx="0" cy="0" r="1" gradientTransform="rotate(144.002 11.659 11.969)scale(9.64789 8.08355)" gradientUnits="userSpaceOnUse"><stop class="jmkeembaf"/><stop offset="1" class="c7qjoj2pk"/></radialGradient><radialGradient id="i8HRy4c" cx="0" cy="0" r="1" gradientTransform="matrix(1.03091 20.17348 -29.01963 1.48297 19.187 12.264)" gradientUnits="userSpaceOnUse"><stop offset=".551" class="nce-9-b3j"/><stop offset="1" class="s2nb2ub4e"/></radialGradient><radialGradient id="itWCkwd" cx="0" cy="0" r="1" gradientTransform="rotate(92.001 3.672 15.396)scale(18.8099 27.2611)" gradientUnits="userSpaceOnUse"><stop offset=".922" class="ome3odbeb"/><stop offset="1" class="dptpf7bae"/></radialGradient><radialGradient id="imyDTMe" cx="0" cy="0" r="1" gradientTransform="rotate(118.752 6.486 5.296)scale(4.02786 5.37368)" gradientUnits="userSpaceOnUse"><stop class="i4knb5-3b"/><stop offset="1" class="zel9-dt1x"/></radialGradient><radialGradient id="iXfT5fb" cx="0" cy="0" r="1" gradientTransform="rotate(16.984 -72.755 35.786)scale(13.2661 17.4906)" gradientUnits="userSpaceOnUse"><stop class="nkhcuebtm"/><stop offset="1" class="oywpyqb1y"/></radialGradient><radialGradient id="iCKZgnt" cx="0" cy="0" r="1" gradientTransform="matrix(0 3.71875 -5.46875 0 22.968 23.063)" gradientUnits="userSpaceOnUse"><stop class="bqri72fbu"/><stop offset="1" class="hxtzfj5-c"/></radialGradient><radialGradient id="iQQYuBf" cx="0" cy="0" r="1" gradientTransform="rotate(159.238 10.676 11.452)scale(22.3916 15.088)" gradientUnits="userSpaceOnUse"><stop offset=".911" class="xssyvlb5l"/><stop offset=".995" class="xccvewk8e"/></radialGradient><radialGradient id="ihVQygc" cx="0" cy="0" r="1" gradientTransform="matrix(3.21375 -7.6875 23.6855 9.9017 9.905 30.438)" gradientUnits="userSpaceOnUse"><stop class="s2nb2ub4e"/><stop offset=".88" class="nce-9-b3j"/></radialGradient><radialGradient id="iXFLBOf" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.51563 3.49949 0 11.537 6.516)" gradientUnits="userSpaceOnUse"><stop offset=".952" class="u6d866bio"/><stop offset="1" class="mvbot0bzc"/></radialGradient><radialGradient id="icXsIFc" cx="0" cy="0" r="1" gradientTransform="rotate(-167.047 11.983 4.909)scale(3.20659 1.5685)" gradientUnits="userSpaceOnUse"><stop class="m_f0evbyx"/><stop offset="1" class="g4udvybro"/></radialGradient><radialGradient id="iwB4AZb" cx="0" cy="0" r="1" gradientTransform="rotate(148.079 11.53 5.43)scale(4.49175 8.31212)" gradientUnits="userSpaceOnUse"><stop class="i4knb5-3b"/><stop offset="1" class="zel9-dt1x"/></radialGradient><radialGradient id="i57puHe" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.51563 3.49949 0 20.95 6.516)" gradientUnits="userSpaceOnUse"><stop offset=".952" class="u6d866bio"/><stop offset="1" class="mvbot0bzc"/></radialGradient><radialGradient id="iF9pXje" cx="0" cy="0" r="1" gradientTransform="matrix(-1.43756 -7.6875 1.521 -.28443 10.999 8.906)" gradientUnits="userSpaceOnUse"><stop class="viia9y6ss"/><stop offset="1" class="yq66j8k3y"/></radialGradient><radialGradient id="iTnrGTd" cx="0" cy="0" r="1" gradientTransform="matrix(2.56179 -4.875 1.97731 1.03907 9.36 7.594)" gradientUnits="userSpaceOnUse"><stop class="viia9y6ss"/><stop offset="1" class="hrwt7wbvm"/></radialGradient><radialGradient id="iJHqwSj" cx="0" cy="0" r="1" gradientTransform="matrix(0 -7.84375 1.58125 0 19.73 8.156)" gradientUnits="userSpaceOnUse"><stop class="viia9y6ss"/><stop offset="1" class="yq66j8k3y"/></radialGradient><radialGradient id="iTWGhCb" cx="0" cy="0" r="1" gradientTransform="matrix(2.5625 -4.875 1.97762 1.03952 18.78 7.594)" gradientUnits="userSpaceOnUse"><stop class="viia9y6ss"/><stop offset="1" class="hrwt7wbvm"/></radialGradient><radialGradient id="iDh9JYb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.71875 -2.18838 0 14.484 24.078)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="e9ucyqbno"/><stop offset="1" class="smhtebbjh"/></radialGradient><radialGradient id="ieKHZEb" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.71875 -2.18838 0 17.974 24.078)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="e9ucyqbno"/><stop offset="1" class="smhtebbjh"/></radialGradient><radialGradient id="iqQqqId" cx="0" cy="0" r="1" gradientTransform="matrix(-.56318 -1.62343 1.554 -.5391 13.534 18.654)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><radialGradient id="iqZVc3d" cx="0" cy="0" r="1" gradientTransform="matrix(-2.51563 -.31418 .26666 -2.13511 17.01 21.23)" gradientUnits="userSpaceOnUse"><stop offset=".452" class="jnn8gachp"/><stop offset="1" class="pbdnt9b_j"/></radialGradient><radialGradient id="iv3CTqe" cx="0" cy="0" r="1" gradientTransform="matrix(-1.33594 .63176 -.3427 -.72468 17.58 20.895)" gradientUnits="userSpaceOnUse"><stop class="cqefsqb0k"/><stop offset=".663" class="v74648q6x"/></radialGradient><radialGradient id="ieYdPuc" cx="0" cy="0" r="1" gradientTransform="matrix(-.56318 -1.62343 1.554 -.5391 19.534 18.654)" gradientUnits="userSpaceOnUse"><stop offset=".814" class="zmzak_sfz"/><stop offset="1" class="dyysy0bzo"/></radialGradient><linearGradient id="iLB15Oc" x1="9.718" x2="13.405" y1="10.375" y2="9.625" gradientUnits="userSpaceOnUse"><stop class="m195wp9jh"/><stop offset="1" class="eys0w0b9l"/></linearGradient><linearGradient id="iQVFHSb" x1="15.436" x2="24.811" y1="6.316" y2="7.066" gradientUnits="userSpaceOnUse"><stop class="m195wp9jh"/><stop offset="1" class="eys0w0b9l"/></linearGradient><linearGradient id="ioI2YIc" x1="20.28" x2="20.28" y1="13.098" y2="7.879" gradientUnits="userSpaceOnUse"><stop class="lqqc0zbph"/><stop offset="1" class="ji4x2b02a"/></linearGradient><linearGradient id="i4Bq0ae" x1="23.139" x2="22.499" y1="8.723" y2="8.613" gradientUnits="userSpaceOnUse"><stop class="huuzjubvn"/><stop offset="1" class="mk3umhn7m"/></linearGradient><linearGradient id="ifzcRie" x1="13.092" x2="11.53" y1="3.5" y2="6.063" gradientUnits="userSpaceOnUse"><stop offset=".109" class="ysodyjd7t"/><stop offset="1" class="hfn1b4bph"/></linearGradient><linearGradient id="i6NDzpb" x1="22.811" x2="20.499" y1="3.813" y2="5.969" gradientUnits="userSpaceOnUse"><stop offset=".109" class="ysodyjd7t"/><stop offset="1" class="hfn1b4bph"/></linearGradient><linearGradient id="iqsDGqb" x1="26.53" x2="26.336" y1="24.328" y2="25.085" gradientUnits="userSpaceOnUse"><stop class="nb0431bup"/><stop offset="1" class="dw5ur8mub"/></linearGradient><linearGradient id="iaXGNCe" x1="26.22" x2="26.22" y1="21.219" y2="22.125" gradientUnits="userSpaceOnUse"><stop class="bkdorobjb"/><stop offset="1" class="tfxx3nbjw"/></linearGradient><linearGradient id="iXjcIGc" x1="6.444" x2="6.655" y1="24.211" y2="25.078" gradientUnits="userSpaceOnUse"><stop class="nb0431bup"/><stop offset="1" class="dw5ur8mub"/></linearGradient><linearGradient id="iCt0fXb" x1="6.27" x2="6.27" y1="21.219" y2="22.125" gradientUnits="userSpaceOnUse"><stop class="bkdorobjb"/><stop offset="1" class="tfxx3nbjw"/></linearGradient><linearGradient id="ihqnkEc" x1="13.98" x2="13.135" y1="18.475" y2="18.475" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iJa1eIq" x1="14.208" x2="14.208" y1="20.008" y2="18.609" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="i14UbIB" x1="15.276" x2="16.58" y1="20.724" y2="22.428" gradientUnits="userSpaceOnUse"><stop class="b_1uydbhs"/><stop offset="1" class="hf-zpcceu"/></linearGradient><linearGradient id="ipsMohd" x1="19.98" x2="19.135" y1="18.475" y2="18.475" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="i7AgGxe" x1="20.208" x2="20.208" y1="20.008" y2="18.609" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="idBuoCc" x1="12.563" x2="20.078" y1="24.02" y2="24.02" gradientUnits="userSpaceOnUse"><stop class="rj14edb9i"/><stop offset=".289" class="zkps8y4ss"/><stop offset=".445" class="zkps8y4ss"/><stop offset=".534" class="rj14edb9i"/><stop offset="1" class="zkps8y4ss"/></linearGradient><filter id="iHHPiSb" width=".867" height=".867" x="9.408" y="20.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3835" stdDeviation=".125"/></filter><filter id="il70Bce" width=".867" height=".867" x="29.33" y="20.91" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3835" stdDeviation=".125"/></filter><filter id="i4jeT3b" width=".867" height=".867" x="29.154" y="24.859" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3835" stdDeviation=".125"/></filter><filter id="ieBiEgc" width=".867" height=".867" x="9.382" y="23.026" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3835" stdDeviation=".125"/></filter><filter id="i7IckGc" width="7.719" height="2.484" x="12.375" y="23.145" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_3835" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:rabbit-face" /></template>
<style>
.awumhdbng {
  d: path("M21.968 29.151V17.438L9.992 11.569c-.714.436-1.427.986-2.102 1.671c-2.43 2.5-3.23 5.58-3.49 7.32c-.08.44-.12.88-.13 1.34v.02c0 2.88 1.67 5.36 4.08 6.55c0 0 2.62 1.53 7.64 1.53c2.7 0 4.701-.44 5.978-.849");
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b_1uydbhs {
  stop-color: var(--svg-color--f03273, #F03273);
}

.bkdorobjb {
  stop-color: var(--svg-color--cac6d0, #CAC6D0);
}

.bqri72fbu {
  stop-color: var(--svg-color--d3c8df, #D3C8DF);
}

.by_-0rbfc {
  d: path("M27.73 21.89c0-.45-.04-.9-.12-1.33c-.26-1.73-1.05-4.82-3.49-7.32c-.55-.57-1.13-1.04-1.72-1.43l1.22-6.61c.3-1.66-.98-3.2-2.67-3.2c-1.5 0-2.71 1.21-2.71 2.71v5.4c-1.32-.26-2.23-.22-2.23-.22s-.7-.04-1.76.13V4.71c0-1.5-1.21-2.71-2.71-2.71c-1.7 0-2.98 1.54-2.67 3.2l1.17 6.34c-.73.44-1.46 1-2.15 1.7c-2.43 2.5-3.23 5.58-3.49 7.32c-.08.44-.12.88-.13 1.34v.02c0 2.88 1.67 5.36 4.08 6.55c0 0 2.62 1.53 7.64 1.53c5.03 0 7.64-1.53 7.64-1.53a7.29 7.29 0 0 0 4.08-6.55c.02 0 .02-.01.02-.03");
}

.c7qjoj2pk {
  stop-color: var(--svg-color--f7f5fa, #F7F5FA);
  stop-opacity: 0;
}

.cddw6q-wp {
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--0-25px, 0.25px);
  d: path("M12.75 23.52c.042.52.534 1.581 1.61 1.656c1.343.094 1.812-.968 1.859-1.656c-.026.552.578 1.734 1.843 1.734c1.088 0 1.6-1.182 1.657-1.734");
}

.cqefsqb0k {
  stop-color: var(--svg-color--ff8ad5, #FF8AD5);
}

.dptpf7bae {
  stop-color: var(--svg-color--d6b8e0, #D6B8E0);
}

.dw5ur8mub {
  stop-color: var(--svg-color--9987aa, #9987AA);
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e9ucyqbno {
  stop-color: var(--svg-color--423539, #423539);
}

.eys0w0b9l {
  stop-color: var(--svg-color--d3ced5, #D3CED5);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g4udvybro {
  stop-color: var(--svg-color--ecebed, #ECEBED);
  stop-opacity: 0;
}

.h_j9u0wvt {
  stop-color: var(--svg-color--e6e6e6, #E6E6E6);
}

.hf-zpcceu {
  stop-color: var(--svg-color--ff32af, #FF32AF);
}

.hfn1b4bph {
  stop-color: var(--svg-color--f2a7a0, #F2A7A0);
  stop-opacity: 0;
}

.hrwt7wbvm {
  stop-color: var(--svg-color--fabdb6, #FABDB6);
  stop-opacity: 0;
}

.huuzjubvn {
  stop-color: var(--svg-color--ddd6e1, #DDD6E1);
}

.hxtzfj5-c {
  stop-color: var(--svg-color--d2cbda, #D2CBDA);
  stop-opacity: 0;
}

.hy9qwtbux {
  d: path("M19.73 10.65V4.74c0-.67.55-1.24 1.23-1.24c.49 0 .79.28.93.44s.35.51.26 1l-1.08 5.84c-.06.32-.34.55-.66.55a.68.68 0 0 1-.68-.68");
}

.i4knb5-3b {
  stop-color: var(--svg-color--e7e3e7, #E7E3E7);
}

.i8a8jkfur {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M16.23 23.52c0 1.045-.78 1.894-1.74 1.894s-1.74-.849-1.74-1.894");
}

.ji4x2b02a {
  stop-color: var(--svg-color--e1e1e1, #E1E1E1);
  stop-opacity: 0;
}

.jmkeembaf {
  stop-color: var(--svg-color--f7f5fa, #F7F5FA);
}

.jnn8gachp {
  stop-color: var(--svg-color--d53238, #D53238);
  stop-opacity: 0;
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.ky_u7idhy {
  cx: 9.842px;
  cy: 21.343px;
  r: 0.184px;
  fill: var(--svg-color--d6cede, #D6CEDE);
}

.lnifzvjin {
  d: path("M19.25 19.964c-.4 0-.73-.33-.73-.73v-1.518c0-.4.33-.73.73-.73s.73.33.73.73v1.518c0 .41-.33.73-.73.73");
}

.lqqc0zbph {
  stop-color: var(--svg-color--e1e1e1, #E1E1E1);
}

.luub8kboe {
  d: path("M12.07 11.33c-.33 0-.6-.23-.66-.55l-1.08-5.85c-.09-.49.13-.84.26-1c.14-.16.44-.43.93-.43c.67 0 1.23.57 1.23 1.24v5.92c0 .36-.3.67-.68.67");
}

.m_f0evbyx {
  stop-color: var(--svg-color--ecebed, #ECEBED);
}

.m195wp9jh {
  stop-color: var(--svg-color--d3ced5, #D3CED5);
}

.mk3umhn7m {
  stop-color: var(--svg-color--dfdbe1, #DFDBE1);
  stop-opacity: 0;
}

.mvbot0bzc {
  stop-color: var(--svg-color--efeeef, #EFEEEF);
}

.nb0431bup {
  stop-color: var(--svg-color--bab4c0, #BAB4C0);
}

.nce-9-b3j {
  stop-color: var(--svg-color--b59ad0, #B59AD0);
  stop-opacity: 0;
}

.nd9mpknek {
  stop-color: var(--svg-color--ccc9cf, #CCC9CF);
  stop-opacity: 0;
}

.nkhcuebtm {
  stop-color: var(--svg-color--cdcad2, #CDCAD2);
}

.nmc8i3f6w {
  cx: 9.816px;
  cy: 23.46px;
  r: 0.184px;
  fill: var(--svg-color--d6cede, #D6CEDE);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
}

.omd6tjb1d {
  d: path("M17.83 21.066c0 .426-.929 1.489-1.577 1.489c-.694 0-1.594-.97-1.594-1.49c0-.518.703-.566 1.594-.566c.89 0 1.578.034 1.578.567");
}

.ome3odbeb {
  stop-color: var(--svg-color--d6b8e0, #D6B8E0);
  stop-opacity: 0;
}

.oywpyqb1y {
  stop-color: var(--svg-color--cdcad2, #CDCAD2);
  stop-opacity: 0;
}

.pbdnt9b_j {
  stop-color: var(--svg-color--d53238, #D53238);
}

.q2svbf0eq {
  d: path("M18.238 7.415h4.97l.41-2.215c.31-1.66-.97-3.2-2.67-3.2c-1.5 0-2.71 1.21-2.71 2.71z");
}

.rj14edb9i {
  stop-color: var(--svg-color--5f5356, #5F5356);
}

.s2nb2ub4e {
  stop-color: var(--svg-color--b59ad0, #B59AD0);
}

.s7it3sb6i {
  d: path("M14.25 7.415H9.279L8.87 5.2C8.56 3.54 9.84 2 11.54 2c1.5 0 2.71 1.21 2.71 2.71z");
}

.smhtebbjh {
  stop-color: var(--svg-color--3c223c, #3C223C);
}

.tfxx3nbjw {
  stop-color: var(--svg-color--ada0bb, #ADA0BB);
}

.toq7bodik {
  cx: 29.588px;
  cy: 25.293px;
  r: 0.184px;
  fill: var(--svg-color--d6cede, #D6CEDE);
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
}

.tpmq194au {
  d: path("m9.65 23.13l-6.74 1.81a.492.492 0 1 0 .25.95l6.74-1.81c.27-.07.42-.34.35-.61a.476.476 0 0 0-.6-.34");
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.u6d866bio {
  stop-color: var(--svg-color--efeeef, #EFEEEF);
  stop-opacity: 0;
}

.u6qr1_bpf {
  stroke-linecap: round;
  stroke-miterlimit: 10;
  d: path("M19.72 23.52c0 1.045-.78 1.894-1.74 1.894s-1.74-.849-1.74-1.894");
}

.u7lun2dqp {
  d: path("M10.042 11.228a2 2 0 0 0 2.245 1.598l.243-.035a2 2 0 0 0 1.719-1.98V5.487l.001-.003V4.71c0-1.5-1.21-2.71-2.71-2.71c-1.7 0-2.98 1.54-2.67 3.2z");
}

.uic2pcc2q {
  d: path("m22.84 23.13l6.74 1.81c.27.07.42.34.35.61s-.34.42-.61.35l-6.74-1.81a.49.49 0 0 1-.35-.61c.07-.27.34-.43.61-.35");
}

.uxnopcb-v {
  d: path("M22.73 20.98h6.98c.28 0 .5.22.5.5s-.22.5-.5.5h-6.98c-.28 0-.5-.22-.5-.5c0-.27.22-.5.5-.5");
}

.v_0oehbjr {
  cx: 29.764px;
  cy: 21.343px;
  r: 0.184px;
  fill: var(--svg-color--d6cede, #D6CEDE);
}

.v74648q6x {
  stop-color: var(--svg-color--ff6ccb, #FF6CCB);
  stop-opacity: 0;
}

.vc5x1qbcn {
  d: path("M13.25 19.964c-.4 0-.73-.33-.73-.73v-1.518c0-.4.33-.73.73-.73s.73.33.73.73v1.518c0 .41-.33.73-.73.73");
}

.viia9y6ss {
  stop-color: var(--svg-color--fabdb6, #FABDB6);
}

.vpfx82b4o {
  d: path("M9.76 20.98H2.78c-.28 0-.5.22-.5.5s.22.5.5.5h6.98c.28 0 .5-.22.5-.5c0-.27-.23-.5-.5-.5");
}

.vq66a8bxb {
  d: path("M22.477 11.232a2 2 0 0 1-2.245 1.598l-.244-.035a2 2 0 0 1-1.718-1.98V5.491l-.001-.003v-.774c0-1.5 1.21-2.71 2.71-2.71c1.7 0 2.98 1.54 2.67 3.2z");
}

.wae-w0imf {
  stop-color: var(--svg-color--d3d3d3, #D3D3D3);
}

.xccvewk8e {
  stop-color: var(--svg-color--e9e9e9, #E9E9E9);
}

.xssyvlb5l {
  stop-color: var(--svg-color--e9e9e9, #E9E9E9);
  stop-opacity: 0;
}

.yq66j8k3y {
  stop-color: var(--svg-color--eea49c, #EEA49C);
}

.ysodyjd7t {
  stop-color: var(--svg-color--f59d94, #F59D94);
}

.yxjp_acss {
  stop-color: var(--svg-color--ccc9cf, #CCC9CF);
}

.zel9-dt1x {
  stop-color: var(--svg-color--e7e3e7, #E7E3E7);
  stop-opacity: 0;
}

.zkps8y4ss {
  stop-color: var(--svg-color--5f5356, #5F5356);
  stop-opacity: 0;
}

.zmzak_sfz {
  stop-color: var(--svg-color--594c4f, #594C4F);
  stop-opacity: 0;
}

</style>
