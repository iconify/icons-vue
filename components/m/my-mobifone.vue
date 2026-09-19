<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g2l41wbze"/><path class="w39durt6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:my-mobifone" /></template>
<style>
.g2l41wbze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 38.32V20.65m-4.875 14.624V20.649M43.5 38.32l-4.875-3.046M4.5 38.32l4.875-3.046m17.062 3.046l-4.875-3.046M4.5 38.32V20.65m4.875 14.624V20.649M26.437 38.32V20.65m-4.875 14.624V20.649m-12.187 0a6.094 6.094 0 1 1 12.187 0m4.875 0a6.094 6.094 0 1 1 12.188 0");
}

.w39durt6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 20.649a10.969 10.969 0 0 1 19.499-6.895m.002-.001A10.969 10.969 0 0 1 43.5 20.648");
}

</style>
