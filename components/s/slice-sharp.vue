<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xhm72kd_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:slice-sharp" /></template>
<style>
.xhm72kd_b {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6.8465 12.5088L12.8418 6.2161C15.8394 3.0697 19.2363 2.3044 22 3.6037L10.3424 15.8395ZM7.1961 12.8419L2.533 17.7362C1.7972 18.5086 1.8268 19.7311 2.5991 20.4669C3.3715 21.2027 4.594 21.1732 5.3298 20.4008L9.9928 15.5065");
}

</style>
