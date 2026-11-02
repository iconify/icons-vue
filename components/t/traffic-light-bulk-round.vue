<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dji0kcbys"/><path class="e1ajxz96l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:traffic-light-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dji0kcbys {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 7a5 5 0 0 1 5-5h2a5 5 0 0 1 5 5v10a5 5 0 0 1-5 5h-2a5 5 0 0 1-5-5Z");
}

.e1ajxz96l {
  d: path("M10.158 6.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m0 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m0 5a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
