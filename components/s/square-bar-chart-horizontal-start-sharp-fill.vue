<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ae_8ftbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-bar-chart-horizontal-start-sharp-fill" /></template>
<style>
.ae_8ftbeg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM7 9L11.6667 9L11.6667 7L7 7L7 9ZM7 13L17 13L17 11L7 11L7 13ZM7 17L14.3333 17L14.3333 15L7 15L7 17Z");
}

</style>
