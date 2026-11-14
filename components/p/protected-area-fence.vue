<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2vxv1hto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:protected-area-fence" /></template>
<style>
.l2vxv1hto {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 13a3.5 3.5 0 0 1-1.25-6.25a5 5 0 0 1 9.5-1A4 4 0 0 1 12.5 13ZM9 13v8.5m9-7.25l3.5 1.25V18c0 2-1.5 3.25-3.5 3.75c-2-.5-3.5-1.75-3.5-3.75v-2.5Z");
}

</style>
