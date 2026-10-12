<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sgzix0bdh"/><path class="sudf02b4w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:marquee-tent-sharp" /></template>
<style>
.sgzix0bdh {
  d: path("M12 7V2.75h4l-1.25 1.6L16 5.95h-4m.64 1.45l7.97 4.95l.64.4H19.5v8.5h-15v-8.5H2.75l.64-.4l7.97-4.95L12 7z");
}

.sudf02b4w {
  d: path("M4.5 12.75h15m-10 8.5L12 16l2.5 5.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
