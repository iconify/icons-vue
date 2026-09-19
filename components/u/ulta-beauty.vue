<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ddd_qegti"/><path class="x9nlzowqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ulta-beauty" /></template>
<style>
.ddd_qegti {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.175 30.153a16.952 9.557 0 0 1-21.711-1.07a16.952 9.557 0 0 1-1.9-12.24");
}

.x9nlzowqt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.731 16.108v9.45h4.677m2.23-9.45h6.197m-3.098 9.451v-9.451m-20.434 0v6.32c0 1.729 1.387 3.13 3.098 3.13s3.098-1.401 3.098-3.13v-6.32m24.977 6.32h-4.144m-1.029 3.13l3.098-9.45l3.098 9.45");
}

</style>
