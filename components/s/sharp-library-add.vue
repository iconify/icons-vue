<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssrj8561x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-library-add" /></template>
<style>
.ssrj8561x {
  fill: currentColor;
  d: path("M4 6H2v16h16v-2H4zm18-4H6v16h16zm-3 9h-4v4h-2v-4H9V9h4V5h2v4h4z");
}

</style>
