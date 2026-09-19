<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bnrwytbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:you-have-mail" /></template>
<style>
.bnrwytbng {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.628 16.173L5.5 41.79h37V16.173H21.154v7.116h-4.981V11.904H24V6.212H11.192v9.961z");
}

</style>
