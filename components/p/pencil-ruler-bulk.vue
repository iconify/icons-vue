<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dgy-fnb-a"/><path class="fg10u-jtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:pencil-ruler-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dgy-fnb-a {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 20v-4c0-.265.105-.52.293-.707l11-11a2.414 2.414 0 0 1 3.414 0l2 2a2.414 2.414 0 0 1 0 3.414l-11 11A1 1 0 0 1 8 21H4a1 1 0 0 1-1-1");
}

.fg10u-jtp {
  d: path("M11 6.414L9.707 7.707a.999.999 0 1 1-1.414-1.414L9.586 5l-.293-.293a.42.42 0 0 0-.586 0l-4 4a.42.42 0 0 0 0 .586l3 3a.999.999 0 1 1-1.414 1.414l-3-3a2.414 2.414 0 0 1 0-3.414l4-4a2.415 2.415 0 0 1 3.414 0l3 3a.999.999 0 1 1-1.414 1.414Zm6.707 3.879l3 3a2.414 2.414 0 0 1 0 3.414l-4 4a2.414 2.414 0 0 1-3.414 0l-3-3a.999.999 0 1 1 1.414-1.414l3 3a.415.415 0 0 0 .586 0l4-4a.415.415 0 0 0 0-.586L19 14.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L17.586 13l-1.293-1.293a.999.999 0 1 1 1.414-1.414");
}

</style>
