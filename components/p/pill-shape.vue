<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qgv_t39ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:pill-shape" /></template>
<style>
.qgv_t39ay {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.5 6.25h9q2.382 0 4.066 1.684T22.25 12t-1.684 4.066T16.5 17.75h-9q-2.382 0-4.066-1.684T1.75 12t1.684-4.066T7.5 6.25");
}

</style>
