<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpbwr0yxt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpbwr0yxt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:message-3-line" /></template>
