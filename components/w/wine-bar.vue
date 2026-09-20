<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xurycdbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:wine-bar" /></template>
<style>
.xurycdbqg {
  fill: currentColor;
  d: path("M8 21v-2h3v-4.1q-2.15-.35-3.575-2T6 9V3h12v6q0 2.25-1.425 3.9T13 14.9V19h3v2zM8 8h8V5H8z");
}

</style>
