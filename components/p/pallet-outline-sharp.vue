<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i02jdz3-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pallet-outline-sharp" /></template>
<style>
.i02jdz3-p {
  fill: currentColor;
  d: path("M2 22v-4h20v4h-3v-2h-5.5v2h-3v-2H5v2zm3-6V2h14v14zm2-2h10V4H7zm2-6h6V6H9zm-2 6V4z");
}

</style>
