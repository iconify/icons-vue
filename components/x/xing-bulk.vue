<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x6n1l4bre"/><path class="v7_53ttto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:xing-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.v7_53ttto {
  d: path("M9.894 9.553a1 1 0 0 1 0 .894l-3 6a1 1 0 1 1-1.788-.894L7.882 10L6.106 6.447a1 1 0 1 1 1.788-.894Z");
}

.x6n1l4bre {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m13.145 13.989l3.723 6.515a1 1 0 1 1-1.736.992l-4-7a1 1 0 0 1-.01-.975l6-11a1 1 0 0 1 1.756.958Z");
}

</style>
