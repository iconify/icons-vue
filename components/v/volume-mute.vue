<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j82ay1b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j82ay1b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:volume-mute" /></template>
