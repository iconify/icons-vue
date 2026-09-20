<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lj105zz1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:next-week-outline-sharp" /></template>
<style>
.lj105zz1c {
  fill: currentColor;
  d: path("M2 21V6h6V2h8v4h6v15zm2-2h16V8H4zm6-13h4V4h-4zM4 19V8zm7-1.5l4-4l-4-4l-1.4 1.4l2.6 2.6l-2.6 2.6z");
}

</style>
