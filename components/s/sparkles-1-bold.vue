<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q221gvjez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="q221gvjez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:sparkles-1-bold" /></template>
