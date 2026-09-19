<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v2x6aybpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v2x6aybpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:multiply" /></template>
