<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kk_myrbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:santander" /></template>
<style>
.kk_myrbxr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.822 22.04c0 6.941 7.608 12.114 8.306 18.096c0 0 1.381-1.381 1.381-4.736s-7.127-13.368-7.127-16.577c0-2.475.231-3.464 1.454-4.907c0 5.598 9.094 11.836 9.094 17.932c0 0 1.381-1.382 1.381-4.736s-7.127-13.368-7.127-16.577c0-2.475.231-3.464 1.453-4.907c0 4.452 5.754 9.34 8.108 16.56C39.123 23.942 43.5 27.55 43.5 31.717c0 5.885-8.73 10.656-19.5 10.656S4.5 37.602 4.5 31.716c0-4.29 4.637-7.986 11.322-9.676");
}

</style>
