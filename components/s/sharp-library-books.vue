<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j3a4yebvh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-library-books" /></template>
<style>
.j3a4yebvh {
  fill: currentColor;
  d: path("M4 6H2v16h16v-2H4zm18-4H6v16h16zm-3 9H9V9h10zm-4 4H9v-2h6zm4-8H9V5h10z");
}

</style>
