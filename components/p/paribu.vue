<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="skcr2nqlu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:paribu" /></template>
<style>
.skcr2nqlu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.902 43.5v-39m-6.482 0h17.62c5.3 0 9.54 4.24 9.54 9.539s-4.24 9.539-9.54 9.539H10.42");
}

</style>
