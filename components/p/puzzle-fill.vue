<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckwzrpb0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:puzzle-fill" /></template>
<style>
.ckwzrpb0q {
  fill: currentColor;
  d: path("M10 2C12.2092 2 14 3.79082 14 6H15C16.6569 6 18 7.34312 18 9V10C20.2092 10 22 11.7908 22 14C22 16.2092 20.2092 18 18 18V19C18 20.6569 16.6569 22 15 22H5C3.34312 22 2 20.6569 2 19V17.5C2 16.6716 2.67162 16 3.5 16H4C5.10462 16 6 15.1046 6 14C6 12.8954 5.10462 12 4 12H3.5C2.67162 12 2 11.3284 2 10.5V9C2 7.34312 3.34312 6 5 6H6C6 3.79082 7.79082 2 10 2Z");
}

</style>
