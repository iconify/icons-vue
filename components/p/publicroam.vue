<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xols-sdyj"/><path class="gp_mzbbvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:publicroam" /></template>
<style>
.gp_mzbbvo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.005 20.556a2.818 2.818 0 0 0 5.636 0v-1.832a2.818 2.818 0 0 0-5.636 0m0 0v8.454m2.818-14.576a6.123 6.123 0 0 0-6.123 6.122m6.123-9.546a9.546 9.546 0 0 0-9.546 9.546");
}

.xols-sdyj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.459 4.5c-7.236 0-13.102 5.866-13.102 13.101c0 10.253 10.003 22.591 12.623 25.622a.81.81 0 0 0 1.14.08l.08-.08C26.784 40.18 36.56 27.854 36.56 17.6c0-7.234-5.866-13.1-13.1-13.1");
}

</style>
