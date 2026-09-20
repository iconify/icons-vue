<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="re8qaebdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:subject" /></template>
<style>
.re8qaebdw {
  fill: currentColor;
  d: path("M4 19v-2h10v2zm0-4v-2h16v2zm0-4V9h16v2zm0-4V5h16v2z");
}

</style>
