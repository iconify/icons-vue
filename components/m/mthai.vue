<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fw6mojbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mthai" /></template>
<style>
.fw6mojbnq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.62 33.99v4.142m-6.84 0V42.5m-9.744-8.51h3.905v8.51m0-8.51h4.934c.498 0 .903.402.904.9v3.129h6.84v4.48h1.897l3.582-7.959c.332-.738 1.617-.732 1.947 0m2.62 5.82h-7.141m4.521-5.819l2.62 5.82l.964 2.139h1.783v-8.51m-6.309-15.173l7.545-8.81m-7.545 8.81v11.616h7.545V9.903L32.172 5.5L24 15.722m-8.103 3.096l-7.545-8.812m7.545 8.811l8.104 9.4m8.102-9.4l-8.102 9.4V15.722L15.828 5.5L8.352 9.902v20.532h7.546V18.817");
}

</style>
