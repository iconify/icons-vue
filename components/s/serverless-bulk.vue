<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y-gn7qzls"/><path class="w70nijb6v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:serverless-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.w70nijb6v {
  d: path("M5.113 7.597a11.66 11.66 0 0 0 0 8.806a11.7 11.7 0 0 0 2.594 3.89a.999.999 0 1 1-1.414 1.414a13.7 13.7 0 0 1-3.031-4.548a13.66 13.66 0 0 1 0-10.318a13.7 13.7 0 0 1 3.031-4.548a.999.999 0 1 1 1.414 1.414a11.7 11.7 0 0 0-2.594 3.89m15.625-.756a13.66 13.66 0 0 1 0 10.318a13.7 13.7 0 0 1-3.031 4.548a.999.999 0 1 1-1.414-1.414a11.7 11.7 0 0 0 2.594-3.89c.573-1.397.866-2.893.863-4.403c.003-1.51-.29-3.006-.863-4.403a11.7 11.7 0 0 0-2.594-3.89a.999.999 0 1 1 1.414-1.414a13.7 13.7 0 0 1 3.031 4.548");
}

.y-gn7qzls {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.135 11H15a1 1 0 0 1 .768 1.64l-5 6a1 1 0 1 1-1.536-1.28L12.865 13H9a1 1 0 0 1-.768-1.64l5-6a1 1 0 1 1 1.536 1.28Z");
}

</style>
