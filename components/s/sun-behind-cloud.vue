<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q6o9oubkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q6o9oubkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sun-behind-cloud" /></template>
