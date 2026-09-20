<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ge7jckuff"/><path class="etx6lfb3j"/><path class="xw-kcgifr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:mcp-stdio-outline-thin" /></template>
<style>
.etx6lfb3j {
  d: path("M2 9h4");
}

.ge7jckuff {
  d: path("M12 4h3a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H9a3 3 0 0 1 -3 -3V7l3 -3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xw-kcgifr {
  d: path("M18 15h4");
}

</style>
