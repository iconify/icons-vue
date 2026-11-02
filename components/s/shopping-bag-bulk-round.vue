<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kxb14t88r"/><path class="j2ocj64rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j2ocj64rv {
  d: path("M8 6a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 1 0-4 0a1 1 0 0 1-2 0");
}

.kxb14t88r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 10a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v7a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 22H9a5 5 0 0 1-5-5Z");
}

</style>
