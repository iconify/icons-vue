<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="ha16swhxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shifts-28-regular" /></template>
<style>
.ha16swhxz {
  fill: currentColor;
  d: path("M14.5 7.75a.75.75 0 0 0-1.5 0v7c0 .414.336.75.75.75h5.5a.75.75 0 0 0 0-1.5H14.5zM6.25 3A3.25 3.25 0 0 0 3 6.25v15.5A3.25 3.25 0 0 0 6.25 25h15.5A3.25 3.25 0 0 0 25 21.75V6.25A3.25 3.25 0 0 0 21.75 3zM4.5 6.25c0-.966.784-1.75 1.75-1.75h15.5c.966 0 1.75.784 1.75 1.75v15.5a1.75 1.75 0 0 1-1.75 1.75H6.25a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
