<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tviqh70qm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-auto-fix-high" /></template>
<style>
.tviqh70qm {
  fill: currentColor;
  d: path("m20 7l.94-2.06L23 4l-2.06-.94L20 1l-.94 2.06L17 4l2.06.94zM8.5 7l.94-2.06L11.5 4l-2.06-.94L8.5 1l-.94 2.06L5.5 4l2.06.94zM20 12.5l-.94 2.06l-2.06.94l2.06.94l.94 2.06l.94-2.06L23 15.5l-2.06-.94zm-1.59-2.67l-4.24-4.24L1.59 18.17l4.24 4.24zm-4.2 1.38L12.8 9.8l1.38-1.38l1.41 1.41z");
}

</style>
