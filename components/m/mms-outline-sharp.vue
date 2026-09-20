<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pks_tqbgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:mms-outline-sharp" /></template>
<style>
.pks_tqbgf {
  fill: currentColor;
  d: path("M7.5 13.308h9.154l-2.827-3.77l-2.615 3.308l-1.75-2.115zM3 20.077V3h18v14H6.077zM5.65 16H20V4H4v13.644zM4 16V4z");
}

</style>
