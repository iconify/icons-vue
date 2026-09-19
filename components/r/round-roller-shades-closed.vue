<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d7u_dgpyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-roller-shades-closed" /></template>
<style>
.d7u_dgpyp {
  fill: currentColor;
  d: path("M20 19V5c0-1.1-.9-2-2-2H6c-1.1 0-2 .9-2 2v14H3c-.55 0-1 .45-1 1s.45 1 1 1h7.25c0 .97.78 1.75 1.75 1.75s1.75-.78 1.75-1.75H21c.55 0 1-.45 1-1s-.45-1-1-1zM6 19v-2h5v2zm7 0v-2h5v2z");
}

</style>
