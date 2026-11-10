<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h8qf08b1m"/><path class="t3xrhccsr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:text-align-justify-character-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h8qf08b1m {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 20V22H2V20H22ZM22 14V16H2V14H22ZM7 2C7.359 2 7.69 2.19 7.868 2.5L11.998 9.73L10.262 10.73L8.705 8H5.295L3.738 10.73L2.002 9.73L6.167 2.44C6.354 2.2 6.686 2 7 2ZM22 8V10H14V8H22ZM6.438 6H7.562L7 5.02L6.438 6ZM22 2V4H14V2H22Z");
}

.t3xrhccsr {
  d: path("M22 22H2V20H22V22ZM22 16H2V14H22V16ZM22 10H14V8H22V10ZM22 4H14V2H22V4Z");
}

</style>
