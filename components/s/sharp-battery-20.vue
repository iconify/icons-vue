<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dtr_d0o8k"/><path class="vxlz0wo_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-20" /></template>
<style>
.dtr_d0o8k {
  fill: currentColor;
  d: path("M7 17v5h10v-5z");
}

.vxlz0wo_h {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v13h10z");
}

</style>
