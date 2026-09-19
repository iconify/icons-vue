<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xz3dkdb-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-charging-station" /></template>
<style>
.xz3dkdb-y {
  fill: currentColor;
  d: path("m14.5 11l-3 6v-4h-2l3-6v4zM5 1h14v22H5zm2 5v12h10V6z");
}

</style>
