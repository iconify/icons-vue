<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gln3qm4mt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-grid-3x3" /></template>
<style>
.gln3qm4mt {
  fill: currentColor;
  d: path("M20 9c0-.55-.45-1-1-1h-3V5c0-.55-.45-1-1-1s-1 .45-1 1v3h-4V5c0-.55-.45-1-1-1s-1 .45-1 1v3H5c-.55 0-1 .45-1 1s.45 1 1 1h3v4H5c-.55 0-1 .45-1 1s.45 1 1 1h3v3c0 .55.45 1 1 1s1-.45 1-1v-3h4v3c0 .55.45 1 1 1s1-.45 1-1v-3h3c.55 0 1-.45 1-1s-.45-1-1-1h-3v-4h3c.55 0 1-.45 1-1m-6 5h-4v-4h4z");
}

</style>
