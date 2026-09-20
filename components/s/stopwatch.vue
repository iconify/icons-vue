<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1y7rt3td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="l1y7rt3td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:stopwatch" /></template>
