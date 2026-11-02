<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c-ti2fbpl"/><path class="xn9cozqeu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:snowflake-bulk-sharp" /></template>
<style>
.c-ti2fbpl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.293 6.207a.999.999 0 1 1 1.414-1.414L12 6.086l1.293-1.293a.999.999 0 1 1 1.414 1.414l-2 2a1 1 0 0 1-1.414 0Zm6.37.552a1 1 0 0 1 1.932.518l-.473 1.766l1.766.473a1 1 0 0 1-.518 1.932l-2.732-.732a1 1 0 0 1-.707-1.225Zm-7.302 3.957l-2.731.732a1 1 0 0 1-.518-1.932l1.766-.473l-.473-1.766a1 1 0 0 1 1.932-.518l.732 2.732a1 1 0 0 1-.707 1.225Zm.708 3.793l-.732 2.732a1 1 0 0 1-1.932-.518l.473-1.766l-1.766-.473a1 1 0 0 1 .518-1.932l2.731.732h.001a1 1 0 0 1 .707 1.225m6.57-1.225l2.731-.732a1 1 0 0 1 .518 1.932l-1.766.473l.473 1.766a1 1 0 0 1-1.932.518l-.732-2.732a1 1 0 0 1 .707-1.225Zm-2.932 2.509l2 2a.999.999 0 1 1-1.414 1.414L12 17.914l-1.293 1.293a.999.999 0 1 1-1.414-1.414l2-2a1 1 0 0 1 1.414 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.xn9cozqeu {
  d: path("M11 10.268V3a1 1 0 0 1 2 0v7.268l6.294-3.634a1 1 0 0 1 1 1.732L14 12l6.294 3.634a1 1 0 1 1-1 1.732L13 13.732V21a1 1 0 0 1-2 0v-7.268l-6.294 3.634a1 1 0 0 1-1-1.732L10 12L3.706 8.366a1 1 0 1 1 1-1.732Z");
}

</style>
