<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tafbr3qfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:north-rounded" /></template>
<style>
.tafbr3qfe {
  fill: currentColor;
  d: path("M11.288 21.713Q11 21.425 11 21V5.825L7.1 9.7q-.275.275-.687.288T5.7 9.7q-.275-.275-.275-.7t.275-.7l5.6-5.6q.15-.15.325-.212T12 2.425t.375.063t.325.212l5.6 5.6q.275.275.275.688T18.3 9.7q-.3.3-.712.3t-.713-.3L13 5.825V21q0 .425-.288.713T12 22t-.712-.288");
}

</style>
