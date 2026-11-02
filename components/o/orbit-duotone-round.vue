<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="s-8rm4p_y"/><path class="uie8-ybok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:orbit-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.s-8rm4p_y {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M16.236 4.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-7.921 5.611a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m-6.079 6.389a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

.uie8-ybok {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0m10-4a8.062 8.062 0 0 1-8 12m-6-4a8.062 8.062 0 0 1 8-12m4 2a2 2 0 1 0 4 0a2 2 0 0 0-4 0M3 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

</style>
