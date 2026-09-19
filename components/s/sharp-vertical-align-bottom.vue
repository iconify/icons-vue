<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nygylfb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-vertical-align-bottom" /></template>
<style>
.nygylfb8t {
  fill: currentColor;
  d: path("M16 13h-3V3h-2v10H8l4 4zM4 19v2h16v-2z");
}

</style>
