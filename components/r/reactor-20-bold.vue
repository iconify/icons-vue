<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uexd2bbpi.css';
import '../../css/q/qan8ow8hl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uexd2bbpi"/><path class="qan8ow8hl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:reactor-20-bold" /></template>
