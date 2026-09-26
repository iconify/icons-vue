<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="j0mppdb_k"/><path class="cjpys8beh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-navigation-sharp" /></template>
<style>
.cjpys8beh {
  d: path("M8.5 19.5L12 12.5L15.5 19.5L12 18.6945L8.5 19.5Z");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.j0mppdb_k {
  d: path("M19 21L21 21L21 3L3 3L3 21L5 21");
}

</style>
