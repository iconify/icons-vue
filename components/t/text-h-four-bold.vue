<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ofefoqb5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-h-four-bold" /></template>
<style>
.ofefoqb5m {
  fill: currentColor;
  d: path("M156 56v120a12 12 0 0 1-24 0v-48H52v48a12 12 0 0 1-24 0V56a12 12 0 0 1 24 0v48h80V56a12 12 0 0 1 24 0m100 128a12 12 0 0 1-12 12v12a12 12 0 0 1-24 0v-12h-40a12 12 0 0 1-9.73-19l52-72a12 12 0 0 1 21.73 7v60a12 12 0 0 1 12 12m-36-34.89L203.47 172H220Z");
}

</style>
