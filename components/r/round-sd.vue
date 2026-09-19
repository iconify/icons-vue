<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3394z0vq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-sd" /></template>
<style>
.i3394z0vq {
  fill: currentColor;
  d: path("M20 4H4a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2m-7 5h4c.55 0 1 .45 1 1v4c0 .55-.45 1-1 1h-4zm-3.5 4.5v-1H7c-.55 0-1-.45-1-1V10c0-.55.45-1 1-1h3c.55 0 1 .45 1 1v1H9.5v-.5h-2v1H10c.55 0 1 .45 1 1V14c0 .55-.45 1-1 1H7c-.55 0-1-.45-1-1v-1h1.5v.5zm5 0h2v-3h-2z");
}

</style>
