<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b8xh7va0t"/><path class="g1rknoa_n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-close-bulk" /></template>
<style>
.b8xh7va0t {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 5h12a1 1 0 0 1 1 1v13a3 3 0 0 1-3 3H8a3 3 0 0 1-3-3V6a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g1rknoa_n {
  d: path("M9.999 2h4a3 3 0 0 1 3 3h3a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h3c0-1.657 1.342-3 2.999-3M15 5a.987.987 0 0 0-.948-.999h-.001L14 4h-4l-.089.004h-.005A1 1 0 0 0 9 4.998V5Zm-4.293 6.293L12 12.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L13.414 14l1.293 1.293a.999.999 0 1 1-1.414 1.414L12 15.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L10.586 14l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
