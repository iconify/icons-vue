<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glfby3bkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vertical-distribute-sharp" /></template>
<style>
.glfby3bkz {
  fill: currentColor;
  d: path("M3 21v-1.23h18V21zm4.5-8v-2h9v2zM3 4.23V3h18v1.23z");
}

</style>
