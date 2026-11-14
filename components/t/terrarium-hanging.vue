<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="pyavkbb5a"/><path class="f2t26jkgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:terrarium-hanging" /></template>
<style>
.f2t26jkgg {
  d: path("M12 14.75c0-1.75 1.25-2.5 3-2.5c0 1.75-1.25 2.5-3 2.5M12 16c0-1.75-1.25-2.75-3-2.75C9 15 10.25 16 12 16");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pyavkbb5a {
  d: path("M10.5 3.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0M12 5v2m.782.478l7.2 4.4a1.5 1.5 0 0 1 .641 1.754l-2.281 6.842a1.5 1.5 0 0 1-1.423 1.026H7.081a1.5 1.5 0 0 1-1.423-1.026l-2.281-6.842a1.5 1.5 0 0 1 .641-1.754l7.2-4.4a1.5 1.5 0 0 1 1.564 0M12 18.75v-4");
}

</style>
