<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz6wiwb7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-new-label" /></template>
<style>
.fz6wiwb7o {
  fill: currentColor;
  d: path("m20.18 13.16l-3.55 5c-.38.53-.98.84-1.63.84h-3v-3c0-1.66-1.34-3-3-3c0-1.66-1.34-3-3-3H3V7c0-1.1.9-2 2-2h10c.65 0 1.26.31 1.63.84l3.55 5c.49.7.49 1.62 0 2.32M10 16c0-.55-.45-1-1-1H7v-2c0-.55-.45-1-1-1s-1 .45-1 1v2H3c-.55 0-1 .45-1 1s.45 1 1 1h2v2c0 .55.45 1 1 1s1-.45 1-1v-2h2c.55 0 1-.45 1-1");
}

</style>
