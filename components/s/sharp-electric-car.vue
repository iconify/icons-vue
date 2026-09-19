<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q6ksw5brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-electric-car" /></template>
<style>
.q6ksw5brh {
  fill: currentColor;
  d: path("M18.58 1H5.43L3 8v9h3v-2h12v2h3V8zM6.5 12c-.83 0-1.5-.67-1.5-1.5S5.67 9 6.5 9S8 9.67 8 10.5S7.33 12 6.5 12m11 0c-.83 0-1.5-.67-1.5-1.5S16.67 9 17.5 9s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5M5 7l1.5-4.5h11L19 7zm2 13h4v-2l6 3h-4v2z");
}

</style>
