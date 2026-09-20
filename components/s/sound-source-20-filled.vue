<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gd89d3bra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-source-20-filled" /></template>
<style>
.gd89d3bra {
  fill: currentColor;
  d: path("M3 10a7 7 0 1 1 12.14 4.752l.65.768a8 8 0 1 0-11.58 0l.65-.768A6.98 6.98 0 0 1 3 10m11.162 3.596a5.5 5.5 0 1 0-8.323 0l.655-.775a4.5 4.5 0 1 1 7.012 0zm-1.652-1.952a3 3 0 1 0-5.02 0l.69-.815a2 2 0 1 1 3.641 0zm-2.128-.967a.5.5 0 0 0-.764 0l-5.5 6.5A.5.5 0 0 0 4.5 18h11a.5.5 0 0 0 .382-.823z");
}

</style>
