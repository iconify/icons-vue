<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="t92vwwb3f"/><path class="rqwxml-5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:perspective-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rqwxml-5e {
  d: path("M12 1V12M12 12V23M12 12H1M12 12H23M5 8V16L19 20V5L5 8Z");
}

.t92vwwb3f {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 5.26L18.79 4.02C19.085 3.96 19.394 4.03 19.629 4.22C19.864 4.41 20 4.7 20 5V11H23V13H20V20C20 20.31 19.853 20.61 19.603 20.8C19.352 20.99 19.027 21.05 18.726 20.96L13 19.33V23H11V18.75L4.726 16.96C4.296 16.84 4 16.45 4 16V13H1V11H4V8C4 7.53 4.329 7.12 4.79 7.02L11 5.69V1H13V5.26Z");
  stroke: none;
}

</style>
