<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywb28ib6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mitre-sharp" /></template>
<style>
.ywb28ib6z {
  fill: currentColor;
  d: path("M13 15V9h2.5V7H13V1h7v6h-2.5v2H20v6zm-9 8v-6h2.5v-2H4V9h2.5V7H4V1h7v6H8.5v2H11v6H8.5v2H11v6z");
}

</style>
