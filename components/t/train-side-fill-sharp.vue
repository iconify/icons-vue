<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfxsiab3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:train-side-fill-sharp" /></template>
<style>
.rfxsiab3n {
  fill: currentColor;
  d: path("M2 15V5a1 1 0 0 1 1-1h8a11 11 0 0 1 8.8 4.4l.325.43c.465.615.945 1.231 1.305 1.915c.366.696.57 1.468.57 2.255c0 .797-.314 1.558-.879 2.121A3 3 0 0 1 19 16H3a1 1 0 0 1-1-1m2-9v2h4V6Zm6 2h6.657A9 9 0 0 0 11 6h-1Zm11 10a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Z");
}

</style>
