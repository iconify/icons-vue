<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xiaawqbyt"/><path class="t9y85lbpz"/><path class="ozf7_rb1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:rss-line-duotone" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ozf7_rb1s {
  d: path("M4 4C12.8366 4 20 11.1634 20 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.t9y85lbpz {
  d: path("M4 12C8.4183 12 12 15.5817 12 20");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xiaawqbyt {
  d: path("M4 20H4.0001");
}

</style>
