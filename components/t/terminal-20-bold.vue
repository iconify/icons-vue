<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fi2c5z44e.css';
import '../../css/x/xmsbzrzmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fi2c5z44e"/><path class="xmsbzrzmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:terminal-20-bold" /></template>
