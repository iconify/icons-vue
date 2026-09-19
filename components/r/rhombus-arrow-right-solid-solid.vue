<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nohw-0bfs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nohw-0bfs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:rhombus-arrow-right-solid-solid" /></template>
