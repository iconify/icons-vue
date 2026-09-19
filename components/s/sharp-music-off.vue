<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="af56uwbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-music-off" /></template>
<style>
.af56uwbjv {
  fill: currentColor;
  d: path("M14 9.61V7h4V3h-6v4.61zM4.41 2.86L3 4.27l9 9v.28c-.94-.54-2.1-.75-3.33-.32c-1.34.48-2.37 1.67-2.61 3.07a4.007 4.007 0 0 0 4.59 4.65c1.96-.31 3.35-2.11 3.35-4.1v-1.58L19.73 21l1.41-1.41L12 10.44z");
}

</style>
