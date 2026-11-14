<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb4g_yx_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:perfume-bottle" /></template>
<style>
.vb4g_yx_x {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 5.25q0-1.5.75-2.25T12 2.25q3 0 3 3q0 1.691-.953 2.429q.203.434.203 1.071q0 .289-.042.536q2.136.22 3.711 1.795q1.831 1.83 1.831 4.419t-1.831 4.419T13.5 21.75h-3q-2.589 0-4.419-1.831Q4.25 18.089 4.25 15.5t1.831-4.419q1.575-1.575 3.711-1.795q-.042-.247-.042-.536q0-.637.203-1.071Q9 6.941 9 5.25");
}

</style>
