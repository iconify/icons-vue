<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gjn4g4bwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:re-order-vertical-20-regular" /></template>
<style>
.gjn4g4bwv {
  fill: currentColor;
  d: path("M8 17.5a.5.5 0 0 0 1 0v-15a.5.5 0 0 0-1 0zm3 0a.5.5 0 0 0 1 0v-15a.5.5 0 0 0-1 0z");
}

</style>
