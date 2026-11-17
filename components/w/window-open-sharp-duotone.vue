<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="mkntqubry"/><path class="gfvp5gbjn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-open-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gfvp5gbjn {
  d: path("M11 4V12H5V4H11ZM19 4V12H13V4H19Z");
}

.mkntqubry {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M20 2C20.552 2 21 2.448 21 3V20H23V22H1V20H3V3C3 2.448 3.448 2 4 2H20ZM5 20H19V14H5V20Z");
}

</style>
