<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkspzmbqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="qkspzmbqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:text-subscript" /></template>
