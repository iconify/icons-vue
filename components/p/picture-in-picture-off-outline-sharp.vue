<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdxb2jb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:picture-in-picture-off-outline-sharp" /></template>
<style>
.qdxb2jb-q {
  fill: currentColor;
  d: path("M15.504 12.692H19V7h-7.692v1.496l1 1V8H18v3.692h-3.496zM20 17.19V6H8.812l-1-1H21v13.189zm1.104 5.342L17.573 19H3V5h2l1 1H4v12h12.573L1.881 3.308l.713-.714l19.223 19.223z");
}

</style>
