<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="emhhm-4mf"/><path class="a7xbknbyy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:viewpoint" /></template>
<style>
.a7xbknbyy {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01");
}

.emhhm-4mf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.41 20.25l4.18-4.75q.66-.75 1.34-.02l1.64 1.79q.68.73 1.34-.02l2.43-2.75q.66-.75 1.31.01l4.95 5.73q.65.76-.35.76H3.75q-1 0-.34-.75M5 6.75C6.75 4.25 9.25 3 12 3s5.25 1.25 7 3.75c-1.75 2.5-4.25 3.75-7 3.75S6.75 9.25 5 6.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
