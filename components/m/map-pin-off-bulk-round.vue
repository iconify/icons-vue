<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="aocjn-brb"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:map-pin-off-bulk-round" /></template>
<style>
.aocjn-brb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.699 4.457L8.2 2.958a8 8 0 0 1 11.171 3.928c.418.985.632 2.044.629 3.114a11 11 0 0 1-.77 3.987Zm-3.834.408l11.892 11.892c-1.358 1.992-3.2 3.74-5.202 5.075a1 1 0 0 1-1.11 0a20 20 0 0 1-2.482-1.956a18.5 18.5 0 0 1-2.394-2.66a14 14 0 0 1-1.832-3.314A10.9 10.9 0 0 1 4 10a7.98 7.98 0 0 1 1.865-5.135");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

</style>
