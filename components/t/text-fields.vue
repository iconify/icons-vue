<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="asdbeh1oc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:text-fields" /></template>
<style>
.asdbeh1oc {
  fill: currentColor;
  d: path("M7 20V7H2V4h13v3h-5v13zm9 0v-8h-3V9h9v3h-3v8z");
}

</style>
