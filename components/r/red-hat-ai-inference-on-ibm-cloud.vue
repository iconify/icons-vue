<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q8_e15b-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q8_e15b-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:red-hat-ai-inference-on-ibm-cloud" /></template>
