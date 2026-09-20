<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hao_l5bco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:turn-slight-left" /></template>
<style>
.hao_l5bco {
  fill: currentColor;
  d: path("M13.5 19.77v-7.062q0-.116-.039-.221t-.134-.202L7.712 6.689v2.98h-1V5h4.669v1H8.4l5.621 5.602q.217.217.348.522t.131.628v7.017z");
}

</style>
