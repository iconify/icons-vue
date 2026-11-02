<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="beo71ab5k"/><path class="o1nlj2b_t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:palette-duotone-sharp" /></template>
<style>
.beo71ab5k {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 17h-2a1 1 0 0 0-1 1v2c0 .531-.21 1.039-.586 1.414A2 2 0 0 1 12 22a9.9 9.9 0 0 1-3.893-.786a9.9 9.9 0 0 1-3.178-2.143A9.97 9.97 0 0 1 2 12a9.9 9.9 0 0 1 .786-3.893a10.03 10.03 0 0 1 5.321-5.321A10.003 10.003 0 0 1 22 12c0 1.33-.522 2.597-1.464 3.536A4.98 4.98 0 0 1 17 17");
}

.ft5dv1b6b {
  fill: none;
}

.o1nlj2b_t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 21a9 9 0 1 1 9-9a4 4 0 0 1-4 4h-2a2 2 0 0 0-2 2v2a1 1 0 0 1-1 1m-5-9h.01M9 8h.01M14 7h.01M17 11h.01");
}

</style>
