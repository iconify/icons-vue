<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="t2g51nbku"/><path class="jl2lv3vzy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:office-location-sharp" /></template>
<style>
.jl2lv3vzy {
  d: path("M9.25 9.75h6.25v4h-7v-4zm1.25 0v-2.5h3v2.5");
}

.t2g51nbku {
  d: path("M12 21.25h-.57l-.38-.38C8.1 18.1 4.75 14.4 4.75 10a7.25 7.25 0 0 1 14.5 0c0 4.4-3.35 8.1-6.3 10.87l-.38.38z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
