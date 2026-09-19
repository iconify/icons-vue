<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ffj0imlgj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-feed" /></template>
<style>
.ffj0imlgj {
  fill: currentColor;
  d: path("M16 3H3v18h18V8zM7 7h5v2H7zm10 10H7v-2h10zm0-4H7v-2h10zm-2-4V5l4 4z");
}

</style>
