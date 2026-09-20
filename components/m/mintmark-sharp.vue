<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ggkqsib8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mintmark-sharp" /></template>
<style>
.ggkqsib8k {
  fill: currentColor;
  d: path("M13 21v-2h4.6L13 14.4v-2.8l6 6V13h2v8zm-7-4v-1H3v-2h6v-3H3V4h3V3h2v1h3v2H5v3h6v7H8v1z");
}

</style>
