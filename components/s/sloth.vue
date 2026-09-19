<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jed9xlkuk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jed9xlkuk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:sloth" /></template>
