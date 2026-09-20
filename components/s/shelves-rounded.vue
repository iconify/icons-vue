<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xburhp6gj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shelves-rounded" /></template>
<style>
.xburhp6gj {
  fill: currentColor;
  d: path("M3.288 22.713Q3 22.425 3 22V2q0-.425.288-.712T4 1t.713.288T5 2v1h14V2q0-.425.288-.712T20 1t.713.288T21 2v20q0 .425-.288.713T20 23t-.712-.288T19 22v-1H5v1q0 .425-.288.713T4 23t-.712-.288M5 11h2V8q0-.425.288-.712T8 7h4q.425 0 .713.288T13 8v3h6V5H5zm0 8h6v-3q0-.425.288-.712T12 15h4q.425 0 .713.288T17 16v3h2v-6H5z");
}

</style>
