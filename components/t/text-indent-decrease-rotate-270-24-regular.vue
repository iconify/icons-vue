<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikbn93boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-indent-decrease-rotate-270-24-regular" /></template>
<style>
.ikbn93boi {
  fill: currentColor;
  d: path("M16 6.25a.75.75 0 0 1 1.5 0v9a.75.75 0 0 1-1.5 0zm-4.78 15.03l-2-2a.75.75 0 0 1 .976-1.133l.084.073l1.47 1.47l1.47-1.47a.75.75 0 0 1 1.133.976l-.073.084l-2 2a.75.75 0 0 1-.976.073zM11 3.25a.75.75 0 0 1 1.5 0v12a.75.75 0 0 1-1.5 0zm-5 3a.75.75 0 0 1 1.5 0v9a.75.75 0 0 1-1.5 0z");
}

</style>
