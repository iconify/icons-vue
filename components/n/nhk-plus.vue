<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="x7bh8vkfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:nhk-plus" /></template>
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

.x7bh8vkfz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.14 27.75l2.017-7.514l3.04 7.514l2.016-7.514m3.431.001l-2.016 7.514m7.074-7.514l-2.016 7.514m-4.046-3.772h5.057m4.434-3.729l-2.016 7.514m.704-2.618l5.41-4.872m-2.009 7.49l-2.131-3.757m5.829 0h4.941m-2.471-2.529v5.057");
}

</style>
