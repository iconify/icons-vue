<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e0t8-abhi.css';
import '../../css/j/j30lsq6za.css';
import '../../css/g/gh5mgezjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="e0t8-abhi"/><path class="j30lsq6za"/><path class="gh5mgezjj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:split-20-bold" /></template>
