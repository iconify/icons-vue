<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p0fl37bcy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-settings-ethernet" /></template>
<style>
.p0fl37bcy {
  fill: currentColor;
  d: path("M7.77 6.76L6.23 5.48L.82 12l5.41 6.52l1.54-1.28L3.42 12zM7 13h2v-2H7zm10-2h-2v2h2zm-6 2h2v-2h-2zm6.77-7.52l-1.54 1.28L20.58 12l-4.35 5.24l1.54 1.28L23.18 12z");
}

</style>
