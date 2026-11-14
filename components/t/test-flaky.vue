<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbw85_bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:test-flaky" /></template>
<style>
.fbw85_bse {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.318 15.439l2.121-2.121a3 3 0 0 1 4.243 0a3 3 0 0 1 0 4.243l-2.121 2.121a3 3 0 0 1-4.243 0a3 3 0 0 1 0-4.243m9-9l2.121-2.121a3 3 0 0 1 4.243 0a3 3 0 0 1 0 4.243l-2.121 2.121a3 3 0 0 1-4.243 0a3 3 0 0 1 0-4.243M16 16l2 2M8 8L6 6");
}

</style>
