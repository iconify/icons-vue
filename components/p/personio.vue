<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ku7zfu82r"/><circle class="y0qo7cbil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:personio" /></template>
<style>
.ku7zfu82r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.18 42.502h29.579M26.717 12.444l-6.454 24.083m-3.906-9.255c6.428.16 35.593-19.664 22.253-21.67C31.698 4.242 7.135 17.113 7.587 22.85c.052.667.8.761 1.866 1.114");
}

.y0qo7cbil {
  cx: 30.733px;
  cy: 35.307px;
  r: 0.75px;
  fill: currentColor;
}

</style>
