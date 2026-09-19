<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hhj7_6cck.css';
import '../../css/d/dc9hw5g_e.css';
import '../../css/c/c9digbcde.css';
import '../../css/x/xajsqxb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hhj7_6cck"/><path class="dc9hw5g_e"/><path class="c9digbcde"/><path class="xajsqxb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stacked-scrolling-2" /></template>
