<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0vfanb9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:screen-rotation-up-outline-sharp" /></template>
<style>
.a0vfanb9d {
  fill: currentColor;
  d: path("m13.25 22.039l-.708-.714L14.887 19H7V8.69l1 1V18h6.867l-2.306-2.325l.689-.713l3.538 3.538zm3.75-6.71l-1-1V6H9.133l2.306 2.325l-.689.714L7.212 5.5l3.538-3.538l.708.713L9.114 5H17z");
}

</style>
