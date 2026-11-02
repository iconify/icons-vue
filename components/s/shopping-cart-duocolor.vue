<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ouhcolk2v"/><path class="jstjunkmm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shopping-cart-duocolor" /></template>
<style>
.jstjunkmm {
  d: path("M3 4c.752 0 1.549.797 2 2l3 8c.451 1.203 1.248 2 2 2h7c.882 0 1.706-.825 2-2l1-4c.254-1.016-.238-2-1-2H6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ouhcolk2v {
  stroke-opacity: 0.4;
  d: path("M8 20a1 1 0 1 0 2 0a1 1 0 0 0-2 0m9 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
