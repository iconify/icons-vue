<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgcif9d1i.css';
import '../../css/w/wsl_n0boy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jgcif9d1i"/><path class="wsl_n0boy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:music-3-fill" /></template>
