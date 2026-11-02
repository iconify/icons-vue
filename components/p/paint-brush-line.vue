<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cl43i_bvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cl43i_bvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paint-brush-line" /></template>
