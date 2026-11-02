<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="quub31myw"/><path class="hb1ohtb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:telegram-duocolor" /></template>
<style>
.hb1ohtb0a {
  d: path("m14 11l-3 3m-4-1l2 6l3-4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.quub31myw {
  stroke-opacity: 0.4;
  d: path("m11 14l6 6l4-16l-18 7l4 2");
}

</style>
