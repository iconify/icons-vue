<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t8hhx0b_l"/><path class="ey6g09wif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:recommendation-jp" /></template>
<style>
.ey6g09wif {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.163 17.561l-4.356-4.755c-2.352-2.568-6.633-.904-6.633 2.579v9.198c0 3.483 4.28 5.147 6.633 2.58l4.356-4.756a3.587 3.587 0 0 0 0-4.845Z");
}

.t8hhx0b_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5c-8.803 0-15.94 7.136-15.94 15.94V43.5h5.338a6.776 6.776 0 0 0 6.776-6.776v-.826c1.228.303 2.505.481 3.826.481c8.803 0 15.94-7.136 15.94-15.94S32.803 4.5 24 4.5m5.006.804v9.903m-8.832 20.708V24.583");
}

</style>
