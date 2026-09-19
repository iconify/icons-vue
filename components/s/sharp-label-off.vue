<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="si2s-cc_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-label-off" /></template>
<style>
.si2s-cc_t {
  fill: currentColor;
  d: path("m22 12l-4.97-7H8.66l10.7 10.73zM2 4l1 1v14h14l2 2l1.41-1.41L3.44 2.62z");
}

</style>
