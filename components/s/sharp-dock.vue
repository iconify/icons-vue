<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tqx3kwm5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-dock" /></template>
<style>
.tqx3kwm5o {
  fill: currentColor;
  d: path("M8 23h8v-2H8zM18 1.01L6 1v18h12zM16 15H8V5h8z");
}

</style>
