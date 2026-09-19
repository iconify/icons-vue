<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ea6dtnbga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-addchart" /></template>
<style>
.ea6dtnbga {
  fill: currentColor;
  d: path("M11 9h2v8h-2zm-2 8v-6H7v6zm10 2H5V5h6V3H3v18h18v-8h-2zm-4-6v4h2v-4zm4-8V2h-2v3h-3v2h3v3h2V7h3V5z");
}

</style>
