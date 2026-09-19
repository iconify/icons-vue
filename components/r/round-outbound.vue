<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc7gbbc0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-outbound" /></template>
<style>
.oc7gbbc0g {
  fill: currentColor;
  d: path("M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10s10-4.48 10-10S17.52 2 12 2m1.88 9.54l-4.25 4.25a.996.996 0 1 1-1.41-1.41l4.25-4.25l-1.27-1.27a.503.503 0 0 1 .35-.86h3.94c.28 0 .5.22.5.5v3.94c0 .45-.54.67-.85.35z");
}

</style>
