<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="phpuw9rea"/><path class="d7mvynzai"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-columns-merge-previous-sharp-fill" /></template>
<style>
.d7mvynzai {
  d: path("M21 3L21 21L3 21L3 3L21 3ZM17 3L17 21M8 3L8 6M8 21L8 18M14 12L7 12M10.2929 8.7071L7 12L10.2929 15.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.phpuw9rea {
  fill: currentColor;
  d: path("M17 3L21 3L21 21L17 21L17 3Z");
  stroke: none;
}

</style>
