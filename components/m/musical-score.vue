<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5vy0x2pp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="m5vy0x2pp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:musical-score" /></template>
