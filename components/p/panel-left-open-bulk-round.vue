<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bwe_218us"/><path class="k2skpw02v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:panel-left-open-bulk-round" /></template>
<style>
.bwe_218us {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 3a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21H8a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.k2skpw02v {
  d: path("M10 4v16a1 1 0 0 1-2 0V4a1 1 0 0 1 2 0m3.293 10.293L15.586 12l-2.293-2.293a.999.999 0 1 1 1.414-1.414l3 3a1 1 0 0 1 0 1.414l-3 3a.999.999 0 1 1-1.414-1.414");
}

</style>
