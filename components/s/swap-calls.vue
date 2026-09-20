<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip0fwbbeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:swap-calls" /></template>
<style>
.ip0fwbbeg {
  fill: currentColor;
  d: path("M6.308 18L3 14.692l.708-.719l2.1 2.1V8.365q0-1.4.973-2.373t2.373-.973t2.373.973q.973.974.973 2.374v6.288q0 .979.684 1.662q.683.684 1.662.684t1.663-.684t.683-1.662V6.946l-2.1 2.1l-.707-.719l3.307-3.308L21 8.327l-.708.72l-2.1-2.1v7.707q0 1.4-.973 2.373T14.846 18t-2.373-.973t-.973-2.373V8.366q0-.98-.684-1.663q-.683-.684-1.662-.684t-1.663.684t-.683 1.663v7.707l2.1-2.1l.708.72z");
}

</style>
