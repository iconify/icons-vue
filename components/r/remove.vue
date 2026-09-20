<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9wvvrbjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:remove" /></template>
<style>
.t9wvvrbjh {
  fill: currentColor;
  d: path("M5 13v-2h14v2z");
}

</style>
