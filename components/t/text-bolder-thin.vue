<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="zaa81lbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:text-bolder-thin" /></template>
<style>
.zaa81lbmo {
  fill: currentColor;
  d: path("M162.3 117.2A40 40 0 0 0 140 44H64a4.1 4.1 0 0 0-4 4v152a4 4 0 0 0 4 4h88a44 44 0 0 0 10.3-86.8ZM68 52h72a32 32 0 0 1 0 64H68Zm84 144H68v-72h84a36 36 0 0 1 0 72Z");
}

</style>
