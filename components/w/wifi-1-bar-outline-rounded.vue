<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppytlccct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wifi-1-bar-outline-rounded" /></template>
<style>
.ppytlccct {
  fill: currentColor;
  d: path("M10.225 20.275Q9.5 19.55 9.5 18.5t.725-1.775T12 16t1.775.725t.725 1.775t-.725 1.775T12 21t-1.775-.725");
}

</style>
