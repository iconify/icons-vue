<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/ve1v3g8oj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ve1v3g8oj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:straight-ruler" /></template>
