<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gnb84-bhc"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zip" /></template>
<style>
.gnb84-bhc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.406 28l-.7-8h5.32c1.48 0 2.786 1.203 2.915 2.687s-.965 2.686-2.445 2.686h-5.32M9.048 20h8l-7.3 8h8m11.248 0h-9l-.7-8h9zm-6.894-11.39c-.075-.858-.83-1.552-1.687-1.552s-1.49.694-1.416 1.551s.83 1.552 1.687 1.552s1.49-.695 1.416-1.552");
}

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

</style>
