<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g class="ft5dv1b6b"><circle fill="url(#i9g5N2b)" class="hpfxxnbdm"/><circle fill="url(#ip6xsze)" class="hpfxxnbdm"/><path fill="url(#iM7sx4b)" clip-rule="evenodd" class="crkuqjm1o"/><path fill="url(#i5gPiec)" clip-rule="evenodd" class="wn0xkmras"/><path fill="url(#i0m6Fjd)" clip-rule="evenodd" class="wn0xkmras"/><path fill="url(#iEqB03b)" clip-rule="evenodd" class="wn0xkmras"/><path fill="url(#ihkDyBe)" clip-rule="evenodd" class="wn0xkmras"/><path fill="url(#ifWyLMf)" clip-rule="evenodd" class="rv8-1dbvp"/><path fill="url(#iqbNYoe)" clip-rule="evenodd" class="rv8-1dbvp"/><path fill="url(#iwkgcPO)" clip-rule="evenodd" class="rv8-1dbvp"/><path fill="url(#ilgisab)" clip-rule="evenodd" class="rv8-1dbvp"/><path fill="url(#itILYHY)" clip-rule="evenodd" class="rv8-1dbvp"/><path fill="url(#ibrdqWd)" clip-rule="evenodd" class="rv8-1dbvp"/><path fill="url(#if9HIec)" clip-rule="evenodd" class="rv8-1dbvp"/><g filter="url(#iVx4V9b)"><path fill="url(#i7PQOwc)" class="v-55yqbxz"/></g><defs><radialGradient id="i9g5N2b" cx="0" cy="0" r="1" gradientTransform="rotate(116.565 6.46 11.134)scale(15.7313 14.9746)" gradientUnits="userSpaceOnUse"><stop class="fs1yivtxj"/><stop offset="1" class="ml6xt0bbo"/></radialGradient><radialGradient id="ip6xsze" cx="0" cy="0" r="1" gradientTransform="rotate(129.632 6.974 11.228)scale(13.4104)" gradientUnits="userSpaceOnUse"><stop offset=".594" class="xdeh8ub_f"/><stop offset="1" class="u1jgqjbri"/></radialGradient><radialGradient id="iM7sx4b" cx="0" cy="0" r="1" gradientTransform="matrix(4.5625 1 -3.38747 15.45532 9.387 10.558)" gradientUnits="userSpaceOnUse"><stop class="sjpl5hbon"/><stop offset="1" class="i0i3f4byn"/></radialGradient><radialGradient id="i5gPiec" cx="0" cy="0" r="1" gradientTransform="matrix(-8.87078 7.41344 -6.98206 -8.3546 23.49 15.807)" gradientUnits="userSpaceOnUse"><stop class="c203s0ktk"/><stop offset="1" class="awrvih1gd"/><stop offset="1" class="awrvih1gd"/><stop offset="1" class="am-jpcbaz"/></radialGradient><radialGradient id="i0m6Fjd" cx="0" cy="0" r="1" gradientTransform="rotate(128.911 9.725 12.438)scale(6.66673 3.90395)" gradientUnits="userSpaceOnUse"><stop class="vbk7w3bbe"/><stop offset="1" class="nwppo0bwi"/></radialGradient><radialGradient id="iEqB03b" cx="0" cy="0" r="1" gradientTransform="matrix(.03125 -3.01989 5.43768 .05627 15.574 24.89)" gradientUnits="userSpaceOnUse"><stop class="y83hqtvxl"/><stop offset="1" class="a741nzbct"/></radialGradient><radialGradient id="ihkDyBe" cx="0" cy="0" r="1" gradientTransform="matrix(.9279 1.03497 -8.6877 7.78899 16.063 15.511)" gradientUnits="userSpaceOnUse"><stop class="j_xns3bqm"/><stop offset="1" class="y5kwqpb_y"/></radialGradient><radialGradient id="iqbNYoe" cx="0" cy="0" r="1" gradientTransform="matrix(4.90625 -5.53125 1.56027 1.38397 21.397 9.259)" gradientUnits="userSpaceOnUse"><stop offset=".101" class="srvf395wb"/><stop offset="1" class="d-lyvh0nv"/></radialGradient><radialGradient id="iwkgcPO" cx="0" cy="0" r="1" gradientTransform="matrix(5.6875 -3.75 1.9437 2.94793 19.272 8.197)" gradientUnits="userSpaceOnUse"><stop class="stizdi3lc"/><stop offset="1" class="uyzhocb_t"/></radialGradient><radialGradient id="ilgisab" cx="0" cy="0" r="1" gradientTransform="matrix(-.31253 -4.375 17.0735 -1.21965 7.428 28.29)" gradientUnits="userSpaceOnUse"><stop class="vz8zj3-lr"/><stop offset="1" class="s_6kinzzz"/></radialGradient><radialGradient id="itILYHY" cx="0" cy="0" r="1" gradientTransform="matrix(-1.85936 1.07814 -.2674 -.46116 7.756 24.384)" gradientUnits="userSpaceOnUse"><stop class="xexmelyhh"/><stop offset="1" class="m68bhihmt"/></radialGradient><radialGradient id="ibrdqWd" cx="0" cy="0" r="1" gradientTransform="rotate(124.301 -.91 12.83)scale(3.46478 .89354)" gradientUnits="userSpaceOnUse"><stop class="lgk3g4c3m"/><stop offset="1" class="bzbh2kbef"/></radialGradient><radialGradient id="if9HIec" cx="0" cy="0" r="1" gradientTransform="rotate(126.992 9.138 10.329)scale(5.86876 1.64082)" gradientUnits="userSpaceOnUse"><stop offset=".154" class="ceehwdp2n"/><stop offset="1" class="lxjgteo1z"/></radialGradient><linearGradient id="ifWyLMf" x1="15.366" x2="27.178" y1="13.79" y2="17.915" gradientUnits="userSpaceOnUse"><stop class="gu1yxib_q"/><stop offset="1" class="y2gqjhh8n"/></linearGradient><linearGradient id="i7PQOwc" x1="24.074" x2="17.387" y1="13.37" y2="19.526" gradientUnits="userSpaceOnUse"><stop class="nu1icgbyp"/><stop offset="1" class="rj0mk10ye"/></linearGradient><filter id="iVx4V9b" width="11.359" height="15.851" x="17.104" y="3.945" color-interpolation-filters="sRGB" filterUnits="userSpaceOnUse"><feFlood flood-opacity="0" result="BackgroundImageFix"/><feBlend in="SourceGraphic" in2="BackgroundImageFix" result="shape"/><feGaussianBlur result="effect1_foregroundBlur_18_14790" stdDeviation=".5"/></filter></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji:ringed-planet" /></template>
<style>
.a741nzbct {
  stop-color: var(--svg-color--c46867, #C46867);
  stop-opacity: 0;
}

.am-jpcbaz {
  stop-color: var(--svg-color--d4726b, #D4726B);
}

.awrvih1gd {
  stop-color: var(--svg-color--de7c60, #DE7C60);
}

.bzbh2kbef {
  stop-color: var(--svg-color--f1b338, #F1B338);
  stop-opacity: 0;
}

.c203s0ktk {
  stop-color: var(--svg-color--ffeac1, #FFEAC1);
}

.ceehwdp2n {
  stop-color: var(--svg-color--eca53b, #ECA53B);
}

.crkuqjm1o {
  fill-rule: evenodd;
  d: path("M7.177 15.29c1.156-.427 3.129-1.465 4.929-3.386c2.298-2.452 2.986-4.025 3.239-4.893a9.03 9.03 0 0 0-8.168 8.279");
}

.d-lyvh0nv {
  stop-color: var(--svg-color--f39d2b, #F39D2B);
  stop-opacity: 0;
}

.fs1yivtxj {
  stop-color: var(--svg-color--ffb455, #FFB455);
}

.ft5dv1b6b {
  fill: none;
}

.gu1yxib_q {
  stop-color: var(--svg-color--e6af22, #E6AF22);
}

.hpfxxnbdm {
  cx: 16.177px;
  cy: 16px;
  r: 9.027px;
}

.i0i3f4byn {
  stop-color: var(--svg-color--ffbc94, #FFBC94);
}

.j_xns3bqm {
  stop-color: var(--svg-color--ffbd91, #FFBD91);
}

.lgk3g4c3m {
  stop-color: var(--svg-color--f1d338, #F1D338);
}

.lxjgteo1z {
  stop-color: var(--svg-color--eca53b, #ECA53B);
  stop-opacity: 0;
}

.m68bhihmt {
  stop-color: var(--svg-color--e9af41, #E9AF41);
  stop-opacity: 0;
}

.ml6xt0bbo {
  stop-color: var(--svg-color--eb6a38, #EB6A38);
}

.nu1icgbyp {
  stop-color: var(--svg-color--ffef33, #FFEF33);
}

.nwppo0bwi {
  stop-color: var(--svg-color--ffe7c2, #FFE7C2);
  stop-opacity: 0;
}

.rj0mk10ye {
  stop-color: var(--svg-color--ffef33, #FFEF33);
  stop-opacity: 0;
}

.rv8-1dbvp {
  fill-rule: evenodd;
  d: path("M27.422 4.92c-.453-.527-1.061-.703-1.584-.718c-.496-.014-.99.109-1.425.264c-.875.312-1.86.884-2.812 1.522a37 37 0 0 0-2.197 1.608a9 9 0 0 1 2.451 1.399c.403-.3.804-.585 1.194-.848c.899-.602 1.67-1.03 2.237-1.232q.034-.013.067-.023c-.028.109-.07.247-.138.419c-.28.72-.84 1.661-1.632 2.754c-1.57 2.169-3.85 4.669-5.91 6.752c-1.995 2.02-4.713 4.43-7.095 6.17c-1.2.875-2.26 1.542-3.075 1.915q-.26.119-.451.185c.125-.34.362-.793.724-1.367c.393-.621.876-1.299 1.402-2.023a9 9 0 0 1-1.414-2.477l-.437.602l-.071.098c-.586.805-1.188 1.635-1.678 2.411c-.477.756-.924 1.574-1.12 2.35c-.2.802-.194 1.891.738 2.654c.59.484 1.298.504 1.802.435c.524-.07 1.069-.266 1.588-.504c1.05-.48 2.275-1.267 3.525-2.18c2.514-1.836 5.337-4.34 7.412-6.44c2.093-2.118 4.48-4.728 6.166-7.056c.836-1.154 1.55-2.308 1.95-3.338c.355-.914.678-2.29-.217-3.332");
}

.s_6kinzzz {
  stop-color: var(--svg-color--d08e28, #D08E28);
  stop-opacity: 0;
}

.sjpl5hbon {
  stop-color: var(--svg-color--d9957b, #D9957B);
}

.srvf395wb {
  stop-color: var(--svg-color--f39d2b, #F39D2B);
}

.stizdi3lc {
  stop-color: var(--svg-color--f19c20, #F19C20);
}

.u1jgqjbri {
  stop-color: var(--svg-color--cc5934, #CC5934);
}

.uyzhocb_t {
  stop-color: var(--svg-color--f19c20, #F19C20);
  stop-opacity: 0;
}

.v-55yqbxz {
  d: path("m26.307 9.117l-.21-.134zm-.77-4.126a.25.25 0 0 0 .12.486zm-7.091 13.805c1.65-1.546 5.782-5.947 8.072-9.545l-.422-.268c-2.258 3.549-6.358 7.917-7.992 9.448zm8.072-9.545c.956-1.502 1.115-2.636.796-3.387c-.325-.765-1.106-1.038-1.777-.873l.12.486c.468-.116.982.075 1.197.583c.222.522.166 1.47-.758 2.923z");
}

.vbk7w3bbe {
  stop-color: var(--svg-color--ffe7c2, #FFE7C2);
}

.vz8zj3-lr {
  stop-color: var(--svg-color--d08e28, #D08E28);
}

.wn0xkmras {
  fill-rule: evenodd;
  d: path("M25.047 14.315c-1.024 1.819-2.399 3.83-4.303 5.975c-1.53 1.723-3.79 3.288-6.144 4.6a9.02 9.02 0 0 1-5.295-3.035c2.072-1.223 4.372-2.973 6.87-5.52c3.158-3.222 4.874-5.945 5.511-7.486a9.03 9.03 0 0 1 3.36 5.466");
}

.xdeh8ub_f {
  stop-color: var(--svg-color--cc5934, #CC5934);
  stop-opacity: 0;
}

.xexmelyhh {
  stop-color: var(--svg-color--e9c441, #E9C441);
}

.y2gqjhh8n {
  stop-color: var(--svg-color--fffb4b, #FFFB4B);
}

.y5kwqpb_y {
  stop-color: var(--svg-color--ffbd91, #FFBD91);
  stop-opacity: 0;
}

.y83hqtvxl {
  stop-color: var(--svg-color--c46867, #C46867);
}

</style>
