<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dcs_cw7zl"/><path class="j2ocj64rv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-bag-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dcs_cw7zl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 8a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v11a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Z");
}

.j2ocj64rv {
  d: path("M8 6a4 4 0 0 1 8 0a1 1 0 0 1-2 0a2 2 0 1 0-4 0a1 1 0 0 1-2 0");
}

</style>
