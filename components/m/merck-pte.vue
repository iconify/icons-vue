<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a5x81kb0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:merck-pte" /></template>
<style>
.a5x81kb0o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.424 8.151c-1.692 0-6.834 8.404-13.424 8.404S12.268 8.151 10.576 8.151H5.5v14.237a2.86 2.86 0 0 0 2.85 2.85h2.226V20.34c0-1.915.935-2.894 2.838-2.894c3.04 0 7.09 6.857 10.586 6.857s7.547-6.857 10.586-6.857c1.903 0 2.838.98 2.838 2.894v2.048a2.85 2.85 0 0 0 2.85 2.85H42.5V10.15a2 2 0 0 0-2-2zM14.862 39.849v-8h2.619c1.48 0 2.68 1.203 2.68 2.686s-1.2 2.687-2.68 2.687h-2.62m14.277-1.373h2.608m1.392 4h-4v-8h4m-11.232 0h5.3m-2.65 8v-8");
}

</style>
