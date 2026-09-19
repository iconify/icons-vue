<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7evb1cib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-iron" /></template>
<style>
.s7evb1cib {
  fill: currentColor;
  d: path("M18 6v8h-1V7H7v3h2V9h6v2H6c-2.21 0-4 1.79-4 4v3h15v-2h3V8h2V6z");
}

</style>
