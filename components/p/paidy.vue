<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f2dq7ct8h"/><circle class="bba3q4btg"/><path class="lvdwwbcyq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paidy" /></template>
<style>
.bba3q4btg {
  cx: 40.094px;
  cy: 24.437px;
  r: 2.122px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.f2dq7ct8h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.094 30.156c0 2.274-1.2 4.379-3.156 5.537l-9.334 5.53a9.15 9.15 0 0 1-9.33 0l-9.334-5.53a6.44 6.44 0 0 1-3.156-5.537V16.1c0-4.409 3.352-8.277 7.756-8.482c2.606-.121 5.002.946 6.535 2.784c1.646 1.972 4.7 6.113 6.405 8.036c1.215 1.37 3.047 2.131 5.01 2.212c4.154.171 7.811-3.203 7.924-7.36A7.578 7.578 0 0 0 26.48 7.72");
}

.lvdwwbcyq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.844 35.087v-14.03");
}

</style>
