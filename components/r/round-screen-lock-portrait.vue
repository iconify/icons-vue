<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="my8zvrh4c"/><path class="ej11ccbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-screen-lock-portrait" /></template>
<style>
.ej11ccbfm {
  fill: currentColor;
  d: path("M14 11v-1c0-1.1-.9-2-2-2s-2 .9-2 2v1c-.55 0-1 .45-1 1v3c0 .55.45 1 1 1h4c.55 0 1-.45 1-1v-3c0-.55-.45-1-1-1m-1 0h-2v-1c0-.55.45-1 1-1s1 .45 1 1z");
}

.my8zvrh4c {
  fill: currentColor;
  d: path("M17 1H7c-1.1 0-2 .9-2 2v18c0 1.1.9 1.99 2 1.99L17 23c1.1 0 2-.9 2-2V3c0-1.1-.9-2-2-2m0 17H7V6h10z");
}

</style>
