<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wql_3nbpq"/><path class="a6__e9p2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sun-duotone" /></template>
<style>
.a6__e9p2h {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0m10 0h2m-4.05 4.95l1.414 1.414M12 19v2m-4.95-4.05l-1.414 1.414M5 12H3m4.05-4.95L5.636 5.636M12 5V3m4.95 4.05l1.414-1.414");
}

.ft5dv1b6b {
  fill: none;
}

.wql_3nbpq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M9 12a3 3 0 1 1 6 0a3 3 0 0 1-6 0");
}

</style>
