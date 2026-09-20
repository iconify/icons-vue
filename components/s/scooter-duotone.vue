<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ox6xxkvjv"/><path class="kngv55veg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:scooter-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kngv55veg {
  d: path("M212 136c-1.18 0-2.35.06-3.51.17l-32.9-98.7A8 8 0 0 0 168 32h-32a8 8 0 0 0 0 16h26.23l17.44 52.31L124.21 168H79.77a36 36 0 1 0-1.83 16H128a8 8 0 0 0 6.19-2.93l51.46-62.81l7.66 23A36 36 0 1 0 212 136M44 192a20 20 0 1 1 20-20a20 20 0 0 1-20 20m168 0a20 20 0 1 1 20-20a20 20 0 0 1-20 20");
}

.ox6xxkvjv {
  d: path("M72 172a28 28 0 1 1-28-28a28 28 0 0 1 28 28m140-28a28 28 0 1 0 28 28a28 28 0 0 0-28-28");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
