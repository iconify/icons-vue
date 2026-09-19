<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h7mcyhecc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h7mcyhecc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sweat-droplets" /></template>
