<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gyhnusb2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rabab-sharp" /></template>
<style>
.gyhnusb2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V10M9.5 4H12m0 1.5h2.5M9.5 7H12m-2.75 3h6.25v2.168l-.95.432a4.45 4.45 0 1 1-5.1 0l-.95-.432V10zm0 6.5h5.5m-2.75 0V19");
}

</style>
