<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqxfwibxg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-desktop-mac" /></template>
<style>
.iqxfwibxg {
  fill: currentColor;
  d: path("M23 2H1v16h9l-2 3v1h8v-1l-2-3h9zm-2 12H3V4h18z");
}

</style>
