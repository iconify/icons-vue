<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_hxwsbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-hourglass-top" /></template>
<style>
.u_hxwsbht {
  fill: currentColor;
  d: path("m6 2l.01 6L10 12l-3.99 4.01L6 22h12v-6l-4-4l4-3.99V2zm10 14.5V20H8v-3.5l4-4z");
}

</style>
