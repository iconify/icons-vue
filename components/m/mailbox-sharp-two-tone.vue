<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="an-hfnoxr"/><path class="dl24elbdt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:mailbox-sharp-two-tone" /></template>
<style>
.an-hfnoxr {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17 3C20.312 3 23 5.69 23 9V18C23 18.55 22.552 19 22 19H13V21H11V19H2C1.448 19 1 18.55 1 18V9C1 5.69 3.686 3 7 3H17Z");
  stroke: none;
}

.dl24elbdt {
  d: path("M7 4H17C19.76 4 22 6.24 22 9V18H11M7 4C4.239 4 2 6.24 2 9V18H12M7 4C9.761 4 12 6.24 12 9V18M12 18V21M5 9H9");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
