<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/te7x2geix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="te7x2geix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tree-4-line" /></template>
