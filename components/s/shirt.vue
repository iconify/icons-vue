<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yotfb98wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yotfb98wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:shirt" /></template>
