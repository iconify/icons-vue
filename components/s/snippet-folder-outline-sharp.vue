<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j7a80db4i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:snippet-folder-outline-sharp" /></template>
<style>
.j7a80db4i {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm2-2h16V8h-8.825l-2-2H4zm0 0V6zm10.5-2.5v-5h1.375l1.625 1.625V15.5zM13 17h6v-5.5L16.5 9H13z");
}

</style>
