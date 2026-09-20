<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9map7_9e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r9map7_9e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:send" /></template>
