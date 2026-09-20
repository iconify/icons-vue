<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="m3h3jkbkg"/><path class="u_au86g1g"/><path class="asgcu0ibt"/><path class="q9qa0ibgm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:mana-background" /></template>
<style>
.asgcu0ibt {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 14.284a8.4 8.4 0 0 0 1.064 1.713h10.43v-1.713zM15.813 12v5.137H20z");
}

.ft5dv1b6b {
  fill: none;
}

.m3h3jkbkg {
  fill: var(--svg-color--ffc95b, #ffc95b);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.q9qa0ibgm {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.63 17.137h4.182V12zm4.183-7.192a2.283 2.283 0 1 0 0-4.566a2.283 2.283 0 0 0 0 4.566M9.516 6.292a1.141 1.141 0 1 0 0-2.283a1.141 1.141 0 0 0 0 2.283");
}

.u_au86g1g {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.516 7.435v6.85h5.9zM4 14.284h5.516v-6.85zm2.89 3.994a9.5 9.5 0 0 0 5.48 1.713a9.5 9.5 0 0 0 5.48-1.713z");
}

</style>
