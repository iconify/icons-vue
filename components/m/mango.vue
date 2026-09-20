<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="t40yacl5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mango" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.t40yacl5y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9 27.061v-6.123l3.1 6.201l3.1-6.201v6.201m7.791 0v-6.201l4.107 6.201v-6.201m9.809 6.2za2 2 0 0 1-2.015-2.015V23.03c0-1.162.93-2.092 2.015-2.092c1.163 0 2.093.93 2.093 2.092v2.015c0 1.163-.93 2.093-2.093 2.093m-3.817-4.184c0-1.163-.93-2.093-2.093-2.093s-2.093.93-2.093 2.093v2.093c0 1.162.93 2.015 2.093 2.015s2.093-.93 2.093-2.015h-2.093m-10.502-.001h-2.79m-.697 2.093l2.092-6.201l2.093 6.201");
}

</style>
