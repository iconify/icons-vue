<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kmu9v49lr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kmu9v49lr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:streaming-embedded" /></template>
