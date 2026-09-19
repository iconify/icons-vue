<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffns4ybyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-featured-play-list" /></template>
<style>
.ffns4ybyp {
  fill: currentColor;
  d: path("M23 3H1v18h22zm-11 8H3V9h9zm0-4H3V5h9z");
}

</style>
