<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yv2gvylve"/><path clip-rule="evenodd" class="fw8-r0bua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:wallet-cards-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fw8-r0bua {
  fill-rule: evenodd;
  d: path("M2 3L22 3C22.5523 3 23 3.4477 23 4L23 20C23 20.5523 22.5523 21 22 21L2 21C1.4477 21 1 20.5523 1 20L1 4C1 3.4477 1.4477 3 2 3ZM3 8L3 12L6 12L6 13C6 14.1046 6.8954 15 8 15C9.1046 15 10 14.1046 10 13L10 12L21 12L21 8L3 8Z");
}

.yv2gvylve {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 8L21 8L21 12L10 12L10 13C10 14.1046 9.1046 15 8 15C6.8954 15 6 14.1046 6 13L6 12L3 12Z");
}

</style>
