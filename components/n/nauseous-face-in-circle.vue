<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i70zh-6ql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i70zh-6ql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:nauseous-face-in-circle" /></template>
