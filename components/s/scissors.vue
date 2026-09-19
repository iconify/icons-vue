<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t675-1b2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t675-1b2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:scissors" /></template>
