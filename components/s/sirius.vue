<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hnxpo3ceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sirius" /></template>
<style>
.hnxpo3ceq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.505 11.474c5.954 8.386 5.169 20.103-2.348 27.62c-8.393 8.392-22.012 8.392-30.405 0C.358 30.7.358 17.08 8.752 8.687C16.268 1.17 27.985.386 36.372 6.34");
}

</style>
