<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="q30iyq9pm"/><path class="uo6o4wbgg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:wave-triangle-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.q30iyq9pm {
  d: path("m76 56l52 72H24Zm156 72H128l52 72Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uo6o4wbgg {
  d: path("m238.48 132.68l-52 72a8 8 0 0 1-13 0L76 69.66l-45.51 63a8 8 0 1 1-13-9.36l52-72a8 8 0 0 1 13 0l97.51 135l45.51-63a8 8 0 1 1 13 9.36Z");
}

</style>
