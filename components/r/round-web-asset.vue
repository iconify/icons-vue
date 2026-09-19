<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="obko32bhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-web-asset" /></template>
<style>
.obko32bhm {
  fill: currentColor;
  d: path("M19 4H5a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h14c1.1 0 2-.9 2-2V6a2 2 0 0 0-2-2m-1 14H6c-.55 0-1-.45-1-1V8h14v9c0 .55-.45 1-1 1");
}

</style>
