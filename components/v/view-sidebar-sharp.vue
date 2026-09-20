<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w0pukz8vh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:view-sidebar-sharp" /></template>
<style>
.w0pukz8vh {
  fill: currentColor;
  d: path("M17 9V5h4v4zm0 5v-4h4v4zM3 19V5h13v14zm14 0v-4h4v4z");
}

</style>
