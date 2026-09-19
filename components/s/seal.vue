<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><path fill="url(#iqXcGfb)" class="im4k4wbeq"/><path fill="url(#i0wrJAe)" class="im4k4wbeq"/><path fill="url(#iJdMsYm)" class="jojtf81hb"/><path fill="url(#iZu1VKc)" class="jojtf81hb"/><path fill="url(#ixgk0ac)" class="jojtf81hb"/><path fill="url(#iOj8G9c)" class="jojtf81hb"/><path fill="url(#iXoHHBe)" class="jojtf81hb"/><path fill="url(#iGy7kuc)" class="jojtf81hb"/><path fill="url(#ixCLQLc)" class="jojtf81hb"/><path fill="url(#i7Mx1jd)" class="jojtf81hb"/><path fill="url(#i7tvY5d)" class="jojtf81hb"/><path fill="url(#imm2bae)" class="jojtf81hb"/><path fill="url(#iUhaFBb)" class="jojtf81hb"/><path fill="url(#iWEZyxj)" class="ga1atdbqu"/><g filter="url(#iNr5AMe)"><path class="cc4_7ab7n"/></g><g filter="url(#iuhKdHT)"><path fill="url(#iNBLIey)" class="dasjr4jbv"/></g><g filter="url(#iQiocpc)"><path class="c7y8u1ssi"/><path fill="url(#i91IIae)" class="nbzzwwyav"/><path fill="url(#i3JdFDb)" class="nbzzwwyav"/><path fill="url(#iS4ukue)" class="nbzzwwyav"/></g><path fill="url(#ikZmdVd)" class="ilqk26bpk"/><path fill="url(#ijGYHZb)" class="ilqk26bpk"/><path fill="url(#iRsWepe)" class="nbzzwwyav"/><path fill="url(#iy3PHqd)" class="nbzzwwyav"/><path fill="url(#ivF4hAh)" class="owjv_xb3f"/><path fill="url(#i3cLHKd)" class="owjv_xb3f"/><path fill="url(#i0PnRSc)" class="owjv_xb3f"/><path fill="url(#iyqSXSd)" class="owjv_xb3f"/><path fill="url(#iHtKiQe)" class="owjv_xb3f"/><path fill="url(#ihVrIXd)" class="zfhn-ib-s"/><path fill="url(#ideYuwc)" class="zfhn-ib-s"/><path fill="url(#iUB9Lnn)" class="zfhn-ib-s"/><path fill="url(#ifXO86a)" class="dlifdqowc"/><path fill="url(#iS9yxXc)" class="dlifdqowc"/><path fill="url(#ijvbx9b)" class="dlifdqowc"/><path fill="url(#ikXKzBd)" class="vtx_5nbuk"/><path fill="url(#inKLdbe)" class="b0keufdgp"/><path fill="url(#iIxzYFb)" class="e5yj9vyxw"/><path fill="url(#i73lNtJ)" class="e5yj9vyxw"/><path fill="url(#i8D4yce)" class="e5yj9vyxw"/><path fill="url(#itSXhsd)" class="fpu213vrl"/><path fill="url(#iBr6nmc)" class="fpu213vrl"/><path fill="url(#iwxwTrb)" class="fpu213vrl"/><g filter="url(#iZk8E9g)"><path stroke="url(#ivZ6sVb)" class="d1fpo0bga"/></g><defs><radialGradient id="iJdMsYm" cx="0" cy="0" r="1" gradientTransform="matrix(-4.37487 14.0625 -14.2848 -4.44402 18.063 19.438)" gradientUnits="userSpaceOnUse"><stop offset=".024" class="hmu70zbin"/><stop offset="1" class="izykdjq5g"/></radialGradient><radialGradient id="iOj8G9c" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.3125 -5.3125 0 20.188 13.625)" gradientUnits="userSpaceOnUse"><stop offset=".59" class="w2drymbqb"/><stop offset="1" class="qa5_nvryz"/></radialGradient><radialGradient id="iXoHHBe" cx="0" cy="0" r="1" gradientTransform="matrix(3.68752 -4.06249 5.71523 5.1877 6.687 28.625)" gradientUnits="userSpaceOnUse"><stop class="f_0rbeadi"/><stop offset="1" class="rpxr4cc6c"/></radialGradient><radialGradient id="iGy7kuc" cx="0" cy="0" r="1" gradientTransform="matrix(0 -4.5 9.66892 0 17.875 30.188)" gradientUnits="userSpaceOnUse"><stop offset=".041" class="f_0rbeadi"/><stop offset="1" class="rpxr4cc6c"/></radialGradient><radialGradient id="ixCLQLc" cx="0" cy="0" r="1" gradientTransform="matrix(7.875 15.8753 -20.0077 9.9249 16.375 13.125)" gradientUnits="userSpaceOnUse"><stop offset=".836" class="rpxr4cc6c"/><stop offset="1" class="f_0rbeadi"/></radialGradient><radialGradient id="i7Mx1jd" cx="0" cy="0" r="1" gradientTransform="matrix(0 6.21875 -1.34375 0 28.063 11.188)" gradientUnits="userSpaceOnUse"><stop offset=".427" class="i5mqi3b2h"/><stop offset="1" class="r4im828xy"/></radialGradient><radialGradient id="i7tvY5d" cx="0" cy="0" r="1" gradientTransform="matrix(0 7.875 -1.41444 0 26.063 10)" gradientUnits="userSpaceOnUse"><stop class="br1fn6nhz"/><stop offset="1" class="felfr8b_g"/></radialGradient><radialGradient id="imm2bae" cx="0" cy="0" r="1" gradientTransform="matrix(0 1.76562 -1.29355 0 27.86 11.078)" gradientUnits="userSpaceOnUse"><stop class="r6rakr-iw"/><stop offset="1" class="y1pztrbfn"/></radialGradient><radialGradient id="iUhaFBb" cx="0" cy="0" r="1" gradientTransform="rotate(101.901 10.82 17.21)scale(3.86431 1.19838)" gradientUnits="userSpaceOnUse"><stop class="zi73z7b7l"/><stop offset=".52" class="pxi468b1k"/></radialGradient><radialGradient id="iWEZyxj" cx="0" cy="0" r="1" gradientTransform="matrix(0 2.0625 -4.0625 0 9.031 8.625)" gradientUnits="userSpaceOnUse"><stop class="fp3alf6vp"/><stop offset=".519" class="aojkp-mii"/><stop offset="1" class="aojkp-mii"/></radialGradient><radialGradient id="i91IIae" cx="0" cy="0" r="1" gradientTransform="matrix(-1.4375 1.21875 -1.00128 -1.181 11.313 15.047)" gradientUnits="userSpaceOnUse"><stop class="vy39f9qzx"/><stop offset="1" class="l7pz9hbeq"/></radialGradient><radialGradient id="i3JdFDb" cx="0" cy="0" r="1" gradientTransform="matrix(.875 -2.0625 3.42339 1.45234 6.563 17.219)" gradientUnits="userSpaceOnUse"><stop class="uq6dvv9qc"/><stop offset="1" class="wd4uqyb7q"/></radialGradient><radialGradient id="iS4ukue" cx="0" cy="0" r="1" gradientTransform="matrix(-.51562 .58396 -.76726 -.67748 7.844 15.156)" gradientUnits="userSpaceOnUse"><stop class="du1goepkf"/><stop offset="1" class="os48sbcvl"/></radialGradient><radialGradient id="ikZmdVd" cx="0" cy="0" r="1" gradientTransform="matrix(-1.46876 2.85937 -2.71794 -1.39611 11.156 14.438)" gradientUnits="userSpaceOnUse"><stop offset=".472" class="wd4uqyb7q"/><stop offset="1" class="uq6dvv9qc"/></radialGradient><radialGradient id="iRsWepe" cx="0" cy="0" r="1" gradientTransform="matrix(.45313 -1.375 2.36064 .77794 7.125 18.078)" gradientUnits="userSpaceOnUse"><stop class="qz5kmw16p"/><stop offset="1" class="n2wyfeg7d"/></radialGradient><radialGradient id="iy3PHqd" cx="0" cy="0" r="1" gradientTransform="rotate(-102.947 12.316 4.823)scale(1.39483 2.39469)" gradientUnits="userSpaceOnUse"><stop class="qz5kmw16p"/><stop offset="1" class="n2wyfeg7d"/></radialGradient><radialGradient id="iyqSXSd" cx="0" cy="0" r="1" gradientTransform="matrix(3.43598 -1.00245 .39757 1.3627 6.832 15.25)" gradientUnits="userSpaceOnUse"><stop offset=".828" class="lm-pdjb-m"/><stop offset=".935" class="z17z3-a-u"/></radialGradient><radialGradient id="iHtKiQe" cx="0" cy="0" r="1" gradientTransform="matrix(-.53122 .31521 -.17946 -.30245 9.454 14.47)" gradientUnits="userSpaceOnUse"><stop class="xbybj_nwx"/><stop offset="1" class="unvvv2nza"/></radialGradient><radialGradient id="ihVrIXd" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -.75223 -.54329 11.293 12.97)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="ideYuwc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 .36328 -.3196 -.35053 11.35 13.023)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="ifXO86a" cx="0" cy="0" r="1" gradientTransform="matrix(-.60938 .84374 -.75223 -.54329 6.283 12.97)" gradientUnits="userSpaceOnUse"><stop offset=".006" class="c4ldw6bcc"/><stop offset="1" class="e9_rv-bpy"/></radialGradient><radialGradient id="iS9yxXc" cx="0" cy="0" r="1" gradientTransform="matrix(-.39844 .36328 -.3196 -.35053 6.34 13.023)" gradientUnits="userSpaceOnUse"><stop class="baf63sd8y"/><stop offset="1" class="hdqm2hb9u"/></radialGradient><radialGradient id="i73lNtJ" cx="0" cy="0" r="1" gradientTransform="rotate(122.856 1.526 16.43)scale(5.35689 6.33721)" gradientUnits="userSpaceOnUse"><stop offset=".78" class="u-8umwdrz"/><stop offset="1" class="crtxnkbhr"/></radialGradient><radialGradient id="i8D4yce" cx="0" cy="0" r="1" gradientTransform="matrix(-.78125 .54687 -1.14826 -1.64037 17.094 27.266)" gradientUnits="userSpaceOnUse"><stop class="jflbgbb0x"/><stop offset="1" class="v1sog0blq"/></radialGradient><radialGradient id="itSXhsd" cx="0" cy="0" r="1" gradientTransform="rotate(85.497 -5.675 13.523)scale(7.14216 8.18302)" gradientUnits="userSpaceOnUse"><stop class="kfc2c1b7h"/><stop offset="1" class="htcu-gvqd"/></radialGradient><radialGradient id="iBr6nmc" cx="0" cy="0" r="1" gradientTransform="rotate(144.219 2.765 15.966)scale(4.27577 4.51285)" gradientUnits="userSpaceOnUse"><stop class="tea0ok9hh"/><stop offset="1" class="ykxldabhl"/></radialGradient><radialGradient id="iwxwTrb" cx="0" cy="0" r="1" gradientTransform="rotate(-117.446 14.927 13.728)scale(10.9836 8.04444)" gradientUnits="userSpaceOnUse"><stop class="tea0ok9hh"/><stop offset="1" class="ykxldabhl"/></radialGradient><linearGradient id="iqXcGfb" x1="5.728" x2="4.313" y1="26.583" y2="28.995" gradientUnits="userSpaceOnUse"><stop class="gsrl8khfy"/><stop offset="1" class="u60k-qfkn"/></linearGradient><linearGradient id="i0wrJAe" x1="4.453" x2="4.453" y1="29.093" y2="28.453" gradientUnits="userSpaceOnUse"><stop class="j16stps8f"/><stop offset="1" class="jmf7cvb3j"/></linearGradient><linearGradient id="iZu1VKc" x1="6.625" x2="10.938" y1="19.75" y2="19.75" gradientUnits="userSpaceOnUse"><stop class="b1pderb3x"/><stop offset="1" class="ig2sw2bfs"/></linearGradient><linearGradient id="ixgk0ac" x1="18.875" x2="18.875" y1="30.5" y2="24.75" gradientUnits="userSpaceOnUse"><stop class="kz1r6ob7p"/><stop offset="1" class="jd8y68m5i"/></linearGradient><linearGradient id="iNBLIey" x1="9.469" x2="6.375" y1="17.745" y2="15.063" gradientUnits="userSpaceOnUse"><stop class="ynf67fbjj"/><stop offset="1" class="m8mxhvbnu"/></linearGradient><linearGradient id="ijGYHZb" x1="8.5" x2="8.805" y1="16.219" y2="16.219" gradientUnits="userSpaceOnUse"><stop class="c1f5m555l"/><stop offset="1" class="foc4y2bdk"/></linearGradient><linearGradient id="ivF4hAh" x1="8.228" x2="8.53" y1="14.219" y2="15.484" gradientUnits="userSpaceOnUse"><stop class="p6vd50w9p"/><stop offset="1" class="fwtna0oas"/></linearGradient><linearGradient id="i3cLHKd" x1="8.374" x2="8.374" y1="14.469" y2="13.631" gradientUnits="userSpaceOnUse"><stop offset=".147" class="ueu24dben"/><stop offset=".873" class="vylhu7i4w"/></linearGradient><linearGradient id="i0PnRSc" x1="7.885" x2="7.885" y1="15.873" y2="14.607" gradientUnits="userSpaceOnUse"><stop class="aztbnnbvp"/><stop offset="1" class="jqmybnbeu"/></linearGradient><linearGradient id="iUB9Lnn" x1="10.923" x2="10.407" y1="12.621" y2="12.293" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ijvbx9b" x1="5.913" x2="5.397" y1="12.621" y2="12.293" gradientUnits="userSpaceOnUse"><stop class="hdqm2hb9u"/><stop offset="1" class="baf63sd8y"/></linearGradient><linearGradient id="ikXKzBd" x1="20.188" x2="18.25" y1="19.75" y2="17.51" gradientUnits="userSpaceOnUse"><stop class="qzooa0bqp"/><stop offset="1" class="rrws99fgw"/></linearGradient><linearGradient id="inKLdbe" x1="22.625" x2="24.71" y1="18.351" y2="20.631" gradientUnits="userSpaceOnUse"><stop class="c1f5m555l"/><stop offset="1" class="uyu1xlbpu"/></linearGradient><linearGradient id="iIxzYFb" x1="16.844" x2="14.938" y1="25.625" y2="30.469" gradientUnits="userSpaceOnUse"><stop class="anziebbxa"/><stop offset="1" class="ry0iw-rhr"/></linearGradient><linearGradient id="ivZ6sVb" x1="17.641" x2="16.953" y1="28.266" y2="25.157" gradientUnits="userSpaceOnUse"><stop class="kn8qe168j"/><stop offset="1" class="g9p4hxtbv"/></linearGradient><filter id="iNr5AMe" width="20.298" height="17.73" x="6.702" y="7.688" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5909" stdDeviation="1.5"/></filter><filter id="iuhKdHT" width="7.25" height="4.409" x="4.719" y="13.836" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5909" stdDeviation=".25"/></filter><filter id="iQiocpc" width="6.38" height="3.48" x="5.37" y="14" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feColorMatrix in="SourceAlpha" result="hardAlpha" values="0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 127 0"/><feOffset/><feGaussianBlur stdDeviation=".2"/><feComposite in2="hardAlpha" k2="-1" k3="1" operator="arithmetic"/><feColorMatrix values="0 0 0 0 0.52549 0 0 0 0 0.517647 0 0 0 0 0.529412 0 0 0 1 0"/><feBlend in2="shape" result="effect1_innerShadow_28327_5909"/></filter><filter id="iZk8E9g" width="2.499" height="3.241" x="15.911" y="25.404" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_28327_5909" stdDeviation=".125"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:seal" /></template>
<style>
.anziebbxa {
  stop-color: var(--svg-color--b7b3bb, #B7B3BB);
}

.aojkp-mii {
  stop-color: var(--svg-color--b3b3b3, #B3B3B3);
  stop-opacity: 0;
}

.aztbnnbvp {
  stop-color: var(--svg-color--552d52, #552D52);
}

.b0keufdgp {
  d: path("M23.57 20.63a1.14 1.14 0 1 0 0-2.28a1.14 1.14 0 0 0 0 2.28");
}

.b1pderb3x {
  stop-color: var(--svg-color--949296, #949296);
}

.baf63sd8y {
  stop-color: var(--svg-color--5c5051, #5C5051);
}

.br1fn6nhz {
  stop-color: var(--svg-color--cac8cc, #CAC8CC);
}

.c1f5m555l {
  stop-color: var(--svg-color--96939a, #96939A);
}

.c4ldw6bcc {
  stop-color: var(--svg-color--433437, #433437);
}

.c7y8u1ssi {
  fill: var(--svg-color--97959a, #97959A);
  d: path("M10.02 14H7.11a1.741 1.741 0 0 0 0 3.48c.473 0 .897-.186 1.209-.488a.36.36 0 0 1 .483 0a1.741 1.741 0 0 0 2.948-1.25A1.727 1.727 0 0 0 10.02 14");
}

.cc4_7ab7n {
  fill: var(--svg-color--d5d1d9, #D5D1D9);
  d: path("M15.063 21.438c-3.106-1.965-4.947-5.147-5.353-9.063c-.096-.928.672-1.687 1.605-1.687c.944 0 1.718.772 1.814 1.71c.215 2.098.82 5.223 2.184 6.54c3.611 3.49 7.331 1.332 8.687-.906c-1.094 4.343-5.75 5.423-8.937 3.406");
}

.crtxnkbhr {
  stop-color: var(--svg-color--79658c, #79658C);
}

.d1fpo0bga {
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-1px, 0.1px);
  d: path("M16.234 25.704c-.109.734.1 2.403 1.875 2.64");
}

.dasjr4jbv {
  d: path("M9.774 14.336h-2.85a1.706 1.706 0 0 0 0 3.409c.597 0 1.116-.304 1.42-.764c.303.46.832.764 1.42.764c.94 0 1.705-.764 1.705-1.705a1.69 1.69 0 0 0-1.695-1.704");
}

.dlifdqowc {
  d: path("M6.06 13.96a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.du1goepkf {
  stop-color: var(--svg-color--9d97a3, #9D97A3);
}

.e5yj9vyxw {
  d: path("M16.62 26.5c0 .82.67 1.49 1.49 1.49c.28 0 .5.22.5.5s-.22.5-.5.5h-2.49a4.01 4.01 0 0 1-4.01-4.01v-2.72l5.01 1.802z");
}

.e9_rv-bpy {
  stop-color: var(--svg-color--3b2838, #3B2838);
}

.f_0rbeadi {
  stop-color: var(--svg-color--79638d, #79638D);
}

.felfr8b_g {
  stop-color: var(--svg-color--cac8cc, #CAC8CC);
  stop-opacity: 0;
}

.foc4y2bdk {
  stop-color: var(--svg-color--96939a, #96939A);
  stop-opacity: 0;
}

.fp3alf6vp {
  stop-color: var(--svg-color--b3b3b3, #B3B3B3);
}

.fpu213vrl {
  d: path("M11.61 24.98v-3.76c0-1.67-1.32-3.07-2.99-3.1a3.046 3.046 0 0 0-3.1 3.04v1.58c0 3.43 2.76 6.22 6.19 6.25h3.92c-2.22 0-4.02-1.8-4.02-4.01");
}

.ft5dv1b6b {
  fill: none;
}

.fwtna0oas {
  stop-color: var(--svg-color--2e2127, #2E2127);
}

.g9p4hxtbv {
  stop-color: var(--svg-color--bfbbc8, #BFBBC8);
  stop-opacity: 0;
}

.ga1atdbqu {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M11.78 29C6.38 29 2 24.62 2 19.22v-4.64C2 11 4.86 8.03 8.44 8a6.5 6.5 0 0 1 6.54 6c.25 2.25 2.21 4 4.52 4h.13c2.45-.07 4.37-2.12 4.37-4.56v-2.31a.92.92 0 0 1 1.33-.82c.505.25.929.638 1.223 1.114a.53.53 0 0 0 .447.264c.184 0 .35-.107.447-.264a3 3 0 0 1 1.223-1.114a.916.916 0 0 1 1.33.82v3.75c0 7.71-4.29 14.13-12 14.12z");
}

.gsrl8khfy {
  stop-color: var(--svg-color--5e5369, #5E5369);
}

.hdqm2hb9u {
  stop-color: var(--svg-color--5c5051, #5C5051);
  stop-opacity: 0;
}

.hmu70zbin {
  stop-color: var(--svg-color--c3bdca, #C3BDCA);
}

.htcu-gvqd {
  stop-color: var(--svg-color--c7bdd3, #C7BDD3);
}

.i5mqi3b2h {
  stop-color: var(--svg-color--97929c, #97929C);
}

.ig2sw2bfs {
  stop-color: var(--svg-color--949296, #949296);
  stop-opacity: 0;
}

.ilqk26bpk {
  d: path("M8.563 16.704V14h1.457c.96 0 1.74.78 1.73 1.74c0 .96-.78 1.74-1.74 1.74a1.74 1.74 0 0 1-1.447-.776");
}

.im4k4wbeq {
  d: path("M3.945 26.745v-3.742H7.97v4.026c0 1.263-1.938 1.966-2.735 1.966H2.531c-.187 0-.531-.125-.531-.5s.393-.535.587-.535c.789 0 1.358-.459 1.358-1.215");
}

.izykdjq5g {
  stop-color: var(--svg-color--9f9ea0, #9F9EA0);
}

.j16stps8f {
  stop-color: var(--svg-color--78638c, #78638C);
}

.jd8y68m5i {
  stop-color: var(--svg-color--89789a, #89789A);
  stop-opacity: 0;
}

.jflbgbb0x {
  stop-color: var(--svg-color--bcb9c2, #BCB9C2);
}

.jmf7cvb3j {
  stop-color: var(--svg-color--78638c, #78638C);
  stop-opacity: 0;
}

.jojtf81hb {
  d: path("M11.78 29C6.38 29 2 24.62 2 19.22v-4.64C2 11 4.86 8.03 8.44 8a6.5 6.5 0 0 1 6.54 6c.25 2.25 2.21 4 4.52 4h.13c2.45-.07 4.37-2.12 4.37-4.56v-2.31a.92.92 0 0 1 1.33-.82c.505.25.929.638 1.223 1.114a.53.53 0 0 0 .447.264c.184 0 .35-.107.447-.264a3 3 0 0 1 1.223-1.114a.916.916 0 0 1 1.33.82v3.75c0 7.71-4.29 14.13-12 14.12z");
}

.jqmybnbeu {
  stop-color: var(--svg-color--552d52, #552D52);
  stop-opacity: 0;
}

.kfc2c1b7h {
  stop-color: var(--svg-color--aea6b7, #AEA6B7);
}

.kn8qe168j {
  stop-color: var(--svg-color--dbd3eb, #DBD3EB);
}

.kz1r6ob7p {
  stop-color: var(--svg-color--89789a, #89789A);
}

.l7pz9hbeq {
  stop-color: var(--svg-color--c8c5cb, #C8C5CB);
  stop-opacity: 0;
}

.lm-pdjb-m {
  stop-color: var(--svg-color--5c5458, #5C5458);
  stop-opacity: 0;
}

.m8mxhvbnu {
  stop-color: var(--svg-color--7d7981, #7D7981);
}

.n2wyfeg7d {
  stop-color: var(--svg-color--88749b, #88749B);
  stop-opacity: 0;
}

.nbzzwwyav {
  d: path("M10.02 14H7.11a1.741 1.741 0 0 0 0 3.48c.473 0 .897-.186 1.209-.488a.36.36 0 0 1 .483 0a1.741 1.741 0 0 0 2.948-1.25A1.727 1.727 0 0 0 10.02 14");
}

.os48sbcvl {
  stop-color: var(--svg-color--9d97a3, #9D97A3);
  stop-opacity: 0;
}

.owjv_xb3f {
  d: path("m8.19 15.65l-.8-.66a.56.56 0 0 1 .36-.99h1.63a.56.56 0 0 1 .36.99l-.8.66c-.22.18-.53.18-.75 0");
}

.p6vd50w9p {
  stop-color: var(--svg-color--5f5254, #5F5254);
}

.pxi468b1k {
  stop-color: var(--svg-color--c9c7ca, #C9C7CA);
  stop-opacity: 0;
}

.qa5_nvryz {
  stop-color: var(--svg-color--99979d, #99979D);
  stop-opacity: 0;
}

.qz5kmw16p {
  stop-color: var(--svg-color--88749b, #88749B);
}

.qzooa0bqp {
  stop-color: var(--svg-color--9b9b9b, #9B9B9B);
}

.r4im828xy {
  stop-color: var(--svg-color--97929c, #97929C);
  stop-opacity: 0;
}

.r6rakr-iw {
  stop-color: var(--svg-color--8b888d, #8B888D);
}

.rpxr4cc6c {
  stop-color: var(--svg-color--79638d, #79638D);
  stop-opacity: 0;
}

.rrws99fgw {
  stop-color: var(--svg-color--9f9fa1, #9F9FA1);
}

.ry0iw-rhr {
  stop-color: var(--svg-color--938a9e, #938A9E);
}

.tea0ok9hh {
  stop-color: var(--svg-color--886ba0, #886BA0);
}

.u-8umwdrz {
  stop-color: var(--svg-color--79658c, #79658C);
  stop-opacity: 0;
}

.u60k-qfkn {
  stop-color: var(--svg-color--7c7089, #7C7089);
}

.ueu24dben {
  stop-color: var(--svg-color--34222c, #34222C);
  stop-opacity: 0;
}

.unvvv2nza {
  stop-color: var(--svg-color--6a5c5e, #6A5C5E);
  stop-opacity: 0;
}

.uq6dvv9qc {
  stop-color: var(--svg-color--877e91, #877E91);
}

.uyu1xlbpu {
  stop-color: var(--svg-color--adaab2, #ADAAB2);
}

.v1sog0blq {
  stop-color: var(--svg-color--bcb9c2, #BCB9C2);
  stop-opacity: 0;
}

.vtx_5nbuk {
  d: path("M19.03 20.35c1.03 0 1.86-.83 1.86-1.86c0-.24-.05-.47-.13-.67q-.54.165-1.14.18h-.13c-.74 0-1.43-.18-2.05-.49c-.18.29-.28.62-.28.98c.01 1.03.84 1.86 1.87 1.86");
}

.vy39f9qzx {
  stop-color: var(--svg-color--c8c5cb, #C8C5CB);
}

.vylhu7i4w {
  stop-color: var(--svg-color--34222c, #34222C);
}

.w2drymbqb {
  stop-color: var(--svg-color--99979d, #99979D);
}

.wd4uqyb7q {
  stop-color: var(--svg-color--877e91, #877E91);
  stop-opacity: 0;
}

.xbybj_nwx {
  stop-color: var(--svg-color--6a5c5e, #6A5C5E);
}

.y1pztrbfn {
  stop-color: var(--svg-color--8b888d, #8B888D);
  stop-opacity: 0;
}

.ykxldabhl {
  stop-color: var(--svg-color--886ba0, #886BA0);
  stop-opacity: 0;
}

.ynf67fbjj {
  stop-color: var(--svg-color--6a5b79, #6A5B79);
}

.z17z3-a-u {
  stop-color: var(--svg-color--5c5458, #5C5458);
}

.zfhn-ib-s {
  d: path("M11.07 13.96a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5");
}

.zi73z7b7l {
  stop-color: var(--svg-color--c9c7ca, #C9C7CA);
}

</style>
