<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dmxzzbb6p"/><path class="sgls5rb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:sprinkler-spray-arc" /></template>
<style>
.dmxzzbb6p {
  d: path("M12 21.5v-7m-2-2h4v2h-4Zm-5 9h14");
}

.sgls5rb0c {
  d: path("M12 12.5c2-9 8-9 9.5 2.5M12 12.5c-2-9-8-9-9.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
