<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq-herb0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-launch" /></template>
<style>
.wq-herb0y {
  fill: currentColor;
  d: path("M19 19H5V5h7V3H3v18h18v-9h-2zM14 3v2h3.59l-9.83 9.83l1.41 1.41L19 6.41V10h2V3z");
}

</style>
