<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l29nnacno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l29nnacno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:polygon-line" /></template>
