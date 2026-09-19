<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqkbldb0v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zqkbldb0v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:shopping-bags" /></template>
