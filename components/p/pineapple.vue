<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="udffosbas"/><path class="zwlicbbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pineapple" /></template>
<style>
.udffosbas {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 15a5.5 6.25 0 1 0 11 0a5.5 6.25 0 1 0-11 0M12 8.75V3.5m0 5.25l-3.5-3.5m3.5 3.5l3.5-3.5");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zwlicbbhm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 12h.01M9.5 15h.01m4.99 0h.01M12 18h.01");
}

</style>
