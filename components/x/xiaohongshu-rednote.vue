<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="ubixkt7iq"/><path class="xe95r4y5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:xiaohongshu-rednote" /></template>
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

.ubixkt7iq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.254 19.374v9.252m-5.781-7.776v7.776M24.95 20.85h3.047m-4.038 7.776h4.803m1.599-7.776h4.13c.49 0 .885.396.885.885v2.696");
}

.xe95r4y5f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.815 24.43h7.194a.99.99 0 0 1 .99.991v2.214a.99.99 0 0 1-.99.99h-1.83m1.859-7.308l.962-.89m-16.316 8.199h-2.118m-2.378-6.655l.697 5.07m-7.202-5.07L10 27.3m3.922-7.926v7.892c0 .75-.609 1.36-1.36 1.36H12.2m9.484-9.252l-1.367 3.253h1.866l-1.367 3.252h1.865");
}

</style>
