<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0zbhv_dd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:schema-sharp" /></template>
<style>
.i0zbhv_dd {
  fill: currentColor;
  d: path("M4 23v-6h2.5v-2H4V9h2.5V7H4V1h7v6H8.5v2H11v2h3V9h7v6h-7v-2h-3v2H8.5v2H11v6z");
}

</style>
