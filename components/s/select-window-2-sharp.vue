<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrjlbih3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:select-window-2-sharp" /></template>
<style>
.nrjlbih3m {
  fill: currentColor;
  d: path("M20 15V7H6V2h16v13zM2 22V9h16v13z");
}

</style>
