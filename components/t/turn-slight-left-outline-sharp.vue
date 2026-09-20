<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2z28acvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-slight-left-outline-sharp" /></template>
<style>
.p2z28acvi {
  fill: currentColor;
  d: path("M13 20v-7.6l-5-5v2.25H6V4h5.65v2H9.4l5.6 5.6V20z");
}

</style>
