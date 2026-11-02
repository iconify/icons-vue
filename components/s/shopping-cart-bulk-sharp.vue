<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fxll31sly"/><path class="rw2olyboe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fxll31sly {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5.03 8.243A.998.998 0 0 1 6 7h15a.998.998 0 0 1 .97 1.243l-2 8A1 1 0 0 1 19 17H8a1 1 0 0 1-.97-.757Z");
}

.rw2olyboe {
  d: path("M3 3h2a1 1 0 0 1 .97.757L6.781 7H21a.998.998 0 0 1 .97 1.243l-2 8A1 1 0 0 1 19 17H8a1 1 0 0 1-.97-.757L4.219 5H3a1 1 0 0 1 0-2m5.781 12h9.438l1.5-6H7.281Zm-1.623 4.221a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558m9 0a2 2 0 1 1 3.684 1.558a2 2 0 0 1-3.684-1.558");
}

</style>
