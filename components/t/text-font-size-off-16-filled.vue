<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vw2po-bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-size-off-16-filled" /></template>
<style>
.vw2po-bju {
  fill: currentColor;
  d: path("M1.146 1.147a.5.5 0 0 1 .708 0l13 13a.5.5 0 1 1-.707.707L9.793 10.5H8.389l-1.184 3.256a.751.751 0 0 1-1.397.032L5.27 12.5H2.73l-.538 1.288a.75.75 0 0 1-1.384-.576l2.5-6l.05-.1a.75.75 0 0 1 1.334.1l1.76 4.224l1.14-3.137l-6.446-6.445a.5.5 0 0 1 0-.707m9.354.603a.75.75 0 0 1 .705.494l3.908 10.748L11.121 9h.944L10.5 4.694l-.983 2.702l-1.17-1.17l1.448-3.982a.75.75 0 0 1 .705-.494M3.355 11h1.29L4 9.45z");
}

</style>
