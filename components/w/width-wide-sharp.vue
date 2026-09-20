<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u2ju54d9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:width-wide-sharp" /></template>
<style>
.u2ju54d9g {
  fill: currentColor;
  d: path("M2 20V4h20v16zm2-2h2V6H4zm14 0h2V6h-2z");
}

</style>
