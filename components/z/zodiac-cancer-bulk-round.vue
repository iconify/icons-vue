<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p31dn-bmr"/><path class="huykblbwc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-cancer-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.huykblbwc {
  d: path("M5.019 8.121A4 4 0 1 1 2 12a9.65 9.65 0 0 1 1.537-5.287a9.6 9.6 0 0 1 1.709-1.986a9.96 9.96 0 0 1 4.589-2.294c2.749-.563 5.523.086 7.765 1.767a1 1 0 1 1-1.2 1.6a7.9 7.9 0 0 0-2.005-1.099c-3.5-1.294-7.514.201-9.376 3.42M4 12a2 2 0 1 0 3.999.001A2 2 0 0 0 4 12");
}

.p31dn-bmr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M18.981 15.879a4.001 4.001 0 1 1 2.704-5.436c.209.492.316 1.022.315 1.557a9.9 9.9 0 0 1-.407 2.834c-1.583 5.317-7.478 8.265-12.682 6.341A9.9 9.9 0 0 1 6.4 19.8a.998.998 0 0 1 .091-1.66a1 1 0 0 1 1.109.06a7.777 7.777 0 0 0 11.381-2.321M20 12a2 2 0 1 0-3.999-.001A2 2 0 0 0 20 12");
}

</style>
