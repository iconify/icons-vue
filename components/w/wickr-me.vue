<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="b0gl9mbll"/><rect class="j3s9ivbxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wickr-me" /></template>
<style>
.b0gl9mbll {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.875 14.457c-.321.641-1.069 1.068-1.816 1.068h0a2.143 2.143 0 0 1-2.137-2.136V12c0-1.175.961-2.137 2.137-2.137h0c1.175 0 2.136.962 2.136 2.137v.748h-4.273m-6.176-.705c0-1.194.977-2.171 2.17-2.171h0c1.195 0 2.172.977 2.172 2.171v3.474M9.404 9.872v5.645m0-3.474c0-1.194.977-2.171 2.17-2.171h0c1.195 0 2.172.977 2.172 2.171v3.474m10.066 22.62l14.784-14.784M14.098 38.137l14.784-14.784");
}

.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
