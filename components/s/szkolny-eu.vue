<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wklvjyxyu"/><circle class="e-q1bpood"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:szkolny-eu" /></template>
<style>
.e-q1bpood {
  cx: 23.912px;
  cy: 25.745px;
  r: 4.221px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.wklvjyxyu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.717 41.597H5.5V24.869m12.217 16.728V24.869m0 16.728h3.625m8.766 0H42.5V24.869M30.108 41.597V24.869m0 16.728h-3.617m-8.774-16.728v-5.244H5.5v5.244m12.217 0H5.5m24.608 0v-5.244H42.5v5.244m-12.392 0H42.5m-26.32-3.69l7.733-8.176l7.721 8.176m-7.721 2.646v1.964h1.864m-4.435 15.808v-6.43c0-1.25 1.32-2.293 2.57-2.294c1.254-.002 2.579 1.04 2.579 2.294v6.43m-5.15 0h5.15M23.932 6.403c3.694 0 1.446.884 6.142.884l.001 3.553c-4.798 0-2.45-.923-6.142-.923z");
}

</style>
