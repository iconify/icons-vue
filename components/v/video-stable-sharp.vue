<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nsb0_pb_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:video-stable-sharp" /></template>
<style>
.nsb0_pb_t {
  fill: currentColor;
  d: path("M2 20V4h20v16zm14.975-2l2.3-8.65L7.075 6l-2.3 8.65z");
}

</style>
