<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s1sem7v0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:team-dashboard-sharp" /></template>
<style>
.s1sem7v0i {
  fill: currentColor;
  d: path("M10.5 20v-7.75H4V20zm1 0H20v-7.75h-8.5zM4 11.25h16V4H4z");
}

</style>
