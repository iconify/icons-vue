<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghig4vbaa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ribbon" /></template>
<style>
.ghig4vbaa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m5.864 20.603l5.252-8.403l-1.752-2.803q-2.077-3.323 1.22-5.521q1.416-.944 2.832 0q3.297 2.198 1.22 5.521L12.884 12.2l5.252 8.403q.039.062.065.131t.039.142t.01.147t-.019.146t-.047.139t-.073.127t-.097.111q-.054.051-.117.09q-.062.039-.131.065t-.142.039t-.147.01t-.146-.019t-.139-.047t-.127-.073t-.111-.097q-.051-.054-.09-.117L12 13.615l-4.864 7.782q-.039.063-.09.117t-.111.097t-.127.073t-.139.047q-.072.016-.146.019t-.147-.01q-.073-.012-.142-.039q-.069-.026-.131-.065q-.127-.079-.214-.201q-.086-.121-.12-.266q-.033-.146-.009-.293q.025-.147.104-.273m7.5-12q1.305-2.089-.78-3.479q-.584-.389-1.168 0q-2.085 1.39-.78 3.479L12 10.785z");
}

</style>
