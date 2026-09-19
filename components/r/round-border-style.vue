<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rbodbdb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-border-style" /></template>
<style>
.rbodbdb_v {
  fill: currentColor;
  d: path("M15 21h2v-2h-2zm4 0h2v-2h-2zM7 21h2v-2H7zm4 0h2v-2h-2zm8-4h2v-2h-2zm0-4h2v-2h-2zM3 5v15c0 .55.45 1 1 1s1-.45 1-1V6c0-.55.45-1 1-1h14c.55 0 1-.45 1-1s-.45-1-1-1H5c-1.1 0-2 .9-2 2m16 4h2V7h-2z");
}

</style>
