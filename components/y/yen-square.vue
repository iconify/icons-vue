<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xrvoa6bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xrvoa6bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:yen-square" /></template>
