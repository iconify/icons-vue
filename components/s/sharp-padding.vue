<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmf0-0hbz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-padding" /></template>
<style>
.jmf0-0hbz {
  fill: currentColor;
  d: path("M3 3v18h18V3zm6 6H7V7h2zm4 0h-2V7h2zm4 0h-2V7h2z");
}

</style>
