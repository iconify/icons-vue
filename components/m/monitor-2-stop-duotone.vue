<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="k_a0lzbfl"/><path class="qb505obkb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:monitor-2-stop-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.k_a0lzbfl {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 18L5 18C2.7908 18 1 16.2092 1 14L1 6C1 3.7908 2.7908 2 5 2L19 2C21.2092 2 23 3.7908 23 6L23 14C23 16.2092 21.2092 18 19 18L13 18L13 20L16 20C16.5523 20 17 20.4477 17 21C17 21.5523 16.5523 22 16 22L8 22C7.4477 22 7 21.5523 7 21C7 20.4477 7.4477 20 8 20L11 20L11 18Z");
}

.qb505obkb {
  d: path("M10 6L14 6C15.1046 6 16 6.8954 16 8L16 12C16 13.1046 15.1046 14 14 14L10 14C8.8954 14 8 13.1046 8 12L8 8C8 6.8954 8.8954 6 10 6Z");
}

</style>
