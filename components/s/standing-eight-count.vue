<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itaz6uayy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:standing-eight-count" /></template>
<style>
.itaz6uayy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.464 3.464Q7 4.929 7 7t1.464 3.536q.372.371.783.648q-.702.39-1.313 1Q6.25 13.868 6.25 16.25t1.684 4.066T12 22t4.066-1.684t1.684-4.066t-1.684-4.066q-.611-.61-1.313-1q.411-.277.783-.648Q17 9.071 17 7t-1.464-3.536T12 2T8.464 3.464");
}

</style>
