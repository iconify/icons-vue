<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yq8mo8u3d"/><path class="pkpd9ydpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vesync" /></template>
<style>
.pkpd9ydpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.837 25.522c0-1.18-.45-2.361-1.35-3.262c-1.802-1.802-4.952-2.005-6.525 0c-3.28 4.18-7.742 13.994-11.022 18.175c-1.573 2.004-4.722 1.802-6.524 0a4.6 4.6 0 0 1-1.35-3.262");
}

.yq8mo8u3d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.065 34.279V22.158m26.772 6.336v7.887a5.405 5.405 0 0 1-5.405 5.405H24M42.5 21.35L24 6.137L5.5 21.35m5.565-9.701V7.87");
}

</style>
