<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="s-6kqdb-n"/><path class="hzy79kbwr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:paper-plane-right-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hzy79kbwr {
  d: path("m231.87 114l-168-95.89a16 16 0 0 0-22.95 19.23L71.55 128l-30.63 90.67A16 16 0 0 0 56 240a16.15 16.15 0 0 0 7.93-2.1l167.92-96.05a16 16 0 0 0 .05-27.89ZM56 224a.6.6 0 0 0 0-.12L85.74 136H144a8 8 0 0 0 0-16H85.74L56.06 32.16A.5.5 0 0 0 56 32l168 95.83Z");
}

.s-6kqdb-n {
  d: path("M227.91 134.86L59.93 231a8 8 0 0 1-11.44-9.67L80 128L48.49 34.72a8 8 0 0 1 11.44-9.67l168 95.85a8 8 0 0 1-.02 13.96");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
