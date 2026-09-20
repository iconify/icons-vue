<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="kdagjgbfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:yougov" /></template>
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

.kdagjgbfj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m39.5 22.803l-1.842 4.881l-1.842-4.881m-17.121 0v3.039a1.842 1.842 0 0 0 3.684 0v-3.04m0 3.04v1.842m-8.998-7.368L10.941 24L8.5 20.316m2.441 7.368V24m18.145-1.243a2.44 2.44 0 0 0-4.881 0v2.486a2.44 2.44 0 0 0 4.881 0h-2.44m-13.486-.598a1.842 1.842 0 0 1 3.684 0v1.197a1.842 1.842 0 0 1-3.684 0zm17.583 0a1.842 1.842 0 0 1 3.684 0v1.197a1.842 1.842 0 0 1-3.684 0z");
}

</style>
