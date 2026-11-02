<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt2ljxb7z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mt2ljxb7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:report-forms-fill" /></template>
