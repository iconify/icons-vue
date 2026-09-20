<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbm2u_bkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:split-scene-left-sharp" /></template>
<style>
.vbm2u_bkj {
  fill: currentColor;
  d: path("M14.885 19V5H20v14zM11.5 21v-2H4V5h7.5V3h1v18z");
}

</style>
