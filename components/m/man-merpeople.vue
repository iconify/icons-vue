<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zfa4yvn9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zfa4yvn9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:man-merpeople" /></template>
