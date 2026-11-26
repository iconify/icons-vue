<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lr4q_rbvr"/><path class="lmcpit57j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:ship-wheel-duotone" /></template>
<style>
.lmcpit57j {
  d: path("M19 12C19 15.866 15.866 19 12 19C8.134 19 5 15.866 5 12C5 8.134 8.134 5 12 5C15.866 5 19 8.134 19 12Z");
}

.lr4q_rbvr {
  stroke-opacity: 0.4;
  d: path("M12 2L12 22M21 6.8038L3 17.1962M21 17.1962L3 6.8038");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
