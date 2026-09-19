<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sbl3q_hii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-stop" /></template>
<style>
.sbl3q_hii {
  fill: currentColor;
  d: path("M16 8v8H8V8zm2-2H6v12h12z");
}

</style>
