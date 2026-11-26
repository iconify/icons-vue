<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="rrzh6xbrb"/><path class="k67rqov_z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:unfold-vertical-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.k67rqov_z {
  d: path("M12 9L12 2M8.7071 5.2929L12 2L15.2929 5.2929M12 15L12 22M8.7071 18.7071L12 22L15.2929 18.7071");
}

.rrzh6xbrb {
  stroke-opacity: 0.4;
  d: path("M4 12L20 12");
}

</style>
