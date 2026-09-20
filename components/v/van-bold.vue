<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="r66nzjb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:van-bold" /></template>
<style>
.r66nzjb5w {
  fill: currentColor;
  d: path("m253.11 104.18l-45.57-53.09A19.94 19.94 0 0 0 192.26 44H32a20 20 0 0 0-20 20v112a20 20 0 0 0 20 20h14.06a36 36 0 0 0 67.88 0h40.12a36 36 0 0 0 67.88 0H236a20 20 0 0 0 20-20v-64a12.05 12.05 0 0 0-2.89-7.82M217.89 100H176V68h14.42ZM104 100V68h48v32ZM80 68v32H36V68Zm0 128a12 12 0 1 1 12-12a12 12 0 0 1-12 12m108 0a12 12 0 1 1 12-12a12 12 0 0 1-12 12m33.94-24a36 36 0 0 0-67.88 0h-40.12a36 36 0 0 0-67.88 0H36v-48h196v48Z");
}

</style>
