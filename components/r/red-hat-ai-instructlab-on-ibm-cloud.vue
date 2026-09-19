<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nsxy61lui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="nsxy61lui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:red-hat-ai-instructlab-on-ibm-cloud" /></template>
