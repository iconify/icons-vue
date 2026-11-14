<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj_jm--sd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:one-to-one" /></template>
<style>
.bj_jm--sd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-3.75 3.75-3.75q3.354 0 3.708 3h5.584q.354-3 3.708-3q3.75 0 3.75 3.75t-3.75 3.75q-3.354 0-3.708-3H9.208q-.354 3-3.708 3q-3.75 0-3.75-3.75");
}

</style>
