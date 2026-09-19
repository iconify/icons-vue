<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ede69qbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-roller-shades" /></template>
<style>
.ede69qbdv {
  fill: currentColor;
  d: path("M20 19V5c0-1.1-.9-2-2-2H6c-1.1 0-2 .9-2 2v14H3c-.55 0-1 .45-1 1s.45 1 1 1h18c.55 0 1-.45 1-1s-.45-1-1-1zM6 19v-6h5v1.8c-.4.3-.8.8-.8 1.4c0 1 .8 1.8 1.8 1.8s1.8-.8 1.8-1.8c0-.6-.3-1.1-.8-1.4V13h5v6z");
}

</style>
