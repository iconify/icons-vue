<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_eqm4hkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:notes-outline" /></template>
<style>
.c_eqm4hkc {
  fill: currentColor;
  d: path("M3 18v-2h12v2zm0-5v-2h18v2zm0-5V6h18v2z");
}

</style>
