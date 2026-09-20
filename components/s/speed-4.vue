<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="phb_9veux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-4" /></template>
<style>
.phb_9veux {
  fill: currentColor;
  d: path("M11.271 15.492q.627.293 1.257.048q.63-.246.822-.898q.667-2.194 1.284-4.378q.616-2.185 1.207-4.41q-1.325 1.879-2.611 3.744t-2.601 3.768q-.385.551-.181 1.19t.823.936M5.106 19q-.281 0-.513-.112t-.391-.338q-.604-1.084-.906-2.253q-.302-1.168-.302-2.408q.006-1.827.735-3.451t1.96-2.83T8.546 5.7T12 5q1.864 0 3.503.71q1.64.711 2.858 1.93t1.929 2.857Q21 12.137 21 14q0 1.196-.302 2.337q-.302 1.14-.894 2.136q-.14.264-.385.395T18.9 19z");
}

</style>
