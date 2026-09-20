<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7-j-k0rq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:speed-2" /></template>
<style>
.o7-j-k0rq {
  fill: currentColor;
  d: path("M13.208 15.175q.476-.477.436-1.144t-.586-1.064q-1.822-1.338-3.716-2.673T5.63 7.662q1.292 1.825 2.646 3.716t2.675 3.697q.404.552 1.083.574t1.175-.474M5.106 19q-.281 0-.513-.112t-.391-.338q-.604-1.084-.906-2.253q-.302-1.168-.302-2.408q.006-1.804.684-3.38q.678-1.574 1.95-2.847Q6.895 6.396 8.55 5.698T12 5q1.864 0 3.503.71q1.64.711 2.858 1.93t1.929 2.857Q21 12.137 21 14q0 1.196-.302 2.337q-.302 1.14-.894 2.136q-.14.264-.385.395T18.9 19z");
}

</style>
