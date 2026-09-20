<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1--lvb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t1--lvb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-ai-3-fill" /></template>
