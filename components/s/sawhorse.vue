<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa1kgbcwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:sawhorse" /></template>
<style>
.xa1kgbcwx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 4.25h-15q-.932 0-1.591.659T2.25 6.5q0 2.25 2.25 2.25h1.092l-1.095 5.694q-.118.106-.182.252q-.065.145-.065.304q0 .174.077.33l-1.064 5.528q-.013.073-.013.147t.015.146t.044.14t.07.13q.041.061.094.113t.114.092t.13.069t.141.042q.147.028.293-.002t.27-.114t.205-.208q.082-.125.111-.271l1.036-5.392h12.454l1.036 5.392q.014.072.042.141t.069.13t.092.114t.113.094t.13.07t.14.044t.146.015t.147-.013t.141-.042t.13-.069t.114-.092t.094-.113q.041-.062.07-.13t.044-.14t.015-.146t-.013-.147l-1.064-5.528q.077-.156.077-.33q0-.159-.065-.304q-.064-.146-.182-.252L18.408 8.75H19.5q2.25 0 2.25-2.25T19.5 4.25m-1.562 10H6.062l1.058-5.5h9.76z");
}

</style>
