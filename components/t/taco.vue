<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_4ct0mzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h_4ct0mzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:taco" /></template>
