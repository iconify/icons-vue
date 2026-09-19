<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cn3v3rbfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cn3v3rbfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:send-backward" /></template>
