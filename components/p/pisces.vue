<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6nrprqvg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g6nrprqvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:pisces" /></template>
