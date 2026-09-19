<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv455vb8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pv455vb8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:safety-vest" /></template>
