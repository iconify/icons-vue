<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z1zft6bgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:next-24-filled" /></template>
<style>
.z1zft6bgu {
  fill: currentColor;
  d: path("M3 4.753c0-1.408 1.578-2.24 2.74-1.444l10.498 7.194a1.75 1.75 0 0 1 .01 2.88L5.749 20.685C4.59 21.492 3 20.66 3 19.248zM21 3.75a.75.75 0 0 0-1.5 0v16.5a.75.75 0 0 0 1.5 0z");
}

</style>
