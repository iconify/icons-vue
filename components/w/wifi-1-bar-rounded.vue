<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqq75b29n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wifi-1-bar-rounded" /></template>
<style>
.qqq75b29n {
  fill: currentColor;
  d: path("M10.908 19.977q-.446-.446-.446-1.092t.446-1.093T12 17.346t1.092.446t.446 1.093t-.446 1.092t-1.092.446t-1.092-.446");
}

</style>
