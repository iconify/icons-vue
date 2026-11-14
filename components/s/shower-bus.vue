<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f89dzobmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shower-bus" /></template>
<style>
.f89dzobmi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.8 17.5H3.5v-15h12v11M3.5 10h12m-9 4h.01m5.99 0h.01M6.5 17.5V20m6-2.5V20m3-1.5a3 3 0 0 1 6 0Zm3-5v2M17 21.25h.01m2.99 0h.01");
}

</style>
