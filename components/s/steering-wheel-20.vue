<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yw3xaacjo.css';
import '../../css/y/yxwm-unqh.css';
import '../../css/c/ctg78en2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="yw3xaacjo"/><path class="yxwm-unqh"/><path class="ctg78en2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:steering-wheel-20" /></template>
