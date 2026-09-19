<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pbx-3wbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-videogame-asset" /></template>
<style>
.pbx-3wbjl {
  fill: currentColor;
  d: path("M23 6H1v12h22zm-12 7H8v3H6v-3H3v-2h3V8h2v3h3zm4.5 2c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5m4-3c-.83 0-1.5-.67-1.5-1.5S18.67 9 19.5 9s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
}

</style>
