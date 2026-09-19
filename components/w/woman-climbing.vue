<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0l6vme3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q0l6vme3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:woman-climbing" /></template>
