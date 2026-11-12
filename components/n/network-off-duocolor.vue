<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s1ajku60m"/><path class="gtil3gp3h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:network-off-duocolor" /></template>
<style>
.gtil3gp3h {
  d: path("M12 3h2a1 1 0 0 1 1 1v2M3 17a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v3a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1zm18 1v2a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-3a1 1 0 0 1 1-1h3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s1ajku60m {
  stroke-opacity: 0.4;
  d: path("M6 16v-2a2 2 0 0 1 2-2h7M5 2l17 17");
}

</style>
