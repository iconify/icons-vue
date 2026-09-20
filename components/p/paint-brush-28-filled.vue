<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="r7gqgqn6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:paint-brush-28-filled" /></template>
<style>
.r7gqgqn6z {
  fill: currentColor;
  d: path("M17 6.25a.75.75 0 0 1-1.5 0V2H6.75a.75.75 0 0 0-.75.75V13h16V2.75a.75.75 0 0 0-.75-.75H20v6.25a.75.75 0 0 1-1.5 0V2H17zM6 14.5v1.75A2.75 2.75 0 0 0 8.75 19h2.75v4.5a2.5 2.5 0 0 0 5 0V19h2.75A2.75 2.75 0 0 0 22 16.25V14.5z");
}

</style>
