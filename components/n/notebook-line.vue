<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz47nnzel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lz47nnzel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:notebook-line" /></template>
