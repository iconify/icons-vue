<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><g filter="url(#iUrO8DO)"><path fill="url(#i7G8ntd)" class="bupxplb6l"/><path fill="url(#iVyOkxn)" class="bupxplb6l"/><path fill="url(#inEdW8d)" class="bupxplb6l"/><path fill="url(#il2avNc)" class="bupxplb6l"/></g><path fill="url(#iKiw8Ub)" clip-rule="evenodd" class="r5i0n2brg"/><path fill="url(#ikR0tmb)" class="ttuo2buhh"/><g filter="url(#iNsfq5c)"><path fill="url(#iVUVWac)" class="g82_46o6b"/></g><path class="ud5dprk-v"/><path fill="url(#iCRu3mb)" class="yoj47oy4e"/><path fill="url(#im91oce)" class="yoj47oy4e"/><path fill="url(#icpuYBB)" class="yoj47oy4e"/><path class="tky7p0b8n"/><path fill="url(#ijNcPlc)" class="le8k_dc3j"/><path fill="url(#iVt9bXq)" class="le8k_dc3j"/><path fill="url(#iQpNXAb)" class="le8k_dc3j"/><path fill="url(#iXAM0od)" class="h-m-91tnb"/><path fill="url(#innTrAb)" class="h-m-91tnb"/><path fill="url(#iqYaQsv)" class="h-m-91tnb"/><path fill="url(#ikxrW9d)" class="h-m-91tnb"/><path fill="url(#in9hD9c)" class="h-m-91tnb"/><path fill="url(#iHKMw3d)" class="h-m-91tnb"/><path fill="url(#ivp4Boy)" class="syplem7tj"/><path fill="url(#ipK4dPt)" class="ectxvsb8q"/><path fill="url(#iLMA6Ac)" class="gvpwnu65w"/><path fill="url(#iZoyKGe)" class="gvpwnu65w"/><path fill="url(#ileSqLe)" class="e0fe4p6cu"/><path fill="url(#i2bZ8Kc)" class="e0fe4p6cu"/><path stroke="url(#iUfvfZb)" class="tca6arbgi"/><path stroke="url(#ivw69eg)" class="tca6arbgi"/><path stroke="url(#iRidOtb)" class="tca6arbgi"/><path stroke="url(#ip9wdYd)" class="e-navhbzv"/><path stroke="url(#i6bqZnb)" class="e-navhbzv"/><g filter="url(#iD6lXNe)"><rect class="gkmqebcvd"/></g><g filter="url(#ihoML8d)"><rect class="v8ik8wb2x"/></g><rect fill="url(#ixmi2Md)" class="b0bwj1s7d"/><rect fill="url(#iZYGu5M)" class="b0bwj1s7d"/><rect fill="url(#ik27xQd)" class="ije5o1ywn"/><rect fill="url(#iS7fGGd)" class="ije5o1ywn"/><path fill="url(#ia8vsqp)" class="pe44dcyzd"/><path fill="url(#iezMKtU)" class="pe44dcyzd"/><path fill="url(#iyuiKUd)" class="pe44dcyzd"/><path fill="url(#iJQh9bc)" class="pe44dcyzd"/><g filter="url(#iLHHebc)"><path class="r0pcmrmhn"/></g><g filter="url(#ipDfZYw)"><path class="nh1amacwm"/></g><g filter="url(#i3fzuxY)"><path fill="url(#iHHeoqe)" class="b38brsj_m"/></g><g filter="url(#iJLqHhb)"><circle class="t36kbtyas"/></g><g filter="url(#iMdFCCd)"><circle class="j2kqk3swa"/></g><g filter="url(#iYx7tWd)"><ellipse transform="rotate(30.37 17.481 21.319)" class="l6p2phbjw"/></g><defs><radialGradient id="i7G8ntd" cx="0" cy="0" r="1" gradientTransform="rotate(119.632 7.395 12.021)scale(15.6749 29.1892)" gradientUnits="userSpaceOnUse"><stop class="unozt67tp"/><stop offset="1" class="nz401ub3w"/></radialGradient><radialGradient id="iVyOkxn" cx="0" cy="0" r="1" gradientTransform="matrix(5.8125 3.375 -3.94223 6.78939 1.5 12.412)" gradientUnits="userSpaceOnUse"><stop class="pftejx_lm"/><stop offset="1" class="plm0m3bld"/></radialGradient><radialGradient id="iKiw8Ub" cx="0" cy="0" r="1" gradientTransform="rotate(-34.848 33.716 7.355)scale(4.07441 1.13657)" gradientUnits="userSpaceOnUse"><stop class="iz_tr8bgj"/><stop offset=".784" class="c165olb4a"/></radialGradient><radialGradient id="ikR0tmb" cx="0" cy="0" r="1" gradientTransform="matrix(-5.45312 -2.87498 .5272 -.99997 30.969 20.913)" gradientUnits="userSpaceOnUse"><stop class="t16rbnb9f"/><stop offset=".909" class="c165olb4a"/></radialGradient><radialGradient id="icpuYBB" cx="0" cy="0" r="1" gradientTransform="rotate(-44.233 16.252 -3.427)scale(2.57588 1.45826)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="wk0eyunld"/></radialGradient><radialGradient id="iQpNXAb" cx="0" cy="0" r="1" gradientTransform="matrix(2.15625 -1 .56607 1.2206 19.594 8.725)" gradientUnits="userSpaceOnUse"><stop class="vc--wpv5i"/><stop offset="1" class="wk0eyunld"/></radialGradient><radialGradient id="innTrAb" cx="0" cy="0" r="1" gradientTransform="matrix(8.875 -8.44564 9.16934 9.63548 6.75 29.92)" gradientUnits="userSpaceOnUse"><stop class="abvyfhqcv"/><stop offset="1" class="kggd1cc2d"/></radialGradient><radialGradient id="iqYaQsv" cx="0" cy="0" r="1" gradientTransform="matrix(-4.20043 -6.4302 3.84816 -2.51376 21.926 28.087)" gradientUnits="userSpaceOnUse"><stop class="abvyfhqcv"/><stop offset=".644" class="kggd1cc2d"/></radialGradient><radialGradient id="in9hD9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 -5 6.33167 0 16.043 30.85)" gradientUnits="userSpaceOnUse"><stop class="mcv6jrbys"/><stop offset="1" class="cz5w9u6in"/></radialGradient><radialGradient id="ivp4Boy" cx="0" cy="0" r="1" gradientTransform="matrix(3.84375 -2.1875 .62071 1.09068 2.344 23.569)" gradientUnits="userSpaceOnUse"><stop class="iz_tr8bgj"/><stop offset=".832" class="c165olb4a"/></radialGradient><radialGradient id="ipK4dPt" cx="0" cy="0" r="1" gradientTransform="rotate(-147.433 18.303 7.443)scale(4.9346 1.40021)" gradientUnits="userSpaceOnUse"><stop class="iz_tr8bgj"/><stop offset=".832" class="c165olb4a"/></radialGradient><radialGradient id="iLMA6Ac" cx="0" cy="0" r="1" gradientTransform="rotate(-50.519 32.873 7.575)scale(9.19079 3.84482)" gradientUnits="userSpaceOnUse"><stop class="pce1w5a_j"/><stop offset=".953" class="c48b8f3sw"/></radialGradient><radialGradient id="iZoyKGe" cx="0" cy="0" r="1" gradientTransform="matrix(5.12496 -8.15628 4.25827 2.67566 6.47 29.07)" gradientUnits="userSpaceOnUse"><stop class="iz_tr8bgj"/><stop offset=".784" class="c165olb4a"/></radialGradient><radialGradient id="ileSqLe" cx="0" cy="0" r="1" gradientTransform="matrix(-7.6875 -7.87493 2.7831 -2.71686 26.656 28.538)" gradientUnits="userSpaceOnUse"><stop class="pce1w5a_j"/><stop offset=".953" class="c48b8f3sw"/></radialGradient><radialGradient id="i2bZ8Kc" cx="0" cy="0" r="1" gradientTransform="rotate(-125.91 20.396 7.812)scale(11.1891 4.60044)" gradientUnits="userSpaceOnUse"><stop class="iz_tr8bgj"/><stop offset=".815" class="c165olb4a"/></radialGradient><radialGradient id="iUfvfZb" cx="0" cy="0" r="1" gradientTransform="matrix(1.73438 2.42188 -3.03987 2.17694 13.797 25.381)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset=".589" class="ajx6-mbfo"/><stop offset=".747" class="z6-ovubwn"/></radialGradient><radialGradient id="ivw69eg" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 -.76562 1.26836 -1.00951 14.61 26.444)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset="1" class="yx-bms0gr"/></radialGradient><radialGradient id="ip9wdYd" cx="0" cy="0" r="1" gradientTransform="rotate(122.471 2.27 17.812)scale(3.05588 4.35358)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset=".589" class="ajx6-mbfo"/><stop offset=".747" class="z6-ovubwn"/></radialGradient><radialGradient id="i6bqZnb" cx="0" cy="0" r="1" gradientTransform="matrix(-.92188 .89062 -1.47543 -1.5272 17.734 25.678)" gradientUnits="userSpaceOnUse"><stop class="ew8h6t88b"/><stop offset="1" class="yx-bms0gr"/></radialGradient><radialGradient id="iezMKtU" cx="0" cy="0" r="1" gradientTransform="matrix(-1.7745 1.90138 -3.49291 -3.25981 16.454 20.948)" gradientUnits="userSpaceOnUse"><stop offset=".463" class="ueu24dben"/><stop offset=".956" class="vylhu7i4w"/></radialGradient><linearGradient id="inEdW8d" x1=".687" x2="12.438" y1="20.475" y2="15.912" gradientUnits="userSpaceOnUse"><stop class="pz8osybzb"/><stop offset=".492" class="cxb6zacre"/></linearGradient><linearGradient id="il2avNc" x1="30.5" x2="24.5" y1="27.787" y2="20.787" gradientUnits="userSpaceOnUse"><stop class="pz8osybzb"/><stop offset="1" class="cxb6zacre"/></linearGradient><linearGradient id="iVUVWac" x1="15.969" x2="15.969" y1="5.412" y2="13.725" gradientUnits="userSpaceOnUse"><stop class="pz8osybzb"/><stop offset="1" class="cxb6zacre"/></linearGradient><linearGradient id="iCRu3mb" x1="11.375" x2="9.25" y1="6.35" y2="9.1" gradientUnits="userSpaceOnUse"><stop class="ac6hf035l"/><stop offset="1" class="w19bcc5ck"/></linearGradient><linearGradient id="im91oce" x1="6.998" x2="8.125" y1="9.459" y2="9.412" gradientUnits="userSpaceOnUse"><stop class="awqtyhbpb"/><stop offset="1" class="wk0eyunld"/></linearGradient><linearGradient id="ijNcPlc" x1="26.063" x2="22.876" y1="8.287" y2="8.484" gradientUnits="userSpaceOnUse"><stop class="ac6hf035l"/><stop offset="1" class="w19bcc5ck"/></linearGradient><linearGradient id="iVt9bXq" x1="20.344" x2="21.155" y1="8.975" y2="7.335" gradientUnits="userSpaceOnUse"><stop offset=".275" class="awqtyhbpb"/><stop offset="1" class="wk0eyunld"/></linearGradient><linearGradient id="iXAM0od" x1="19.75" x2="11.625" y1="19.35" y2="29.921" gradientUnits="userSpaceOnUse"><stop class="paruexevs"/><stop offset="1" class="zyl6abgtz"/></linearGradient><linearGradient id="ikxrW9d" x1="2.063" x2="12.313" y1="31.537" y2="23.475" gradientUnits="userSpaceOnUse"><stop class="abvyfhqcv"/><stop offset="1" class="kggd1cc2d"/></linearGradient><linearGradient id="iHKMw3d" x1="16.043" x2="16.043" y1="31.35" y2="29.412" gradientUnits="userSpaceOnUse"><stop class="pce1w5a_j"/><stop offset="1" class="c48b8f3sw"/></linearGradient><linearGradient id="iRidOtb" x1="15.891" x2="15.188" y1="25.709" y2="26.725" gradientUnits="userSpaceOnUse"><stop class="z6-ovubwn"/><stop offset="1" class="fmxmxcb-i"/></linearGradient><linearGradient id="ixmi2Md" x1="12.714" x2="11.902" y1="15.493" y2="15.493" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iZYGu5M" x1="13.031" x2="13.031" y1="17.521" y2="15.928" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ik27xQd" x1="20.687" x2="19.875" y1="15.493" y2="15.493" gradientUnits="userSpaceOnUse"><stop offset=".225" class="dyysy0bzo"/><stop offset="1" class="u6_e1kz0i"/></linearGradient><linearGradient id="iS7fGGd" x1="21.004" x2="21.004" y1="17.521" y2="15.928" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="ia8vsqp" x1="17.649" x2="14.019" y1="19.823" y2="23.11" gradientUnits="userSpaceOnUse"><stop offset=".191" class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="iyuiKUd" x1="16.5" x2="16.5" y1="21.272" y2="19.288" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="iJQh9bc" x1="17.516" x2="17.516" y1="24.6" y2="21.6" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iHHeoqe" x1="24.469" x2="26.938" y1="17.506" y2="24.163" gradientUnits="userSpaceOnUse"><stop class="j0tv7kbkf"/><stop offset=".724" class="vo-0zu4ae"/></linearGradient><filter id="iUrO8DO" width="28.565" height="23.074" x="2" y="1.75" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset dx=".5" dy="-.25"/><feGaussianBlur stdDeviation=".375"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.4625 0 0 0 0 0.458646 0 0 0 0 0.458646 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_1901"/></filter><filter id="iNsfq5c" width="28.375" height="11.875" x="1.813" y="7.256" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation=".5"/></filter><filter id="iD6lXNe" width="2.906" height="4.362" x="10.308" y="13.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation=".375"/></filter><filter id="ihoML8d" width="2.906" height="4.362" x="18.362" y="13.537" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation=".375"/></filter><filter id="iLHHebc" width="8.813" height="7.375" x="5.844" y="2.131" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation=".5"/></filter><filter id="ipDfZYw" width="1.9" height="8.713" x="24.113" y="2.587" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation=".35"/></filter><filter id="i3fzuxY" width="11.625" height="17.656" x="19.625" y="8.225" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation="1"/></filter><filter id="iJLqHhb" width="1.539" height="1.539" x="11.512" y="13.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation=".25"/></filter><filter id="iMdFCCd" width="1.539" height="1.539" x="19.535" y="13.858" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation=".25"/></filter><filter id="iYx7tWd" width="2.066" height="2.174" x="16.448" y="20.231" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_1901" stdDeviation=".25"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:wolf" /></template>
<style>
.abvyfhqcv {
  stop-color: var(--svg-color--9890a0, #9890A0);
}

.ac6hf035l {
  stop-color: var(--svg-color--bab8bd, #BAB8BD);
}

.ajx6-mbfo {
  stop-color: var(--svg-color--4e4647, #4E4647);
}

.awqtyhbpb {
  stop-color: var(--svg-color--dcdbdd, #DCDBDD);
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b0bwj1s7d {
  width: 1.477px;
  height: 3.004px;
  x: 11.324px;
  y: 13.991px;
  rx: 0.738px;
}

.b38brsj_m {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m21.625 10.225l5 13.656l.906-2.656h1.282l-.875-2.625l1.312-.625l-3.875-6.25z");
}

.bupxplb6l {
  d: path("M29.978 17.96c-1.172-2.044-2.405-4.075-3.519-6.145a3.9 3.9 0 0 1-.454-1.82l-.027-7.324c.03-.59-.69-.9-1.09-.47l-7.07 5.4c-.27.21-.61.32-.95.32h-1.75c-.34 0-.68-.11-.95-.32l-7.07-5.4c-.4-.43-1.12-.12-1.09.47l-.026 7.493a3.8 3.8 0 0 1-.432 1.77c-1.08 2.046-2.313 4.022-3.462 6.027c-.25.43.06.96.56.96c.44 0 .75.43.61.85l-.44 1.3c-.14.41.17.84.6.85h.23c.44 0 .74.43.6.85l-.4 1.21c-.15.44.21.89.68.84l8.07-.89h6.85l8.07.89c.47.05.83-.4.68-.84l-.4-1.21c-.14-.41.17-.84.6-.85h.23c.44 0 .74-.43.6-.85l-.42-1.24c-.14-.42.14-.91.58-.9c.52 0 .84-.54.59-.97");
}

.c165olb4a {
  stop-color: var(--svg-color--634185, #634185);
  stop-opacity: 0;
}

.c48b8f3sw {
  stop-color: var(--svg-color--855cae, #855CAE);
  stop-opacity: 0;
}

.cxb6zacre {
  stop-color: var(--svg-color--747474, #747474);
  stop-opacity: 0;
}

.cz5w9u6in {
  stop-color: var(--svg-color--8a74a0, #8A74A0);
  stop-opacity: 0;
}

.dyysy0bzo {
  stop-color: var(--svg-color--594c4f, #594C4F);
}

.e-navhbzv {
  stroke-linecap: round;
  d: path("M16.048 24.82c0 1.45 1.17 2.62 2.62 2.62");
}

.e0fe4p6cu {
  d: path("M20.465 28.323L17.804 15.88l10.395 8.574c-.062.19-.287.41-.719.36c-.738-.086-3.743-.394-5.263-.584a.91.91 0 0 0-.99.71l-.68 3.18a3 3 0 0 1-.082.202");
}

.ectxvsb8q {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m28.25 24.105l-4.531-4.74l5.199 2.56a2 2 0 0 1-.277.019c-.96-.01-.83.81-.78.96l.364 1.079s.015.048.025.122");
}

.ew8h6t88b {
  stop-color: var(--svg-color--261317, #261317);
}

.fmxmxcb-i {
  stop-color: var(--svg-color--2f172a, #2F172A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.g82_46o6b {
  d: path("m19.43 8.647l5.129 2.157a2 2 0 0 1 .965.858l3.663 6.47H2.814l3.59-6.442a2 2 0 0 1 1.008-.884l5.51-2.195a5 5 0 0 1 1.85-.355h2.72a5 5 0 0 1 1.939.391");
}

.gkmqebcvd {
  width: 1.406px;
  height: 2.862px;
  x: 11.058px;
  y: 14.287px;
  fill: var(--svg-color--6b676e, #6B676E);
  rx: 0.703px;
}

.gvpwnu65w {
  d: path("m11.62 28.323l2.661-12.442l-10.433 8.554c.062.19.244.366.7.366c.64 0 3.8-.38 5.32-.57c.46-.05.89.25.99.71l.68 3.18q.038.103.082.202");
}

.h-m-91tnb {
  d: path("M14.098 29.92h3.89c1.15 0 2.17-.72 2.56-1.8l.68-3.18c.1-.46.53-.76.99-.71c1.52.19 4.384.48 5.259.589c.984.07.741-.858.741-.858l-.35-1.05c-.05-.15-.18-.97.78-.96c1.024.011.524-1.043.524-1.043l-4.734-1.997s-2.58-1.26-3.85.02l-2.92 2.94c-.06.07-.14.12-.22.17a3.06 3.06 0 0 1-1.405.37a3.06 3.06 0 0 1-1.405-.37c-.08-.05-.16-.1-.22-.17l-2.92-2.94c-1.27-1.28-3.85-.02-3.85-.02l-4.773 1.997s-.517 1.032.563 1.012c.96-.01.815.835.765.985l-.363 1.078s-.271.905.715.836c.703-.082 3.793-.398 5.313-.588c.46-.05.89.25.99.71l.68 3.18a2.72 2.72 0 0 0 2.56 1.8");
}

.ije5o1ywn {
  width: 1.477px;
  height: 3.004px;
  x: 19.296px;
  y: 13.991px;
  rx: 0.738px;
}

.iz_tr8bgj {
  stop-color: var(--svg-color--634185, #634185);
}

.j0tv7kbkf {
  stop-color: var(--svg-color--c2c1c3, #C2C1C3);
}

.j2kqk3swa {
  cx: 20.304px;
  cy: 14.627px;
  r: 0.27px;
  fill: var(--svg-color--635859, #635859);
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.kggd1cc2d {
  stop-color: var(--svg-color--9890a0, #9890A0);
  stop-opacity: 0;
}

.l6p2phbjw {
  cx: 17.481px;
  cy: 21.319px;
  fill: var(--svg-color--6a6566, #6A6566);
  rx: 0.502px;
  ry: 0.614px;
}

.le8k_dc3j {
  d: path("M24.438 10.17c.28.1.57-.11.57-.4l-.02-4.87c.02-.37-.44-.57-.69-.3l-4.28 3.27c-.27.21-.2.63.11.74z");
}

.mcv6jrbys {
  stop-color: var(--svg-color--9874bc, #9874BC);
}

.nh1amacwm {
  stroke: var(--svg-color--ccc9cc, #CCC9CC);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("M25.063 3.537v6.813");
}

.nz401ub3w {
  stop-color: var(--svg-color--848484, #848484);
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.paruexevs {
  stop-color: var(--svg-color--d7d3db, #D7D3DB);
}

.pce1w5a_j {
  stop-color: var(--svg-color--855cae, #855CAE);
}

.pe44dcyzd {
  d: path("M17.325 20.163H14.63c-.777 0-1.355.736-1.019 1.437a6.1 6.1 0 0 0 1.4 1.895c.584.53 1.475.48 2.037-.072a7 7 0 0 0 1.297-1.747c.377-.718-.208-1.513-1.019-1.513");
}

.pftejx_lm {
  stop-color: var(--svg-color--767575, #767575);
}

.plm0m3bld {
  stop-color: var(--svg-color--767575, #767575);
  stop-opacity: 0;
}

.pz8osybzb {
  stop-color: var(--svg-color--747474, #747474);
}

.r0pcmrmhn {
  stroke: var(--svg-color--ccc9cc, #CCC9CC);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-5px, 0.5px);
  d: path("m7.094 3.381l6.312 4.875");
}

.r5i0n2brg {
  fill-rule: evenodd;
  d: path("m2.872 20.913l4.206-3.125l-4.39 1.134a.644.644 0 0 1 .57.849z");
}

.syplem7tj {
  fill-opacity: var(--svg-fill-opacity--0-75, 0.75);
  d: path("m3.815 24.105l3.779-3.333l-4.369 1.137q.094.014.213.011c.96-.01.815.835.765.985l-.363 1.078s-.015.048-.025.122");
}

.t16rbnb9f {
  stop-color: var(--svg-color--351f4b, #351F4B);
}

.t36kbtyas {
  cx: 12.282px;
  cy: 14.627px;
  r: 0.27px;
  fill: var(--svg-color--635859, #635859);
}

.tca6arbgi {
  stroke-linecap: round;
  d: path("M16.025 24.82c0 1.45-1.17 2.62-2.62 2.62");
}

.tky7p0b8n {
  fill: var(--svg-color--d3d3d3, #D3D3D3);
  d: path("M24.438 10.17c.28.1.57-.11.57-.4l-.02-4.87c.02-.37-.44-.57-.69-.3l-4.28 3.27c-.27.21-.2.63.11.74z");
}

.ttuo2buhh {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("m29.18 20.913l-7.055-4.391l7.238 2.4c-.419.024-.672.47-.57.849z");
}

.u6_e1kz0i {
  stop-color: var(--svg-color--392833, #392833);
}

.ud5dprk-v {
  fill: var(--svg-color--d3d3d3, #D3D3D3);
  d: path("M7.568 10.17c-.28.1-.58-.11-.57-.4l.01-4.88c-.02-.37.44-.57.69-.29l4.28 3.27c.27.21.2.63-.11.74z");
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.unozt67tp {
  stop-color: var(--svg-color--b4b3b5, #B4B3B5);
}

.v8ik8wb2x {
  width: 1.406px;
  height: 2.862px;
  x: 19.112px;
  y: 14.287px;
  fill: var(--svg-color--6b676e, #6B676E);
  rx: 0.703px;
}

.vc--wpv5i {
  stop-color: var(--svg-color--fff, #fff);
}

.vo-0zu4ae {
  stop-color: var(--svg-color--d9d9d9, #D9D9D9);
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.w19bcc5ck {
  stop-color: var(--svg-color--bab8bd, #BAB8BD);
  stop-opacity: 0;
}

.wk0eyunld {
  stop-color: var(--svg-color--dcdbdd, #DCDBDD);
  stop-opacity: 0;
}

.yoj47oy4e {
  d: path("M7.568 10.17c-.28.1-.58-.11-.57-.4l.01-4.88c-.02-.37.44-.57.69-.29l4.28 3.27c.27.21.2.63-.11.74z");
}

.yx-bms0gr {
  stop-color: var(--svg-color--261317, #261317);
  stop-opacity: 0;
}

.z6-ovubwn {
  stop-color: var(--svg-color--2f172a, #2F172A);
}

.zyl6abgtz {
  stop-color: var(--svg-color--b7b1bc, #B7B1BC);
}

</style>
