<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qyybg5byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-send" /></template>
<style>
.qyybg5byb {
  fill: currentColor;
  d: path("m4.01 6.03l7.51 3.22l-7.52-1zm7.5 8.72L4 17.97v-2.22zM2.01 3L2 10l15 2l-15 2l.01 7L23 12z");
}

</style>
