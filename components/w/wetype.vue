<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="px05azbfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wetype" /></template>
<style>
.px05azbfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.2 8.586h1.354c5.173 0 8.661 3.666 7.821 8.22s-5.682 8.222-10.855 8.222H5.5M24.747 8.587l-8.719 30.827");
}

</style>
