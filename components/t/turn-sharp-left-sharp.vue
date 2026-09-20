<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t7zedfgwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:turn-sharp-left-sharp" /></template>
<style>
.t7zedfgwr {
  fill: currentColor;
  d: path("M16 21v-6H6V6.8L4.4 8.4L3 7l4-4l4 4l-1.4 1.4L8 6.8V13h10v8z");
}

</style>
