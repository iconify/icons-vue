<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdsbgw0rr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:save-outline-sharp" /></template>
<style>
.tdsbgw0rr {
  fill: currentColor;
  d: path("M21 7v14H3V3h14zm-2 .85L16.15 5H5v14h14zm-4.875 9.275Q15 16.25 15 15t-.875-2.125T12 12t-2.125.875T9 15t.875 2.125T12 18t2.125-.875M6 10h9V6H6zM5 7.85V19V5z");
}

</style>
