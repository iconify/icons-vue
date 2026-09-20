<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="dl3dfjbmi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-expand-32-regular" /></template>
<style>
.dl3dfjbmi {
  fill: currentColor;
  d: path("M29 25a1 1 0 1 1 0 2H9a1 1 0 1 1 0-2zM9 8.5a7.5 7.5 0 1 1 0 15a7.5 7.5 0 0 1 0-15m.25 2a.75.75 0 0 0-.75.75V15H4.75a.75.75 0 0 0 0 1.5H8.5v3.75a.75.75 0 0 0 1.5 0V16.5h3.75a.75.75 0 0 0 0-1.5H10v-3.75a.75.75 0 0 0-.75-.75M29 18a1 1 0 1 1 0 2H19a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H19a1 1 0 1 1 0-2zm0-7a1 1 0 1 1 0 2H9a1 1 0 0 1 0-2z");
}

</style>
