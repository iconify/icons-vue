<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="x5c2xn8ms"/><path class="jpovxwu5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:superset-proper-of-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jpovxwu5o {
  d: path("M224 128a88.1 88.1 0 0 1-88 88H64a8 8 0 0 1 0-16h72a72 72 0 0 0 0-144H64a8 8 0 0 1 0-16h72a88.1 88.1 0 0 1 88 88");
}

.x5c2xn8ms {
  d: path("M216 128a80 80 0 0 1-80 80H64V48h72a80 80 0 0 1 80 80");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
