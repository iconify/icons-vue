<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/un5oheb6g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="un5oheb6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:t-shirt" /></template>
