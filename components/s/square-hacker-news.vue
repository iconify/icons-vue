<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o196-bcxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="o196-bcxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-brands:square-hacker-news" /></template>
