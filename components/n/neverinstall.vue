<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r6z4tbi8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:neverinstall" /></template>
<style>
.r6z4tbi8t {
  fill: var(--svg-color--0064ff, #0064ff);
  d: path("m128 128l32 28.224v95.744A128.3 128.3 0 0 1 128 256zM64 17.124v54.428l32 28.224v152.185a127.2 127.2 0 0 1-32-13.092V71.56L32 43.335a128.8 128.8 0 0 1 32-26.211m96-13.092a127 127 0 0 1 32 13.091v167.31l32 28.225l-.574.645A128.8 128.8 0 0 1 192 238.87v-54.421l-32-28.224zM32 43.335v169.33C12.096 190.108 0 160.448 0 128s12.096-62.109 32-84.665m192 0c19.904 22.556 32 52.217 32 84.665s-12.096 62.101-32 84.665zM128 0v128L96 99.776V4.032A128.3 128.3 0 0 1 128 0");
}

</style>
