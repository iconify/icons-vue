<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="db4np_a7j"/><path class="yh2gtlbfn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-close-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.db4np_a7j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 9h-9a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 22 8a1 1 0 0 1-1 1");
}

.yh2gtlbfn {
  d: path("M3 7h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m11.707 6.293L17 15.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L18.414 17l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 18.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L15.586 17l-2.293-2.293a.999.999 0 1 1 1.414-1.414");
}

</style>
