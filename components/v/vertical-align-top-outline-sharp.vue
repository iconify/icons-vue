<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a8sjy7wwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:vertical-align-top-outline-sharp" /></template>
<style>
.a8sjy7wwc {
  fill: currentColor;
  d: path("M4 5V3h16v2zm7 16V10.8l-2.6 2.6L7 12l5-5l5 5l-1.4 1.4l-2.6-2.6V21z");
}

</style>
