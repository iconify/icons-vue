<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="srtt1ab1o"/><path class="a7d_3hbej"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:tram-duotone" /></template>
<style>
.a7d_3hbej {
  d: path("M184 48h-48V24h32a8 8 0 0 0 0-16H88a8 8 0 0 0 0 16h32v24H72a32 32 0 0 0-32 32v104a32 32 0 0 0 32 32h8l-14.4 19.2a8 8 0 1 0 12.8 9.6L100 216h56l21.6 28.8a8 8 0 1 0 12.8-9.6L176 216h8a32 32 0 0 0 32-32V80a32 32 0 0 0-32-32M72 64h112a16 16 0 0 1 16 16v40H56V80a16 16 0 0 1 16-16m112 136H72a16 16 0 0 1-16-16v-48h144v48a16 16 0 0 1-16 16m-88-28a12 12 0 1 1-12-12a12 12 0 0 1 12 12m88 0a12 12 0 1 1-12-12a12 12 0 0 1 12 12");
}

.cuyn6tgcc {
  fill: currentColor;
}

.srtt1ab1o {
  d: path("M208 80v48H48V80a24 24 0 0 1 24-24h112a24 24 0 0 1 24 24");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
