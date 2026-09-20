<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jpkh_x32w"/><path class="b50v9_b6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:whatsappwebtogo" /></template>
<style>
.b50v9_b6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.14 17.36A1.61 1.61 0 0 0 30.53 19v16.5a1.61 1.61 0 0 0 1.61 1.6h10.25A1.61 1.61 0 0 0 44 35.49V19a1.61 1.61 0 0 0-1.61-1.61Zm8.64 14.77h-7V20.58h7Z");
}

.jpkh_x32w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.47 14.14v-3.21H10.75a3.23 3.23 0 0 0-3.22 3.21v18H4v4.94h23.51v-4.95H10.75v-18Z");
}

</style>
