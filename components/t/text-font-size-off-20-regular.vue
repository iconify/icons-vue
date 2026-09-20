<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fqqeedb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-font-size-off-20-regular" /></template>
<style>
.fqqeedb2b {
  fill: currentColor;
  d: path("M2.147 2.147a.5.5 0 0 1 .707 0l15 15a.5.5 0 0 1-.707.707L11.793 12.5h-1.446l-1.38 3.676a.5.5 0 0 1-.93.01L6.96 13.5H4.038l-1.074 2.686a.5.5 0 0 1-.928-.371l1.195-2.99l.01-.021l1.795-4.49a.5.5 0 0 1 .928 0l1.796 4.49l.009.021l.715 1.791l1.043-2.781l.01-.022l.426-1.143l-7.816-7.816a.5.5 0 0 1 0-.707M13 3.5a.5.5 0 0 1 .468.324l2.996 7.99l.008.021l1.496 3.99l.008.03l-1.704-1.705l-.619-1.65h-1.032l-1-1h1.657L13 5.424L11.512 9.39l-.777-.777l1.796-4.79A.5.5 0 0 1 13 3.5m-8.561 9h2.123L5.5 9.847z");
}

</style>
