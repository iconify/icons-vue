<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxd2m9zn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-24-filled" /></template>
<style>
.mhxd2m9zn {
  fill: currentColor;
  d: path("M21 18a1 1 0 1 1 0 2H6a1 1 0 1 1 0-2zM6.5 7a4.5 4.5 0 1 1 0 9a4.5 4.5 0 0 1 0-9m-2 4a.5.5 0 0 0 0 1h4a.5.5 0 0 0 0-1zM21 13a1 1 0 1 1 0 2h-7a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2h-7a1 1 0 1 1 0-2zm0-5a1 1 0 1 1 0 2H6a1 1 0 0 1 0-2z");
}

</style>
