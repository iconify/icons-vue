<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="uzfgnvbcj"/><path class="zw__fdcto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shapes-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.uzfgnvbcj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m10.08 5.317l1.197 1.796A2.5 2.5 0 0 1 9.197 11H6.803a2.5 2.5 0 0 1-2.08-3.887L5.92 5.317a2.5 2.5 0 0 1 4.16 0M12 17a5 5 0 1 1 10.001.001A5 5 0 0 1 12 17M2 17a3 3 0 0 1 3-3h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

.zw__fdcto {
  d: path("M11.277 7.113A2.5 2.5 0 0 1 9.197 11H6.803a2.5 2.5 0 0 1-2.08-3.887L5.92 5.317a2.5 2.5 0 0 1 4.16 0Zm-3.693-.686L6.387 8.223A.498.498 0 0 0 6.803 9h2.394a.499.499 0 0 0 .416-.777L8.416 6.427a.5.5 0 0 0-.832 0");
}

</style>
