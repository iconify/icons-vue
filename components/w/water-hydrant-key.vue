<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w_ke9i4lu"/><path class="k775g4biz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:water-hydrant-key" /></template>
<style>
.k775g4biz {
  d: path("m15.5 6.5l1.902 1.382l-.726 2.236h-2.352l-.726-2.236Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w_ke9i4lu {
  d: path("m15.5 3l5.231 3.8l-1.998 6.15h-6.466L10.269 6.8Zm-3.75 9.25L3.5 20.5m2.25-2.25l2 2m.5-4.5l1.5 1.5");
}

</style>
