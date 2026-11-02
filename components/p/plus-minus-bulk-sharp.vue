<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a06aaqtap"/><path class="juiz4l5bu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plus-minus-bulk-sharp" /></template>
<style>
.a06aaqtap {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 19h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

.cuyn6tgcc {
  fill: currentColor;
}

.juiz4l5bu {
  d: path("M13 9h5a1 1 0 0 1 0 2h-5v5a1 1 0 0 1-2 0v-5H6a1 1 0 0 1 0-2h5V4a1 1 0 0 1 2 0Z");
}

</style>
