<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="it8s0_guq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-stay-current-landscape" /></template>
<style>
.it8s0_guq {
  fill: currentColor;
  d: path("M1 19h22V5H1zM19 7v10H5V7z");
}

</style>
