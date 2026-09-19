<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iwy1bxbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="iwy1bxbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:tornado" /></template>
