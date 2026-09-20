<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jicqg58ad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sweat" /></template>
<style>
.jicqg58ad {
  fill: var(--svg-color--ff0d74, #ff0d74);
  d: path("M15.96 5.118h-2.774l-2.213 2.45l-1.292-2.45h-2.88L3 9.332v.074l5.003 9.476h2.822L13 16.463l1.28 2.42h2.928L21 14.672zM9.554 16.685l-3.669-6.95L8.11 7.271l3.663 6.946l-2.223 2.467zm6.316.074L12.2 9.814l2.224-2.462l3.668 6.951z");
}

</style>
