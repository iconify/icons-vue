<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="jjqurebpy"/><path class="ef3axhsdk"/><path class="ro3t6fcmg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reindeer" /></template>
<style>
.ef3axhsdk {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.2 11.25c-1.75-.5-3.25 0-4 1c1.25.75 2.75.75 4 .25Zm7.6 0c1.75-.5 3.25 0 4 1c-1.25.75-2.75.75-4 .25Z");
}

.jjqurebpy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 9c2.5 0 4 1.75 4 4.5c0 3.5-2 7.75-4 7.75S8 17 8 13.5C8 10.75 9.5 9 12 9m-2 .25c-1-2-2.5-3-4.5-3.5m2.1.75l.15-3.75m-2.25 3L3 3.5m11 5.75c1-2 2.5-3 4.5-3.5m-2.1.75l-.15-3.75m2.25 3L21 3.5");
}

.ro3t6fcmg {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 13h.01m2.99 0h.01M12 17h.01");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
