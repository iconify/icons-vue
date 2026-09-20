<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yat7r_bam.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yat7r_bam"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:search-slash-solid" /></template>
