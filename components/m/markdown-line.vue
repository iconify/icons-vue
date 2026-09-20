<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-o72s6ja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-o72s6ja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:markdown-line" /></template>
