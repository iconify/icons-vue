<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv7gr-brn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tile-large-outline-sharp" /></template>
<style>
.hv7gr-brn {
  fill: currentColor;
  d: path("M3 21v-6h8v6zm10 0v-6h8v6zm-8-2h4v-2H5zm10 0h4v-2h-4zM3 13V3h18v10zm14 5");
}

</style>
