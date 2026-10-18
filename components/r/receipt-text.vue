<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zrkh3bzpu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zrkh3bzpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:receipt-text" /></template>
