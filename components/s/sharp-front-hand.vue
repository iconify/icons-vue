<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxpxm0tkq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-front-hand" /></template>
<style>
.yxpxm0tkq {
  fill: currentColor;
  d: path("M18.5 8v7H18c-1.65 0-3 1.35-3 3h-1c0-2.04 1.53-3.72 3.5-3.97V2H15v9h-1V0h-2.5v11h-1V1.5H8V12H7V4.5H4.5v11.25c0 4.56 3.69 8.25 8.25 8.25S21 20.31 21 15.75V8z");
}

</style>
