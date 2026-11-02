<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tpm1nlt8l"/><path class="q91fq6boi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q91fq6boi {
  d: path("M16.707 11.293a.999.999 0 1 1-1.414 1.414l-4-4a.999.999 0 1 1 1.414-1.414Z");
}

.tpm1nlt8l {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 20v-4c0-.265.105-.52.293-.707l12-12a1 1 0 0 1 1.414 0l4 4a1 1 0 0 1 0 1.414l-12 12A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1");
}

</style>
