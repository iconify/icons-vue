<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="p_802tbgz"/><path class="yn6zku7qr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-basket-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.p_802tbgz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.019 10.196A1.003 1.003 0 0 1 4 9h16a.998.998 0 0 1 .981 1.196l-2 10A1 1 0 0 1 18 21H6a1 1 0 0 1-.981-.804Z");
}

.yn6zku7qr {
  d: path("M8.168 3.445a1 1 0 0 1 1.664 1.11L6.869 9h10.262l-2.963-4.445a1 1 0 0 1 1.664-1.11L19.535 9H21a1 1 0 0 1 0 2h-6v9a1 1 0 0 1-2 0v-9h-2v9a1 1 0 0 1-2 0v-9H3a1 1 0 0 1 0-2h1.465Z");
}

</style>
