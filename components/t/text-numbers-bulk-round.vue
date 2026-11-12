<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="t5sw1uels"/><path class="hgjr31bma"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:text-numbers-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hgjr31bma {
  d: path("M21 2a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm-8 4a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

.t5sw1uels {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4.293 12.293A1 1 0 0 1 6 13v8a1 1 0 0 1-2 0v-5.586l-.293.293a.999.999 0 1 1-1.414-1.414Zm9.539 3.262L10.869 20H13a1 1 0 0 1 0 2H9a1 1 0 0 1-.832-1.555l3.801-5.701a1 1 0 0 0-.262-.451a1 1 0 0 0-1.094-.215A.99.99 0 0 0 10 15a1 1 0 0 1-2 0a3 3 0 1 1 6 0a1 1 0 0 1-.168.555M21 12a.998.998 0 0 1 .8 1.6l-1.902 2.537A3.001 3.001 0 0 1 19 22h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 0-2h-1a.998.998 0 0 1-.8-1.6L19 14h-2a1 1 0 0 1 0-2Z");
}

</style>
