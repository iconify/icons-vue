<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c9n_kv69p"/><path class="e1ajxz96l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:traffic-light-bulk" /></template>
<style>
.c9n_kv69p {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H9a3 3 0 0 1-3-3Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.e1ajxz96l {
  d: path("M10.158 6.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m0 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m0 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
