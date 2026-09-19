<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d6qwklb1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="d6qwklb1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:waveform" /></template>
