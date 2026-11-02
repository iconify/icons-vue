<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w30nbkbiw"/><path class="yfhcqibox"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-warning-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.w30nbkbiw {
  stroke-opacity: 0.4;
  d: path("M12 9v4m0 3h.01");
}

.yfhcqibox {
  d: path("M19 9c2.667 1.111 2.667 4.889 0 6c1.219 2.552-1.448 5.219-4 4c-1.111 2.667-4.889 2.667-6 0c-2.552 1.219-5.219-1.448-4-4c-2.667-1.111-2.667-4.889 0-6c-1.219-2.552 1.448-5.219 4-4c1.111-2.667 4.889-2.667 6 0c2.552-1.219 5.219 1.448 4 4");
}

</style>
