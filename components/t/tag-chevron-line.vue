<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjm2_8ziu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjm2_8ziu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:tag-chevron-line" /></template>
