<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wy96vnrxk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-brush" /></template>
<style>
.wy96vnrxk {
  fill: currentColor;
  d: path("M7 14c-1.66 0-3 1.34-3 3c0 1.31-1.16 2-2 2c.92 1.22 2.49 2 4 2c2.21 0 4-1.79 4-4c0-1.66-1.34-3-3-3m13.71-9.37l-1.34-1.34a.996.996 0 0 0-1.41 0L9 12.25L11.75 15l8.96-8.96a.996.996 0 0 0 0-1.41");
}

</style>
