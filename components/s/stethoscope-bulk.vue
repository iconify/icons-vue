<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ejfagnbsy"/><path class="jrm76tm4n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stethoscope-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ejfagnbsy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 12.829V15a7 7 0 1 1-14 0a1 1 0 0 1 2 0a5 5 0 1 0 10 0v-2.171a3 3 0 1 1 2 0M19 11a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

.jrm76tm4n {
  d: path("M6 3v2a1 1 0 0 1-1.867.498A1 1 0 0 0 4 6v5a3 3 0 1 0 6 0V6a1 1 0 0 0-.133-.502A1 1 0 0 1 8 5V3a1 1 0 0 1 2 0v.171A3 3 0 0 1 12 6v5a5 5 0 0 1-10 0V6c0-1.27.803-2.405 2-2.829V3a1 1 0 0 1 2 0");
}

</style>
