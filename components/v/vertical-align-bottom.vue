<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1f6mbbnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:vertical-align-bottom" /></template>
<style>
.v1f6mbbnl {
  fill: currentColor;
  d: path("M5 20v-1h14v1zm7-3.692L7.692 12l.708-.708l3.1 3.1V4h1v10.392l3.1-3.1l.708.708z");
}

</style>
