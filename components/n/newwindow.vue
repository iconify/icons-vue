<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vtk_jhbwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":1024};
const content = `<path class="vtk_jhbwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:newwindow" /></template>
