<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gd66bdkym.css';
import '../../css/c/cuq6r7b0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gd66bdkym"/><path class="cuq6r7b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:music-48" /></template>
