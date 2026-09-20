<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-fqp1bus"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:stairs-2-rounded" /></template>
<style>
.j-fqp1bus {
  fill: currentColor;
  d: path("M3 19q-.425 0-.712-.288T2 18t.288-.712T3 17h5v-5q0-.425.288-.712T9 11h5V6q0-.425.288-.712T15 5h6q.425 0 .713.288T22 6t-.288.713T21 7h-5v5q0 .425-.288.713T15 13h-5v5q0 .425-.288.713T9 19z");
}

</style>
