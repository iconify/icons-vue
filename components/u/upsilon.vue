<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="og34jvd-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:upsilon" /></template>
<style>
.og34jvd-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.304 5.5v11.284c0 6.615 4.505 12.397 10.967 14.076V42.5h7.458V30.86c6.462-1.679 10.967-7.461 10.967-14.076V5.5h-7.458v11.284c0 3.958-3.24 7.167-7.238 7.167s-7.238-3.209-7.238-7.167V5.5z");
}

</style>
