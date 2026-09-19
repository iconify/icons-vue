<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x78t-5ygy"/><circle class="mxc6vr24n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-remember-me" /></template>
<style>
.mxc6vr24n {
  cx: 12px;
  cy: 10px;
  r: 3px;
  fill: currentColor;
}

.x78t-5ygy {
  fill: currentColor;
  d: path("M17 1H7c-1.1 0-2 .9-2 2v18c0 1.1.9 2 2 2h10c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 14.21c-1.5-.77-3.2-1.21-5-1.21s-3.5.44-5 1.21V6h10z");
}

</style>
