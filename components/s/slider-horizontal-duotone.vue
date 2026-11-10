<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zmc4g-b1r"/><path class="la9cdqbrj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slider-horizontal-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.la9cdqbrj {
  d: path("M17 15C19.2092 15 21 16.79 21 19C21 21.21 19.2092 23 17 23H15C12.7908 23 11 21.21 11 19C11 16.79 12.7908 15 15 15H17Z");
}

.zmc4g-b1r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 18C12.5523 18 13 18.45 13 19C13 19.55 12.5523 20 12 20H2C1.4477 20 1 19.55 1 19C1 18.45 1.4477 18 2 18H12ZM22 18C22.5523 18 23 18.45 23 19C23 19.55 22.5523 20 22 20H20C19.4477 20 19 19.55 19 19C19 18.45 19.4477 18 20 18H22ZM20 1C21.6569 1 23 2.34 23 4V10C23 11.66 21.6569 13 20 13H4C2.3432 13 1 11.66 1 10V4C1 2.34 2.3431 1 4 1H20Z");
}

</style>
