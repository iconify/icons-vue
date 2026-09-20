<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuoxx-7fa.css';
import '../../css/q/qdqr_q1-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cuoxx-7fa"/><path class="qdqr_q1-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:repeat-line" /></template>
