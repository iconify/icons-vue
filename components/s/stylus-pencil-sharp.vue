<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk_x74hud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:stylus-pencil-sharp" /></template>
<style>
.jk_x74hud {
  fill: currentColor;
  d: path("M6.923 15.308L11.346 4h1.289l4.423 11.308zM5 20l.827-2.308h12.346L19 20z");
}

</style>
