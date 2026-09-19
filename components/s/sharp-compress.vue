<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo1oj3utg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-compress" /></template>
<style>
.eo1oj3utg {
  fill: currentColor;
  d: path("M4 9h16v2H4zm12-5h-3V1h-2v3H8l4 4zM8 19h3v3h2v-3h3l-4-4zm-4-7h16v2H4z");
}

</style>
