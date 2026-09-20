<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n9avs0ujt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:toolbar-sharp" /></template>
<style>
.n9avs0ujt {
  fill: currentColor;
  d: path("M4 8V4h16v4zm0 12V9h16v11z");
}

</style>
