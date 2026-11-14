<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mtqfx78sk"/><path class="obxv41bqt"/><path class="c969xj0nh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scan-progress" /></template>
<style>
.c969xj0nh {
  d: path("m7.5 9l4.5 2.5L16.5 9M12 11.5v6");
}

.mtqfx78sk {
  d: path("M2.5 12a9.5 9.5 0 1 1 9.5 9.5");
}

.obxv41bqt {
  d: path("M12 6.5L16.5 9v6L12 17.5L7.5 15V9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
