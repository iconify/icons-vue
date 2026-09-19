<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zv_m01c0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-account-balance" /></template>
<style>
.zv_m01c0a {
  fill: currentColor;
  d: path("M4 10v7h3v-7zm6 0v7h3v-7zM2 22h19v-3H2zm14-12v7h3v-7zm-4.5-9L2 6v2h19V6z");
}

</style>
