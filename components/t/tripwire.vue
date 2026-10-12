<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uul0tdbxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tripwire" /></template>
<style>
.uul0tdbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 7.5v12.25M19.25 7.5v12.25m-14.5-7h6l1.25-1.5l1.25 1.5h6M12 5.5v2.75m-3.25-2l1 1.5m5.5-1.5l-1 1.5");
}

</style>
