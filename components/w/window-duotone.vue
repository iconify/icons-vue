<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="g8lst8bih"/><path class="j9mc13bit"/><path class="yzp1an2yx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.g8lst8bih {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19 2C20.1046 2 21 2.895 21 4V20H22C22.5523 20 23 20.448 23 21C23 21.552 22.5523 22 22 22H2C1.4477 22 1 21.552 1 21C1 20.448 1.4477 20 2 20H3V4C3 2.895 3.8954 2 5 2H19Z");
}

.j9mc13bit {
  d: path("M11 20H5V13H11V20ZM19 13V20H13V13H19ZM11 11H5V4H11V11Z");
}

.yzp1an2yx {
  d: path("M19 11H13V4H19V11Z");
}

</style>
