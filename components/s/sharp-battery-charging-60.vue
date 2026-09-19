<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lyow0wb0a"/><path class="ipfvtgbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-battery-charging-60" /></template>
<style>
.ipfvtgbrq {
  fill: currentColor;
  d: path("M13 12.5h2L11 20v-5.5H9l1.87-3.5H7v11h10V11h-4z");
}

.lyow0wb0a {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-3, 0.3);
  d: path("M17 4h-3V2h-4v2H7v7h3.87L13 7v4h4z");
}

</style>
