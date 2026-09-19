<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3d85uqxm"/><path class="ym8zes7nn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-chair" /></template>
<style>
.u3d85uqxm {
  fill: currentColor;
  d: path("M7 13h10V7h3V3H4v4h3z");
}

.ym8zes7nn {
  fill: currentColor;
  d: path("M23 9h-4v6H5V9H1v10h3v1c0 .55.45 1 1 1s1-.45 1-1v-1h12v1c0 .55.45 1 1 1s1-.45 1-1v-1h3z");
}

</style>
