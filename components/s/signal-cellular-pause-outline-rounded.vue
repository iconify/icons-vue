<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qou2r53ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:signal-cellular-pause-outline-rounded" /></template>
<style>
.qou2r53ww {
  fill: currentColor;
  d: path("M3.7 20.3L20.3 3.7q.475-.475 1.088-.213t.612.938V12q0 .425-.288.713T21 13t-.712-.288T20 12V6.825L6.825 20H12q.425 0 .713.288T13 21t-.288.713T12 22H4.425q-.675 0-.937-.612T3.7 20.3m11.588 1.413Q15 21.425 15 21v-5q0-.425.288-.712T16 15t.713.288T17 16v5q0 .425-.288.713T16 22t-.712-.288m4 0Q19 21.426 19 21v-5q0-.425.288-.712T20 15t.713.288T21 16v5q0 .425-.288.713T20 22t-.712-.288M13.425 13.4");
}

</style>
