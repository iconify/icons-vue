<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="b7spmpbul"/><path class="ul0ji55js"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wifi-problem-bulk" /></template>
<style>
.b7spmpbul {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m19 5.586l1.293-1.293a.999.999 0 1 1 1.414 1.414L20.414 7l1.293 1.293a.999.999 0 1 1-1.414 1.414L19 8.414l-1.293 1.293a.999.999 0 1 1-1.414-1.414L17.586 7l-1.293-1.293a.999.999 0 1 1 1.414-1.414Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ul0ji55js {
  d: path("M6.663 6.121A13.1 13.1 0 0 1 12 5a1.002 1.002 0 0 1 .707 1.707A1 1 0 0 1 12 7a11.05 11.05 0 0 0-4.528.951a10.7 10.7 0 0 0-3.725 2.713a1 1 0 0 1-.688.334a.999.999 0 0 1-.806-1.662a12.7 12.7 0 0 1 4.41-3.215M8.23 9.943C9.397 9.343 10.685 9 12 9a1 1 0 0 1 0 2c-2.038.001-3.949 1.101-5.232 2.64a1 1 0 1 1-1.536-1.28A9.6 9.6 0 0 1 8.23 9.943m1.65 3.964a4.64 4.64 0 0 1 4.24 0a4.54 4.54 0 0 1 1.712 1.538a1 1 0 0 1-1.664 1.11a2.55 2.55 0 0 0-.966-.871a2.6 2.6 0 0 0-1.202-.29a2.58 2.58 0 0 0-2.168 1.161a1.003 1.003 0 0 1-1.387.277a1 1 0 0 1-.277-1.387a4.54 4.54 0 0 1 1.712-1.538M12.01 18a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Z");
}

</style>
