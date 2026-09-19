<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="anoeir6zt"/><path class="qs882432w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:zoho-vault" /></template>
<style>
.anoeir6zt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 37.5c2.216 0 4-1.784 4-4v-24c0-2.216-1.784-4-4-4h-29c-2.216 0-4 1.784-4 4v24c0 2.216 1.784 4 4 4v3c0 1.108.892 2 2 2H15c1.108 0 2-.892 2-2v-1c0-1.108.892-2 2-2h10c1.108 0 2 .892 2 2v1c0 1.108.892 2 2 2h3.5c1.108 0 2-.892 2-2z");
}

.qs882432w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.343 20.005L20 22.187l6.658-2.182m-2.543 7.826L20 22.187l-4.114 5.644M20 15.168v7m14 5.664V15.169");
}

</style>
