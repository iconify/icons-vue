<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x620qib3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:person-home-48-regular" /></template>
<style>
.x620qib3i {
  fill: currentColor;
  d: path("M33.048 24.722a3 3 0 0 1 3.904 0l8 6.852A3 3 0 0 1 46 33.852V44a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2v-6a2 2 0 0 0-2-2h-4a2 2 0 0 0-2 2v6a2 2 0 0 1-2 2h-3a2 2 0 0 1-2-2V33.853a3 3 0 0 1 1.048-2.279zm-9.3 5.334a5 5 0 0 0-.455.444H12.25a1.75 1.75 0 0 0-1.75 1.749V33c0 2.744 1.36 4.808 3.72 6.245c1.991 1.212 4.685 1.96 7.78 2.183v2.505c-3.449-.228-6.62-1.056-9.08-2.553C9.942 39.567 8 36.755 8 33v-.751A4.25 4.25 0 0 1 12.25 28h13.897zM24 4c5.523 0 10 4.477 10 10s-4.477 10-10 10s-10-4.477-10-10S18.477 4 24 4m0 2.5a7.5 7.5 0 1 0 0 15a7.5 7.5 0 0 0 0-15");
}

</style>
