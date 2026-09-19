<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vo4qn1t0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vo4qn1t0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:telephone-receiver" /></template>
