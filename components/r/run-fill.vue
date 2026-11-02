<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhxljyxlq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhxljyxlq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:run-fill" /></template>
