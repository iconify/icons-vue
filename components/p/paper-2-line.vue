<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt27gzbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt27gzbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:paper-2-line" /></template>
