<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6s657bdi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-padding" /></template>
<style>
.x6s657bdi {
  fill: currentColor;
  d: path("M3 5v14c0 1.1.9 2 2 2h14c1.1 0 2-.9 2-2V5c0-1.1-.9-2-2-2H5c-1.1 0-2 .9-2 2m6 3c0 .55-.45 1-1 1s-1-.45-1-1s.45-1 1-1s1 .45 1 1m4 0c0 .55-.45 1-1 1s-1-.45-1-1s.45-1 1-1s1 .45 1 1m4 0c0 .55-.45 1-1 1s-1-.45-1-1s.45-1 1-1s1 .45 1 1");
}

</style>
