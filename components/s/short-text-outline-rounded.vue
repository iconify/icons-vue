<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mneoaccvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:short-text-outline-rounded" /></template>
<style>
.mneoaccvk {
  fill: currentColor;
  d: path("M5 15q-.425 0-.712-.288T4 14t.288-.712T5 13h8q.425 0 .713.288T14 14t-.288.713T13 15zm0-4q-.425 0-.712-.288T4 10t.288-.712T5 9h14q.425 0 .713.288T20 10t-.288.713T19 11z");
}

</style>
