<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="wevrqpbgx"/><path class="b-b7_4wvu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sparkle-duotone-round" /></template>
<style>
.b-b7_4wvu {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3c0 4 5 9 9 9c-4 0-9 5-9 9c0-4-5-9-9-9c4 0 9-5 9-9");
}

.ft5dv1b6b {
  fill: none;
}

.wevrqpbgx {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M21 12c-4.007.005-8.995 4.993-9 9c-.005-4.007-4.993-8.995-9-9c4.007-.005 8.995-4.993 9-9c.005 4.007 4.993 8.995 9 9");
}

</style>
