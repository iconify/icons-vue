<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="k7scgu3hb"/><path class="mcpy8rnzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:medal-military-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k7scgu3hb {
  d: path("M168 192a40 40 0 1 1-40-40a40 40 0 0 1 40 40m39-144h-39v85.82l42.72-19.42a9 9 0 0 0 5.28-8.2V57a9 9 0 0 0-9-9M88 48H49a9 9 0 0 0-9 9v49.2a9 9 0 0 0 5.28 8.2L88 133.82Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mcpy8rnzk {
  d: path("M207 40H49a17 17 0 0 0-17 17v49.21a17 17 0 0 0 10 15.47l62.6 28.45a48 48 0 1 0 46.88 0L214 121.68a17 17 0 0 0 10-15.47V57a17 17 0 0 0-17-17m-47 16v72.67l-32 14.54l-32-14.54V56ZM48 106.21V57a1 1 0 0 1 1-1h31v65.39l-31.41-14.27a1 1 0 0 1-.59-.91M128 224a32 32 0 1 1 32-32a32 32 0 0 1-32 32m80-117.79a1 1 0 0 1-.59.91L176 121.39V56h31a1 1 0 0 1 1 1Z");
}

</style>
