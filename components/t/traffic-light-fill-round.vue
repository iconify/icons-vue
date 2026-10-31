<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkhkkx8gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkhkkx8gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:traffic-light-fill-round" /></template>
