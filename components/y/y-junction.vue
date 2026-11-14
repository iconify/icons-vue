<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npihnkotn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:y-junction" /></template>
<style>
.npihnkotn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 21.5v-7c0-3.5-5-5.5-5.5-12m10.5 19v-7c0-3.5 5-5.5 5.5-12m-11.25 0C9.5 6 12 7.5 12 10c0-2.5 2.5-4 3.25-7.5M12 14.5v4");
}

</style>
