<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qp5fi2byd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qp5fi2byd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:mountain-snow-filled" /></template>
