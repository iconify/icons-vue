<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="d0q_v-0ci"/><path class="tzg22jwzo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:skip-forward-duotone-round" /></template>
<style>
.d0q_v-0ci {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M14.664 9.504a2.998 2.998 0 0 1 0 4.992l-6 4A3 3 0 0 1 4 16V8a3 3 0 0 1 4.664-2.496Z");
}

.ft5dv1b6b {
  fill: none;
}

.tzg22jwzo {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8.664 5.504l6 4c1.781 1.187 1.781 3.805 0 4.992l-6 4C6.67 19.826 4 18.396 4 16V8c0-2.396 2.67-3.825 4.664-2.496M20 5v14");
}

</style>
