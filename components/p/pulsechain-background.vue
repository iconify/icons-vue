<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGjBQZWa7h)" class="r4i437pya"/><path clip-rule="evenodd" class="cb-vt7bgd"/></g><defs><linearGradient id="SVGjBQZWa7h" x1="20.301" x2="3.101" y1="-1.138" y2="23.585" gradientUnits="userSpaceOnUse"><stop class="rlp60sb4c"/><stop offset=".253" class="g9cn6cb6i"/><stop offset=".497" class="ky-o6c4pf"/><stop offset=".75" class="q1a3ybc8v"/><stop offset=".999" class="la1q1sbut"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pulsechain-background" /></template>
<style>
.cb-vt7bgd {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M19.985 12.913q0 .125-.05.227l-3.425 6.388a.8.8 0 0 1-.704.438H8.198a.8.8 0 0 1-.705-.438L4.07 13.14a.5.5 0 0 1-.05-.226c0-.264.199-.478.444-.478H8.22l.952 1.742l.006.01c.127.22.394.291.603.16l.01-.008a.48.48 0 0 0 .194-.285l1.213-5.052l1.042 8.133l.002.011c.038.256.26.433.5.398l.01-.002a.46.46 0 0 0 .359-.353l1.462-6.089l.6 1.099l.007.01c.08.14.223.226.377.226h3.984c.245 0 .444.214.444.478M15.806 4.02c.29 0 .56.166.704.437l3.425 6.389q.05.102.05.226c0 .264-.199.479-.444.479h-3.77l-.952-1.742l-.006-.012a.45.45 0 0 0-.265-.209l-.01-.002c-.235-.06-.471.094-.532.346l-1.213 5.051l-1.042-8.132l-.001-.012a.47.47 0 0 0-.328-.386c-.237-.067-.48.087-.541.343l-1.463 6.09l-.6-1.1l-.006-.01a.44.44 0 0 0-.377-.225H4.463c-.245 0-.444-.215-.444-.479a.5.5 0 0 1 .049-.224l3.426-6.39a.8.8 0 0 1 .704-.438z");
}

.ft5dv1b6b {
  fill: none;
}

.g9cn6cb6i {
  stop-color: var(--svg-color--0080ff, #0080ff);
}

.ky-o6c4pf {
  stop-color: var(--svg-color--8000ff, #8000ff);
}

.la1q1sbut {
  stop-color: var(--svg-color--red, red);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q1a3ybc8v {
  stop-color: var(--svg-color--e619e6, #e619e6);
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rlp60sb4c {
  stop-color: var(--svg-color--00eaff, #00eaff);
}

</style>
