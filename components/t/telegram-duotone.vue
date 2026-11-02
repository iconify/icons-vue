<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="p0zf_k2da"/><path class="mldb561ka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telegram-duotone" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mldb561ka {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m14 11l-3 3m-4-1l2 6l3-4m-1-1l6 6l4-16l-18 7l4 2");
}

.p0zf_k2da {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M20.638 3.068a1 1 0 0 1 1.332 1.175l-4 16a1 1 0 0 1-1.677.464l-4.185-4.185L9.8 19.6a1 1 0 0 1-1.749-.284l-1.869-5.607l-3.629-1.815a.999.999 0 0 1 .085-1.826Z");
}

</style>
