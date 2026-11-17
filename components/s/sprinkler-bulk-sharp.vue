<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="w1agndv1m"/><path class="toy_1rbdp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sprinkler-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.toy_1rbdp {
  d: path("M9 3h.01a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2m6 0h.01a1 1 0 0 1 0 2H15a1 1 0 0 1 0-2M5 6h.01a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2m14 0h.01a1 1 0 0 1 0 2H19a1 1 0 0 1 0-2m-7 1h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2M8 9h.01a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2m8 0h.01a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2m-5 6a1 1 0 0 1 2 0v4h3a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2h3Z");
}

.w1agndv1m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9.236 11.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338");
}

</style>
