<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y-aszetuv"/><path class="wsyw1acko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thumbs-up-duotone-sharp" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.wsyw1acko {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 10a4 4 0 0 0 4-4V5a2 2 0 1 1 4 0v5h6v4l-2 7H7m0-11H3v11h4z");
}

.y-aszetuv {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M10 6V5a3 3 0 1 1 6 0v4h5a1 1 0 0 1 1 1v4q0 .14-.038.275l-2 7A1 1 0 0 1 19 22H3a1 1 0 0 1-1-1V10a1 1 0 0 1 1-1h4a3 3 0 0 0 3-3");
}

</style>
