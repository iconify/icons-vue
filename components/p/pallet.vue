<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oq7sgpbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pallet" /></template>
<style>
.oq7sgpbiq {
  fill: currentColor;
  d: path("M2 22v-4h20v4h-3v-2h-5.5v2h-3v-2H5v2zm4-6q-.425 0-.712-.288T5 15V3q0-.425.288-.712T6 2h12q.425 0 .713.288T19 3v12q0 .425-.288.713T18 16zm3-8h6V6H9z");
}

</style>
