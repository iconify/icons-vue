<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fo5znccjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-wrap-off-20-regular" /></template>
<style>
.fo5znccjb {
  fill: currentColor;
  d: path("M2.854 2.146a.5.5 0 1 0-.708.708L3.293 4H2.5a.5.5 0 0 0 0 1h1.793l4 4H2.5a.5.5 0 0 0 0 1h6.793l2.532 2.532a.5.5 0 0 0-.179.114l-1.5 1.5a.5.5 0 0 0 0 .708l1.5 1.5a.5.5 0 0 0 .708-.708L11.707 15h2.586l2.853 2.854a.5.5 0 0 0 .708-.708zM13.293 14h-1.586l.647-.646a.5.5 0 0 0 .114-.179zM11.12 9l1 1H16a2 2 0 0 1 .118 3.997l.845.845A3.001 3.001 0 0 0 16 9zm-5-5l1 1H17.5a.5.5 0 0 0 0-1zM2 14.5a.5.5 0 0 1 .5-.5h5a.5.5 0 0 1 0 1h-5a.5.5 0 0 1-.5-.5");
}

</style>
