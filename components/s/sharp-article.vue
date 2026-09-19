<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am437zbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-article" /></template>
<style>
.am437zbcu {
  fill: currentColor;
  d: path("M3 3v18h18V3zm11 14H7v-2h7zm3-4H7v-2h10zm0-4H7V7h10z");
}

</style>
