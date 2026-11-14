<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a88uu03mv"/><path class="q71_nnwus"/><path class="vm1z6pbjb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sell-through-rate" /></template>
<style>
.a88uu03mv {
  d: path("M12 2.5A9.5 9.5 0 1 1 2.5 12");
}

.q71_nnwus {
  d: path("M12 6.5L16.75 9v6L12 17.5L7.25 15V9Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vm1z6pbjb {
  d: path("M7.25 9L12 11.5L16.75 9M12 11.5v6");
}

</style>
