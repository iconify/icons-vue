<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p1j9-otyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:monitor-weight-sharp" /></template>
<style>
.p1j9-otyn {
  fill: currentColor;
  d: path("M3 21V3h18v18zm11.125-9.875Q15 10.25 15 9t-.875-2.125T12 6t-2.125.875T9 9t.875 2.125T12 12t2.125-.875M10 9.5v-1h1v1zm1.5 0v-1h1v1zm1.5 0v-1h1v1z");
}

</style>
