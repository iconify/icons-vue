<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lk2vjsbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:signal-cellular-add" /></template>
<style>
.lk2vjsbzo {
  fill: currentColor;
  d: path("M18.5 21v-3h-3v-1h3v-3h1v3h3v1h-3v3zM3 21L20.994 3.006v8.933q-.386-.17-.976-.27T19 11.566q-2.47 0-4.201 1.732q-1.732 1.731-1.732 4.201q0 .939.299 1.84q.298.9.855 1.66z");
}

</style>
