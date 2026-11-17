<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lnukntb5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:stroller-fill" /></template>
<style>
.lnukntb5h {
  fill: currentColor;
  d: path("M14 9V4a1 1 0 0 1 1-1a6.9 6.9 0 0 1 2.725.551A6.9 6.9 0 0 1 19.95 5.05A7 7 0 0 1 21.93 9ZM3 4h2c.409 0 .777.249.928.629L7.677 9H12v2h9.558A9.1 9.1 0 0 1 19 13.558v2.613a3 3 0 1 1-2 0v-1.618a9.1 9.1 0 0 1-6 0v1.618a3 3 0 1 1-2 0v-2.613a9.06 9.06 0 0 1-2.868-3.062a1 1 0 0 1-.06-.125h-.001L4.323 6H3a1 1 0 0 1 0-2m6.295 14.291l-.002.002l-.002.002l-.001.001a1 1 0 0 0 0 1.408l.001.001l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002l.001-.001a1 1 0 0 0 0-1.408l-.001-.001l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0m8.001-.001l-.001.001l-.002.002l-.002.002l-.001.001a1 1 0 0 0 0 1.408l.001.001l.002.002l.002.002l.001.001a1 1 0 0 0 1.408 0l.001-.001l.002-.002l.002-.002l.001-.001a1 1 0 0 0 0-1.408l-.001-.001l-.002-.002l-.002-.002l-.001-.001a1 1 0 0 0-1.408 0");
}

</style>
