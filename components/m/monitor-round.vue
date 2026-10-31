<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gt9su1b-k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gt9su1b-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:monitor-round" /></template>
