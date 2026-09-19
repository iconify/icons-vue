<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5i7robgd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:outline-emoji-flags" /></template>
<style>
.q5i7robgd {
  fill: currentColor;
  d: path("m14 9l-1-2H7V5.72c.6-.34 1-.98 1-1.72c0-1.1-.9-2-2-2s-2 .9-2 2c0 .74.4 1.38 1 1.72V21h2v-4h5l1 2h7V9zm4 8h-4l-1-2H7V9h5l1 2h5z");
}

</style>
