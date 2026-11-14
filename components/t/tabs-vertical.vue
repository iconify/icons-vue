<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chps_ebwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tabs-vertical" /></template>
<style>
.chps_ebwf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.5 1.75h15q2.75 0 2.75 2.75V19q0 2.75-2.75 2.75h-8.25Q8.5 21.75 8.5 19V9.25h-4q-2.75 0-2.75-2.75v-2q0-1.139.805-1.945q.806-.805 1.945-.805m-.25 8.75q-1.036 0-1.768.732T1.75 13q0 2.5 2.5 2.5h.5q2.5 0 2.5-2.5t-2.5-2.5zm-1.768 6.982q.732-.732 1.768-.732h.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-.5q-1.036 0-1.768-.732T1.75 19.25t.732-1.768");
}

</style>
