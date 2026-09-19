<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp37qvbds"/><circle class="su3kdjb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-sports-martial-arts" /></template>
<style>
.rp37qvbds {
  fill: currentColor;
  d: path("M19.06 2.6L11.6 8.7l-1.21-1.04l2.48-1.43a1 1 0 0 0 .21-1.57l-2.95-2.95a.996.996 0 1 0-1.41 1.41l2.03 2.03l-5.4 3.11a1 1 0 0 0-.46.6l-.96 3.49c-.07.26-.04.53.1.77l1.74 3.02c.28.48.89.64 1.37.37c.48-.28.64-.89.37-1.37l-1.53-2.66l.36-1.29L9.5 13l.44 8c.03.56.49 1 1.05 1s1.02-.44 1.05-1l.45-9l7.87-7.96a.972.972 0 0 0-1.3-1.44");
}

.su3kdjb3z {
  cx: 5px;
  cy: 5px;
  r: 2px;
  fill: currentColor;
}

</style>
