<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/e/ec9y-vbgq.css';
import '../../css/q/qxzl8mbit.css';
import '../../css/v/vcav8zb4u.css';
import '../../css/z/zkmoqc5yr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="ec9y-vbgq"/><path class="qxzl8mbit"/><path clip-rule="evenodd" class="vcav8zb4u"/><path clip-rule="evenodd" class="zkmoqc5yr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-print:smartphone" /></template>
