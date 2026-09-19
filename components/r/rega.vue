<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m1pwionrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:rega" /></template>
<style>
.m1pwionrw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.384 17.5H13.181l3.384-13h14.202zm10.818 13H24l3.384-13h14.202zm-17.586 13H6.414l3.384-13H24z");
}

</style>
