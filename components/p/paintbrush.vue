<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg0fw_-ya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zg0fw_-ya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:paintbrush" /></template>
