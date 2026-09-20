<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="tgmofuejb"/><path class="qo3n-9bgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:synagogue-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qo3n-9bgr {
  d: path("M208 57.38V32a8 8 0 0 0-16 0v25.38A24 24 0 0 0 176 80v42.21l-40-22.85V72a8 8 0 0 0-16 0v27.36l-40 22.85V80a24 24 0 0 0-16-22.62V32a8 8 0 0 0-16 0v25.38A24 24 0 0 0 32 80v136a8 8 0 0 0 8 8h72a8 8 0 0 0 8-8v-40a8 8 0 0 1 16 0v40a8 8 0 0 0 8 8h72a8 8 0 0 0 8-8V80a24 24 0 0 0-16-22.62M200 72a8 8 0 0 1 8 8v24h-16V80a8 8 0 0 1 8-8M56 72a8 8 0 0 1 8 8v24H48V80a8 8 0 0 1 8-8m-8 48h16v88H48Zm80 32a24 24 0 0 0-24 24v32H80v-67.36l48-27.43l48 27.43V208h-24v-32a24 24 0 0 0-24-24m64 56v-88h16v88Z");
}

.tgmofuejb {
  d: path("M216 80v32h-32V80a16 16 0 0 1 16-16a16 16 0 0 1 16 16M72 80a16 16 0 0 0-16-16a16 16 0 0 0-16 16v32h32Zm0 56v80h40v-40a16 16 0 0 1 16-16a16 16 0 0 1 16 16v40h40v-80l-56-32Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
