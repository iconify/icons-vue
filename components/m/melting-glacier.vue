<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwqa6_b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:melting-glacier" /></template>
<style>
.dwqa6_b8i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 5.25a2.5 2.5 0 0 1 2.5-2.5h7.5a2.5 2.5 0 0 1 2.5 2.5v6.5a1.5 1.5 0 0 1-3 0a1 1 0 0 0-2 0v2a1.5 1.5 0 0 1-3 0v-2a1 1 0 0 0-2 0a1.25 1.25 0 0 1-2.5 0Zm3 2.5l2.5-2.5m.5 12c.85 1.1 1.35 1.85 1.35 2.5a1.35 1.35 0 0 1-2.7 0c0-.65.5-1.4 1.35-2.5");
}

</style>
