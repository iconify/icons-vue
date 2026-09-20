<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zig9k8bwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zig9k8bwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:search-ai-4-fill" /></template>
