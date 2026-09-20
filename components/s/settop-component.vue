<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxasisbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:settop-component" /></template>
<style>
.uxasisbks {
  fill: currentColor;
  d: path("M2 17V7h20v10zm3-4h6v-2H5zm9.713-.288Q15 12.426 15 12t-.288-.712T14 11t-.712.288T13 12t.288.713T14 13t.713-.288m3 0Q18 12.426 18 12t-.288-.712T17 11t-.712.288T16 12t.288.713T17 13t.713-.288");
}

</style>
