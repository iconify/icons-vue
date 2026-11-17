<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="vrxb5sbfr"/><path class="gfvp5gbjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-open-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gfvp5gbjn {
  d: path("M11 4V12H5V4H11ZM19 4V12H13V4H19Z");
}

.vrxb5sbfr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M19 2C20.105 2 21 2.895 21 4V20H22C22.552 20 23 20.448 23 21C23 21.552 22.552 22 22 22H2C1.448 22 1 21.552 1 21C1 20.448 1.448 20 2 20H3V4C3 2.895 3.895 2 5 2H19ZM5 20H19V14H5V20Z");
}

</style>
