<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e3kmaemrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mytelkomsel" /></template>
<style>
.e3kmaemrf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.558 43.5c-1.662-5.297 12.827-14.125 12.827-21.707c0-7.27-12.256-15.216-15.943-17.293C24.104 9.797 9.615 18.625 9.615 26.207c0 7.27 12.256 15.216 15.943 17.293M27 18.5h1.969m-9.938 0H24m0 15v-15");
}

</style>
