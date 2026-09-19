<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fp0cz4b8m"/><circle class="aqszcbwbb"/><circle class="w3n24fbgj"/><path class="pwp7wrb7q"/><path class="h2otdgi-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-taxi-alert" /></template>
<style>
.aqszcbwbb {
  cx: 6.5px;
  cy: 15.5px;
  r: 1.5px;
  fill: currentColor;
}

.fp0cz4b8m {
  fill: currentColor;
  d: path("M4 18h14v-5H4zm11.5-4c.83 0 1.5.67 1.5 1.5s-.67 1.5-1.5 1.5s-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5m-9 0c.83 0 1.5.67 1.5 1.5S7.33 17 6.5 17S5 16.33 5 15.5S5.67 14 6.5 14");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.h2otdgi-r {
  fill: currentColor;
  d: path("M18 1c-2.76 0-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5s-2.24-5-5-5m.5 2v4h-1V3zm0 6h-1V8h1z");
}

.pwp7wrb7q {
  fill: currentColor;
  d: path("M18 18H4v-5h14c-1.91 0-3.63-.76-4.89-2h-8.3l1.04-3h5.44C11.1 7.37 11 6.7 11 6s.1-1.37.29-2H8v2H5.5c-.66 0-1.21.42-1.42 1.01L2 13v8c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-1h12v1c0 .55.45 1 1 1h1c.55 0 1-.45 1-1v-8l-.09-.27c-.61.17-1.25.27-1.91.27z");
}

.w3n24fbgj {
  cx: 15.5px;
  cy: 15.5px;
  r: 1.5px;
  fill: currentColor;
}

</style>
