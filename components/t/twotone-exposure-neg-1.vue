<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nos1pgduy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-exposure-neg-1" /></template>
<style>
.nos1pgduy {
  fill: currentColor;
  d: path("M19 18V5h-.3L14 6.7v1.7l3-1.02V18zM4 11h8v2H4z");
}

</style>
