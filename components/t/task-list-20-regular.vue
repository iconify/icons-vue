<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="dyedfrb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:task-list-20-regular" /></template>
<style>
.dyedfrb6w {
  fill: currentColor;
  d: path("M5.854 4.354a.5.5 0 1 0-.708-.708L3.5 5.293l-.646-.647a.5.5 0 1 0-.708.708l1 1a.5.5 0 0 0 .708 0zM8.5 5a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1zm0 5a.5.5 0 0 0 0 1h9a.5.5 0 0 0 0-1zM8 15.5a.5.5 0 0 1 .5-.5h9a.5.5 0 0 1 0 1h-9a.5.5 0 0 1-.5-.5M5.854 9.854a.5.5 0 1 0-.708-.708L3.5 10.793l-.646-.647a.5.5 0 0 0-.708.708l1 1a.5.5 0 0 0 .708 0zm0 4.292a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708 0l-1-1a.5.5 0 0 1 .708-.708l.646.647l1.646-1.647a.5.5 0 0 1 .708 0");
}

</style>
