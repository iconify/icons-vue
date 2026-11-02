<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oj031sb1b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oj031sb1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:puzzled-line" /></template>
