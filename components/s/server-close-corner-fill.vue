<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ng-16rbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-close-corner-fill" /></template>
<style>
.ng-16rbve {
  fill: currentColor;
  d: path("M5 3h14a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3m2.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M9 21H5a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3h4a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m5.707-7.707L17 15.586l2.293-2.293a.999.999 0 1 1 1.414 1.414L18.414 17l2.293 2.293a.999.999 0 1 1-1.414 1.414L17 18.414l-2.293 2.293a.999.999 0 1 1-1.414-1.414L15.586 17l-2.293-2.293a.999.999 0 1 1 1.414-1.414M7.01 16H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2");
}

</style>
