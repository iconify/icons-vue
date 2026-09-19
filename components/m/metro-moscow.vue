<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nqhr4dbiv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:metro-moscow" /></template>
<style>
.nqhr4dbiv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.725 32.067a16.03 16.03 0 0 1-4.83-11.49C7.905 11.693 15.114 4.497 24 4.5c8.893 0 16.328 7.204 16.1 16.085c-.101 4.139-1.152 7.722-3.96 10.556L23.9 43.501m-5.737-17.829v-11.64l5.835 11.652l5.836-11.641v11.64");
}

</style>
