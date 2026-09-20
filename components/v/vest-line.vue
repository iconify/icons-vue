<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux-3xnbyv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux-3xnbyv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:vest-line" /></template>
