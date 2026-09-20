<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppg_lklbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:report" /></template>
<style>
.ppg_lklbv {
  fill: currentColor;
  d: path("M12 16.423q.262 0 .439-.182t.176-.433t-.177-.434t-.438-.182t-.438.182t-.177.434t.177.433t.438.182m-.5-2.961h1V7.385h-1zM8.673 20L4 15.336V8.673L8.664 4h6.663L20 8.664v6.663L15.336 20z");
}

</style>
