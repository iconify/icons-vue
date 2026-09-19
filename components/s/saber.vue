<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ppx2-xbhb"/><path class="agtiik0ly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:saber" /></template>
<style>
.agtiik0ly {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 29.29H29.29V42.5m-1.21-27.343c-7.104-2.86-10.606.644-10.92 3.689c-.568 5.506 10.19.902 11.123 5.88s-7.37 9.984-12.6 5.345");
}

.ppx2-xbhb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h19.79L42.5 29.29V9.5a4 4 0 0 0-4-4");
}

</style>
