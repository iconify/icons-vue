<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pg1487bug"/><path class="ohev-g22f"/><path class="v2c2b2wls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ohev-g22f {
  d: path("M11 20H5V16H11V20ZM19 16V20H13V16H19ZM11 14H5V10H11V14Z");
}

.pg1487bug {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 2C20.105 2 21 2.895 21 4V20H22C22.552 20 23 20.448 23 21C23 21.552 22.552 22 22 22H2C1.448 22 1 21.552 1 21C1 20.448 1.448 20 2 20H3V4C3 2.895 3.895 2 5 2H19Z");
}

.v2c2b2wls {
  d: path("M19 14H13V10H19V14ZM19 8H5V4H19V8Z");
}

</style>
