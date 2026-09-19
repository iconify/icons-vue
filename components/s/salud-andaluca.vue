<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="dsmh6rbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:salud-andaluca" /></template>
<style>
.dsmh6rbal {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.773 16.227h5.789m-2.906-2.939v5.947M12.5 25.247h11.174M12.5 28.89h9.714M12.5 32.629h8.153m5.085 1.407l4.795-9.973l4.423 9.879c-1.304-.94-2.43-2.054-4.984-1.759");
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
