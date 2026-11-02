<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a9815muvx"/><path class="i81m2bbsb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wheelchair-bulk-sharp" /></template>
<style>
.a9815muvx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.443 12.314a4.002 4.002 0 0 0 0 7.372A4 4 0 0 0 12.2 18.4a1 1 0 0 1 1.6 1.2A6 6 0 1 1 9 10a1 1 0 0 1 0 2a3.95 3.95 0 0 0-1.557.314");
}

.cuyn6tgcc {
  fill: currentColor;
}

.i81m2bbsb {
  d: path("M7.158 3.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558M10 9h4a1 1 0 0 1 0 2h-4v2h5c.379 0 .725.214.894.553L18.618 19H20a1 1 0 0 1 0 2h-2a1 1 0 0 1-.894-.553L14.382 15H9a1 1 0 0 1-1-1V8a1 1 0 0 1 2 0Z");
}

</style>
