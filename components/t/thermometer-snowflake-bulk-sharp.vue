<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="q95mx0efm"/><path class="ekusi0boa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:thermometer-snowflake-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ekusi0boa {
  d: path("M17 10.464V8.732l-1.5.866a1 1 0 0 1-1-1.732L16 7l-1.5-.866a1.002 1.002 0 0 1 0-1.732a1 1 0 0 1 1 0l1.5.866V3.536a1 1 0 0 1 2 0v1.732l1.5-.866a.998.998 0 0 1 1.5.866c0 .357-.191.687-.5.866L20 7l1.5.866a1 1 0 0 1-1 1.732L19 8.732v1.732a1 1 0 0 1-2 0");
}

.q95mx0efm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 11.423V5a3 3 0 1 1 6 0v6.423a5.473 5.473 0 1 1-6 0");
}

</style>
