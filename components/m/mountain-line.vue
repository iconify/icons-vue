<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/knskys3gy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="knskys3gy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:mountain-line" /></template>
