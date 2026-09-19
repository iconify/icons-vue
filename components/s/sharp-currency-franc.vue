<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jr0advatx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-currency-franc" /></template>
<style>
.jr0advatx {
  fill: currentColor;
  d: path("M18 5V3H7v13H5v2h2v3h2v-3h4v-2H9v-3h8v-2H9V5z");
}

</style>
