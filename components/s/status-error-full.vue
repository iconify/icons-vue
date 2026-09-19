<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kvt4wtb1k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="kvt4wtb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:status-error-full" /></template>
