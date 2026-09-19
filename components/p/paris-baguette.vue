<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nky89ie-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paris-baguette" /></template>
<style>
.nky89ie-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.619 21.86A11 11 0 0 1 31.499 42h-14m12-16h2a5 5 0 1 1 0 10h-14m0-10v16h-6V26h-6v-6h6V6h18c5.523 0 10 4.477 10 10s-4.477 10-10 10zm0-14v8h12a4 4 0 1 0 0-8z");
}

</style>
