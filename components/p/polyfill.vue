<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh7lehbfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:polyfill" /></template>
<style>
.nh7lehbfw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.282 13.061l7.779-7.779a4 4 0 0 1 5.657 0a4 4 0 0 1 0 5.657l-7.779 7.779a4 4 0 0 1-5.657 0a4 4 0 0 1 0-5.657m2.122-1.415l4.95 4.95m-.708-9.192l4.95 4.95M12 12h.01");
}

</style>
