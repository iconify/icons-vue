<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1de22b7f.css';
import '../../css/w/wzwobcbwt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i1de22b7f"/><path class="wzwobcbwt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:pickaxe-20-bold" /></template>
