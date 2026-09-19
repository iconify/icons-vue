<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ror_132vc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-camera-enhance" /></template>
<style>
.ror_132vc {
  fill: currentColor;
  d: path("M16.83 5L15 3H9L7.17 5H2v16h20V5zM12 18c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5m0-9l-1.25 2.75L8 13l2.75 1.25L12 17l1.25-2.75L16 13l-2.75-1.25z");
}

</style>
