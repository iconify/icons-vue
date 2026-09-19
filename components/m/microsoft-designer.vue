<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vy9tqu0fh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:microsoft-designer" /></template>
<style>
.vy9tqu0fh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.625 23.992C12.609 23.982 8.055 16.698 7.93 8.1c-.026-1.67 1.142-2.6 2.6-2.6h11.68c9.112 0 17.544 7.513 17.861 18.5c-.317 10.99-8.75 18.5-17.865 18.5H10.53c-1.458 0-2.626-.93-2.6-2.6c.125-8.594 4.68-15.881 14.694-15.892L27.326 24a8.704 8.704 0 0 1 8.73 8.677v2.866");
}

</style>
