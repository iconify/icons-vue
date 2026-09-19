<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g1n8n1jfq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g1n8n1jfq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pandas-wordmark" /></template>
