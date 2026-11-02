<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="gx8j36kqa"/><path class="s95zvrsyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gx8j36kqa {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8c0-.155.036-.308.106-.447l1-2C4.643 4.478 5.652 3.001 7 3h10c1.348.001 2.357 1.478 2.894 2.553l1 2c.07.139.106.292.106.447v10a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3Z");
}

.s95zvrsyk {
  d: path("M4 7h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2");
}

</style>
