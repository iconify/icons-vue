<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c9n_kv69p"/><path class="zenlmhbbk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mobile-button-bulk" /></template>
<style>
.c9n_kv69p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.zenlmhbbk {
  d: path("M12 17h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
