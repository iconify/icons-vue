<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vskshjb3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shoe-polish" /></template>
<style>
.vskshjb3k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.458 7.81l9.959-5.75q1.731-.999 2.731.732q.415.717.201 1.518q-.214.8-.932 1.214l-9.959 5.751q-.718.414-1.518.199q-.801-.214-1.215-.932q-.998-1.732.733-2.732M3.25 14q0-3 8.75-3t8.75 3v4q0 3-8.75 3t-8.75-3zm1.5 1.97V18q0 .364 1.796.869Q8.79 19.5 12 19.5t5.454-.631q1.796-.505 1.796-.869v-2.03Q17.127 17 12 17t-7.25-1.03");
}

</style>
