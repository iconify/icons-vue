<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nuvbu6bqy"/><path class="t8q_ld_2l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telescope-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nuvbu6bqy {
  stroke-opacity: 0.4;
  d: path("M12 11L7 21m5-10l5 10");
}

.t8q_ld_2l {
  d: path("m4 10l14-7l2 4l-14 7zm10-5l2 4");
}

</style>
