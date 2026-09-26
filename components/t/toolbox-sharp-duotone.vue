<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="aiytbqb_a"/><path class="oq-xadcze"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:toolbox-sharp-duotone" /></template>
<style>
.aiytbqb_a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 7L19 7C19.2652 7 19.5196 7.1054 19.7071 7.2929L22.7071 10.2929C22.8946 10.4804 23 10.7348 23 11L23 21C23 21.5523 22.5523 22 22 22L2 22C1.4477 22 1 21.5523 1 21L1 11C1 10.7348 1.1054 10.4804 1.2929 10.2929L4.2929 7.2929C4.4804 7.1054 4.7348 7 5 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oq-xadcze {
  d: path("M3 14L21 14M8 11L8 17M16 11L16 17M8 8L8 3L16 3L16 8");
}

</style>
