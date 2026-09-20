<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtdmqnbzt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:verse" /></template>
<style>
.qtdmqnbzt {
  fill: var(--svg-color--0085ff, #0085ff);
  d: path("m12.402 6.706l-1.64-2.647H3l8.92 15.882l1.668-2.78L7.664 6.707zm-2.54 1.588h3.218l1.287 2.139l3.414-6.374H21l-6.633 11.795z");
}

</style>
