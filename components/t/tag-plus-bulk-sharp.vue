<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dqnggab5f"/><path class="zz9dj1bep"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tag-plus-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dqnggab5f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M9 2h6c.265 0 .52.105.707.293l4 4A1 1 0 0 1 20 7v14a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V7c0-.265.105-.52.293-.707l4-4A1 1 0 0 1 9 2");
}

.zz9dj1bep {
  d: path("M11 5h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2m2 7v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2H9a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>
