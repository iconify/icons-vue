<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bpsls5gij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-food-bank" /></template>
<style>
.bpsls5gij {
  fill: currentColor;
  d: path("M12 3L4 9v12h16V9zm.5 9.5c0 .83-.67 1.5-1.5 1.5v4h-1v-4c-.83 0-1.5-.67-1.5-1.5v-3h1v3h.5v-3h1v3h.5v-3h1zM15 18h-1v-3.5h-1v-3c0-1.1.9-2 2-2z");
}

</style>
