<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a6o0urbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:perk" /></template>
<style>
.a6o0urbkw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 21.523L4 23.45v3.641l15.003 1.287l1.254 1.228l1.892 14.368h3.702l1.892-14.368l1.254-1.228L44 27.09v-3.64zm1.84-17.495h-3.68l-1.87 13.657l3.71-.588l3.71.588z");
}

</style>
