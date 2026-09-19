<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r7sbz51hb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-directions-off" /></template>
<style>
.r7sbz51hb {
  fill: currentColor;
  d: path("m13 7.5l3.5 3.5l-1.33 1.34l3.45 3.45L22.41 12L12.01 1.58l-3.8 3.8L13 10.17zM1.39 4.22l3.99 3.99L1.59 12l10.42 10.4l3.79-3.79l3.99 3.99l1.41-1.41L2.81 2.81zm8.6 8.6V15h-2v-4.18z");
}

</style>
