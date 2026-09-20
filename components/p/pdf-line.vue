<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ti02oybof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ti02oybof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pdf-line" /></template>
