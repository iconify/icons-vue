<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vfq2nobmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-caret-right-sharp-fill" /></template>
<style>
.vfq2nobmf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 2L21 2C21.5523 2 22 2.4477 22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21L2 3C2 2.4477 2.4477 2 3 2ZM16.9856 12.8742C17.6715 12.4932 17.6715 11.5068 16.9856 11.1258L7.9856 6.1258C7.3191 5.7555 6.5 6.2375 6.5 7L6.5 17C6.5 17.7625 7.3191 18.2445 7.9856 17.8742L16.9856 12.8742Z");
}

</style>
