<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tpm1nlt8l"/><path class="bdsc608ue"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-bulk-sharp" /></template>
<style>
.bdsc608ue {
  d: path("M11 6.414L9.707 7.707a.999.999 0 1 1-1.414-1.414L9.586 5L9 4.414L4.414 9l3.293 3.293a.999.999 0 1 1-1.414 1.414l-4-4a1 1 0 0 1 0-1.414l6-6a1 1 0 0 1 1.414 0l4 4a.999.999 0 1 1-1.414 1.414Zm6.707 3.879l4 4a1 1 0 0 1 0 1.414l-6 6a1 1 0 0 1-1.414 0l-4-4a.999.999 0 1 1 1.414-1.414L15 19.586L19.586 15L19 14.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L17.586 13l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tpm1nlt8l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 20v-4c0-.265.105-.52.293-.707l12-12a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414l-12 12A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1");
}

</style>
