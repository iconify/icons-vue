<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xjvv5xafc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-add-20-filled" /></template>
<style>
.xjvv5xafc {
  fill: currentColor;
  d: path("M3 3.75A.75.75 0 0 1 3.75 3h10a.75.75 0 0 1 .75.75v1.5a.75.75 0 0 1-1.5 0V4.5H9.5v7.706A5.5 5.5 0 0 0 9 14.5c0 .9.216 1.75.6 2.5H6.75a.75.75 0 0 1 0-1.5H8v-11H4.5v.75a.75.75 0 0 1-1.5 0zM19 14.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4-2a.5.5 0 0 0-1 0V14h-1.5a.5.5 0 0 0 0 1H14v1.5a.5.5 0 0 0 1 0V15h1.5a.5.5 0 0 0 0-1H15z");
}

</style>
