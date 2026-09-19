<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_f6jmvbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m_f6jmvbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:white-exclamation-mark" /></template>
