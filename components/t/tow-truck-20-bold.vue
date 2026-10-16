<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcs-irhnv.css';
import '../../css/z/zq0sxpb8q.css';
import '../../css/k/kr3y4cv8i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xcs-irhnv"/><path class="zq0sxpb8q"/><path class="kr3y4cv8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:tow-truck-20-bold" /></template>
