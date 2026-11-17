<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="iu3a4cbne"/><path class="ohev-g22f"/><path class="v2c2b2wls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.iu3a4cbne {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 2C20.552 2 21 2.448 21 3V20H23V22H1V20H3V3C3 2.448 3.448 2 4 2H20Z");
}

.ohev-g22f {
  d: path("M11 20H5V16H11V20ZM19 16V20H13V16H19ZM11 14H5V10H11V14Z");
}

.v2c2b2wls {
  d: path("M19 14H13V10H19V14ZM19 8H5V4H19V8Z");
}

</style>
