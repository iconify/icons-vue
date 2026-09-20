<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ck12p5bii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ck12p5bii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:numbers-09-sort-ascending-fill" /></template>
