<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tlfcv1bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tlfcv1bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:users-x" /></template>
