<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/am90fyq1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="am90fyq1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:ticket-line" /></template>
