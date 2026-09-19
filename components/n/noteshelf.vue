<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fv6zw5bwu"/><path class="awi6awgfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:noteshelf" /></template>
<style>
.awi6awgfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.018 6.982a5.06 5.06 0 0 0-7.22.067l-11.553 11.99l6.716 6.715l11.99-11.552a5.06 5.06 0 0 0 .067-7.22m-19.252 9.263l8.79-9.166a2.27 2.27 0 0 1 3.242-.03M15.832 36.297l-7.85 5.88c-1.426 1.068-3.227-.733-2.159-2.159l5.88-7.85");
}

.fv6zw5bwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m28.516 25.309l-5.825-5.825l-11.608 12.065l5.368 5.368z");
}

</style>
