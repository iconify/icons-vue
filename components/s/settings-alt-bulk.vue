<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p-35u173h"/><path class="k1623nsxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-alt-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k1623nsxf {
  d: path("M8.315 10.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

.p-35u173h {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m19.342 18.447l-6 3a3 3 0 0 1-2.684 0l-6-3A3 3 0 0 1 3 15.764V8.236a3 3 0 0 1 1.658-2.683l6-3a3 3 0 0 1 2.684 0l6 3A3 3 0 0 1 21 8.236v7.528a3 3 0 0 1-1.658 2.683M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
