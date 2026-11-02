<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5-jrab_j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p5-jrab_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sun-2-fill" /></template>
