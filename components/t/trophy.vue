<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p5jgqf6cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1536};
const content = `<path class="p5jgqf6cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:trophy" /></template>
