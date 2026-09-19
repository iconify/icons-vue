<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="v4i2ew1ke"/><path class="zkn839b1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-photo-camera" /></template>
<style>
.v4i2ew1ke {
  cx: 12px;
  cy: 12px;
  r: 3px;
  fill: currentColor;
}

.zkn839b1k {
  fill: currentColor;
  d: path("M20 4h-3.17l-1.24-1.35A2 2 0 0 0 14.12 2H9.88c-.56 0-1.1.24-1.48.65L7.17 4H4c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m-8 13c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
}

</style>
