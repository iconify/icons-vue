<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bwxgai-2l"/><path class="pjg3v3b7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shapes-bulk" /></template>
<style>
.bwxgai-2l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.664 4.693l2.132 3.198A2 2 0 0 1 10.131 11H5.869a2 2 0 0 1-1.665-3.109l2.132-3.198a2 2 0 0 1 3.328 0M12 17a5 5 0 1 1 10.001.001A5 5 0 0 1 12 17M2 16a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v4a2 2 0 0 1-2 2H4a2 2 0 0 1-2-2Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.pjg3v3b7z {
  d: path("M11.796 7.891A2 2 0 0 1 10.131 11H5.869a2 2 0 0 1-1.665-3.109l2.132-3.198a2 2 0 0 1 3.328 0ZM5.869 9h4.262L8 5.803Z");
}

</style>
