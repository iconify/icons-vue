<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rrhce6uaz"/><path class="k1623nsxf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:settings-alt-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k1623nsxf {
  d: path("M8.315 10.443a4.001 4.001 0 0 1 7.37 3.114a4.001 4.001 0 0 1-7.37-3.114m1.842 2.335a2 2 0 1 0 3.686-1.556a2 2 0 0 0-3.686 1.556");
}

.rrhce6uaz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 9v6c0 1.693-1.069 3.152-2.553 3.894l-4 2a5.47 5.47 0 0 1-4.894 0l-4-2C4.069 18.152 3 16.693 3 15V9c0-1.693 1.069-3.152 2.553-3.894l4-2a5.47 5.47 0 0 1 4.894 0l4 2C19.931 5.848 21 7.307 21 9M9 12a3 3 0 1 0 6 0a3 3 0 0 0-6 0");
}

</style>
