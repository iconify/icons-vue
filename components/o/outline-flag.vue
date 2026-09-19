<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e3a7sacgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-flag" /></template>
<style>
.e3a7sacgj {
  fill: currentColor;
  d: path("m12.36 6l.4 2H18v6h-3.36l-.4-2H7V6zM14 4H5v17h2v-7h5.6l.4 2h7V6h-5.6z");
}

</style>
