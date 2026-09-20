<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ju9i4sfwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:photo-camera-back" /></template>
<style>
.ju9i4sfwz {
  fill: currentColor;
  d: path("M4.616 20q-.691 0-1.153-.462T3 18.384V7.616q0-.691.463-1.153T4.615 6h2.958l1.85-2h5.154l1.85 2h2.958q.69 0 1.152.463T21 7.616v10.769q0 .69-.463 1.153T19.385 20zM7.5 16.616h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115z");
}

</style>
