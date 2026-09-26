<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqwrcabqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:message-square-off" /></template>
<style>
.mqwrcabqx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 17L7 17L3 21L3 6C3 5.2044 3.3161 4.4413 3.8787 3.8787M8.6569 3L18 3C19.6569 3 21 4.3431 21 6L21 14C21 14.3854 20.9257 14.7672 20.7813 15.1244M2 2L22 22");
}

</style>
