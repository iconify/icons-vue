<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zafgt3y5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path clip-rule="evenodd" class="zafgt3y5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-red-hair" /></template>
