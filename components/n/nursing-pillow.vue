<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhcv-ix5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:nursing-pillow" /></template>
<style>
.qhcv-ix5s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.761 11.376Q1.96 7.649 5.23 5.202q2.074-2.475 4.617-.408q2.582 2.097.485 4.679q-.045.055-.1.101q-.908.763-.977 1.947T10 13.568t2 .863t2-.863t.745-2.047t-.977-1.947q-.055-.046-.1-.101q-2.097-2.582.485-4.679q2.543-2.067 4.617.408q3.27 2.447 3.469 6.174q.202 3.778-2.877 6.49q-3.018 2.659-7.362 2.659t-7.362-2.659q-3.079-2.712-2.877-6.49");
}

</style>
