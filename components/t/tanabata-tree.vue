<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpxba793f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tpxba793f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:tanabata-tree" /></template>
