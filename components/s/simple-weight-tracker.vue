<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fzjuq7b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:simple-weight-tracker" /></template>
<style>
.fzjuq7b0a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.843 5.723c6.894-2.065 18.022 10.709 20.56 17.265c0 0 5.53 12.343 13.97 13.469l.071 5.731s-8.091 4.33-21.563-19.27c-2.83-5.513-8.087-11.155-13.325-11.105z");
}

</style>
