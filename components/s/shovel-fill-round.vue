<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jrl-mxbcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jrl-mxbcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-fill-round" /></template>
