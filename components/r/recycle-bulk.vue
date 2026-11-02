<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dqszr-vzb"/><path class="b0bbmvxny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:recycle-bulk" /></template>
<style>
.b0bbmvxny {
  d: path("M9.893 4.5a2.999 2.999 0 0 1 5.196 0l1.639 2.839l.473-1.766a1 1 0 1 1 1.932.517l-1.098 4.099a1 1 0 0 1-1.225.707l-4.098-1.098a1 1 0 1 1 .518-1.932l1.766.473L13.357 5.5a1.002 1.002 0 0 0-1.732 0l-.25.433a1 1 0 0 1-1.732-1Zm10.392 9a3 3 0 0 1-2.598 4.5h-3.278l1.293 1.293a1 1 0 0 1-1.415 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a1 1 0 1 1 1.415 1.414L14.409 16h3.278a1.002 1.002 0 0 0 .866-1.5l-.25-.433a1 1 0 0 1 1.732-1Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.dqszr-vzb {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.068 11.661L6.428 14.5a1.002 1.002 0 0 0 .866 1.5h.5a1 1 0 1 1 0 2h-.5a3 3 0 0 1-2.598-4.5l1.639-2.839l-1.766.473a.999.999 0 1 1-.517-1.932l4.097-1.097l.001-.001a1 1 0 0 1 1.225.708l1.098 4.098a1 1 0 0 1-1.932.517Z");
}

</style>
