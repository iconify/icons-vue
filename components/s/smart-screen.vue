<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsk279_4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:smart-screen" /></template>
<style>
.dsk279_4g {
  fill: currentColor;
  d: path("M6.751 12.52q.21-.209.21-.52t-.21-.52t-.52-.21t-.52.21q-.211.209-.211.52t.21.52t.52.21t.521-.21m3.846 0q.21-.209.21-.52t-.21-.52q-.209-.21-.52-.21q-.31 0-.52.21q-.21.209-.21.52t.209.52t.52.21t.521-.21m3.846 0q.21-.209.21-.52t-.209-.52t-.52-.21t-.521.21q-.21.209-.21.52t.21.52q.209.21.52.21q.31 0 .52-.21m3.847 0q.21-.209.21-.52t-.21-.52t-.52-.21t-.521.21q-.21.209-.21.52t.21.52t.52.21t.52-.21M3.617 18q-.691 0-1.153-.462T2 16.384V7.54q0-.667.475-1.141t1.14-.475h3.216q.04-.373.31-.648Q7.41 5 7.789 5h1.769q.379 0 .648.275t.31.648h9.869q.666 0 1.14.475T22 7.538v8.847q0 .666-.475 1.14t-1.14.475z");
}

</style>
