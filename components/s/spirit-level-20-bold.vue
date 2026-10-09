<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m2a3x9b1l.css';
import '../../css/n/nv5lv4auf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m2a3x9b1l"/><path class="nv5lv4auf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:spirit-level-20-bold" /></template>
