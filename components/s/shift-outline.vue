<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o9tunqyot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:shift-outline" /></template>
<style>
.o9tunqyot {
  fill: currentColor;
  d: path("M8 21v-8H3l9-11l9 11h-5v8zm2-2h4v-8h2.775L12 5.15L7.225 11H10zm2-8");
}

</style>
