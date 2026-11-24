<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rz6gt6b4y"/><path class="fc3n5bobo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-plus-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fc3n5bobo {
  d: path("M4 7h16a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2m9 5v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

.rz6gt6b4y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m3.106 7.553l1-2C4.643 4.478 5.652 3.001 7 3h10c1.348.001 2.357 1.478 2.894 2.553l1 2c.07.139.106.292.106.447v10a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3V8c0-.155.036-.308.106-.447");
}

</style>
