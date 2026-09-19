<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj4qn8git.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wj4qn8git"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:rightwards-hand" /></template>
