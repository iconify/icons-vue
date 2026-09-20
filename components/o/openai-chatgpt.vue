<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/awg1bybys.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="awg1bybys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:openai-chatgpt" /></template>
