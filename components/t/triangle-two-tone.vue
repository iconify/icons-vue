<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dqcwucc-i"/><path class="pgzoxkbrf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:triangle-two-tone" /></template>
<style>
.dqcwucc-i {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.7328 3.8869C10.2061 1.3716 13.7947 1.3715 15.268 3.8869L22.4623 16.172C23.9502 18.7134 22.1759 21.9998 19.1947 22.0002L4.8061 22.0002C1.8245 22.0001 0.0502 18.7136 1.5385 16.172L8.7328 3.8869Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pgzoxkbrf {
  d: path("M14.4051 4.3922C13.3181 2.536 10.6819 2.536 9.5949 4.3922L2.4006 16.6777C1.2854 18.5822 2.6307 21 4.8057 21L19.1943 21C21.3693 21 22.7146 18.5822 21.5994 16.6777L14.4051 4.3922Z");
}

</style>
