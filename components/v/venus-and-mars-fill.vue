<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpu5q9b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpu5q9b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:venus-and-mars-fill" /></template>
