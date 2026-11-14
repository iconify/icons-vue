<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i24r6jblh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:telescope-off" /></template>
<style>
.i24r6jblh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.782 15.705L8.818 18.01L5.99 15.182l2.272-2.921m3.499-4.499l.416-.535l-.884-.884l3.535-3.535l6.364 6.364l-3.535 3.535l-.884-.884l-.571.444m-10.92 6.451l2.122-2.122M3.5 3.5l17 17");
}

</style>
