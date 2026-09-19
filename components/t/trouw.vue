<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="lrggl-ytj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:trouw" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.lrggl-ytj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 18.66h5.751m-4.406 8.68l1.53-8.68M38.5 21.589l-2.804 5.751l-.777-5.751l-2.804 5.751l-.776-5.751M19.518 27.34c-1.199 0-1.999-.971-1.788-2.17l.249-1.41c.211-1.199 1.354-2.17 2.553-2.17h0c1.198 0 1.999.971 1.787 2.17l-.248 1.41c-.212 1.199-1.355 2.17-2.553 2.17m5.412-5.75l-.631 3.58c-.212 1.199.588 2.17 1.787 2.17h0c1.199 0 2.341-.971 2.553-2.17l.631-3.58m-.631 3.58l-.383 2.17m-13.904-3.58c.21-1.199 1.354-2.17 2.552-2.17h0m-2.17-.001L13.72 27.34");
}

</style>
