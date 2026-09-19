<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkfswseve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-electric-meter" /></template>
<style>
.dkfswseve {
  fill: currentColor;
  d: path("M12 2c-4.96 0-9 4.04-9 9c0 3.91 2.51 7.24 6 8.47V22h2v-2.06a8.3 8.3 0 0 0 2 0V22h2v-2.53c3.49-1.24 6-4.57 6-8.47c0-4.96-4.04-9-9-9m2.25 12l-3 3l-1.5-1.5L11 14.25L9.75 13l3-3l1.5 1.5L13 12.75zM16 9H8V7h8z");
}

</style>
