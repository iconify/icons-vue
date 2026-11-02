<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9yuexbbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9yuexbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sob-line" /></template>
