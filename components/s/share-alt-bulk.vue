<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="r65c07b1e"/><path class="hug0rshgv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:share-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hug0rshgv {
  d: path("m9.4 10.2l4-3a1 1 0 0 1 1.2 1.6l-4 3a1 1 0 0 1-.599.2c.216 0 .426.07.599.2l4 3a1 1 0 0 1-1.2 1.6l-4-3a1 1 0 0 1 .599-1.8a1 1 0 0 1-.599-1.8");
}

.r65c07b1e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.949 8.316a4.162 4.162 0 1 1-7.898-2.632a4.162 4.162 0 0 1 7.898 2.632m-10 5a4.162 4.162 0 1 1-7.898-2.632a4.162 4.162 0 0 1 7.898 2.632m10 5a4.162 4.162 0 1 1-7.898-2.632a4.162 4.162 0 0 1 7.898 2.632");
}

</style>
