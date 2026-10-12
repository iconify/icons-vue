<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><rect class="dhjtq6qyd"/><path class="b5lbygb_t"/><path class="em-7wkv2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:phone-brick" /></template>
<style>
.b5lbygb_t {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 5.5h4.5a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1h-4.5a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1");
}

.dhjtq6qyd {
  width: 11.5px;
  height: 18.5px;
  x: 6.25px;
  y: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  rx: 2.5px;
}

.em-7wkv2l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 14h.01M12 14h.01M15 14h.01M9 17.5h.01m2.99 0h.01m2.99 0h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
