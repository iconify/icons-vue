<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzlvgiczh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzlvgiczh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:radiology-scanner-bold" /></template>
