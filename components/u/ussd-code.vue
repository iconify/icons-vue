<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="prkw795-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ussd-code" /></template>
<style>
.prkw795-d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H6V6H2.5Zm6.5 0h3.5V6H9Zm6.5 0H19V6h-3.5ZM2.5 9H6v3.5H2.5ZM9 9h3.5v3.5H9Zm6.5 0H19v3.5h-3.5Zm-13 6.5H6V19H2.5Zm6.5 0h3.5V19H9Zm8.25 0v6m2.75-6v6M15.75 17h5.75m-5.75 3h5.75");
}

</style>
