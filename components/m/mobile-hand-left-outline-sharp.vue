<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-6g01b3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mobile-hand-left-outline-sharp" /></template>
<style>
.q-6g01b3c {
  fill: currentColor;
  d: path("M18 20v-7.425v1.7V4zM7 23q-1.65 0-2.825-1.175T3 19v-8l4-4h2v8.875l4.2-2.075l2.15 2.15L10.3 22q-.425.475-1 .738T8.075 23zm3.3-1l1.675-2H18V4H9v3H7V2h13v20zm3.913-15.288Q14.5 6.425 14.5 6t-.288-.712T13.5 5t-.712.288T12.5 6t.288.713T13.5 7t.713-.288M7 21h1.075q.225 0 .425-.088t.35-.262l3.45-4.2L7 19.125V9.9l-2 2V19q0 .85.588 1.425T7 21");
}

</style>
