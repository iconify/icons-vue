<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4-8knw7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:medical-cross-duocolor-round" /></template>
<style>
.l4-8knw7n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 8.536l3.928-2.268a1 1 0 0 1 1.366.366l1 1.732a1 1 0 0 1-.366 1.366L16 12l3.928 2.268a1 1 0 0 1 .366 1.366l-1 1.732a1 1 0 0 1-1.366.366L14 15.464V20a1 1 0 0 1-1 1h-2a1 1 0 0 1-1-1v-4.536l-3.928 2.268a1 1 0 0 1-1.366-.366l-1-1.732a1 1 0 0 1 .366-1.366L8 12L4.072 9.732a1 1 0 0 1-.366-1.366l1-1.732a1 1 0 0 1 1.366-.366L10 8.536V4a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1z");
}

</style>
