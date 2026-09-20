<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":135};
const content = `<path class="q8_nnghpa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:openframeworks" /></template>
<style>
.q8_nnghpa {
  d: path("M67.49 0c37.237 0 67.492 30.255 67.492 67.49c0 37.237-30.255 67.492-67.491 67.492S0 104.727 0 67.49S30.255 0 67.49 0m128 0v134.982h-58.18V0zm37.237 60.51v34.908h-34.909V60.51zM256 0l-58.182 58.182V0z");
}

</style>
