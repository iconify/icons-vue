<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmi8epdoy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:statement-passbook" /></template>
<style>
.mmi8epdoy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6c-2-1.5-5-2-9.5-1.5v14C7 18 10 18.5 12 20c2-1.5 5-2 9.5-1.5v-14C17 4 14 4.5 12 6Zm0 0v14M5.5 8.5h4m-4 3h4m-4 3h4m5-6h4m-4 3h4");
}

</style>
