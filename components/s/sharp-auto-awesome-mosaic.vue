<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srk9s2h0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-auto-awesome-mosaic" /></template>
<style>
.srk9s2h0i {
  fill: currentColor;
  d: path("M3 21h8V3H3zM21 3h-8v8h8zm-8 18h8v-8h-8z");
}

</style>
