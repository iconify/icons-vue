<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="td2orpdal"/><path class="xgn5z8cfz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ship-wheel-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.td2orpdal {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.6569 17.6569C16.2102 19.1035 14.2089 20 12 20C7.5817 20 4 16.4183 4 12C4 7.5817 7.5817 4 12 4C16.4183 4 20 7.5817 20 12C20 14.2089 19.1035 16.2102 17.6569 17.6569Z");
  stroke: none;
}

.xgn5z8cfz {
  d: path("M19 12C19 15.866 15.866 19 12 19C8.134 19 5 15.866 5 12C5 8.134 8.134 5 12 5C15.866 5 19 8.134 19 12ZM12 1L12 2L12 22L12 23M21.5 6.5151L21 6.8038L3 17.1962L2.5 17.4849M21.5 17.4849L21 17.1962L3 6.8038L2.5 6.5151");
}

</style>
