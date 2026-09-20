<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba2ca2jpb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:switch-access-sharp" /></template>
<style>
.ba2ca2jpb {
  fill: currentColor;
  d: path("M7.692 16.308V7.692h8.616v8.616zm-3.692 0v-1.231h1.23v1.23zm0-7.385v-1.23h1.23v1.23zM7.692 20v-1.23h1.231V20zm0-14.77V4h1.231v1.23zM15.077 20v-1.23h1.23V20zm0-14.77V4h1.23v1.23zm3.692 11.078v-1.231H20v1.23zm0-7.385v-1.23H20v1.23z");
}

</style>
