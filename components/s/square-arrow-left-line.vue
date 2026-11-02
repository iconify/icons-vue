<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz5qr-wbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oz5qr-wbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:square-arrow-left-line" /></template>
