<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ig0u6q-wi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ig0u6q-wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:openai-line" /></template>
