<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mver5acni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mver5acni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:memo" /></template>
