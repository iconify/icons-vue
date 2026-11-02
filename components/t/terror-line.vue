<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dimqnxboo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dimqnxboo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:terror-line" /></template>
