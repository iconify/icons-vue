<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrzkgybst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-camera-outline-sharp" /></template>
<style>
.xrzkgybst {
  fill: currentColor;
  d: path("M7 18v3V3zm5.713-12.288Q13 5.425 13 5t-.288-.712T12 4t-.712.288T11 5t.288.713T12 6t.713-.288M17 18h2v5H5V1h14v5h-2V3H7v18h10zm-4-2V9h2.5l1-1h2l1 1H22v7zm5.738-2.262q.512-.513.512-1.238t-.513-1.237t-1.237-.513t-1.237.513t-.513 1.237t.513 1.238t1.237.512t1.238-.513");
}

</style>
