<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqiq-ebfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqiq-ebfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:presentation-1-line" /></template>
