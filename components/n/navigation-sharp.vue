<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eld51ebxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:navigation-sharp" /></template>
<style>
.eld51ebxl {
  fill: currentColor;
  d: path("m5.962 19.5l-.462-.423L12 4.462l6.5 14.615l-.462.423L12 16.923z");
}

</style>
