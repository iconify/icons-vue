<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="qs16tfbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:task-list-rectangle-28-regular" /></template>
<style>
.qs16tfbzj {
  fill: currentColor;
  d: path("M9.97 15.22a.75.75 0 1 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-1-1a.75.75 0 1 1 1.06-1.06l.47.47zM20.5 16a.75.75 0 0 1 0 1.5h-7a.75.75 0 0 1 0-1.5zM9.97 9.72a.75.75 0 1 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-1-1a.75.75 0 1 1 1.06-1.06l.47.47zm10.53.78a.75.75 0 0 1 0 1.5h-7a.75.75 0 0 1 0-1.5zM22.248 4a3.75 3.75 0 0 1 3.75 3.75v12.5a3.75 3.75 0 0 1-3.75 3.75H5.752a3.75 3.75 0 0 1-3.75-3.75V7.75A3.75 3.75 0 0 1 5.752 4zM5.752 5.5a2.25 2.25 0 0 0-2.25 2.25v12.5a2.25 2.25 0 0 0 2.25 2.25h16.496a2.25 2.25 0 0 0 2.25-2.25V7.75a2.25 2.25 0 0 0-2.25-2.25z");
}

</style>
