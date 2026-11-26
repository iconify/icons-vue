<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="u9i5jc3mv"/><path class="u7j23si5d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:table-rows-move-up-fill" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u7j23si5d {
  d: path("M5 4.1716C3.8014 4.5954 3 5.7287 3 7L3 19C3 20.6569 4.3431 22 6 22L18 22C19.6569 22 21 20.6569 21 19L21 7C21 5.7287 20.1986 4.5954 19 4.1716M3 13L21 13M12 8V2M9 5L12 2L15 5");
}

.u9i5jc3mv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 13L3 19C3 20.6569 4.3431 22 6 22L18 22C19.6569 22 21 20.6569 21 19L21 13Z");
  stroke: none;
}

</style>
