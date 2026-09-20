<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zukts29ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-layout-sharp" /></template>
<style>
.zukts29ki {
  fill: currentColor;
  d: path("M1 21v-6h10v6zm12 0V3h10v18zm5-3q.425 0 .713-.288T19 17t-.288-.712T18 16t-.712.288T17 17t.288.713T18 18M1 13V3h10v10zm6-5q.425 0 .713-.288T8 7t-.288-.712T7 6t-.712.288T6 7t.288.713T7 8m-4.25 3h4.5L5 8z");
}

</style>
