<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rpoz87_zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:transgender-sharp" /></template>
<style>
.rpoz87_zh {
  fill: currentColor;
  d: path("M14.475 13.975Q15.5 12.95 15.5 11.5t-1.025-2.475T12 8T9.525 9.025T8.5 11.5t1.025 2.475T12 15t2.475-1.025M11 23v-2H9v-2h2v-2.1q-1.95-.35-3.225-1.875T6.5 11.5q0-.825.238-1.625T7.45 8.4l-.65-.65l-1.4 1.4L4 7.75l1.4-1.425l-1.9-1.9V7h-2V1h6v2H4.925l1.9 1.9L8.25 3.5l1.4 1.4l-1.4 1.425l.65.65q.675-.5 1.475-.737T12 6t1.625.238t1.475.737L19.075 3H16.5V1h6v6h-2V4.425l-3.975 3.95q.475.7.725 1.488t.25 1.637q0 2-1.275 3.525T13 16.9V19h2v2h-2v2z");
}

</style>
