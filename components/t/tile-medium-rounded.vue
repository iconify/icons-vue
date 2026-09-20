<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tegrb_trf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tile-medium-rounded" /></template>
<style>
.tegrb_trf {
  fill: currentColor;
  d: path("M3 18v-4q0-.425.288-.712T4 13h6q.425 0 .713.288T11 14v4q0 .425-.288.713T10 19H4q-.425 0-.712-.288T3 18m10 0v-4q0-.425.288-.712T14 13h6q.425 0 .713.288T21 14v4q0 .425-.288.713T20 19h-6q-.425 0-.712-.288T13 18M3 10V6q0-.425.288-.712T4 5h16q.425 0 .713.288T21 6v4q0 .425-.288.713T20 11H4q-.425 0-.712-.288T3 10");
}

</style>
