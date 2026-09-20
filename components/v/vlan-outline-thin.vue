<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="x26a8iq1c"/><path class="i0evvabox"/><path class="ce69xy8qu"/><path class="m0h1krb4m"/><path class="waw_mpbxq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vlan-outline-thin" /></template>
<style>
.ce69xy8qu {
  d: path("M13 6.5A2.5 2.5 0 0 1 15.5 4h3A2.5 2.5 0 0 1 21 6.5 2.5 2.5 0 0 1 18.5 9h-3A2.5 2.5 0 0 1 13 6.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i0evvabox {
  d: path("M3 6.5A2.5 2.5 0 0 1 5.5 4h3A2.5 2.5 0 0 1 11 6.5 2.5 2.5 0 0 1 8.5 9h-3A2.5 2.5 0 0 1 3 6.5");
}

.m0h1krb4m {
  d: path("M3 17.5A2.5 2.5 0 0 1 5.5 15h3a2.5 2.5 0 0 1 2.5 2.5A2.5 2.5 0 0 1 8.5 20h-3A2.5 2.5 0 0 1 3 17.5");
}

.waw_mpbxq {
  d: path("M13 17.5a2.5 2.5 0 0 1 2.5 -2.5h3a2.5 2.5 0 0 1 2.5 2.5 2.5 2.5 0 0 1 -2.5 2.5h-3a2.5 2.5 0 0 1 -2.5 -2.5");
}

.x26a8iq1c {
  d: path("M2 12h20");
}

</style>
