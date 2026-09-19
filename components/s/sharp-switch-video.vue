<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rfavfbb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-switch-video" /></template>
<style>
.rfavfbb2f {
  fill: currentColor;
  d: path("M18 9.5V5H2v14h16v-4.5l4 4v-13zm-5 6V13H7v2.5L3.5 12L7 8.5V11h6V8.5l3.5 3.5z");
}

</style>
