<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vh4-2yy8y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:steppers-sharp" /></template>
<style>
.vh4-2yy8y {
  fill: currentColor;
  d: path("M4.192 13.582q-.653-.65-.653-1.578q0-.927.649-1.581t1.577-.654t1.581.65T8 11.995t-.65 1.582t-1.576.654t-1.582-.65m2.453-.704Q7 12.524 7 12.001t-.354-.877t-.876-.355t-.877.354t-.355.876t.354.877t.876.355t.877-.354m3.778.704q-.654-.649-.654-1.576q0-.928.65-1.582q.649-.654 1.576-.654q.928 0 1.582.65q.654.649.654 1.576q0 .928-.65 1.582q-.649.654-1.576.654q-.928 0-1.582-.65m2.453-.704q.355-.353.355-.876t-.354-.877t-.876-.355t-.877.354t-.355.876t.354.877t.876.355t.877-.354m3.778.704Q16 12.933 16 12.006q0-.928.65-1.582q.649-.654 1.576-.654t1.582.65t.653 1.576t-.649 1.582t-1.577.654t-1.581-.65");
}

</style>
