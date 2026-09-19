<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvbdow_er.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lvbdow_er"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:minus" /></template>
