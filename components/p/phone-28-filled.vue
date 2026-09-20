<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="mgacj0bhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:phone-28-filled" /></template>
<style>
.mgacj0bhl {
  fill: currentColor;
  d: path("M7 4.75A2.75 2.75 0 0 1 9.75 2h8.5A2.75 2.75 0 0 1 21 4.75v18.5A2.75 2.75 0 0 1 18.25 26h-8.5A2.75 2.75 0 0 1 7 23.25zM12.25 21a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5z");
}

</style>
