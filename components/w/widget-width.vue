<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjut-502m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:widget-width" /></template>
<style>
.hjut-502m {
  fill: currentColor;
  d: path("M2 22v-6h6v6zm7 0v-6h6v6zm7 0v-6h6v6zM2 15V9h6v6zm7 0V9h6v6zm7 0V9h6v6zM2 8V2h20v6z");
}

</style>
