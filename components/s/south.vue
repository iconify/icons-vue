<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hc91lmb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:south" /></template>
<style>
.hc91lmb8b {
  fill: currentColor;
  d: path("m12 21l-6.346-6.346l.688-.688l5.158 5.151V2.981h1v16.117l5.158-5.157l.688.713z");
}

</style>
