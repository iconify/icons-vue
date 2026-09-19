<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddrhh7k7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-5g" /></template>
<style>
.ddrhh7k7f {
  fill: currentColor;
  d: path("M17 13h2v2h-5V9h7V7h-9v10h9v-6h-4zM3 13h5v2H3v2h7v-6H5V9h5V7H3z");
}

</style>
