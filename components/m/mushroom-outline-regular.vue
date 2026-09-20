<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="e4rbzsbiw"/><path class="sg8usjbiz"/><path class="u2vvzw7_k"/><path class="wuk2mlziz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mushroom-outline-regular" /></template>
<style>
.e4rbzsbiw {
  d: path("M3 11a9 9 0 0 1 18 0Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sg8usjbiz {
  d: path("M9 13v6");
}

.u2vvzw7_k {
  d: path("M15 13v6");
}

.wuk2mlziz {
  d: path("M7 19h10");
}

</style>
