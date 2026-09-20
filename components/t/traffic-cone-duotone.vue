<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="gu0ourlyo"/><path class="eqq-ofbsn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:traffic-cone-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.eqq-ofbsn {
  d: path("M232 208h-18.31L153.42 34.75A16 16 0 0 0 138.31 24h-20.62a16 16 0 0 0-15.11 10.74L42.31 208H24a8 8 0 0 0 0 16h208a8 8 0 0 0 0-16M117.69 40h20.62L155 88h-54Zm-22.26 64h65.14l16.7 48H78.73ZM59.25 208l13.92-40h109.66l13.92 40Z");
}

.gu0ourlyo {
  d: path("M188.52 160h-121l22.22-64h76.52Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
