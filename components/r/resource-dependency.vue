<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qurq3_w3t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:resource-dependency" /></template>
<style>
.qurq3_w3t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75q-3.75 0-3.75 3.75q0 3.354 3 3.708v5.584q-3 .354-3 3.708q0 3.75 3.75 3.75t3.75-3.75q0-.617-.101-1.132l5.287-2.847Q15.853 15.75 18 15.75q3.75 0 3.75-3.75T18 8.25q-2.147 0-3.064 1.229L9.649 6.632q.101-.515.101-1.132q0-3.75-3.75-3.75m.75 13.042V9.208q1.566-.185 2.314-1.187l5.287 2.847q-.101.515-.101 1.132t.101 1.132l-5.287 2.847q-.748-1.002-2.314-1.187");
}

</style>
