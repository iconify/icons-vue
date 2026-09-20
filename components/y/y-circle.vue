<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srsjnzvag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:y-circle" /></template>
<style>
.srsjnzvag {
  fill: currentColor;
  d: path("M11.546 17.539h.92v-3.972L15.59 7.77h-1.01L12 12.6L9.45 7.77H8.41l3.136 5.842zm-3.052 2.76q-1.642-.701-2.867-1.926t-1.926-2.867T3 12t.701-3.506t1.926-2.857T8.494 3.71T12 3t3.506.71t2.857 1.927t1.926 2.857T21 12t-.71 3.506t-1.926 2.867t-2.858 1.926T12 21t-3.506-.701");
}

</style>
