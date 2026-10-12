<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ctf3frbdz"/><path class="zw5t1zbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sprinkler" /></template>
<style>
.ctf3frbdz {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 21.25a5.75 5.75 0 0 1 11.5 0ZM12 15.5v-2.25M9.75 11L7 8.25m5 2v-4M14.25 11L17 8.25");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.zw5t1zbyy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.75 5.5h.01M12 3h.01m7.24 2.5h.01");
}

</style>
