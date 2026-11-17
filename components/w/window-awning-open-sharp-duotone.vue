<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="bpybgflwc"/><path class="ju4yl5b1u"/><path class="ny8qsib8t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-awning-open-sharp-duotone" /></template>
<style>
.bpybgflwc {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M20 2C20.486 2 20.902 2.35 20.985 2.829L22.89 13.829C22.94 14.12 22.86 14.418 22.67 14.644C22.48 14.869 22.199 15 21.904 15H21V20H23V22H1V20H3V15H2.096C1.801 15 1.521 14.869 1.331 14.644C1.141 14.418 1.06 14.12 1.11 13.829L3.015 2.829L3.034 2.741C3.15 2.308 3.544 2 4 2H20ZM5 20H19V15H5V20Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ju4yl5b1u {
  d: path("M11 13H3.284L3.89 9.5H11V13ZM20.11 9.5L20.716 13H13V9.5H20.11ZM11 7.5H4.236L4.842 4H11V7.5Z");
}

.ny8qsib8t {
  d: path("M19.764 7.5H13V4H19.158L19.764 7.5Z");
}

</style>
