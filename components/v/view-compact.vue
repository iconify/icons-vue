<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cbvah06vk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:view-compact" /></template>
<style>
.cbvah06vk {
  fill: currentColor;
  d: path("M22 19.75V4.25zm-20-11v-4.5h4.25v4.5zm5.25 0v-4.5h4.25v4.5zm5.25 0v-4.5h4.25v4.5zm5.25 0v-4.5H22v4.5zm0 5.5v-4.5H22v4.5zm-5.25 0v-4.5h4.25v4.5zm-5.25 0v-4.5h4.25v4.5zm-5.25 0v-4.5h4.25v4.5zm15.75 5.5v-4.5H22v4.5zm-5.25 0v-4.5h4.25v4.5zm-5.25 0v-4.5h4.25v4.5zm-5.25 0v-4.5h4.25v4.5z");
}

</style>
