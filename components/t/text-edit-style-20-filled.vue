<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="lycz5i9im"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-edit-style-20-filled" /></template>
<style>
.lycz5i9im {
  fill: currentColor;
  d: path("M14.087 6.703a2.263 2.263 0 0 1 3.07-.126l.13.12l.126.137a2.28 2.28 0 0 1 0 2.951l-.12.13l-6.876 6.903a1.5 1.5 0 0 1-.547.35l-.157.048l-3.086.76a.5.5 0 0 1-.618-.526l.015-.084l.792-3.07a1.5 1.5 0 0 1 .283-.566l.106-.119zM6.424 2.23l.042.084l2.982 7.63l-.772.774l-.672-1.719H4.007l-1.04 2.68a.5.5 0 0 1-.561.31l-.087-.025a.5.5 0 0 1-.31-.56l.025-.087l3.5-9.002a.5.5 0 0 1 .89-.085m-.423 1.64L4.396 7.998h3.218z");
}

</style>
