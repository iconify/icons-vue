<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihrj52b0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-fill" /></template>
<style>
.ihrj52b0i {
  fill: currentColor;
  d: path("M18 22H6a3 3 0 0 1-3-3V9c.001-1.348 1.478-2.357 2.553-2.894l6-3a1 1 0 0 1 .894 0l6 3C19.522 6.643 20.999 7.652 21 9v10a3 3 0 0 1-3 3m-2.536-9l.866-1.5a.998.998 0 0 0-.866-1.5h-1.732l-.866-1.5a1.002 1.002 0 0 0-1.732 0l-.866 1.5H8.536a1.002 1.002 0 0 0-.866 1.5l.866 1.5l-.866 1.5a.998.998 0 0 0 .866 1.5h1.732l.866 1.5a1.002 1.002 0 0 0 1.732 0l.866-1.5h1.732a1.002 1.002 0 0 0 .866-1.5Z");
}

</style>
