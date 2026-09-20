<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5diiu3xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:umbrella-outline" /></template>
<style>
.f5diiu3xf {
  fill: currentColor;
  d: path("M11.716 21.424q-.118-.076-.185-.253L6.75 6.767l2.866.697L11.5 6.025V3.4q0-.788.58-1.344T13.5 1.5t1.42.556t.58 1.344V4h-1v-.6q0-.43-.294-.703t-.706-.272t-.706.291q-.294.292-.294.684v2.625l1.885 1.439l2.865-.697l-4.78 14.38q-.068.176-.186.265T12 21.5t-.284-.076m.784-3.49l3.2-9.795l-1.535.398L12.5 7.3zm-1 0V7.3L9.834 8.562l-1.578-.443z");
}

</style>
