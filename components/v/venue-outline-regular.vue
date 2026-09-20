<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xgrfb-bqu"/><path class="vjqs2ebif"/><path class="k6x6uv-ap"/><path class="s09hy0b0y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:venue-outline-regular" /></template>
<style>
.k6x6uv-ap {
  d: path("M12 11v8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.vjqs2ebif {
  d: path("M5 6v13h14V6");
}

.xgrfb-bqu {
  d: path("M3 6h18");
}

</style>
