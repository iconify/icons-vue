<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="h3tu1ablx"/><path class="yglrxlepm"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pec-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h3tu1ablx {
  fill: var(--svg-color--4669d1, #4669d1);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.yglrxlepm {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.831 5.234C16.081 4.446 15.072 4 14.023 4H9.517C7.57 4 6 5.66 6 7.712V7.61v8.679C6 18.34 7.569 20 9.517 20c1.459 0 2.728-1.047 3.078-2.55l1.168-5.04c.43-.073.86-.146 1.27-.208C16.74 11.912 18 10.356 18 8.532V8.21c0-1.11-.42-2.178-1.159-2.966zm-4.916 11.53c-.27 1.245-1.269 2.127-2.408 2.127c-1.519 0-2.758-1.39-2.758-3.09v-.218c0-1.255.86-2.085 1.999-2.271c.02 0 .969-.176 2.188-.394c.59-.104 1.239-.208 1.898-.322l-.909 4.169z");
}

</style>
