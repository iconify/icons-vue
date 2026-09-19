<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6fqggbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-message" /></template>
<style>
.t6fqggbqi {
  fill: currentColor;
  d: path("M22 2H2.01L2 22l4-4h16zm-4 12H6v-2h12zm0-3H6V9h12zm0-3H6V6h12z");
}

</style>
