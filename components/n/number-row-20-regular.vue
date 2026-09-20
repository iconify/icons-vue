<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l2uk5yzax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:number-row-20-regular" /></template>
<style>
.l2uk5yzax {
  fill: currentColor;
  d: path("M5 6.5a.5.5 0 0 1 1 0v7a.5.5 0 0 1-1 0zM4 3a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zM3 5a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1zm10.5 1a.5.5 0 0 0 0 1H15v2.5h-1.5a.5.5 0 0 0-.5.5v3.5a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 0-1H14v-2.5h1.5a.5.5 0 0 0 .5-.5V6.5a.5.5 0 0 0-.5-.5zM13 3a2 2 0 0 0-2 2v10a2 2 0 0 0 2 2h3a2 2 0 0 0 2-2V5a2 2 0 0 0-2-2zm-1 2a1 1 0 0 1 1-1h3a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1h-3a1 1 0 0 1-1-1z");
}

</style>
