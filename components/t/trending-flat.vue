<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fhl8kcbfh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:trending-flat" /></template>
<style>
.fhl8kcbfh {
  fill: currentColor;
  d: path("m22 12l-4-4v3H3v2h15v3z");
}

</style>
