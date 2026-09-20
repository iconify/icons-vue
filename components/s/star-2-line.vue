<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dygkkyb2f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dygkkyb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:star-2-line" /></template>
