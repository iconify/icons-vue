<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pzqp3ibvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rtp-play" /></template>
<style>
.pzqp3ibvn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.022 24L7.979 5.5v37zM18.66 11.667v24.667m10.68-18.501v12.333");
}

</style>
