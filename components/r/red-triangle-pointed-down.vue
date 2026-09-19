<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wy4pajm8z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wy4pajm8z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:red-triangle-pointed-down" /></template>
