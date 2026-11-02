<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g2ye-wb1r"/><path class="wulec5l-i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g2ye-wb1r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 20v-4c0-.265.105-.52.293-.707l10-10a3.828 3.828 0 0 1 5.414 5.414l-10 10A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1");
}

.wulec5l-i {
  d: path("M11 6.414L9.707 7.707a.999.999 0 1 1-1.414-1.414L9.376 5.21a1.83 1.83 0 0 0-1.669.497l-2 2a1.83 1.83 0 0 0 0 2.586l2 2a.999.999 0 1 1-1.414 1.414l-2-2a3.82 3.82 0 0 1 0-5.414l2-2a3.823 3.823 0 0 1 5.414 0l2 2a.999.999 0 1 1-1.414 1.414Zm6.707 3.879l2 2a3.823 3.823 0 0 1 0 5.414l-2.001 2.002a3.83 3.83 0 0 1-5.413-.002l-2-2a.999.999 0 1 1 1.414-1.414l2 2a1.83 1.83 0 0 0 2.586 0l2.001-2.001a1.83 1.83 0 0 0 .496-1.668l-1.083 1.083a.999.999 0 1 1-1.414-1.414L17.586 13l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
