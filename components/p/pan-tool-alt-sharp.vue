<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xt5l1rbts"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:pan-tool-alt-sharp" /></template>
<style>
.xt5l1rbts {
  fill: currentColor;
  d: path("M8.525 21L1.15 11.925l1.775-1.7L7 13.075V2h2v9h2V6h2v5h2V7h2v4h2V9h2v12z");
}

</style>
