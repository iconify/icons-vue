<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path class="ni8alac1u"/><path fill="url(#iOTM7Ae)" class="cspsl8w-s"/><path fill="url(#iH0GZAc)" class="cspsl8w-s"/><path fill="url(#i2sZGWc)" class="cspsl8w-s"/><path fill="url(#ii88mBc)" class="cspsl8w-s"/><path class="aobgkmbfl"/><path fill="url(#irYAzPb)" class="j7q_u5bav"/><path fill="url(#iDMArEb)" class="j7q_u5bav"/><path fill="url(#i4piFvb)" class="j7q_u5bav"/><path clip-rule="evenodd" class="qj7ezibni"/><path fill="url(#iSgWwnd)" clip-rule="evenodd" class="hhpqh1bgc"/><path fill="url(#i1pFaSf)" clip-rule="evenodd" class="hhpqh1bgc"/><path fill="url(#iQbhf0d)" clip-rule="evenodd" class="hhpqh1bgc"/><path fill="url(#iauMGvd)" class="l5abf2t0x"/><path fill="url(#iT7h51b)" class="ekyo_3bxs"/><path fill="url(#iOi2Wmb)" class="l5abf2t0x"/><path fill="url(#iIipEtb)" class="bx01npd4c"/><path fill="url(#i7Sgnjb)" class="bx01npd4c"/><path fill="url(#iKSByHb)" class="bx01npd4c"/><path fill="url(#iQnsu8I)" class="bx01npd4c"/><path fill="url(#inOOXeb)" class="bx01npd4c"/><path class="s2p9csbxm"/><path fill="url(#iBVoeBe)" class="ac-n8k96v"/><path fill="url(#ixgORLl)" class="ac-n8k96v"/><path fill="url(#i5PoXBH)" class="ac-n8k96v"/><path class="z5iirsbgb"/><path fill="url(#igJfTDc)" class="q996081qd"/><path fill="url(#iKItIrc)" class="q996081qd"/><path fill="url(#iLToLSd)" class="q996081qd"/><path fill="url(#iX1Gasg)" class="q996081qd"/><path class="t-d40jwyj"/><path fill="url(#i2XsvNc)" class="mbqz1dbtf"/><path fill="url(#i1aHvib)" class="mbqz1dbtf"/><path fill="url(#iKRCFco)" class="mbqz1dbtf"/><path fill="url(#iCWp8pa)" class="mbqz1dbtf"/><path fill="url(#iswYHJb)" clip-rule="evenodd" class="whqf16bzx"/><path fill="url(#iAaIkNb)" clip-rule="evenodd" class="xu2jckbua"/><path fill="url(#iQHffVd)" clip-rule="evenodd" class="whqf16bzx"/><defs><radialGradient id="iOTM7Ae" cx="0" cy="0" r="1" gradientTransform="rotate(140.243 5.727 12.99)scale(18.8614 12.1767)" gradientUnits="userSpaceOnUse"><stop offset=".798" class="wrfga0bmr"/><stop offset="1" class="zscrl6bgl"/></radialGradient><radialGradient id="iH0GZAc" cx="0" cy="0" r="1" gradientTransform="rotate(116.131 -1.836 11.091)scale(11.0689 6.33986)" gradientUnits="userSpaceOnUse"><stop offset=".11" class="ouvaoca2l"/><stop offset="1" class="xbcgp-qsp"/></radialGradient><radialGradient id="i2sZGWc" cx="0" cy="0" r="1" gradientTransform="matrix(0 2 -3.98 0 19.688 6.563)" gradientUnits="userSpaceOnUse"><stop offset=".19" class="ly71i6b2o"/><stop offset="1" class="l16s-xb5o"/></radialGradient><radialGradient id="ii88mBc" cx="0" cy="0" r="1" gradientTransform="matrix(-4.1875 4.62499 -4.6409 -4.20192 2.75 27.688)" gradientUnits="userSpaceOnUse"><stop class="q0jdmhbos"/><stop offset="1" class="onwqrlbzi"/></radialGradient><radialGradient id="irYAzPb" cx="0" cy="0" r="1" gradientTransform="matrix(-4.0625 5.5 -5.07343 -3.74743 8.063 16.563)" gradientUnits="userSpaceOnUse"><stop offset=".113" class="ko491wjme"/><stop offset="1" class="trnh8vb_a"/></radialGradient><radialGradient id="iDMArEb" cx="0" cy="0" r="1" gradientTransform="matrix(2.3125 2.8125 -2.60843 2.14471 4 27.125)" gradientUnits="userSpaceOnUse"><stop offset=".271" class="ir4p8hb6d"/><stop offset="1" class="sffudqb6y"/></radialGradient><radialGradient id="i4piFvb" cx="0" cy="0" r="1" gradientTransform="rotate(125.311 9.84 10)scale(7.35272)" gradientUnits="userSpaceOnUse"><stop offset=".314" class="vjbod2awr"/><stop offset="1" class="k4gj5xf7p"/></radialGradient><radialGradient id="i1pFaSf" cx="0" cy="0" r="1" gradientTransform="matrix(2.375 3.90235 -.8681 .52833 4.344 27.191)" gradientUnits="userSpaceOnUse"><stop offset=".556" class="d6xbzc7kc"/><stop offset=".952" class="pfyp1gb0t"/></radialGradient><radialGradient id="iQbhf0d" cx="0" cy="0" r="1" gradientTransform="rotate(146.524 9.182 6.748)scale(4.64565 4.59069)" gradientUnits="userSpaceOnUse"><stop class="g4y4zpbie"/><stop offset="1" class="tob-eub5i"/></radialGradient><radialGradient id="iauMGvd" cx="0" cy="0" r="1" gradientTransform="matrix(-4.71875 4.65624 -3.44485 -3.4911 11.438 19.875)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="htfw7_bpx"/><stop offset=".485" class="h7bd9gr6i"/><stop offset=".829" class="ddldaeqeh"/></radialGradient><radialGradient id="iOi2Wmb" cx="0" cy="0" r="1" gradientTransform="matrix(-10 12.31246 -8.69762 -7.06408 9.063 18.063)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="g1kq9-tng"/><stop offset=".526" class="z39blhnii"/></radialGradient><radialGradient id="iIipEtb" cx="0" cy="0" r="1" gradientTransform="matrix(-12.9298 14.05267 -9.90767 -9.116 16.742 15.75)" gradientUnits="userSpaceOnUse"><stop offset=".204" class="oqyy10ymb"/><stop offset=".45" class="z3j4v8v1k"/><stop offset=".687" class="io7haug0z"/></radialGradient><radialGradient id="i7Sgnjb" cx="0" cy="0" r="1" gradientTransform="matrix(-15.81255 16.4863 -.69852 -.66998 16.031 17.42)" gradientUnits="userSpaceOnUse"><stop offset=".158" class="g0ja5sbwu"/><stop offset=".819" class="nlqapmb7z"/></radialGradient><radialGradient id="iKSByHb" cx="0" cy="0" r="1" gradientTransform="matrix(.4375 6.4375 -2.6836 .18238 26.125 10.25)" gradientUnits="userSpaceOnUse"><stop offset=".592" class="sosr_9bue"/><stop offset="1" class="k8wl7mbgy"/></radialGradient><radialGradient id="iQnsu8I" cx="0" cy="0" r="1" gradientTransform="rotate(131.513 -3.947 15.024)scale(6.17652 6.19184)" gradientUnits="userSpaceOnUse"><stop class="o82htgbtt"/><stop offset="1" class="onwqrlbzi"/></radialGradient><radialGradient id="inOOXeb" cx="0" cy="0" r="1" gradientTransform="matrix(9.18752 19.68745 -34.21192 15.96564 8.312 9.688)" gradientUnits="userSpaceOnUse"><stop offset=".768" class="t0m1kebny"/><stop offset=".852" class="xny9crb0h"/></radialGradient><radialGradient id="iBVoeBe" cx="0" cy="0" r="1" gradientTransform="rotate(139.946 13.682 7.093)scale(4.61337)" gradientUnits="userSpaceOnUse"><stop offset=".123" class="b8wedti-v"/><stop offset=".677" class="h14-pmboe"/></radialGradient><radialGradient id="ixgORLl" cx="0" cy="0" r="1" gradientTransform="matrix(-1.28124 1.0625 -1.9389 -2.33808 25.531 4.125)" gradientUnits="userSpaceOnUse"><stop offset=".453" class="xrjt6r5-w"/><stop offset=".76" class="wnvv6e90f"/></radialGradient><radialGradient id="i5PoXBH" cx="0" cy="0" r="1" gradientTransform="matrix(-.90624 1.09375 -2.27115 -1.8818 27 5.156)" gradientUnits="userSpaceOnUse"><stop class="v8qlrz3vz"/><stop offset="1" class="a08wb7zvl"/></radialGradient><radialGradient id="igJfTDc" cx="0" cy="0" r="1" gradientTransform="matrix(.53126 6.53907 -3.22542 .26204 28.281 8.563)" gradientUnits="userSpaceOnUse"><stop class="va8ufnb-v"/><stop offset=".294" class="vb1tu8blb"/><stop offset="1" class="ir_n1eb2c"/></radialGradient><radialGradient id="iKItIrc" cx="0" cy="0" r="1" gradientTransform="matrix(.92969 5.875 -2.82098 .4464 26.063 14.25)" gradientUnits="userSpaceOnUse"><stop class="yi0ywz64e"/><stop offset="1" class="cxqkc-bec"/></radialGradient><radialGradient id="iLToLSd" cx="0" cy="0" r="1" gradientTransform="matrix(1.5 17.9961 -9.65583 .80483 28.656 10.066)" gradientUnits="userSpaceOnUse"><stop offset=".266" class="exz-abcnw"/><stop offset=".431" class="uip8nzayz"/></radialGradient><radialGradient id="iX1Gasg" cx="0" cy="0" r="1" gradientTransform="matrix(-1.57812 1.89063 -.87529 -.7306 26.328 5.578)" gradientUnits="userSpaceOnUse"><stop offset=".307" class="dih1nwvxw"/><stop offset=".823" class="qhid52bbd"/></radialGradient><radialGradient id="i2XsvNc" cx="0" cy="0" r="1" gradientTransform="matrix(-.5 3.9375 -7.13513 -.90605 25.063 4.438)" gradientUnits="userSpaceOnUse"><stop offset=".103" class="zmp84izhm"/><stop offset="1" class="rcbaceb0m"/></radialGradient><radialGradient id="i1aHvib" cx="0" cy="0" r="1" gradientTransform="matrix(-.1875 2.75 -8.82558 -.60175 21.125 8.25)" gradientUnits="userSpaceOnUse"><stop class="nvkxvab-g"/><stop offset="1" class="xphu5c_3p"/></radialGradient><radialGradient id="iKRCFco" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.66113 -3.13086 0 16.943 4.999)" gradientUnits="userSpaceOnUse"><stop class="jj_5yu73l"/><stop offset="1" class="d6gbn8g5h"/></radialGradient><radialGradient id="iCWp8pa" cx="0" cy="0" r="1" gradientTransform="matrix(-.375 .9375 -1.76575 -.70629 26.063 3.438)" gradientUnits="userSpaceOnUse"><stop class="b5qooibdp"/><stop offset="1" class="friom6b3q"/></radialGradient><radialGradient id="iswYHJb" cx="0" cy="0" r="1" gradientTransform="matrix(-3.7792 4.78941 -3.09865 -2.44506 18.092 12.687)" gradientUnits="userSpaceOnUse"><stop offset=".125" class="htfw7_bpx"/><stop offset=".485" class="h7bd9gr6i"/><stop offset=".829" class="ddldaeqeh"/></radialGradient><radialGradient id="iQHffVd" cx="0" cy="0" r="1" gradientTransform="rotate(128.703 5.312 9.314)scale(14.7464 10.3871)" gradientUnits="userSpaceOnUse"><stop offset=".352" class="g1kq9-tng"/><stop offset=".526" class="z39blhnii"/></radialGradient><linearGradient id="iSgWwnd" x1="4.688" x2="22.625" y1="26.688" y2="7.625" gradientUnits="userSpaceOnUse"><stop class="zg38hhb9n"/><stop offset=".263" class="i951few5x"/><stop offset=".648" class="byk76xbtv"/><stop offset="1" class="j2r3-dbyb"/></linearGradient><linearGradient id="iT7h51b" x1="12.281" x2="10.688" y1="21.625" y2="20.063" gradientUnits="userSpaceOnUse"><stop offset=".25" class="pomfuubgb"/><stop offset="1" class="elu454_gr"/></linearGradient><linearGradient id="iAaIkNb" x1="18.87" x2="17.381" y1="14.323" y2="12.883" gradientUnits="userSpaceOnUse"><stop offset=".25" class="pomfuubgb"/><stop offset="1" class="elu454_gr"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:pea-pod" /></template>
<style>
.a08wb7zvl {
  stop-color: var(--svg-color--97e061, #97E061);
  stop-opacity: 0;
}

.ac-n8k96v {
  d: path("M30 5a3 3 0 0 1-.794 2.033l.339 1.692a6 6 0 0 1-.739 4.264l-.949 1.582a1 1 0 0 1-1.715 0l-.949-1.582a6 6 0 0 1-.738-4.264l.295-1.475l-1.476.295a6 6 0 0 1-4.263-.738l-1.582-.95a1 1 0 0 1 0-1.714l1.582-.95a6 6 0 0 1 4.263-.738l1.693.338A3 3 0 0 1 30 5");
}

.aobgkmbfl {
  fill: var(--svg-color--1b3e25, #1B3E25);
  d: path("M9.5 14c-3.878 4.46-5.049 9.22-5.38 11.132c-.094.55.107 1.095.501 1.49c.756.755 1.987.74 2.724-.034L26 7l-1-1S14.5 8.25 9.5 14");
}

.b5qooibdp {
  stop-color: var(--svg-color--62bd0a, #62BD0A);
}

.b8wedti-v {
  stop-color: var(--svg-color--97de61, #97DE61);
}

.bx01npd4c {
  d: path("M5.485 29.803C8.692 29.298 16.35 27.652 21.001 23c7-7 7-18 7-18c-2.062 2.047-7.248 7.494-12.587 13.078A1963 1963 0 0 0 7.36 26.57c-.458.487-1.21.696-1.68.61c-1 .879-1.83 1.587-2.374 2.062c1.093.813 2.18.561 2.18.561");
}

.byk76xbtv {
  stop-color: var(--svg-color--5ea556, #5EA556);
}

.cspsl8w-s {
  d: path("M8.5 12.5c-4.952 5.282-6.13 11.512-6.412 14.18c-.089.846.25 1.658.851 2.259c.673.672 1.606 1.012 2.546.864C8.69 29.298 16.349 27.652 21 23c7-7 7-18 7-18l-1-1S15 5.567 8.5 12.5");
}

.cxqkc-bec {
  stop-color: var(--svg-color--7ab445, #7AB445);
  stop-opacity: 0;
}

.d6gbn8g5h {
  stop-color: var(--svg-color--7ea32e, #7EA32E);
  stop-opacity: 0;
}

.d6xbzc7kc {
  stop-color: var(--svg-color--76b86b, #76B86B);
}

.ddldaeqeh {
  stop-color: var(--svg-color--396607, #396607);
}

.dih1nwvxw {
  stop-color: var(--svg-color--9ae465, #9AE465);
}

.ekyo_3bxs {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M15 21a4 4 0 1 1-8 0a4 4 0 0 1 8 0");
}

.elu454_gr {
  stop-color: var(--svg-color--538312, #538312);
  stop-opacity: 0;
}

.exz-abcnw {
  stop-color: var(--svg-color--74b633, #74B633);
  stop-opacity: 0;
}

.friom6b3q {
  stop-color: var(--svg-color--62bd0a, #62BD0A);
  stop-opacity: 0;
}

.ft5dv1b6b {
  fill: none;
}

.g0ja5sbwu {
  stop-color: var(--svg-color--397e23, #397E23);
}

.g1kq9-tng {
  stop-color: var(--svg-color--487a00, #487A00);
  stop-opacity: 0;
}

.g4y4zpbie {
  stop-color: var(--svg-color--4a794a, #4A794A);
}

.h14-pmboe {
  stop-color: var(--svg-color--5cb808, #5CB808);
}

.h7bd9gr6i {
  stop-color: var(--svg-color--77a80f, #77A80F);
}

.hhpqh1bgc {
  fill-rule: evenodd;
  d: path("M19.65 8.31c-3.229 1.272-7.012 3.236-9.432 6.018c-3.796 4.366-4.942 9.028-5.264 10.89c-.064.37.069.757.362 1.05c.557.558 1.561.787 2.105.216c-.5.703-1.974 1.025-2.718.282c-.495-.496-.775-1.156-.65-1.883c.34-1.963 1.451-6.658 5.41-11.21c2.58-2.968 6.547-5.004 9.82-6.294a45 45 0 0 1 4.203-1.418a37 37 0 0 1 1.717-.442l.024-.005l.006-.002h.002l.106.488l.105.49h-.006l-.021.005a12 12 0 0 0-.42.099c-.292.071-.716.18-1.24.329a44 44 0 0 0-4.11 1.386");
}

.htfw7_bpx {
  stop-color: var(--svg-color--94c74e, #94C74E);
}

.i951few5x {
  stop-color: var(--svg-color--61a75d, #61A75D);
}

.io7haug0z {
  stop-color: var(--svg-color--5fa05f, #5FA05F);
}

.ir_n1eb2c {
  stop-color: var(--svg-color--7cc936, #7CC936);
  stop-opacity: 0;
}

.ir4p8hb6d {
  stop-color: var(--svg-color--255a2e, #255A2E);
}

.j2r3-dbyb {
  stop-color: var(--svg-color--61a358, #61A358);
}

.j7q_u5bav {
  d: path("M9.5 14c-3.878 4.46-5.049 9.22-5.38 11.132c-.094.55.107 1.095.501 1.49c.756.755 1.987.74 2.724-.034L26 7l-1-1S14.5 8.25 9.5 14");
}

.jj_5yu73l {
  stop-color: var(--svg-color--7ea32e, #7EA32E);
}

.k4gj5xf7p {
  stop-color: var(--svg-color--0e3615, #0E3615);
  stop-opacity: 0;
}

.k8wl7mbgy {
  stop-color: var(--svg-color--4f9244, #4F9244);
  stop-opacity: 0;
}

.ko491wjme {
  stop-color: var(--svg-color--1f5f29, #1F5F29);
}

.l16s-xb5o {
  stop-color: var(--svg-color--427d33, #427D33);
  stop-opacity: 0;
}

.l5abf2t0x {
  d: path("M15 21a4 4 0 1 1-8 0a4 4 0 0 1 8 0");
}

.ly71i6b2o {
  stop-color: var(--svg-color--2d6a17, #2D6A17);
}

.mbqz1dbtf {
  d: path("m24.75 7.25l-1.476.295a6 6 0 0 1-4.263-.739l-1.582-.949a1 1 0 0 1 0-1.715l1.582-.95a6 6 0 0 1 4.263-.738l1.693.339c.674.16 1.96 1.35 2.002 2.207c.031.656-1.407 2.078-2.22 2.25");
}

.ni8alac1u {
  fill: var(--svg-color--559b40, #559B40);
  d: path("M8.5 12.5c-4.952 5.282-6.13 11.512-6.412 14.18c-.089.846.25 1.658.851 2.259c.673.672 1.606 1.012 2.546.864C8.69 29.298 16.349 27.652 21 23c7-7 7-18 7-18l-1-1S15 5.567 8.5 12.5");
}

.nlqapmb7z {
  stop-color: var(--svg-color--559439, #559439);
  stop-opacity: 0;
}

.nvkxvab-g {
  stop-color: var(--svg-color--73a34d, #73A34D);
}

.o82htgbtt {
  stop-color: var(--svg-color--528348, #528348);
}

.onwqrlbzi {
  stop-color: var(--svg-color--4e7d45, #4E7D45);
  stop-opacity: 0;
}

.oqyy10ymb {
  stop-color: var(--svg-color--63a863, #63A863);
}

.ouvaoca2l {
  stop-color: var(--svg-color--739242, #739242);
}

.pfyp1gb0t {
  stop-color: var(--svg-color--76b86b, #76B86B);
  stop-opacity: 0;
}

.pomfuubgb {
  stop-color: var(--svg-color--518213, #518213);
}

.q0jdmhbos {
  stop-color: var(--svg-color--4e7d45, #4E7D45);
}

.q996081qd {
  d: path("m29.239 7.254l.31 1.473a5.96 5.96 0 0 1-.71 4.27l-.943 1.59a1.013 1.013 0 0 1-1.73.014l-.971-1.574a5.96 5.96 0 0 1-.781-4.257l.327-1.696c.156-.675 1.345-1.972 2.21-2.02c.662-.037 2.108 1.388 2.288 2.2");
}

.qhid52bbd {
  stop-color: var(--svg-color--9ae465, #9AE465);
  stop-opacity: 0;
}

.qj7ezibni {
  fill: var(--svg-color--63a860, #63A860);
  fill-rule: evenodd;
  d: path("M19.65 8.31c-3.229 1.272-7.012 3.236-9.432 6.018c-3.796 4.366-4.942 9.028-5.264 10.89c-.064.37.069.757.362 1.05c.557.558 1.561.787 2.105.216c-.5.703-1.974 1.025-2.718.282c-.495-.496-.775-1.156-.65-1.883c.34-1.963 1.451-6.658 5.41-11.21c2.58-2.968 6.547-5.004 9.82-6.294a45 45 0 0 1 4.203-1.418a37 37 0 0 1 1.717-.442l.024-.005l.006-.002h.002l.106.488l.105.49h-.006l-.021.005a12 12 0 0 0-.42.099c-.292.071-.716.18-1.24.329a44 44 0 0 0-4.11 1.386");
}

.rcbaceb0m {
  stop-color: var(--svg-color--7ac430, #7AC430);
  stop-opacity: 0;
}

.s2p9csbxm {
  fill: var(--svg-color--8dd753, #8DD753);
  d: path("M30 5a3 3 0 0 1-.794 2.033l.339 1.692a6 6 0 0 1-.739 4.264l-.949 1.582a1 1 0 0 1-1.715 0l-.949-1.582a6 6 0 0 1-.738-4.264l.295-1.475l-1.476.295a6 6 0 0 1-4.263-.738l-1.582-.95a1 1 0 0 1 0-1.714l1.582-.95a6 6 0 0 1 4.263-.738l1.693.338A3 3 0 0 1 30 5");
}

.sffudqb6y {
  stop-color: var(--svg-color--255a2e, #255A2E);
  stop-opacity: 0;
}

.sosr_9bue {
  stop-color: var(--svg-color--336b2b, #336B2B);
}

.t-d40jwyj {
  fill: var(--svg-color--72b325, #72B325);
  d: path("m24.75 7.25l-1.476.295a6 6 0 0 1-4.263-.739l-1.582-.949a1 1 0 0 1 0-1.715l1.582-.95a6 6 0 0 1 4.263-.738l1.693.339c.674.16 1.96 1.35 2.002 2.207c.031.656-1.407 2.078-2.22 2.25");
}

.t0m1kebny {
  stop-color: var(--svg-color--609765, #609765);
  stop-opacity: 0;
}

.tob-eub5i {
  stop-color: var(--svg-color--559752, #559752);
  stop-opacity: 0;
}

.trnh8vb_a {
  stop-color: var(--svg-color--10481b, #10481B);
  stop-opacity: 0;
}

.uip8nzayz {
  stop-color: var(--svg-color--569614, #569614);
}

.v8qlrz3vz {
  stop-color: var(--svg-color--97e061, #97E061);
}

.va8ufnb-v {
  stop-color: var(--svg-color--9eeb66, #9EEB66);
}

.vb1tu8blb {
  stop-color: var(--svg-color--8edd4a, #8EDD4A);
}

.vjbod2awr {
  stop-color: var(--svg-color--0e3615, #0E3615);
}

.whqf16bzx {
  fill-rule: evenodd;
  d: path("M21.377 11.855a4 4 0 1 0-5.355 5.623z");
}

.wnvv6e90f {
  stop-color: var(--svg-color--87d34c, #87D34C);
  stop-opacity: 0;
}

.wrfga0bmr {
  stop-color: var(--svg-color--6b9562, #6B9562);
  stop-opacity: 0;
}

.xbcgp-qsp {
  stop-color: var(--svg-color--739242, #739242);
  stop-opacity: 0;
}

.xny9crb0h {
  stop-color: var(--svg-color--7b7c93, #7B7C93);
}

.xphu5c_3p {
  stop-color: var(--svg-color--73a34d, #73A34D);
  stop-opacity: 0;
}

.xrjt6r5-w {
  stop-color: var(--svg-color--87d34c, #87D34C);
}

.xu2jckbua {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  fill-rule: evenodd;
  d: path("M21.377 11.855a4 4 0 1 0-5.355 5.623z");
}

.yi0ywz64e {
  stop-color: var(--svg-color--74a34e, #74A34E);
}

.z39blhnii {
  stop-color: var(--svg-color--487a00, #487A00);
}

.z3j4v8v1k {
  stop-color: var(--svg-color--5fa95b, #5FA95B);
}

.z5iirsbgb {
  fill: var(--svg-color--73b530, #73B530);
  d: path("m29.239 7.254l.31 1.473a5.96 5.96 0 0 1-.71 4.27l-.943 1.59a1.013 1.013 0 0 1-1.73.014l-.971-1.574a5.96 5.96 0 0 1-.781-4.257l.327-1.696c.156-.675 1.345-1.972 2.21-2.02c.662-.037 2.108 1.388 2.288 2.2");
}

.zg38hhb9n {
  stop-color: var(--svg-color--4ba335, #4BA335);
}

.zmp84izhm {
  stop-color: var(--svg-color--97dd61, #97DD61);
}

.zscrl6bgl {
  stop-color: var(--svg-color--6b9562, #6B9562);
}

</style>
